---
layout: post
title:  "git 원격저장소 주소 변경"
date:   2016-01-11 21:18:00
categories: git github
---

git 원격저장소를 옮기거나 주소가 잘못되었을 때, URL을 수정하는 방법은 두가지가 있다. `.git/config` 파일을 직접 수정하거나 `git remote set-url`를 사용하는 것이다.

새로운 URL 의 형태는
 
   - HTTPS 로 업데이트 할 때,
   `https://github.com/USERNAME/OTHERREPOSITORY.git`

   - SSH 로 업데이트 할 때,
   `git@github.com:USERNAME/OTHREREPOSITORY.git`

다음과 같다.

`git remote set-url`를 사용하여 바꾸기.

```
$ git remote set-url origin https://github.com/USERNAME/OTHERREPOSITORY.git
```
