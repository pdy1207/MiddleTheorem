<h1 align="center">
<br>
  <a href="#"><img src="https://teslacafe.co.kr/data/editor/2112/16399792526435.gif" alt="Front-End Performance Checklist" height="300"></a>
  <br>
  <br>
  프론트 개발자 맞습니까?
  <br>
</h1>

<h4 align="center"> 👤 최소한 알아야하는것과 보고 느낀것들 정리하기</h4>
<p align="center">한가지 단순한 규칙: "성능을 고려한 설계와 코드"</p>

## 소개

```
프론트 개발하면서 필자가 공부했던 자료와 보았던것과 
프론트엔드 개발자로서 최소한 알아야하거나 체크해야할 요소들의 목록이며, 프로젝트에 적용해야 하는 것입니다.
또한, 프론트에 관한 정리를 한 곳 입니다.
```

## 내 코드가 좋은코드인지 모르겠어요.

1. 원하는 기능이 잘 구현되었는가 
2. 확장성이 좋은가
3. 나중에 관리가 쉬울 것인가
4. 성능문제 없는가

## 기본적으로 다 알고 대답할 수 있어야 하는 내용

```
웹 서비스를 개발하기 위해서 기본적으로 알아야 하는 지식과 함께 
빠르게 변화하는 프런트엔드 개발 생태계를 따라가기 위한 노력
```

