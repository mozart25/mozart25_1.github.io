---
layout: post
title:  "터미널에서 디렉토리를 쉽게 보는 법"
date:   2019-04-26 23:57:57 +0900
categories: jekyll update
---

이번 블로그는 터미널에서 tree를 사용하는 법입니다.

사실 이전의 블로그에서 NERDTree 플러그인을 사용하게 되면서, 블로그에 대한 접근이 시각적으로 수월해 졌습니다.

다만, vim을 사용하지 않는 경우에 특정 디렉토리 내에 있는 파일이나, 디렉토리를 보기 위해서 tree라는 것을 알게 되었고, 유용하게 사용하고 있습니다.

tree는 "brew install tree"를 통해 사용할 수 있습니다. (사진은 차후에 첨부하겠습니다.)

특정 디렉토리 내에서 tree를 치면, 하위 디렉토리가 적은 경우에는 쉽게 파악이 가능합니다.

하지만, 하위 디렉토리나, 파일이 엄청나게 많은 경우, tree를 통해 터미널 상에서 내부 내용들을 파악하기가 힘이 듭니다.

따라서, 이번에 드리고 싶은 팁은 최대한 보고 싶은 레벨(수준)으로 tree를 설정하는 것입니다.

1) 먼저, tldr tree를 입력합니다.

2) - Show files and directories up to 'num' levels of depth (where 1 means the current directory):
    tree -L num

3) 여기서 tree -L 2 나 tree -L 1 과 같이 숫자를 바꾸면서 tree의 레벨을 설정할 수 있습니다.

3-1) 1이면 1번째 디렉토리(?) 2이면 한 번더 깊게 들어갑니다.

4) vim 상에서 NERDTree를 사용함과 동시에 터미널 상에서 tree를 같이 사용하니, 정말 편리하네요!

이번 블로그를 작성하면서 듣고 있는 노래는 "EPIK HIGH - LOVE STORY, fest. 아이유" 입니다.
