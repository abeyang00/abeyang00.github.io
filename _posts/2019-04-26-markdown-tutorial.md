---
layout: post
title: Markdown을 사용할 때 필요한 최소한의 지식
image: /img/markdown.png
---

맨처음 .md파일로 포스트를 할때는 위에 layout, title등을 정해줄 수 있다.

image: /path/to/image.png 를 써주면 제목 위에 조그만한 이미지가 뜨게된다
bigimg: /path/to/big/img.png 를 써주면 제목이 들어가는 칸의 background 이미지로 사용된다
tags: [books, test] 같은걸 지정해주면 나중에 tag 별로 

### Italics and Bold
- Italics를 사용하고 싶으면 (_) 를 사용하면 된다.
  - Writing is _not_ hard
- Bold를 사용하고 싶으면 두 개의 asterisks(**)로 단어를 surround 시켜주면 된다.
  - Writing is **not** hard
- Bold와 Italics를 동시에 주고싶다면 **_ 단어 _** 를 사용해주면 된다.
  - Writing is **_not_** hard

### Headers
Header는 #를 사용해주면 된다.
- #를 사용을 많이 하면 할수록 header의 사이즈가 줄어들게 되고 총 6가지의 header가 존재한다.
- Header는 Bold로 바꿀수는 없지만 Italics는 해줄 수 있다.

### Links
기본적으로 두 가지의 link가 존재한다.
1. _inline link_
  - 링크를 걸고 싶은 단어에 bracket ([ ])을 쳐주고 그 다음 paranthesis ( )로 링크를 wrap 시켜준다. 
    - [Visit Github](https://www.github.com)
  - 링크를 걸고 싶은 단어에 emphasis를 bold를 사용해 줄 수 있다.
    - [Visit **Github**](https://www.github.com)
    
2. _reference link_
이름이 말해주는 것처럼 다른 장소에 있는 document등을 reference삼고 싶을때 사용할 수 있다.
Do you want to see [something fun][fun place]?

Here is [the website for you][another fun place]!

[fun place]: https://www.github.com

[another fun place]: https://www.google.com

### Images
이미지를 만드는것도 링크랑 동일하게 두가지의 방법이 있다. 링크랑 다른점은 느낌표[!] 를 bracket ([ ])으로 wrap해줄 단어앞에 사용해 준다는것이다
1. _inline image link_
  - ![이미지를 설명하는 단어] (이미지가 있는 링크)
![A representation of Octdrey Catburn](https://octodex.github.com/images/bannekat.png)

### Blockquotes
다른 소스에서의 quote를 불러오고 싶으면 caret (>) 를 사용해주면 된다.
> "May the force be with you" -Yoda

### Lists
list에도 두 가지 종류가 존재한다: unordered와 ordered. 이걸 다시 말하자면 bullet point가 있는 list로 만들것인가 아니면 number로 되어있는 list로 만들것인가 라고 볼수 있다.
- Unordered: asterisk ( * ) 을 단어 앞에 써주면 된다. list에 들어갈 각각의 item은 한줄에 하나씩 asterisk을 사용해서 써주면 된다.
- Ordered: 번호를 사용해서 list를 동일하게 만들어주면 된다

### Paragraph
Markdown에서 paragraph를 만드는건 그냥 text editor같이 줄을 바꿔서 새로운 문장을 쓰는 것이랑은 다르다.
그렇다고해서 매번 새로운 줄을 중간마다 삽입해서 또 paragraph를 만들자니 보기도 이상하고.. 이렇게 강제로 paragraph를 만드는걸 _hard break_라고 부른다. 하지만 우리가 원하는건 _soft break_! _soft break_는 그냥 키보드의 space를 눌러줘서 paragraph를 만드는 방식. 사실 이것도 난 무식한 방식이라 본다. 좀 더 손쉽고 무식하지 않은 방법이 있을 것 같기도한대....

Markdown에 대해 더 알고싶으면 다음 링크에서 알아보면 된다
- [http://en.wikipedia.org/wiki/Markdown#Example](http://en.wikipedia.org/wiki/Markdown#Example)
- [http://spec.commonmark.org/dingus/](http://spec.commonmark.org/dingus/)
- [http://johnmacfarlane.net/babelmark2/faq.html](http://johnmacfarlane.net/babelmark2/faq.html)
- [http://idratherbewriting.com/2013/06/04/exploring-markdown-in-collaborative-authoring-to-publishing-workflows/](http://idratherbewriting.com/2013/06/04/exploring-markdown-in-collaborative-authoring-to-publishing-workflows/)
- [https://www.markdownguide.org](https://www.markdownguide.org)

