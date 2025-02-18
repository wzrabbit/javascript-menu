![banner_final](https://user-images.githubusercontent.com/87642422/208154435-c89807e8-6413-4241-b87b-47e32474f522.png)

# 미션 - 점심 메뉴 추천

## 파일 구조

```
📦src
 ┣ 📂constant
 ┃ ┗ 📜Constant.js
 ┣ 📂model
 ┃ ┣ 📜CategoryChooser.js
 ┃ ┣ 📜ChooseSystem.js
 ┃ ┗ 📜MenuChooser.js
 ┣ 📂view
 ┃ ┣ 📜InputView.js
 ┃ ┗ 📜OutputView.js
 ┣ 📜App.js
 ┣ 📜Trimmer.js
 ┗ 📜Validator.js
```

## 기능 목록

### Model

#### ChooseSystem

- [x] 카테고리를 무작위로 선정하는 기능 구현
- [x] 새로운 코치의 이름들이 주어지면 모두 등록하는 기능 구현
- [x] 코치가 못 먹는 음식이 주어지면 등록하는 기능 구현
- [x] 메뉴를 모두 선정하는 기능 구현
- [x] 결과를 정리하여 반환하는 기능 구현

#### CategoryChooser

- [x] 월~금요일의 추천 카테고리를 무작위로 골라 반환하는 기능 구현

#### MenuChooser

- [x] 코치 1명의 메뉴를 모두 정하고 반환하는 기능 구현
  - [x] 랜덤 수 선정에 필요한 셔플 배열을 만드는 기능 구현
  - [x] 메뉴를 한 번 정하는 기능 구현
  - [x] 랜덤 메뉴를 하나 반환하는 기능 구현

### Controller

#### App

- [x] 게임 시작 단계 구현
- [x] 코치들의 이름을 입력받는 단계 구현
- [x] 각 코치마다 싫어하는 메뉴를 입력받는 단계 구현
- [x] 최종 결과를 보여주는 단계 구현

### View

#### InputView

- [x] 코치 이름 입력받는 기능 구현
- [x] 코치가 못 먹는 메뉴 입력받는 기능 구현

#### OutputView

- [x] 기본 시작/에러 메시지 출력하는 기능 구현
- [x] 최종 추천 결과를 출력하는 기능 구현
- [x] 출력 뷰를 닫는 기능 구현

### Miscellaneous

#### Validator

- [x] 코치 이름이 올바르게 입력되지 않았으면 에러를 발생시키는 기능 구현
- [x] 못 먹는 메뉴가 올바르게 입력되지 않았으면 에러를 발생시키는 기능 구현

#### Trimmer

- [x] 탬플릿 문자열의 출력을 위해 문자열을 정리하는 기능 구현
