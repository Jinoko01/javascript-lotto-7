## 💻프로젝트 소개

### 로또 발매기

로또 발매기는 1,000원에 1개 씩 중복되지 않는 6개의 번호로 구성된 로또를 구매하고 사용자가 중복되지 않은 6개의 번호와 보너스 번호를 입력하여 당첨 기준에 따라 1등부터 5등까지의 당첨금을 받고 당첨 내역과 수익률을 출력하는 프로그램입니다. 당첨 기준은 아래와 같습니다.

- 1등: 6개 번호 일치 / 2,000,000,000원
- 2등: 5개 번호 일치 + 보너스 번호 일치 / 30,000,000원
- 3등: 5개 번호 일치 / 1,500,000원
- 4등: 4개 번호 일치 / 50,000원
- 5등: 3개 번호 일치 / 5,000원

### 주요 기능

| **핵심 기능** | **명세**                                                                         |
| ------------- | -------------------------------------------------------------------------------- |
| 입력          | 사용자로부터 로또 구매 금액을 입력받는다.                                        |
| 로또          | 로또는 중복되지않는 6개의 번호를 랜덤으로 구성된다.                              |
| 당첨          | 사용자가 구매한 로또를 당첨 기준에 따라 등수를 매긴다.                           |
| 수익률        | 구매 금액과 당첨 금액을 비교하여 수익률이 얼마나 되는지 수치를 나타낸다.         |
| 출력          | 구매한 로또들의 번호를 오름차순으로 출력하고 당첨 통계와 수익률도 함께 출력한다. |

### 폴더 구조

```
📦src
 ┣ 📂constant
 ┃ ┣ 📜errorMessage.js
 ┃ ┣ 📜ioMessage.js
 ┃ ┗ 📜regex.js
 ┣ 📂utils
 ┃ ┣ 📜buyLottos.js
 ┃ ┣ 📜checkDuplication.js
 ┃ ┣ 📜checkNumberRange.js
 ┃ ┣ 📜inputService.js
 ┃ ┗ 📜outputService.js
 ┣ 📜App.js
 ┣ 📜index.js
 ┣ 📜Lotto.js
 ┗ 📜Validator.js
```

### 예외 케이스

| **기능**         | **명세**                                            | **에러 메시지**                              |
| ---------------- | --------------------------------------------------- | -------------------------------------------- |
| 구매 금액 입력   | 숫자로 입력되지 않은 경우                           | 금액은 숫자로 입력해주세요.                  |
| 구매 금액 입력   | 입력받은 금액이 0이하로 입력된 경우                 | 구매금액은 0보다 커야 합니다.                |
| 구매 금액 입력   | 입력받은 금액이 1,000으로 나누어 떨어지지 않는 경우 | 구매금액은 1000원 단위로 입력해주세요.       |
| 당첨 번호 입력   | 구분자가 쉼표가 아닌 경우                           | 구분자는 , 이어야 합니다.                    |
| 당첨 번호 입력   | 입력받은 숫자가 1~45 범위를 벗어나는 경우           | 로또 번호는 1부터 45 사이의 숫자여야 합니다. |
| 당첨 번호 입력   | 입력받은 숫자가 6개가 아닌 경우                     | 로또 번호는 6개여야 합니다.                  |
| 당첨 번호 입력   | 중복된 숫자가 있는 경우                             | 로또 번호에 중복된 숫자가 있습니다.          |
| 보너스 번호 입력 | 입력받은 숫자가 1~45 범위를 벗어나는 경우           | 로또 번호는 1부터 45 사이의 숫자여야 합니다. |
| 보너스 번호 입력 | 입력받은 문자열이 숫자가 아닌 경우                  | 보너스 번호는 숫자로 입력해주세요.           |

### 프로젝트 플로우 차트

## 🛠️ 테스트 케이스 목록

## 📺 실행 결과

## 📕 TMI

-
