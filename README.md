# ToyProject - 날씨 정보 조회 App

## 소개

Web에서 iOS로 직무를 변경한 후 iOS팀의 on boarding기간동안 진행한 toy project로 공공데이터의 날씨api 데이터를 이용한다. <br>
`Swift`, `SnapKit`, `Then` 을 이용해 기본적인 방식으로 어플을 만들었고, 이후 `RxSwift`, `ReactorKit` 을 사용한 방식으로 refactoring 진행했다. <br>
회사계정인 [sungyeopTW](https://github.com/sungyeopTW)에서 작업 및 완성 후 현 위치인 개인계정 [danielsychoo](https://github.com/danielsychoo)로 프로젝트 이관한 상태. <br>

<br>

## 스크린샷

### 1. 즐겨찾기 화면

<img
  alt="즐겨찾기화면"
  src="https://user-images.githubusercontent.com/72306693/177334082-835dda0d-3301-451f-8744-861dca146f02.png"
  width="500"
  height="500"
/> <br>
첫 화면은 즐겨찾기 화면으로 즐겨찾기 된 지역들의 날씨를 확인할 수 있고, 우측 상단의 온도계 버튼을 이용해 섭씨/화씨를 변경할 수 있다. <br>

### 2. 검색화면 및 세부화면

<img
  alt="검색화면 및 세부화면"
  src="https://user-images.githubusercontent.com/72306693/177334136-042bf16a-b7dc-46f3-8916-a632a86264fe.png"
  width="500"
  height="500"
/> <br>
즐겨찾기 화면의 searchBar를 이용해 지역을 검색할 수 있다. <br>
이때 검색결과를 통해 즐겨찾기를 할 수 있으며, 지역을 선택해 해당 지역의 세부날씨를 확인할 수 있다. <br>

<br>

## 사용방식

```shell
$ git clone [repository]
$ pod install
```

repository를 clone한 후 CocoaPods를 이용해 사용된 framework를 설치한다. <br>
이후 Xcode를 이용해 해당 project를 열고 build한다. <br>
