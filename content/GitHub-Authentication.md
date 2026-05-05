---
title: 🔐 GitHub 인증 상세 가이드
---

# GitHub 인증 가이드

<a name="PAT"></a>
## 1. Personal Access Token (PAT)
1. GitHub Settings > Developer settings > Personal access tokens에서 생성.
2. `repo` 권한 부여 필수.
3. Push 시 Password 칸에 발급받은 `ghp_...` 토큰 입력.

<a name="SSH"></a>
## 2. SSH Key (추천)
1. 키 생성: `ssh-keygen -t ed25519 -C "email@example.com"`
2. 공개키 복사: `pbcopy < ~/.ssh/id_ed25519.pub`
3. GitHub SSH Settings에 등록.
4. 원격 주소를 SSH 포맷(`git@github.com:...`)으로 변경.

---
알고리즘 상세 정보: [[SSH-Ed25519]]