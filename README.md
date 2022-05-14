## iOS 커리어 스타터 캠프

### 묵찌빠 프로젝트 저장소
> 프로젝트 기간 2022/04/18 ~ 2022/04/22  
> 팀원: [@kiwi](https://github.com/kiwi1023) [@bard](https://github.com/bar-d)/ 리뷰어: [@FirstDo](https://github.com/FirstDo)


# 목차
- [프로젝트 소개](#프로젝트-소개)
- [순서도](#순서도)
- [키워드](#키워드)

- [그라운드 룰](#그라운드-룰)
	- [활동시간](##활동시간)
	- [예외사항](##예외사항)
	- [의사소통 방법](##의사소통-방법)
	- [코딩 컨벤션](##코딩-컨벤션)

- [STEP 0](#STEP-0)
	- [고민한점](#고민한점)
	- [배운 개념](#배운개념)
- [STEP 1](#STEP-1)
	- [고민한점](#고민한점)
	- [배운개념](#배운개념)
- [STEP 2](#STEP-2)
	- [고민한점](#고민한점)
	- [배운개념](##배운개념)


# 프로젝트 소개
사용자의 입력값을 받는 숫자야구 게임

# 개발환경 및 라이브러리
[![swift](https://img.shields.io/badge/swift-5.6-orange)]()
[![xcode](https://img.shields.io/badge/Xcode-13.3-blue)]()

# 순서도 
- step 1
![](https://i.imgur.com/vBsl4sT.jpg)

- step 2
![](https://i.imgur.com/YVImTUM.png)

# 키워드  
- `switch`, `static`, `재귀함수`, `case`, `extension`, `guard`  
- `enum`, `class`, `protocol`
- `파일 분리화`, `함수 세분화`
# 그라운드 룰

## 활동시간
변동사항 있으면 DM 보내줄 것


+ 점심시간 12:30 ~ 13:30
+ 저녁시간 19:00 ~ 20:00

## 예외사항
- 있으면 dm으로 연락

## 의사소통 방법
+ 디스코드 회의실
+ 단톡방


## 코딩 컨벤션

1. Swift 코드 스타일 : [스위프트 API 가이드라인](https://gist.github.com/godrm/d07ae33973bf71c5324058406dfe42dd) 
2. 커밋 
+ 커밋 Title 규칙

	+ add: 새로운 파일 추가
	+ refactor: 코드 리팩토링
	+ style: 코드 내 들여쓰기나 부가적인 수정
	+ feat: 새로운 기능 추가
	+ fix: 버그 수정
	+ docs: 문서 수정
+ 커밋 body 규칙

	+ 현제 시제를 사용, 이전 행동과 대조하여 변경을 한 동기를 포함하는 것을 권장 문장형으로 끝내지 않기
	+ commitTitle 과 body 사이는 한 줄 띄워 구분하기
	+ commitTitle line의 글자수는 50자 이내로 제한하기
	+ commitTitle line의 마지작에 마침표(.) 사용하지 않기
	+ commitBody는 72자마다 줄 바꾸기
	+ commitBody는 어떻게 보다 무엇을,왜 에 맞춰 작성하기

# 핵심경험
- [x]  Swift의 Optional 안전하게 처리하기
- [x] if와 switch 조건문의 차이와 장단점 비교해보기
- [x] 순환함수(재귀함수)와 반복문의 장단점 비교해보기
- [x] 함수가 한 가지 일만 하도록 기능 분리하기
- [x] guard 구문의 이해와 활용
- [x] Git의 커밋단위 고민하고 커밋에 적용하기
- [x] Git 커밋 로그 형식에 맞춰 커밋하기
- [x] 코딩 컨벤션 고민하기
- [x] 동료와 협업자세 고민하기

# [STEP 0]

## 고민한점  
- 논리적으로 순서도 만들기


## 배운개념


# [STEP 1]

## 고민한점
- 이중문을 사용하지 않고 코드를 짤 수 있을까? -> 함수 세분화
- 옵셔널 값을 어떻게 벗겨줄 것인가? -> `guard let`을 사용함
- `guard let` 구문을 사용할 때 `return` 값을 어떤 식으로 줄 것인가? -> 아에 나올수 없는 `Int`타입인 -1로 해결
- 사용자의 입력값을 몽키 테스트를 통해 오류를 제거
- `enum`타입 활용법


## 배운개념
- `guart let`, `switch`, `enum`, `extenstion`
- `파일 세분화`, `함수 세분화`
- `main.swift내에 실행함수만 두기`
- `static`
# [STEP 2]

## 고민한점
- 가위바위보 게임과는 다르게 묵찌빠 게임은 가위바위보 게임을 한 후, 다시 결과를 통해 게임을 진행하기에 재귀함수 사용은 어떤가?
- 함수를 `struct`내부에서 구현할 것인가, `class`내부에서 구현할 것인가
- 공통 로직을 묶은 클래스를 부모 클래스를 만든다면 그 부모 클래스는 온전히 작동하는가? -> 작동이 안한다면 `protocol`사용 권장
- `startMukJiPa`함수 실행시 잘못된 입력이 되어도 누구의 턴인지 표시가 됨 -> 로직을 고치기 위해 가위바위보, 묵찌빠 구조체 분리
- 재귀함수와 반복문의 장단점 비교
- 프린트하는 함수를 따로 어떻게 모을 것인가?


## 배운개념
- `재귀함수`, `protocol`, `nested function`, `private`
- `data`, `heap`, `stack`, `class`
