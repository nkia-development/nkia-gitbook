---
layout: home
title: Jekyll Gitbook Theme
permalink: /
---

## Published

[https://nkia-development.github.io/nkia-gitbook/](https://nkia-development.github.io/nkia-gitbook/)

[![Jekyll Themes](https://img.shields.io/badge/featured%20on-JekyllThemes-red.svg)](https://jekyll-themes.com/jekyll-gitbook/)

<br>
<br>

## 엔키아 기술 블로그

<br>

> 엔키아 기술 블로그 입니다.  
> [http://www.nkia.co.kr/](http://www.nkia.co.kr/)

<br>
<br>

## local 에서 배포될 페이지 미리보기 (개발서버)

<br>

mac OS 기준

> (brew 설치 되어있어야함)

<br>

1. ```
   brew install chruby ruby-install xz
   ```

2. ```
   ruby-install ruby
   ```

3. ```echo "source $(brew --prefix)/opt/chruby/share/chruby/chruby.sh" >> ~/.zshrc
   echo "source $(brew --prefix)/opt/chruby/share/chruby/auto.sh" >> ~/.zshrc
   echo "chruby ruby-3.1.2" >> ~/.zshrc # run 'chruby' to see actual version
   ```

4. ```
   gem install jekyll bundler
   ```
5. ```
   jekyll new myblog
   ```

6. ```
   bundle exec jekyll serve
   ```

<br>
<br>

### 로컬 환경에서 markdown 미리 보기

1. vscode 기준 `command + shift + p` -> Markdown One Preview to the side
