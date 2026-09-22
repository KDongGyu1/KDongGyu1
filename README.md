<div align="center">

![header](https://capsule-render.vercel.app/api?type=waving&color=0:2F80ED,100:56CCF2&height=180&section=header&text=KDongGyu1&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=Cloud%20Security%20%7C%20DevSecOps%20%7C%20Security%20Automation&descAlignY=58&descSize=16)

### 안녕하세요, **클라우드 보안**과 **보안 자동화**를 공부하는 **김동규**입니다.

AWS 기반 인프라를 직접 설계·구축하며 보안 아키텍처를 학습하고,  
Python을 활용해 자산 수집·로그 파이프라인·공격 경로 탐지를 자동화하는 방법을 탐구합니다.  
AI 도구를 학습·개발·문서화 전 과정에 적극 활용해 생산성을 높입니다.

</div>

---

## 자기소개

- 클라우드 보안(AWS)과 **DevSecOps** 방향으로 커리어를 설계하고 있습니다.
- **AWS 기반 핀테크 보안 프로젝트**에서 팀장으로 참여해 전자금융감독규정을 준수한 AWS 아키텍처를 설계하고, ALB + ASG 기반 애플리케이션 서버 운영과 성능 측정을 담당했습니다.
- **하이브리드 공격 경로 탐지 시스템** 프로젝트에서 자산 수집 자동화(Trivy·Scout Suite·AWS CLI)를 담당하며, 온프레미스와 AWS 자산을 Neo4j 그래프로 연동하는 파이프라인을 구축했습니다.
- **게임 로그 수집 파이프라인**에서 Redis Streams + FastAPI + Docker 기반 유실 방지 아키텍처를 설계하고, 10,000건 부하 테스트에서 **성공률 100%·pending 0·lag 0** 을 검증했습니다.
- 현재 **24인 규모 통합 프로젝트**에서 사이버보안 담당으로 SIEM 파이프라인 아키텍처 설계와 WAF/IDS/IPS 로그 정규화 포맷 작업을 진행 중입니다.
- **Python·Shell·AWS CLI**를 활용한 보안 업무 자동화와 반복 작업 효율화에 관심이 많습니다.
- AI 도구(ChatGPT, Claude 등)를 학습·코드 리뷰·문서화·문제 해결에 적극 활용합니다.
- 현재 **정보처리기사(필기 합격·실기 준비 중)·정보보안기사(필기 합격·실기 준비 중)** 취득을 위해 학습 중입니다.
- Notion에 학습 내용을 꾸준히 정리합니다.

---

## 주요 학습 내용

| Area | What I'm Doing |
| --- | --- |
| **Cloud Security** | AWS IAM·VPC·WAF·KMS·CloudTrail 기반 보안 아키텍처 설계 및 Terraform IaC 실습 |
| **Security Automation** | Python으로 AWS 자산 인벤토리·취약점 스캔(Trivy, Scout Suite)·로그 수집 자동화 |
| **DevSecOps** | GitHub Actions 기반 CI/CD 파이프라인 및 IaC 보안 검증 도구 학습 |
| **Threat Analysis** | Neo4j 그래프 기반 하이브리드(온프렘+AWS) 공격 경로 탐지 프로젝트 참여 |
| **Data Pipeline** | Redis Streams·FastAPI 기반 대용량 로그 수집 파이프라인 설계 및 부하 테스트 |
| **AI Utilization** | AI 도구를 활용한 학습·개발 효율화, 문서 자동화 |

---

## 기술 스택

<div align="center">

### Languages & Backend
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)


