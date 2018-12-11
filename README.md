# Hexo를 이용한 Blog.

## 환경
- Node js
- NPM

## Feature
- Sitemap
- Search
- Theme : NEXT

## 개인이 커스텀하여 사용해야하는 File
- _config.yml
- /themes/next/_config.yml

## _config.yml (필수 수정 필요)
```yaml
# Blog title
title: Seo
# Blog admin
author: Mun-su Seo
# Blog url (사용자 이름.github.io)
url: https://mun-su.github.io

# git pages 배포를 하기위한 설정.
deploy:
  # Git
  type: git
  # Repository 명은 반드시 https://github.com/{사용자 이름}/{blog url}.git
  repo: https://github.com/mun-su/mun-su.github.io.git
  # Branch
  branch: master
```

## /themes/next/_config.yml
```yaml
# 개인의 Social 입력 및 내용 제거 후 주석 처리.
social:
  GitHub: https://github.com/mun-su || github
  E-Mail: mailto:dev.munsu@gmail.com || envelope
# Google Console 연동하여 analytics 사용시 개인의 Key를 입력하여 사용
google_analytics:
```

## 기본 명령어
| Command | Short Command | Description |
|:-------:|:-------------:|:------------|
| hexo server | 없음 | 개발용 Node 서버 실행 |
| hexo clean | 없음 | build 제거 |
| hexo generate | hexo g | build |
| hexo deploy | hexo d | 배포 |
