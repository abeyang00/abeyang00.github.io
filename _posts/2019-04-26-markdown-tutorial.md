---
layout: post
title: Markdown을 사용할 때 필요한 최소한의 지식
---
## Italics and Bold

- Italics를 사용하고 싶으면 (_) 를 사용하면 된다.
  - Writing is _not_ hard
- Bold를 사용하고 싶으면 두 개의 asterisks(**)로 단어를 surround 시켜주면 된다.
  - Writing is **not** hard
- Bold와 Italics를 동시에 주고싶다면 **_단어_** 를 사용해주면 된다.
  - Writing is **_not_** hard

## Headers

Header는 #를 사용해주면 된다.
- #를 사용을 많이 하면 할수록 header의 사이즈가 줄어들게 되고 총 6가지의 header가 존재한다.
- Header는 Bold로 바꿀수는 없지만 Italics는 해줄 수 있다.

## Links

기본적으로 두 가지의 link가 존재한다.
1. _inline link_
  - 링크를 걸고 싶은 단어에 bracket ([])을 쳐주고 그 다음 paranthesis로 링크를 wrap 시켜준다. 
    - [Visit Github](www.github.com)
  - 링크를 걸고 싶은 단어에 emphasis를 bold를 사용해 줄 수 있다.
    - [Visit **Github**](www.github.com)
    
2. _reference lin
이름이 말해주는 것처럼 다른 장소에 있는 document등을 reference삼고 싶을때 사용할 수 있다.
  - Do you want to see [something fun][fun place]. Here is [something fun2][fun place2]
    [fun place]: www.github.com
    [fun place2]: www.google.com
