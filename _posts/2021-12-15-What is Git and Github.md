---
layout: post
title: "What is Git and Github"
date: 2021-12-15
comments: true
---

## 1. Git 
### 1-1. GIt이란?
Git 이란 분산형 버전 관리 시스템(Version Control System, VCS)의 한 종류이다.

### 1-2. Git의 기능들
git init: 깃 저장소를 초기화한다.

git commit -m "커밋 내용": 커밋 내용으로 커밋한다

git status: 현재 상태를 확인하는 명령어

git add <파일이름>: 파일을 커밋할 상태에 추가한다

git push origin main: 현재 커밋 상태로 원격 github에 저장한다

## 2.지역(local) 저장소 와 원격(remote)저장소
git에서 파일을 저장하는 장소는 크게 local과 remote로 나눌 수 있다.
### 2-1 지역(local) 저장소란?
지역 저장소라는 것은 나만의 컴퓨터에서 작업을 한 뒤 작업한 것들을 저장하는 저장소를 말한다.
git add 이라는 명령어를 통해 working에서 staging으로 상태를 변경 할 수 있고 git commit 명령어를 통해 staging에서 지역(local) 저장소로 파일을 옮길 수 있으며
git push를 통하여 파일 들을 지역(local)저장소에서 원격(remote)저장소로 이동 시킬 수 있다.
### 2-2 원격(remote)저장소란?
원격 저장소 라는 것은 it이 제공하는 저장소를 의미한다. 

## 3. Github

### 3-1 Github이란?
가장 많이 사용되는 무료 git 저장소이다.

다른 사람들과 협업하거나, 오픈 소스를 배포할 때 사용할 수 있다.


