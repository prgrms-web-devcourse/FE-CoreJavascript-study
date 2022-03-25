# Chapter2

## 1번 문제
- OX 퀴즈

    1) Variable Environment는 Lexical Environment와 달리 변경사항이 실시간으로 반영된다. (O, X)
    
    2) 전역 컨텍스트는 자바스크립트 파일이 열리는 순간 실행된다. (O, X)

    3) 여러 스코프에서 동일한 식별자를 선언한 경우에는 스코프 체인 상에서 가장 먼저 발견된 식별자에만 접근 가능하다. (O, X)

## 2번 문제

함수 선언문과 함수 표현식에서의 **호이스팅의 차이**에 대해 서술해주세요

## 3번 문제
아래의 코드를 보고 출력 결과를 작성하세요
```javascript

var a = 1;
var outer = function(){
    console.log(b); 
    var b = 'b';
    console.log(b); 

    var inner = function (){
        console.log(a);
        var a = 3;
    };
    inner();
    console.log(a);
    function b(){};
    console.log(b);
}
outer();
console.log(a);
```



