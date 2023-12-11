# controller

# service

# model

---
## Game

### 필드
- private final HostNumbers
- private PlayerNumbers

### 메서드
- 생성자 메서드
- 입력받은 숫자가 1인지 검증하는 메서드


- 두 숫자들을 비교해 성적을 계산하는 메서드


## Numbers

## HostNumbers

## PlayerNumbers


# view

## InputView
- 입력에 관한 안내사항과 입력을 받아오는 클래스

### 필드
- INPUT_NUMBERS
  - "숫자를 입력해주세요 : "
- RESTART_OR_END
  - 게임을 새로 시작하려면 1, 종료하려면 2를 입력하세요.

### 메서드
- 게임에 사용될 3자리의 숫자를 입력받는 메서드
- 게임 종료 후 다시 시작할지 종료할지 입력받는 메서드

---

## OutputView
- 인삿말, 성적 그리고 게임 종료에 대한 상태를 출력해주는 클래스

### 필드
- START_GAME
  - "숫자 야구 게임을 시작합니다."
- GAME_END
  - "3개의 숫자를 모두 맞히셨습니다! 게임 종료"

### 메서드
- 게임 시작 문구를 출력하는 메서드
- 게임 중 성적을 출력하는 메서드
- 게임 종료 시 게임 종료를 안내하는 메서드


---

# validator

