# 우아한테크코스 5기 프리코스 1주차

## 기능 구현 목록 📝

### 문제 1

- **각 사용자의 페이지 번호 리스트 유효성 검사**
    - [예외처리] 리스트의 사이즈가 2인지 검사
    - [예외처리] 값이 [3, 398] 인지 검사
    - [예외처리] 리스트의 인덱스 0번 값이 홀수인지 검사
    - [예외처리] 리스트의 인덱스 1번 값이 짝수인지 검사
    - [예외처리] `인덱스 0번 값 + 1 = 인덱스 1번 값` 인지 검사
- **각 사용자의 점수 구하기**
    - 왼쪽 페이지 번호의 각 자리 숫자를 더한다.
    - 왼쪽 페이지 번호의 각 자리 숫자를 곱한다.
    - 오른쪽 페이지 번호의 각 자리 숫자를 더한다.
    - 오른쪽 페이지 번호의 각 자리 숫자를 곱한다.
    - 위 네 개의 숫자 중 가장 큰 수가 점수가 된다.
- **게임의 승자 구하기**
    - 각 사용자의 점수를 비교
    - 무승부는 0, 포비가 이긴다면 1, 크롱이 이긴다면 2 반환하고 종료
- **예외처리**
    - -1 을 반환하고 종료