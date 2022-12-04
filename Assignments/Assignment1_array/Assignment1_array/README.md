# [Data Structure]Assignment1_Array

## 목적

- 기본적인 자료구조로인 배열 (array)의 정의와 활용
- 포인터를 이용하는 배열의 정의와 접근법 숙지
- 동적 메모리 할당을 이용한 다양한 크기의 행열 연산의 이해와 구현
- 희소 행열과 전치 행열의 활용
- 주어진 입력에 따른 시간의 복잡도 분석: 실행시간, 반복수 등

---

## 기능과 사양 (Function & Specification)

- 주어진 입력 데이터의 크기에 무관한 2-차원 행열의 연산
- 각 행열의 크기는 입력으로 받아야 함
- 행열의 값은 random 함수를 사용하여 채워짐
- 행열 연산을 구현하기 위한 자료구조
    - C 언어의 기본 자료구조인 배열
    - 기본 자료구조의 변형

---

## **Problems**

### Problem1

덧셈, 뺄셈, 곱셈, element-wise 나눗셈을 수행하는 함수를 설계하고 구현하시오. Element-wise 나눗셈은 동일한 행열 위치의 값과 나눗셈을 수행하는 연산입니다. 덧셈, 뺄셈, element-wise 나눗셈 연산은 동일한 크기의 행열에서만 사용합니다.

### Problem2

Problem 1의 테스트를 다양한 행열의 크기에 따라 실행하여 시간의 복잡도를 분석하시오. 테스트는 10개 이상입니다.

<aside>
💡 조건

- *덧셈, 뺄셈, 나눗셈 입력이 m과 n이면 x−축은 m × n으로 함*
- *곱셈 입력이 m, k과 k, n이면 x−축은 n × k × m으로 함*
</aside>

### Problem3

주어진 2차 행열의 희소 행열과 전치 행열을 구성하는 함수를 작성하고 테스트하시오.

### Problem4

Problem 3의 테스트를 Problem 2와 동일한 행열에 대해 실행하여 시간의 복잡도를 분석하시오.

### Problem5

Problem 2 & 4의 결과를 데이터 크기와 실행시간을 비교하고 설명하시오.