# kotepreps

## [SK네트웍스 Family AI캠프 13기] 스터디: 코딩 테스트 준비

: 코린이의 우당탕탕 코딩 테스트 도전기입니다.

## WORKFLOW

1. 팀장님께 문제를 받은 뒤, 미팅 전까지 `.ipynb` 파일에 풀어본 뒤 커밋합니다.

2. 미팅 이후 주고받은 피드백들을 반영하여 다시 커밋합니다.

## `/kotepreps`

- 매 회차마다 만든 `.ipynb` 문제풀이 파일을 저장합니다.

- 각 파일마다 문제 별 팁, 애로사항 등을 간략하게 기록합니다.

- 마지막엔 느낀점(개선된 부분, 아쉬웠던 부분 등)을 `총평`으로 기록합니다.

### 20250414: `kotepreps_01.ipynb`

1. video_ PCCP

* 알고리즘도 알고리즘이지만 문해력이 요구됐던

* 시간 연산을 위한 하위 함수(encode to int & decode to str)

* skip을 어떻게 볼 것인가(되감기 같은 연속적 작업 or 해당 시점으로의 Teleportation)?

    - What if an opening lasts just for 5 seconds?

* 두 가지 중 큰 값을 뽑아내는 것 `if ~, list_name.append(val)`도 되지만, built-in function `max`쓰면 용이할 듯

2. sum angle_ PCCE

* 평이한 문제: Remainder

3. fold money_ PCCE

* 지폐를 접어서 지갑 크기에 맞춰서 지갑에 넣자

* `While True:` vs `While meeting certain conditions:`

4. divide num_ PCCE

* 바보같이 홀짝으로 케이스 나눠서 포맷팅했던 문제

* 두자리씩 끊으니까, 이것도 100의 **remainder**로 개선

* **TRICK**: 정석은 `range(len(number_left) // 2)`지만, 숫자 크기 제약조건 활용하면 `range(5)`로 표기해도 테스트 통과하는 데는 문제 없음

5. cpr_ PCCE

* 리스트로 풀 경우 인덱싱을 i가 아닌 i+1로

* 빈 칸 채우기 문제였는데, 소스코드 짜는 문제였다면 딕셔너리에 저장해서 푸는 게 훨씬 나을 듯

6. Extra Problem: 물병_ BAEKJOON_1052

* **미쳐버린 문제** 🥴

* 이걸 이진수로 접근할 생각을 하기까지 오래걸렸던 문제. 이마저도 팀원분들과 머리 싸매고 한참 생각한 뒤 깨달았던

* 이진수로 풀기로 했다면, 그 뒤로는 Brute-force

7. 총평

* 쉬운 문제도 팀원분들이랑 같이 피드백해보니 얻을 게 많았다. 제약조건을 이용해 오히려 숏코딩을 실현하는 등.

* 어려운 문제는 지금 당장은 답도 없다. 특히 물병 풀면서 느낀 건, 이런 것들은 문제 풀이를 많이 해봐야 유사한 문제와 맞닥뜨렸을 때도 금방금방 생각날 것 같다.

> 이렇게 하면 풀리겠구나...!

## Retrospect: 코딩테스트

### 20250430: PCCE