### Cloud & Infrastructure
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Amazon EKS](https://img.shields.io/badge/Amazon%20EKS-FF9900?style=for-the-badge&logo=amazoneks&logoColor=white)

### Security & Data
![AWS IAM](https://img.shields.io/badge/AWS%20IAM-DD344C?style=for-the-badge&logo=amazoniam&logoColor=white)
![AWS WAF](https://img.shields.io/badge/AWS%20WAF-DD344C?style=for-the-badge&logo=amazonaws&logoColor=white)

### DevOps & Tools
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)

### Collaboration & AI
![Notion](https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white)
![OpenAI](https://img.shields.io/badge/AI%20Tools-412991?style=for-the-badge&logo=openai&logoColor=white)

</div>

---

## 📂 프로젝트

### [FinPay 심화 보안 고도화 프로젝트](https://github.com/KDongGyu1/tectupSCPJ3)
> **전자금융 서비스를 가정한 AWS 클라우드 보안 아키텍처 (Terraform IaC)**  
> `AWS` `Terraform` `ALB` `ASG` `CloudFront` `RDS` `보안 헤더`

**역할**: 팀장 / App·운영·성능 담당 (KT tech up 사이버보안 2기 · 4인 팀)

- **인프라 코드화**: Terraform으로 VPC·ALB·ASG·RDS·CloudFront 전체 인프라 구성
- **App 서버 운영**: ALB + ASG 기반 애플리케이션 서버 구성 및 운영 상태 진단
- **보안 헤더 적용**: HSTS·CSP·X-Content-Type-Options·Secure Cookie 직접 구현
- **성능 측정**: 부하 테스트로 p95 응답 0.087초, 실패율 0% 기준선 확보
- **문서화**: 전자금융감독규정 매핑 문서 작성 및 팀 산출물 취합 주도

---

### [하이브리드 공격 경로 탐지 시스템](https://github.com/KDongGyu1/hybrid-attack-pathfinder.git)
> **온프레미스 + AWS 하이브리드 인프라의 공격 경로를 Neo4j 그래프로 탐색하는 SOC 시스템**  
> `AWS` `Neo4j` `Cypher` `Trivy` `Scout Suite` `AWS CLI` `Python`

**역할**: 인프라3 - 자산 수집 담당 (KT tech up 사이버보안 2기)

- **자산 수집 자동화**: AWS CLI·Trivy·Scout Suite를 venv 격리 환경으로 구성해 EC2·IAM·S3·RDS·KMS 등 8종 60개 이상 자산 수집
- **취약점 스캔**: Trivy로 컨테이너 이미지 188개 취약점 탐지, Scout Suite로 AWS 계정 357개 Finding 도출
- **팀 시나리오 연계**: 스캔 결과를 S1~S4 공격 시나리오와 매핑해 위험 지점 문서화
- **위협 모델링 문서**: STRIDE + MITRE ATT&CK 기반 62개 위협 도출, CVSS v3.1 위험 평가 매트릭스 작성

---

### [게임 로그 수집 파이프라인](https://github.com/KDongGyu1/game-log-ingestion-pipeline)
> **초당 수만 건의 인게임 로그를 유실 없이 수집·적재하는 큐 기반 파이프라인**  
> `FastAPI` `Redis Streams` `Docker Compose` `Terraform` `AWS ECS`

- **아키텍처 설계**: File·Queue·DB 3가지 방식 비교 후 Redis Streams 기반 Queue 방식 채택
- **유실 방지 3중 구조**: XADD 실패 시 503 재시도 유도 · Redis AOF 영속화 · XAUTOCLAIM 회수 재처리
- **부하 테스트**: bombardier 동시 100 커넥션·10,000건 요청 → 성공률 100%, pending 0, lag 0 검증
- **재시작 유실 검증**: docker compose restart 후 10,000건 데이터 유지 확인
- **IaC**: Terraform으로 VPC·ALB·ECS·ElastiCache 인프라 코드화

---

## 현재 학습 중

- **정보처리기사** 필기 합격 · 실기 준비 중
- **정보보안기사** 필기 합격 · 실기 준비 중
- **GitOps K8s Platform**: Terraform + EKS + GitHub Actions + ArgoCD + Prometheus 구성 실습
- **DevSecOps 파이프라인**: GitHub Actions + Trivy(컨테이너 스캔) + tfsec(IaC 스캔) + Slack 알림

---

## GitHub Stats

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=KDongGyu1&show_icons=true&theme=tokyonight&hide_border=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=KDongGyu1&layout=compact&theme=tokyonight&hide_border=true)

![GitHub Streak](https://streak-stats.demolab.com?user=KDongGyu1&theme=tokyonight&hide_border=true)

</div>

---

##  Contact & Links

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-KDongGyu1-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/KDongGyu1)
[![Notion](https://img.shields.io/badge/Notion-Portfolio-000000?style=for-the-badge&logo=notion&logoColor=white)](https://www.notion.so/8a256ecf01dc8337a12e01c8eadd13ac?source=copy_link)
[![Velog](https://img.shields.io/badge/Velog-kimdk1125-20C997?style=for-the-badge&logo=velog&logoColor=white)](https://velog.io/@kimdk1125/posts)

</div>

---

<div align="center">

**"AI를 도구로, 보안을 관점으로."**  
안전하고 효율적인 클라우드 서비스를 만드는 엔지니어로 성장하겠습니다.

</div>

![footer](https://capsule-render.vercel.app/api?type=waving&color=0:56CCF2,100:2F80ED&height=120&section=footer)
