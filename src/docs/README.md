# ✏️ 과제 진행 기능 요구 사항

## Goal
기본적으로 1부터 9까지 서로 다른 수로 이루어진 3자리의 수를 맞추는 게임이다.

### TODO - 기능 목록
 - [ ] 실행 결과 예시에 따라 입, 출력 컨벤션 맞추기
 - [ ] 컴퓨터의 입력 값과 사용자의 입력 값 스트라이크, 볼, 낫싱 counting 하기
 - [ ] 사용자가 잘못된 값 입력 시 `IllegalArgumentException` 예외 발생 후 종료시키기
 - [ ] 게임 종료 선택 구현

### 실행 결과 예시
```kotlin
숫자 야구 게임을 시작합니다.
숫자를 입력해주세요 : 123
1볼 1스트라이크
숫자를 입력해주세요 : 145
1볼
숫자를 입력해주세요 : 671
2볼
숫자를 입력해주세요 : 216
1스트라이크
숫자를 입력해주세요 : 713
3스트라이크
3개의 숫자를 모두 맞히셨습니다! 게임 종료
게임을 새로 시작하려면 1, 종료하려면 2를 입력하세요.
1
숫자를 입력해주세요 : 123
1볼
...
```