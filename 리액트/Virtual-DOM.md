# Virtual-DOM?

> DOM의 복사본 js 객체 형식으로 메모리안에 저장됨

## DOM?

> 웹 페이지을 구성하고있는 HTML 요소들을 트리 구조로 표현한 것

### DOM 조작

querySelector, getElementById 키워드를 사용해서 직접적으로 DOM을 조작

1. 조작되는 엘리먼트 탐색
2. 해당 엘리먼트와 자식 엘리먼트 제거
3. 새롭게 수정된 엘리먼트로 교체
4. 이후 다시 브라우저 렌더링 과정 진행 (DOM -> CSSOM -> Render Tree)

DOM을 변경하는 작업은