1. **[❓ 프론트엔드가 뭐에요?  ](https://github.com/pdy1207/MiddleTheorem/blob/main/%EA%B8%B0%EB%B3%B8%EC%A0%81%EC%9C%BC%EB%A1%9C%EC%95%8C%EA%B3%A0%EC%9E%88%EC%96%B4%EC%95%BC../%EA%B7%B8%EB%9E%98%EC%84%9C%20%ED%94%84%EB%A1%A0%ED%8A%B8%EC%97%94%EB%93%9C%EA%B0%80%20%EB%AD%94%EB%8D%B0%3F.md)**
2. **[❓ 라이브러리 vs 프레임워크  ](https://github.com/pdy1207/MiddleTheorem/blob/main/%EA%B8%B0%EB%B3%B8%EC%A0%81%EC%9C%BC%EB%A1%9C%EC%95%8C%EA%B3%A0%EC%9E%88%EC%96%B4%EC%95%BC../%ED%94%84%EB%A0%88%EC%9E%84%EC%9B%8C%ED%81%AC%20vs%20%EB%9D%BC%EC%9D%B4%EB%B8%8C%EB%9F%AC%EB%A6%AC.md)**
3. **[❓ 브라우저 저장소에 대해서 설명해 보세요  ](https://github.com/pdy1207/MiddleTheorem/blob/main/%EA%B8%B0%EB%B3%B8%EC%A0%81%EC%9C%BC%EB%A1%9C%EC%95%8C%EA%B3%A0%EC%9E%88%EC%96%B4%EC%95%BC../%EB%B8%8C%EB%9D%BC%EC%9A%B0%EC%A0%80%20%EC%A0%80%EC%9E%A5%EC%86%8C%EC%97%90%20%EB%8C%80%ED%95%B4%EC%84%9C%20%EC%84%A4%EB%AA%85%ED%95%B4%20%EB%B3%B4%EC%84%B8%EC%9A%94.md)**
4. **[❓ 자바스크립트 this란?  ]**
5. **[❓ 자바스크립트 이벤트 관리 방법? 보통 어떤 식으로 이벤트를 설계해야 하는지?  ]**
6. **[❓ 자바스크립트 비동기 처리에 대한 설명  ]**
7. **[❓ 프런트엔드 개발은 지속적으로 학습해야 하는 분야인데 어떤식으로 학습을 하고 있는지?  ]**

## 알아야 할 것이다.

1. **[서버 란?](https://github.com/pdy1207/Node.js/wiki/1.-%EC%84%9C%EB%B2%84%EB%9E%80-%EB%AC%B4%EC%97%87%EC%9D%B8%EA%B0%80%3F)**
2. **["REST API작성해주세요" "REST API" 뭔데?](https://github.com/pdy1207/Node.js/wiki/4.-%22REST-API%EC%9E%91%EC%84%B1%ED%95%B4%EC%A3%BC%EC%84%B8%EC%9A%94%22-%22REST-API%22-%EB%AD%94%EB%8D%B0%3F)**



## 직무와 관련하여서 최소 70% 이상 대답할 수 있으면 좋지 않을까? 하는 내용

```
프런트엔드 개발의 기술적인 부분뿐만 아니라 지원자의 전반적인 웹 서비스 개발 경험을 파악
```

- 프런트엔드 빌드 시스템에 대해서 설명해보세요.
    - 바벨이란?
    - 폴리필이란?
    - [Node.js란?](https://github.com/pdy1207/MiddleTheorem/blob/main/%EC%A7%81%EB%AC%B4%EA%B4%80%EB%A0%A8%2070%25%EB%8C%80%EB%8B%B5%EC%9D%84%20%ED%95%A0%EC%A4%84%EC%95%8C%EC%95%84%EC%95%BC../%ED%94%84%EB%9F%B0%ED%8A%B8%EC%97%94%EB%93%9C%20%EB%B9%8C%EB%93%9C%20%EC%8B%9C%EC%8A%A4%ED%85%9C/Node.js%EB%9E%80%3F.md)
    - [NPM이란?](https://github.com/pdy1207/MiddleTheorem/blob/main/%EC%A7%81%EB%AC%B4%EA%B4%80%EB%A0%A8%2070%25%EB%8C%80%EB%8B%B5%EC%9D%84%20%ED%95%A0%EC%A4%84%EC%95%8C%EC%95%84%EC%95%BC../%ED%94%84%EB%9F%B0%ED%8A%B8%EC%97%94%EB%93%9C%20%EB%B9%8C%EB%93%9C%20%EC%8B%9C%EC%8A%A4%ED%85%9C/npm%EC%9D%B4%EB%9E%80%3F.md)
    - ESLint란?
    - [Prettier란?](https://github.com/pdy1207/MiddleTheorem/blob/main/%EC%A7%81%EB%AC%B4%EA%B4%80%EB%A0%A8%2070%25%EB%8C%80%EB%8B%B5%EC%9D%84%20%ED%95%A0%EC%A4%84%EC%95%8C%EC%95%84%EC%95%BC../%ED%94%84%EB%9F%B0%ED%8A%B8%EC%97%94%EB%93%9C%20%EB%B9%8C%EB%93%9C%20%EC%8B%9C%EC%8A%A4%ED%85%9C/Prettier%EB%9E%80%3F.md)
    - 웹 태스크 매니저란?
- 웹팩이란? 모듈 번들러가 무엇인가요?

- 자바스크립트 프레임워크를 써봤는지? 써봤다면 어떤 걸 쓰는지? 만약 쓴다면 쓰는 이유와 썼을 때의 장점?

- “기획 - 디자인 - API 개발 - 프런트엔드 개발”의 서비스 절차에서 프런트엔드 개발자의 역할은 무엇이라고 생각하는지?

- CORS란? CORS를 해결하기 위한 방법을 아는 대로 모두 설명해 주시고 보통 어떤 방식으로 해결하는지 <br>
   자주 사용하는 방법 1가지와 함께 실제 해결하신 경험을 공유해 주세요. <br>
- 프런트엔드 성능 최적화란? 프런트엔드 성능 최적화 경험이 있다면 자세하게 설명해달라.
- 백엔드 개발 경험이 있는가?
    - (꼬리 질문) REST API 구축 경험과 구현 관점에서의 간단한 REST API 설계 방식 설명해 보세요. <br>
      브라우저의 URL 요청을 받아서 서버의 데이터를 화면에 다시 뿌려주기까지의 백엔드 쪽의 플로우를 알고 있는지 확인하는 차원. <br>
      
- Virtual DOM이 뭔지 아시는지? 썼을 때의 장점?

    - (꼬리 질문) 브라우저 동작 원리 아는 만큼 설명
    
- 웹 서비스 배포 시스템 구축 경험?
    - (꼬리 질문) CI, CD가 무엇인지 아는지? 구축해본 경험 혹은 사용해본 경험이 있는지
    
- 테스트 자동화 경험? 단위 테스트 또는 E2E 코드를 작성해 본적이 있는지?
    - (꼬리 질문) 테스팅 라이브러리와 프레임워크에 특화된 테스팅 라이브러리는 각각 어떤 걸 썼는지?
    - (꼬리 질문) 테스트 대상과 커버리지는 보통 어떻게 잡는지?
    
- 웹 접근성과 시맨틱 마크업이란? 이 2가지를 지키기 위해 보통 어떤식으로 마크업을 작성하는지?

- 웹 서비스를 기획부터 배포까지 모두 스스로 해본 경험이 있는가? 토이 프로젝트나 회사 서비스 등
    - (꼬리 질문) 구체적으로 어떤 역할을 수행했는지 설명
    
- SEO(검색 엔진 최적화)란? 적용 사례가 있으면 구체적인 적용 방법도 같이 설명

- REST API로 받은 객체와 배열은 보통 어떤 자바스크립트 API나 로직을 이용해서 화면에 맞게 가공을 하는지?

    - (꼬리 질문) map, filter, reduce API 사용 경험과 각각 설명
    
- 함수형 프로그래밍이란?
    - (꼬리 질문) 자바스크립트 클로저란?
    - (꼬리 질문) 자바스크립트 프로토타입이란?
- 서버 사이드 렌더링과 싱글 페이지 애플리케이션의 차이점?

    - (꼬리 질문) 서버 사이드 렌더링이나 SPA로 각각 구현해 본 경험이 있는지?




## 알면 좋음

- top, body, bottom 부분을 나눠서 하나 씩 천천히 공부하세요. 굳이 한번에 끝! <br>
이렇게 하면 괜히 배워야 하는 양에 압도 당하고 힘들어합니다. <br>
- 품에 차고 다닐 칼은 하나만 잘 갈아서 가지고 다니자.
- 문법을 알고 활용도를 높이며, 가장 많이 사용되는 부분을 캐치해야한다.

## 그 외 더 기초는 [욜?루](https://github.com/pdy1207/FSR)
