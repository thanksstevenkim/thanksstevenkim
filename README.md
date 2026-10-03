# 안녕하세요, Steven Kim입니다 👋

[English](./README.en.md)

**Systems & Infrastructure · Technical Support · Service Operations**

실제로 운영되는 서비스를 관리하고, 장애의 원인을 추적하고, 반복되는 작업을 자동화하고, 그 과정을 다시 사용할 수 있는 문서로 남기는 일을 해왔습니다.

Linux 기반 서버 운영과 트러블슈팅을 중심으로 Mastodon 공개 서비스 운영, MediaWiki 홈랩, Python 기반 Fediverse 데이터 수집·검증 자동화 등의 프로젝트를 진행하고 있습니다.

단순히 기술을 설치해보는 것보다,

**운영 → 문제 발견 → 조사 → 복구 → 검증 → 문서화**

까지 이어지는 과정을 중요하게 생각합니다.

한국어를 모국어로 사용하며 일본어와 영어 환경에서도 기술 커뮤니케이션이 가능합니다.

## 제가 주로 하는 일

**Operate**  
실제 사용자가 있는 self-hosted 서비스를 운영하고 유지보수합니다.

**Troubleshoot**  
웹 서버, 데이터베이스, 애플리케이션 업그레이드, 검색 인프라, CI 등에서 발생한 장애의 원인을 추적합니다.

**Automate**  
Python과 GitHub Actions를 사용해 데이터 수집, 검증, 상태 확인, 반복 작업과 배포 흐름을 자동화합니다.

**Document**  
장애와 실험에서 얻은 판단을 incident report, runbook, troubleshooting note, knowledge base로 남깁니다.

---

## 대표 프로젝트

### 🛠 [Mastodon Operations Lab](https://github.com/thanksstevenkim/mastodon-lab)

**Production service operations · Linux · Docker · Nginx · PostgreSQL · Cloudflare**

2022년부터 self-hosted Mastodon 서비스를 운영하며 얻은 실전 운영 지식을 정리한 저장소입니다.

일반적인 설치 가이드보다 실제 장애와 반복 가능한 운영 절차에 초점을 맞춥니다.

- Cloudflare 521 장애 조사
- incomplete database migration
- Elasticsearch 구성 문제
- fork drift로 인한 CI 실패
- signup abuse와 moderation tooling
- 업그레이드, 백업, 복구, 유지보수 runbook

---

### 🧪 [LibreWiki Homelab](https://github.com/thanksstevenkim/librewiki-homelab)

**Linux · Nginx · PHP-FPM · MariaDB · MediaWiki · Migration**

기존 MediaWiki 환경을 안전하게 재현하고 호환성과 migration을 실험하기 위한 홈랩입니다.

- Ubuntu Server VM 구축
- Nginx, PHP-FPM, MariaDB 구성
- 데이터베이스 백업 및 복원
- MediaWiki 문서와 revision migration
- extension / template dependency troubleshooting
- 기존 wiki customization을 최신 MediaWiki markup에 맞게 이식

향후 network segmentation, monitoring, disaster recovery 실습까지 확장할 계획입니다.

---

### 🌐 [The Hitchhiker's Guide to the Fediverse](https://github.com/thanksstevenkim/the-hitchhikers-guide-to-the-fediverse)

**Python · Data pipelines · Validation · GitHub Actions · ActivityPub**

공개 API에서 Fediverse 인스턴스 데이터를 수집하고 검증해 탐색할 수 있도록 만든 프로젝트입니다.

- Python 기반 통계 수집
- canonical host / alias 처리
- health-state transition과 failure threshold
- spam / anomaly filtering
- software taxonomy와 review queue
- 데이터 검증
- scheduled GitHub Actions
- GitHub Pages 자동 배포

분산 환경에서 불완전하고 변동하는 데이터를 어떻게 안전하게 다룰지도 함께 실험하고 있습니다.

---

### 📚 [thanks-wiki](https://github.com/thanksstevenkim/thanks-wiki)

**Knowledge engineering · Astro · Documentation · Case studies**

기술적 사건과 여러 관찰을 다시 사용할 수 있는 지식으로 정리하는 개인 knowledge base입니다.

- **Notes** — 관찰, 가설, 사례, 생각이 생긴 과정
- **Docs** — 여러 Notes와 사례에서 반복된 내용을 정리한 재사용 가능한 방법론

결론만 남기기보다, 왜 그런 판단에 도달했는지를 다시 복원할 수 있도록 구체적인 사례와 근거를 함께 보존합니다.

---

## 기술 작업 방식

제가 가장 관심을 두는 지점은 **시스템이 배포된 이후**입니다.

문제가 생겼을 때 마지막 해결 명령만 남기기보다 다음 흐름을 보존하려고 합니다.

```text
증상
 ↓
증거
 ↓
가설
 ↓
원인
 ↓
변경
 ↓
검증
 ↓
재사용 가능한 절차
```

서비스를 복구하는 것뿐 아니라, 다음 장애 조사와 운영 판단이 더 쉬워지는 것을 목표로 합니다.

## 주요 경험 영역

```text
Systems & Operations
├── Linux server administration
├── Docker-based services
├── Nginx / Cloudflare
├── PostgreSQL / MariaDB / Redis
├── backup and recovery
└── incident response

Automation
├── Python
├── GitHub Actions
├── data validation
├── health monitoring logic
└── repeatable operational workflows

Documentation
├── incident reports
├── runbooks
├── troubleshooting notes
├── architecture documentation
└── knowledge bases
```

## 언어

- 🇰🇷 한국어 — Native
- 🇯🇵 일본어 — Professional working proficiency
- 🇬🇧 영어 — Professional working proficiency

## Portfolio

프로젝트와 경험을 더 구조적으로 정리한 포트폴리오:

**[thanksstevenkim.dev](https://thanksstevenkim.dev)**
