# 스코프

- 결론
    - 모든 식별자(변수 이름, 함수 이름, 클래스 이름 등)는 자신이 선언된 위치에 의해 다른 코드에서 식별자 자신을 참조할 수 있는 유효 범위가 결정
- 설명
    - 상위 스코프에서 유효한 변수는 하위 스코프에서 참조 가능하지만 반대로는 안됨
    - 함수레벨 스코프(ES6이전부터 사용)
        - var 키워드로 선언된 변수
        - 함수의 코드 블록만을 지역 스코프로 인정
        - 블록 레벨 스코프 불인정
    - 블록레벨 스코프(ES6부터 사용)
        - let 키워드로 선언한 변수
        - 모든 코드 블록(함수, if, for, while, try/catch 등)을 지역 스코프로 인정
- 요약
    - 식별자가 유효한 범위
- 참고
    - 모던 자바스크립트 Deep Dive