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
<img src="./nuxt_new.jpg" width="732px" height="412px">   

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
<img src="./devvsbuild.jpg" width="940px" height="587px">   

### 구조적 차이
<img src="./vuevsnuxt.png" width="1610px" height="646px">   

  
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
