---
layout: post
title: "Git & GitHub"
date: 2021-12-16 19:00:00 +0900
description: "Git과 GitHub에 대해서 알아보자!"
categories: jekyll update
---

# Git
## What is Git?
* 분산 버전 관리 시스템 : Distributed version control system
* Free
* Open source

## How to use?
### Create local repository
* 현재 작업중인 디렉토리를 git 저장소로 지정 : `git init`
* Local; Working Directory → Local; Staging Area : `git add`
* Local; Staging Area → Local; Working Directory : `git reset`
* Local; Staging Area → Local; Repository : `git commit`
* Local; Repository → Remote; Repository : `git push`
* Remote; Repository → Local; Repository : `git pull`

### Reflect changes in Git
* 현재 Git 상태 확인 : `git status`
* <file_name>를 생성/수정하고, 이를 Commit에 반영 : `git add <file_name>'
* 변경사항이 반영된 new commit 생성 : `git commit -m "<commit_msg>"
* commit 기록 확인하기 : `git log`

## Branch
* 코드의 흐름 분산

* branch 생성 : `git branch <branch_name>`

* 작업중인 branch 전환 : `git checkout <branch_name>`

* branch 병합 : `git merge <branch_name>`

* branch 삭제 : `git branch -d <branch_name>`

  

# Github

* 원격 저장소 중 가장 대표적임.