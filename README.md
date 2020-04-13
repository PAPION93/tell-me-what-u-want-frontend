# 최적의 음식점 찾기

> 현재위치와 음식종류 그리고 +a 로 최적의 음식점을 찾아보자  
> 2020-01-06 첫 작성, 최대 일주일간 아이디어만 내볼 것  
> 2020-01-11 추가작성  
> 2020-01-13 시작예정

# 시작 전

## 1. 계기

-   나는 퇴근하고 그분과 함께 무엇을 먹으면 좋을지 생각이 나지 않는다.
-   미리 생각안하고 계획없다고 혼이 난다.
-   그래도 난 업무시간엔 생각할 수 없다! 개발을 열심히!
-   지금도 혼나고 먼길 돌아와 공부할겸 한번 만들어본다.
-   간단하게

## 2. 사용기술

-   Front-end : React
-   Back-end : Spring boot
-   AWS
-   도커라이징
-   네이버 클라우드 플랫폼 Maps
-   사실 모든것이 처음이다. 이번 토이프로젝트로 사용해보고 싶었던 기술을 모두 건드려보기만해도 핵이득.

## 2.5 추가 생각

-   모두 새로 접하는 기술이기 때문에 Study Log 작성하기
-   꾸준하게 + 데드라인 잡기
    -   벌써 오랜만에 들어옴. 그래서 꾸준함을 위해 날짜나 시간을 정할 필요가 있음.
    -   주중 2번, 주말은 들여다볼 것
    -   1차 데드라인 : 4/30

## 3. 기능

-   가. 현위치 또는 위치검색으로 시작
-   나. 원하는 음식 종류 필터링 또는 선정
-   다. 음식점 선택
    -   블로그 서칭
    -   길찾기 안내
-   라. 추천 음식점

    -   날씨와 거리를 고려

-   만다라트 계획표

    -   음식을 좀더 세부적으로 구분가능한지 서칭
    -   너무 딱딱한 느낌이 들 수 있음

-   부가 기능
    -   음식점 평가 기능
    -   일일 검색 순위

---

# 시작

## 1. ReactJS

1.0. 세팅

-   [node.js 설치](https://nodejs.org/ko/) (npm)
-   npx 설치(npm install npx -g)
-   Git 준비
-   VScode 사용

1.1. 생성 및 실행

-   `npx create-react-app tell-me-what-u-want`
-   In VScode `Open Folder`
-   `npm start`

1.2. ReactJS

-   Virtual DOM
-   Component
-   JSX
-   prop-types 유효성검사
    -   `npm i prop-types`
-   axios API 요청
    -   `npm i axios`
-   router
    -   `npm install react-router-dom`
-   redux (state save)
