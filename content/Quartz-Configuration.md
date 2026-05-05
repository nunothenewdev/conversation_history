---
title: 💎 Quartz 설정 및 초기화
---

# Quartz 설정

## 1. 프로젝트 초기화
새로운 Quartz 프로젝트를 시작할 때는 반드시 아래 명령어를 사용합니다.
- 명령어: `npx quartz create`
- *참고: 시스템 내부의 가상환경(.venv) 경로나 다른 라이브러리 명령어와 혼동하지 않도록 주의하십시오.*

## 2. 링크 해결 방식 (Link Resolution)
Quartz 설정 중 **Choose how Quartz should resolve links** 단계에서는 다음을 권장합니다.
- **선택**: `Treat links as shortest path (default)`
- **이유**: [[Obsidian]]의 기본 링크 방식과 가장 잘 호환되며, 파일 이동 시에도 링크가 깨지지 않습니다.

---
다음 단계: [[GitHub-Integration]]