# Nuxt.js?
Nuxt.js는 Vue.js 프레임워크를 기반으로 SSR(Server Side Rendering) 웹 페이지를 만들 수 있도록 해 주는 라이브러리입니다.    
SEO 등의 문제로 CSR이 아닌 SSR 웹을 구축해야 하는 경우에 유용하게 사용할 수 있습니다.           

### Nuxt.js 설치
설치하는 방법은 크게 [3가지 방법](https://uxgjs.tistory.com/146)이 있습니다.   
1. 수동으로 설치하는 방법
2. vue-cli로 설치로 설치하는 방법
3. npm(yarn)으로 설치하는 방법
```
$ npx create-nuxt-app nuxt_app
$ yarn create-nuxt-app nuxt_app
```
<img src="/img/nuxt_new.jpg" width="732px" height="412px">   

참고 : [프로젝트 설정 방법](https://velog.io/@brviolet/Nuxt.js-%EC%8B%9C%EC%9E%91%ED%95%98%EA%B8%B0-1.-%EC%84%A4%EC%B9%98)   

### Nuxt.js 실행
해당 폴더(nuxt_app)로 이동후 실행 합니다.   
Development         
```
$ npm run dev
$ yarn run dev
```
Production         
```
$ npm run build
$ npm start
$ yarn run build
$ yarn start
```    
<img src="../img/devvsbuild.jpg" width="940px" height="587px">   

### 차이점  
* 프로젝트 전반적인 폴더 구조가 조금 다르지만 대체로 비슷하게 동작합니다.   
* 라우터 셋업이 달라집니다. 디렉토리 구조에 따라 자동생성하는 것을 디폴트로 합니다.   
* 개발 및 배포 환경이 조금 달라집니다.   
* Layout을 컴포넌트의 프로퍼티로써 사용할 수 있습니다.   

### 메타 태그   
SSR의 가장 중요한 목적 중의 하나인 SEO에 필요한 메타태그를 훨씬 편하게 달 수 있게 되었습니다.      
기존 Vue 프로젝트에서 메타 태그를 달기 위해서는 vue-meta 등의 외부 라이브러리를 이용해야 했지만 nuxt에서는 별다른 추가작업 없이 메타 태그를 작성할 수 있습니다.      
참고 :[메타 태그 ](https://ko.nuxtjs.org/docs/2.x/components-glossary/pages-head/)

### 구조적 차이
<img src="./img/vuevsnuxt.png" width="1040px" height="500px">  

### 풀어야할 숙제
NUXT 관련 front 예상 이슈 검토사항.   
* * *   
0. jquery 관련 이벤트 맵핑
1. youtube 여러개 영상 제어.(youtube api사용)
2. mp4 영상제어
3. slick 배너 롤링 관련 이슈.
4. naver, 카카오, google map 지원 관련.
5. 주소검색 다음 api 관련
6. 동적컨텐츠 로드시 event관련.(click등)
7. sns공유시 url 관련 이슈.(서버랜더링)
* * *

### 참고 문서   
* [공식 가이드](https://nuxtjs.org/docs/2.x/get-started/installation)   
* [가이드북(한글)](https://vue-nuxt.gitbook.io/nuxt/)   
* [Vue.js vs Nuxt.js](https://velog.io/@bluestragglr/Nuxt.js-vs-Vue.js-SSR-%EC%8B%9C%EC%9E%91%ED%95%98%EA%B8%B0#%EB%B0%94%EC%81%9C-%ED%98%84%EB%8C%80%EC%9D%B8%EC%9D%84-%EC%9C%84%ED%95%9C-%EC%9A%94%EC%95%BD)   
* [캡틴판교의 Cracking Vue.js(T아카데미)](https://joshua1988.github.io/vue-camp/textbook.html)   
