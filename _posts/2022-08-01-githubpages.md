---
title: "GitHub Pages"
description: "GitHub의 무료 호스팅 서비스를 이용하여 웹페이지를 만들어보자."
---

{% if page.description %} {{ page.description }}{% endif %}

---

### ✔ Summary
- GitHub Pages = GitHub 저장소에서 바로 호스팅이 가능한 정적 웹 페이지
- Git Repository를 사용자이름.github.io라는 이름으로 생성하면 "https://사용자이름.github.io/" 라는 url을 가지는 웹사이트가 바로 만들어진다.
- 공식사이트 참고 : [https://pages.github.com/](https://pages.github.com/)

--- 


기술블로그를 쓰기 위한 방법으로  GitHub Pages를 택했다. 이를 알아보자.

# ✅ GitHub Pages 소개

공식사이트에서 가장 처음에 보이는 페이지이다. GitHub Pages는 GitHub 저장소에서 바로 호스팅이 가능한 웹사이트라고 소개한다. 개발자라면 모두가 사용하는 Git을 이용하여 자신만의 사이트를 쉽게 만들 수 있는 것이다. 

| ![GitHub Pages 공식사이트의 첫화면](/assets/images/2022-08-01-githubpages/introduce.png) |
|:--:|
| <b>GitHub Pages 공식사이트의 첫화면</b>|

이때 기억할 것은 GitHub Pages는 <span style="color: #35a8ad">정적 웹 페이지</span>인 점이다. 웹 서버에 미리 저장된 HTML, CSS, JavaScript 및 이미지 파일 등을 그대로 보여주는 것이다. 


# ✅ GitHub Pages 만들기

### 🟢 사용자명.github.io

GitHub Pages를 만드는 방법은 공식사이트에 잘 설명되어 있으며 매우 간단하다. <span style="color: #35a8ad">Git Repository를 사용자이름.github.io라는 이름으로 생성</span>하기만 하면 된다. 그러면 자동으로 "https://사용자이름.github.io/" 라는 url을 가지는 웹사이트가 만들어진다. 

만약 404에러가 난다면 호스팅에 시간이 걸리는 것이다. 잠시 후에 다시 시도해보자.

| ![잘 호스팅 된 GitHub Pages](/assets/images/2022-08-01-githubpages/gitbubpages.png) |
|:--:|
| <b>잘 호스팅 된 GitHub Pages</b>|


### 🟢 내 마음대로 이름 설정

Repository의 이름을 다른 것으로 설정하면 Git을 이용한 호스팅은 아예 불가능한가? 직접 해보니 그런것은 아니다. 직접 Setting에서 Pages를 직접 설정해야 하며 url이 "https://사용자이름.github.io/임의의Repository이름" 이 된다. 그리고 Branch 역시 설정할 수 있다. 

그러나 공식문서의 방법이 대표적이고 url도 더 심플하여 권장하는 방법이다.

| ![Setting에서 Pages를 GitHub Pages를 확인하고 설정할 수 있다.](/assets/images/2022-08-01-githubpages/setting.png) |
|:--:|
| <b>Setting에서 Pages를 GitHub Pages를 확인하고 설정할 수 있다.</b>|