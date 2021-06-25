---
layout: page
title: HOW TO USE github.io?
image: ect/26.jpg
---

## youtube
<iframe width="560" height="315" src="https://www.youtube.com/embed/8Q99GeMjx_0" frameborder="0" allowfullscreen></iframe>



적용 참고 :

GitHub 블로그 기본 설정하기 - 취미로 코딩하는 개발자 (devinlife.com)



1. 지킬테마란

- 깃허브 블로그 스킨같은것

- 유료  or 무료

- 기본적으로 정적페이지



2. HOW TO

- 기존방법인 저장소/유저이름.github.io 를 먼저 만들면 페이지 생성이 안된다(404)

- Jekyll Themes  사이트에 접속한다

- 마음에 드는 테마를 클릭한다

- homepage 버튼을 클릭

- FORK해 내 저장소로 가져온다 (SELEN/테마이름.io)

- 저장소이름을 변경한다. (SELEN/테마이름.github.io - > SELEN/SELEN.github.io)

- _config.yml 파일을 찾아서 수정한다(3번에서 계속)





3. _config.yml 수정하는법

- _config.yml은 블로그 설정파일

- title : 블로그이름

- description : 설명



- 현재 테마는 다른 주소로 되어있을 수도 있어 바로 적용을 확인하면 에러가 발생할 수도 있다.

- 따라서 baseurl은 ““으로 url은 “[내블로그주소]“로 변경해주어야 한다.

-> baseurl: ""
#블로그 메인 사이트
-> url: "https://imselen.github.io/"







4. post 쓰는법

- _posts/ 밑에 있다.

- post는 블로그에 글이나 이미지 등을 올릴 수 있는 페이지 이다.

- yyyy-mm-dd-쓰고싶은말.markdown( OR md이라고 써도 읽힘)


![1]({{site.baseurl}}/images/pages/set_git_io/1.png)



- layout을 post라 작성

- title에 제목 작성

- date에 yyyy-mm-dd 작성(시간 초 등은 생략가능)

- img : 지킬테마마다 다른듯(img / or image)  어느 폴더 아래있는지 확인 후 경로 작성하는걸 추천(여기 테마는 안그래도 적용됨)


![2]({{site.baseurl}}/images/pages/set_git_io/2.png)









