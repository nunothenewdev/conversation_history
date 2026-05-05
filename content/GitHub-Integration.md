---
title: 🐙 GitHub 연동 및 인증
---

# GitHub 연동

## 1. 원격 저장소 연결 오류 해결
`error: remote origin already exists.` 오류 발생 시, 기존 연결을 수정해야 합니다.
- 수정 명령어: `git remote set-url origin [내-저장소-주소]`

## 2. 인증 방식 선택
GitHub는 보안상 비밀번호 인증을 지원하지 않으므로 다음 두 가지 방식 중 하나를 사용합니다.

### A. Personal Access Token (PAT)
- 보안 토큰을 발급받아 비밀번호 대신 입력하는 방식입니다.
- 상세 방법은 [[GitHub-Authentication#PAT]]를 참조하십시오.

### B. SSH Key (권장)
- 한 번 설정하면 자동 인증되는 현대적인 방식입니다.
- 상세 방법은 [[GitHub-Authentication#SSH]]를 참조하십시오.
- 사용되는 알고리즘: [[SSH-Ed25519|Ed25519]]