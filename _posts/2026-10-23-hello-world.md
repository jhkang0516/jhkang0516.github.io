---
title: 블로그를 시작합니다
date: 2026-10-23 17:00:00 +0900
categories: [Blog, Setup]
tags: [jekyll, chirpy, github-pages]
---

GitHub Pages 와 Jekyll [Chirpy](https://github.com/cotes2020/jekyll-theme-chirpy) 테마로 블로그를 시작합니다.

## 글 쓰는 법

`_posts/` 폴더에 `YYYY-MM-DD-제목.md` 파일을 만들고 상단에 front matter 를 적습니다.

```yaml
---
title: 글 제목
date: 2026-10-23 17:00:00 +0900
categories: [카테고리, 하위카테고리]
tags: [태그1, 태그2]
---
```

`main` 브랜치에 push 하면 GitHub Actions 가 빌드해서 자동으로 배포합니다.

> 이미지는 `assets/img/` 아래에 두고 `![설명](/assets/img/파일.png)` 처럼 참조합니다.
{: .prompt-tip }
