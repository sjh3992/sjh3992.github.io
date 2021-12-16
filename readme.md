# prepare
1. github에 sjh3992.github.io 라는 이름의 repository를 만든다.
2. 컴퓨터에 jekyll+devkit을 설치한다.
3. `gem install jekyll bundler`를 명령 프롬포트에 입력한다.
4. `jekyll -v`로 jekyll 설치 여부를 확인한다.
5. 생성할 디렉토리로 이동하여 `jekyll new . --force` 를 입력하여 블로그를 설치한다.
6. `bundle exec jekyll serve`로 빌드한다.
7. commit 후 push!

# jekyll
1. `_config.yml` 파일에서 속성을 수정 가능!

# post
1. `_post` 폴더에서 블로그 포스팅을 진행한다.
2. `YYYY-MM-DD-TITLE.md`의 형태로 문서를 생성한다.
3. 다음 형식으로 Post 문서를 시작한다.
```
---
layout: post
title: "example"
date: 2021-12-16 23:30:00 +0900
categories: jekyll update
---
```
4. 그 이후에 Markdown 형식을 사용하여 내용을 작성한다.
5. commit 후 push!