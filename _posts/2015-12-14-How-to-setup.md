---
layout: post
title:  "Git Clone 하는 방법"
date:   2015-12-13 21:01:00
---

1. ssh key 생성
    - 참고: [Generating SSH keys](https://help.github.com/articles/generating-ssh-keys/)
2. (option): ssh-add ~/.ssh/asella_github
    - 보이는지 확인: ssh-add -l > "The agent has no identities" 라면 필요함
3. Clone   
```bash
git clone git@github.com:asellachoi/asellachoi.github.io.git
```
