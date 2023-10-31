---
layout: post
title:  "vs code 로 git blog markdown 작성하는 방법 - 윤슬"
date:   2023-10-30 21:03:36 
categories: vs-code markdown
---
어떤 Markdown 에디터를 사용해도 되고 텍스트 파일을 생성하는 어떤 편집틀이라도 마크다운 파일을 만들수 있지만 vs code로 작성하는 방법을 알아본다

<!--주석으로 사용함 -->
### [vs code 를 다운](https://code.visualstudio.com/download) 받아 설치한다   

### vs code를 실행하고 좌측 extentions(Ctrl + Shift + x) 에서 "Markdown All in One" 플러그인을 설치 한다  
<!-- 이미지 삽입 방법은 아래 두가지 모두 사용 할수 있으나 아래것(![image])은 크기 조절이 되지 않는다 -->
<img src="/img/markdownAllinOne.png" width="500px" height="400px" title="px(픽셀) 크기 설정" alt="markdownAllinOne"><br/>  

### "File" 메뉴에서 "New Text File" 선택해서 새 파일을 생성하면 아래와 같은 메시지가 나온다  
    새 파일의 이름은 날짜-제목-작성자이름"2023-10-31-_title_" 형색으로 한다

### "Select a language" - "Select language Mode" 에서 "m" 을 치면 확장자들이 죽 나열되는데 markdown 을 선택한다
![image](/img/마크다운새파일생성.png){: width="1200" height="450"}

## preview 창을 열면 실제 블로그에서 적용된 view를 실시간으로 볼수 있다
<img src="/img/open_preview.png" width="1200px" height="450px" title="px(픽셀) 크기 설정" alt="open_preview"><br/>  

## 문서의 헤더 부분 작성 방법
    문서 제목과 작성자
        title: "문서제목 - 작성자 이름"
    날짜
        date: year-month-day hour:minute:second
    분류
        category: 현재 사용하지 않으므로 비워 둬도 된다  

<img src="/img/post_header.png" width="800px" height="300px" title="px(픽셀) 크기 설정" alt="post_header"><br/>   

## 중산고 코딩 동아리 B조 블로그에 포스팅  

<span style="color: #2D3748; background-color:#f6f8fa;"> 이렇게 작성한 파일을 조장의 "[github repository][git-hub-repo]" 로 **pull request** 하면 됩니다.</span>

이렇게 작성한 파일을 조장의 "[github repository][git-hub-repo]" 로 <span style="font-family:Papyrus; font-size:4em;">pull request !</span> 하면 됩니다.


[git-hub-repo]: https://jekyllrb.com/docs/home
