## 11.15
- 알바를 하던 중 공부를 하기 위해 맥북을 꺼냈지만 와이파이 비밀번호를 모르는 상황이 벌어져서 와이파이 해킹하는 법에 대해 찾아봤습니다.
Xcode를 설치하고 설정에 들어가 cli를 설치하라고 했지만 영알못인 저는 알아듣지 못했음
- 맞춤법 '되'와 '돼'가 간간히 헷갈려서 글을 찾아 봤습니다. 세가지 방법(?)이 있더군요.
  - '되'는 '하'로 '돼'는 '해'로 바꿔서 더 자연스러운게 맞다는군요.
   ```
   밥 먹어야 돼요. > 밥 먹어야 해요. (O)
   밥 먹어야 되요. > 밥 먹어야 하요. (X)
   ```
  - '돼'를 '되어'로 풀어 사용해봅니다.
  ```
  박사가 돼고 싶다. > 박사가 되어고 싶다. (X)
  나는 아빠가 됐어. > 나는 아빠가 되었어. (O)
  ```
- 문장 마지막에는 무조건 '돼'  
  ```안되.(X) / 안돼.(O)```
## 11.16
- 친구가 '넌 프론트엔드야 백엔드야?' 라는 질문을 받았을때 이름만 알고 뜻을 몰라서 간단하게 찾아봤습니다.
  - Front End(프론트엔드): 사이트 이용자의 눈에 보이는 부분(HTML/CSS/JavaScript)을 개발하는 사람
  - Back End(백엔드): 사이트 이용자의 눈에 보이지 않는 부분(Server/DB/API)을 개발하는 사람
  - Full Stack: Front End와 Back End를 한꺼번에 다 하는 사람
- 맞춤법 '됬'과 '됐'의 구분법: '됬'은 없는 말임

## 11.18
- 맞춤법에 대한 슬랙봇을 만들었습니다!!! 새벽에 완성시키는게 목표였지만 지금 생각하면 정말 이상한 것에 삽질을 했습니다(새벽에 화나있었음)
아무튼 지금은 완성시킨 상태여서 매우 기분이 좋은 상태입니다. 새로운 레포지토리를 만들어서 파일을 올렸는데 실수 없이 돼서 숙련도가 조금은 올라간 느낌이랄까요 조금 뿌듯합니다! 

## 11.20
- .gitignore -> ```*.log  // '*'은 모든 것을 의미하며 *.log라면 a.log, b.log, c.log 모두 포함시킨다는 뜻입니다.```

## 11.24
- 맞춤법 봇을 heroku에 배포 했습니다.
- 함께 스터디 하는분이랑 "Greeny"라는 잔디봇 만들기 프로젝트를 시작하였습니다.

## 11.25
- Axios : 브라우저와 Node 환경에서 사용하는 Promise 기반의 HTTP Client로 사이트의 HTML을 가져올 때 사용할 라이브러리입니다.
- Cheerio : Node.js 환경에서 JQuery 처럼 DOM Selector 기능들을 제공합니다. Axios의 결과로 받은 데이터에서 필요한 데이터를 추출하는데 사용하는 라이브러리 입니다.
- Promise의 3가지 상태
  - Pending(대기): 비동기 처리 로직이 아직 완료되지 않은 상태
  - Fulfilled(이행): 비동기 처리가 완료되어 프로미스가 결과 값을 반환해준 상태
  - Rejected(실패): 비동기 처리가 실패하거나 오류가 발생한 상태
- [HTTP Request Headers](https://developer.mozilla.org/ko/docs/Web/HTTP/Headers)

## 11.26
- Math 객체는 수학 상수와 함수를 위한 프로퍼티와 메소드를 제공하는 빌트인 객체이다. Math 객체는 생성자 함수가 아니다. 따라서 Math 객체는 정적(static) 프로퍼티와 메소드만을 제공한다.
- '초보자를 위한 파이썬 300제' 내용을 바탕으로 자바스크립트 문제로 바꿔 풀어가면서 기본기를 다지는 중

## 11.27
- 컴퓨터 공부는 못했으나 휴대폰 구매 방법에 좀 더 능숙해지는 하루였음..
- 밖에 나가 놀기 전에 최소한의 할 일은 마치고 나가야 마음이 편하고 몸도 편하다..

## 11.28
- '초보자를 위한 파이썬 300제' 문제들을 자바스크립트 문제로 바꿔 공부했습니다.

## 11.29
> [프로그래머스](https://programmers.co.kr/)라는 곳에서 문제를 풀고 있으며 새로 알게 된 것들을 정리합니다.
- `includes()`: 메서드는 하나의 문자열이 다른 문자열에 포함되어 있는지를 판별하고, 결과를 true 또는 false 로 반환합니다.
```
// example
var sentence = 'The quick brown fox jumps over the lazy dog.';

var word = 'fox';

console.log(`The word "${word}" ${sentence.includes(word)? 'is' : 'is not'} in the sentence`);
// expected output: "The word "fox" is in the sentence"
```
- `compareFunction`: 정렬 순서를 정의하는 함수. 생략하면 배열은 각 요소의 문자열 변환에 따라 각 문자의 유니 코드 코드 포인트 값에 따라 정렬됩니다.
- [JavaScript Basic Function](Function of Basic JavaScript) 자바스크립트의 기초적인 문법들이 잘 정리되어있는 곳

## 11.30
- [프론트엔드 면접 문제](https://github.com/Songhun/Front-end-Developer-Interview-Questions/blob/master/Korean/README_KR.md?fbclid=IwAR2ILsRR9S0YW1nqkG2gHMykNFR6D6ziNLnuEskpaiKik3uXZeveERbk_Os)를 보며 공부를 해봤습니다.
- 영어 공부와 `Function()`에 대해 찾아보고 여러가지 방법으로 사용해봤습니다.
- [생활코딩](https://opentutorials.org/course/3085/18882)을 들었습니다.
