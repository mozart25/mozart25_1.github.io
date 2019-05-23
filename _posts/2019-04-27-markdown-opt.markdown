---
layout: post
title:  "markdown 기능 사용법"
date:   2019-04-27 22:26:00
categories: jekyll update
---

<h3> 오늘은 Markdown 에 대해서 하나씩 하나씩 알아보겠습니다.</h3>
<h4> 아직 Markdown을 배워가는 과정이라 부족한 부분이 많습니다.</h4>


수정할 부분이 많은 하루입니다.<br>

지하철에서 계속 __markdown__ 사용법을 검색해 보았습니다. 목적은 블로그의 가독성을 높임과 동시에 전달력을 높이기 위함입니다.<br>

어제는 **markdown**을 작성하다가 졸고있는 저의 모습을 보니, 역시 markdown에 익숙해지는데 상당한 시간이 필요함을 느꼈습니다.<br>

**markdown** 사용법에 앞서서, 제가 놓치고 있었던 부분에 대한 설명을 드리고자 합니다.<br>
바로,로컬 서버에서 수정사항을 바로바로 확인할 수 있었던 점입니다.~~(그런데, 새로운 마크다운 파일을 git push 후에 로컬로 수행하면 새로운 포스트가 뜨지 않는 현상이 나타납니다..뭐지)~~


  > 다음은 블로그 root가 있는 곳으로 이동한 후 site를 build하는 작업입니다.

  ```
  # change into root directory
  cd myblog

  # build the site and make it on a local server
  bundle exec jekyll serve 또는  jekyll serve 입력
  ```

  - 로컬 서버를 통해서, markdown의 수정사항을 바로바로 체크할 수 있습니다.~~(git push를 하면서 markdown을 확인하는 나란 바보..)~~


  > 추가로, 수정이나 작성한 블로그를 깃 푸쉬하기 위해서는 __.git__ 이 위치한 디렉토리에서 푸쉬를 해주어야 합니다.

  ```
  git push origin master
  ```
  > 본격적으로 마크다운을 이용한 방법을 설명드리겠습니다.


  > 자바스크립트 코드를 작성한 경우입니다.

  ```js
  let a = 2;
  ```
  > 다음의 경우에는 파이썬 코드를 작성한 경우입니다.

  ```python
  list = [1,2,3,4]
  ```

  > 다음은 html 코드를 작성한 경우입니다.

  ```html
  <p class="dd">hello</p>
  ```

  > 다음은 터미널에서 코드를 작성한 경우입니다.
  ```
  ls -al
  ```

  > 네이버로 링크를 통해서 연결하는 방법입니다. "네이버로 이동"이라는 링크가 나타납니다.

  ```
  [네이버로 이동](https://www.naver.com)
  ```
  [네이버로 이동](https://www.naver.com)


  > 이미지를 삽입하는 방법입니다.

  ![](/img/aaa.png)
  <img src="/img/aaa.png" width="100">
