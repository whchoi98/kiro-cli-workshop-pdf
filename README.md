# kiro-cli-workshop-pdf

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](LICENSE)
[![Chapters](https://img.shields.io/badge/Chapters-18-blue.svg)](#english)
[![Slides](https://img.shields.io/badge/Slides-180-blue.svg)](#english)
[![English](https://img.shields.io/badge/Language-English-red.svg)](#english)
[![한국어](https://img.shields.io/badge/Language-한국어-red.svg)](#한국어)

A comprehensive 18-chapter workshop on AWS Kiro CLI, the agentic AI development tool. / AWS Kiro CLI(에이전틱 AI 개발 도구)를 다루는 18챕터 종합 워크샵 자료입니다.

---

# English

## Overview

Kiro is AWS's new agentic AI development tool that goes beyond a simple code assistant to provide custom agents, multi-agent collaboration, MCP external integration, lifecycle hooks, and CI/CD automation — all production-ready capabilities. This workshop is designed for technical seminars of fewer than 50 attendees and serves everyone from first-time Kiro users to those seeking advanced usage. It consists of 18 chapters totaling 180 slides, with each chapter running approximately 30 to 45 minutes.

## Features

- **Foundations — CH01 to CH06** — Kiro CLI introduction and architecture, installation, authentication, 12 model options, chat basics, and session management
- **Core — CH07 to CH11** — Context resource management, terminal UI and Crew Monitor, permission system, steering for persistent project guidelines, and custom agent JSON configuration
- **Advanced — CH12 to CH17** — Multi-agent collaboration, on-demand knowledge via skills, MCP external integration, lifecycle hooks automation, headless mode for CI/CD, and command autocomplete
- **Reference — CH18** — Complete command reference and curated learning resources
- **Verified accuracy** — All content validated 100% against official AWS documentation

## Prerequisites

- A PDF reader (Adobe Acrobat Reader, Preview, browser viewer, or equivalent)
- Optional: an AWS account if you plan to follow the hands-on examples
- Optional: Kiro CLI installed locally (see CH02 for setup instructions)

## Installation

```bash
# Clone the repository
git clone https://github.com/whchoi98/kiro-cli-workshop-pdf.git

# Move into the project directory
cd kiro-cli-workshop-pdf

# Or download a single chapter directly
curl -LO https://github.com/whchoi98/kiro-cli-workshop-pdf/raw/main/CH01_Kiro_CLI_Introduction.pdf
```

## Usage

Open the PDFs in chapter order for the full workshop experience, or jump to a specific topic.

```bash
# macOS
open CH01_Kiro_CLI_Introduction.pdf

# Linux
xdg-open CH01_Kiro_CLI_Introduction.pdf

# Windows
start CH01_Kiro_CLI_Introduction.pdf
```

Recommended learning paths:

- **First-time users** — Read CH01 through CH06 sequentially
- **Returning users** — Jump to CH07 through CH11 for core productivity features
- **Power users** — Focus on CH12 through CH17 for multi-agent and CI/CD integration

## Project Structure

```
kiro-cli-workshop-pdf/
├── CH01_Kiro_CLI_Introduction.pdf        # Introduction and architecture
├── CH02_Installation_and_Setup.pdf       # Installation guide
├── CH03_Authentication_and_Security.pdf  # Authentication and security
├── CH04_Models.pdf                       # 12 model options
├── CH05_Chat_Basics.pdf                  # Chat basics
├── CH06_Sessions.pdf                     # Session management
├── CH07_Context.pdf                      # Context resource management
├── CH08_Terminal_UI.pdf                  # Terminal UI and Crew Monitor
├── CH09_Permissions.pdf                  # Permission system
├── CH10_Steering.pdf                     # Project steering
├── CH11_Custom_Agents.pdf                # Custom agent configuration
├── CH12_Subagents.pdf                    # Multi-agent collaboration
├── CH13_Skills.pdf                       # On-demand knowledge system
├── CH14_MCP.pdf                          # MCP external integration
├── CH15_Hooks.pdf                        # Lifecycle hooks automation
├── CH16_Headless.pdf                     # Headless mode for CI/CD
├── CH17_Autocomplete.pdf                 # Command autocomplete
├── CH18_Reference.pdf                    # Command reference
├── CHANGELOG.md                          # Release history
├── LICENSE                               # CC BY 4.0 license text
└── README.md                             # This file
```

## Contributing

Contributions for typo fixes, factual corrections, and translations are welcome.

1. Fork the repository
2. Create a feature branch (`git checkout -b fix/chapter-typo`)
3. Commit your changes using Conventional Commits (`git commit -m "fix: correct typo in CH04"`)
4. Push to your fork (`git push origin fix/chapter-typo`)
5. Open a Pull Request

Commit message types:

- `feat:` — new content or new chapter
- `fix:` — typo or factual correction
- `docs:` — README or supporting documentation
- `chore:` — formatting or metadata

## License

Released under the [Creative Commons Attribution 4.0 International License](LICENSE) (CC BY 4.0). Reuse this material freely for internal training, team study groups, and your own presentations, with attribution.

## Contact

- Maintainer: [whchoi98](https://github.com/whchoi98)
- Issues: [GitHub Issues](https://github.com/whchoi98/kiro-cli-workshop-pdf/issues)
- Email: whchoi98@gmail.com
- Workshop requests: Contact via DM, comments, or your AWS Account team

---

# 한국어

## 개요

Kiro는 AWS가 새롭게 선보인 에이전틱 AI 개발 도구로, 단순한 코드 어시스턴트를 넘어 커스텀 에이전트, 멀티 에이전트 협업, MCP 외부 통합, 라이프사이클 훅, CI/CD 자동화까지 프로덕션 환경에서 활용 가능한 모든 기능을 제공합니다. 본 워크샵은 50명 미만의 기술 세미나용으로 설계되었으며, Kiro를 처음 사용하시는 분부터 고급 활용을 원하시는 분까지 모두를 대상으로 합니다. 전체 18챕터, 180슬라이드로 구성되어 있으며 챕터당 약 30분에서 45분 분량입니다.

## 주요 기능

- **기초편 — CH01부터 CH06** — Kiro CLI의 소개와 아키텍처, 설치, 인증, 12종 모델 선택, 채팅 기초, 세션 관리를 다룹니다
- **핵심편 — CH07부터 CH11** — 컨텍스트 자원 관리, 터미널 UI와 Crew Monitor, 권한 시스템, steering을 통한 프로젝트 가이드라인 영속화, 커스텀 에이전트의 JSON 설정을 다룹니다
- **고급편 — CH12부터 CH17** — 멀티 에이전트 협업, 온디맨드 지식 시스템인 skills, MCP 외부 통합, 라이프사이클 훅 자동화, CI/CD 통합용 headless 모드, 명령어 자동완성까지 Kiro의 가장 강력한 기능들을 다룹니다
- **참고편 — CH18** — 전체 명령어 reference와 학습 자료 정리입니다
- **검증된 정확성** — AWS 공식 문서를 기반으로 모든 콘텐츠의 정확성을 100% 검증했습니다

## 사전 요구 사항

- PDF 뷰어 (Adobe Acrobat Reader, Preview, 브라우저 뷰어 등)
- 선택사항: 실습 예제를 따라하시려면 AWS 계정이 필요합니다
- 선택사항: 로컬에 Kiro CLI 설치 (설치 방법은 CH02 참조)

## 설치 방법

```bash
# 저장소 클론
git clone https://github.com/whchoi98/kiro-cli-workshop-pdf.git

# 프로젝트 디렉토리로 이동
cd kiro-cli-workshop-pdf

# 또는 특정 챕터만 직접 다운로드
curl -LO https://github.com/whchoi98/kiro-cli-workshop-pdf/raw/main/CH01_Kiro_CLI_Introduction.pdf
```

## 사용법

워크샵 전체를 경험하시려면 챕터 순서대로 읽으시거나, 특정 주제로 바로 이동하실 수 있습니다.

```bash
# macOS
open CH01_Kiro_CLI_Introduction.pdf

# Linux
xdg-open CH01_Kiro_CLI_Introduction.pdf

# Windows
start CH01_Kiro_CLI_Introduction.pdf
```

추천 학습 경로:

- **처음 사용하시는 분** — CH01부터 CH06까지 순차적으로 읽으시기 바랍니다
- **재방문자** — 핵심 생산성 기능을 다루는 CH07부터 CH11로 바로 이동하시기 바랍니다
- **고급 사용자** — 멀티 에이전트 및 CI/CD 통합을 다루는 CH12부터 CH17에 집중하시기 바랍니다

## 프로젝트 구조

```
kiro-cli-workshop-pdf/
├── CH01_Kiro_CLI_Introduction.pdf        # 소개 및 아키텍처
├── CH02_Installation_and_Setup.pdf       # 설치 가이드
├── CH03_Authentication_and_Security.pdf  # 인증 및 보안
├── CH04_Models.pdf                       # 12종 모델
├── CH05_Chat_Basics.pdf                  # 채팅 기초
├── CH06_Sessions.pdf                     # 세션 관리
├── CH07_Context.pdf                      # 컨텍스트 자원 관리
├── CH08_Terminal_UI.pdf                  # 터미널 UI와 Crew Monitor
├── CH09_Permissions.pdf                  # 권한 시스템
├── CH10_Steering.pdf                     # 프로젝트 steering
├── CH11_Custom_Agents.pdf                # 커스텀 에이전트 설정
├── CH12_Subagents.pdf                    # 멀티 에이전트 협업
├── CH13_Skills.pdf                       # 온디맨드 지식 시스템
├── CH14_MCP.pdf                          # MCP 외부 통합
├── CH15_Hooks.pdf                        # 라이프사이클 훅 자동화
├── CH16_Headless.pdf                     # CI/CD용 headless 모드
├── CH17_Autocomplete.pdf                 # 명령어 자동완성
├── CH18_Reference.pdf                    # 명령어 reference
├── CHANGELOG.md                          # 릴리스 이력
├── LICENSE                               # CC BY 4.0 라이선스 전문
└── README.md                             # 본 문서
```

## 기여 방법

오타 수정, 사실 정정, 번역에 대한 기여를 환영합니다.

1. 저장소를 Fork 하시기 바랍니다
2. 기능 브랜치를 생성하시기 바랍니다 (`git checkout -b fix/chapter-typo`)
3. Conventional Commits 형식으로 변경사항을 커밋하시기 바랍니다 (`git commit -m "fix: correct typo in CH04"`)
4. 본인의 Fork로 푸쉬하시기 바랍니다 (`git push origin fix/chapter-typo`)
5. Pull Request를 생성하시기 바랍니다

커밋 메시지 타입:

- `feat:` — 신규 콘텐츠 또는 신규 챕터
- `fix:` — 오타 또는 사실 정정
- `docs:` — README 또는 보조 문서
- `chore:` — 포맷팅 또는 메타데이터

## 라이선스

본 자료는 [Creative Commons Attribution 4.0 International License](LICENSE) (CC BY 4.0) 하에 배포됩니다. 출처를 표기하시면 사내 교육 자료, 팀 스터디, 본인 발표 자료로 자유롭게 재사용하실 수 있습니다.

## 연락처

- 메인테이너: [whchoi98](https://github.com/whchoi98)
- 이슈: [GitHub Issues](https://github.com/whchoi98/kiro-cli-workshop-pdf/issues)
- 이메일: whchoi98@gmail.com
- 워크샵 요청: DM, 댓글, 또는 AWS Account 팀을 통해 연락 주시기 바랍니다
