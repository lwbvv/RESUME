# Resume

<br><br/>

## Profile

- Name: 이치원
- Email: lwbvvbusiness@gmail.com
- Github: https://github.com/lwbvv
- TISTORY: https://richone.tistory.com
- Instagram: https://instagram.com/chichilee_table?igshid=awmrxk33n1ka

<br><br/>

## Career(3년차 iOS Developer)

### 캔랩코리아

- 기간: 2022.06 ~
- 내용:  소셜, 커머스 서비스를 코드 없이 쉽게 빌딩해서 서비스 할 수 있도록 제공하는 서비스의 모바일 어플리케이션 모듈 개발

### 파이언스

- 기간: 2021.06 ~ 2022. 05
- 내용: 피트니스 예약 서비스의 iOS 어플리케이션 개발

### 앱지

- 기간: 2020.05 ~ 2022. 05
- 내용: 에이전시 회사로, 다수의 외주 프로젝트의 iOS 어플리케이션 개발

<br><br/>

## Skills

### iOS

Architecture - Ribs, Clean Architecture, MVVM, MVVM-C, ReactorKit, MVC

Favorite OpenSource

- infra
  - ReactorKit
  - Rxswift, RxCocoa, RxDatasource
  - Network(Alamofire, Moya)
- UI
  - snapKit

### Flutter

Architecture - BLOC

<br><br/>

## Contribute OpenSource

Flutter Flip Card - https://github.com/BrunoJurkovic/flip_card

iOS The Composable Architecture Sdudy - https://github.com/tca-study/The-Composable-Architecture

<br><br/>

## Company Project

### Moim(Application And WebSite Builder)

---

소셜, 커머스 서비스를 코드 없이 쉽게 빌딩해서 서비스 할 수 있도록 제공하는 서비스

- 기간: 2022.06 ~

- 역할
  - Flutter를 이용한 모바일 어플리케이션 개발

- 개발환경

  - IDE: Android Studio
  - 언어: Dart(2.3 ~ 2.7)
  - Framework: Flutter

- **대표 업무**

  - 신기능
    - 퀘스트 모듈 개발 (2022. 10 ~)
      - 퀘스트를 통해 서비스에 게임적 요소를 더해서 유저들의 재방문률을 높이고자 개발
    - 상품 디테일 페이지 셀렉트 리뷰 섹션 추가 (2022. 9. 24 ~ 2022. 9. 27)
      - 구매욕 증대를 위해 상품 디테일 페이지에서 어드민에서 설정한 리뷰만 모아서 상단에 노출
    - 온보딩 페이지 개발 (2022. 08. 25 ~ 2022. 08. 31)
      - 온보딩 페이지를 원하는 니즈를 충족시키고자 어드민 설정에 따라 동적으로 보여줄 온보딩 페이지 개발
    - 소멸 예정 적립금 페이지 개발 (2022. 08. 17 ~ 2022. 08. 19)
      - 소멸 예정 적립금을 보고 싶어하는 엔드유저의 니즈 충족
    - 서브 커뮤니티 그룹 프리뷰 섹션 및 리스트 페이지 개발 (2022. 07. 11 ~ 2022. 07. 15) 
      - 커뮤니티 내에서 만들고 이동할 수 있는 서브 커뮤니티 그룹의 프리뷰 섹션과 리스트 페이지 개발

  - 개편, 고도화 및 리팩토링
    - 상품 프리뷰 컴포넌트 서버드리븐UI로 변경 (2022. 11. 14 ~ 2022. 11. 21)
      - 고객사들의 다양한 니즈를 충족시키기 위해 상품 프리뷰 리스트 안에 들어가는 컴포넌트를 어드민 설정에 따라 위치 스타일 조정 가능하게 변경
    - 장바구니 쿠폰 UI/UX개편 (2022. 10. 17 ~ 2022. 10. 23)
      - 기존에 장바구니 내에서 쿠폰 목록까지 보여주는 형태가 엔드유저에게 불편함을 초래해 다음 뎁스로 뺌
    - 쿠폰 컴포넌트 리팩토링 및 UI 개선 (2022. 09. 12 ~ 2022. 09. 16)
      - 기존에 사용하던 쿠폰 컴포넌트를 확장성 있게 리팩토링(해당 기능 리팩토링으로 쿠폰 타입이 추가 될 때 동료 개발자가 20분 안팎의 시간을 들여 추가)
      - 쿠폰 플립 애니메이션 개선
    - 앱 아키텍쳐 개선 (2022. 09 ~)
      - 기존에 View에서 모든 로직을 처리하고 있는 문제를 해결하고자 BLOC 패턴을 서비스에 맞게 개선한 아키텍처 설계 및 도입
      - 현재(2022. 11. 27 기준) 10% 정도의 Feature에 적용

  - Flutter Develop Infra
    - 로깅 시스템 개선 (2022. 09. 1 ~ 2022. 09. 30)
      - 기존 Level단위 로그 출력의 불편함을 느껴 자체 로거를 만들고, 로그를 카테고리화 시켜 출력하고 원하는 로그만 볼 수 있게함
    - Safety Decoder, 모델 제너레이터 개발 (2022. 10. 4 ~ 2022. 10. 14)
      - 기존 모델 제네레이터를 이용했을 때 Null과 Type Error를 잡아주지 못해서, Json Safety 개발과 자체 모델 제너레이터 개발(모델 제너레이터는 파이썬으로 개발함)
        - Json Safety 개발로 Decoding이 안 됐을 시 해당 라인과 이유를 출력해 줘서, 데이터가 많을 경우 `1시간 넘게 걸리던 작업을 1분 이내로 단축`
        - 기존 모델 제너레이터를 구동시키는데 `3~5분 가량 소요 되었으나 해당 시간을 5초대로 단축`
    - 코드 템플릿 도입(안드로이드 스튜디오 플러그인 개발) (2022. 09. 07 ~ 2022. 09. 09)
      - 보일러 플레이팅 코드 작성 시간을 줄이고, 컨벤션을 맞추기 위해 코드 템플릿 도입
    - 코드 템플릿 개선 (2022. 11. 07 ~ 2022. 11. 11)
      - VSCode용 코드 템플릿 플러그인을 찾던 와중 CLI로 코드 템플릿 적용이 가능한 오픈 소스를 발견하여 해당 방식으로 변경
      - 각 IDLE 마다 만들어야 됐던 코드템플릿 프로그램을 CLI방식으로 바꿔 유지보수 비용 절감

  

- **대표 어플리케이션**

  - [파도상자](https://apps.apple.com/kr/app/%ED%8C%8C%EB%8F%84%EC%83%81%EC%9E%90/id1597052767?l=en)
  - [배이크](https://apps.apple.com/kr/app/%EB%B2%A0%EC%9D%B4%ED%81%AC-vake-%EA%B0%80%EC%B9%98%EB%A5%BC-%EB%A7%8C%EB%93%9C%EB%8A%94-%EC%82%AC%EB%9E%8C%EB%93%A4%EC%9D%98-%EC%BB%A4%EB%AE%A4%EB%8B%88%ED%8B%B0/id1597029530)

<br><br/>

### 배달의 반띵 (외주 프로젝트)

---

배달 음식의 금액을 반띵할 사람을 매칭 시켜주는 어플리케이션

- 개발기간: 2022. 05. 15 ~ 2022. 06. 05
- 역할: iOS 개발
- 개발환경: Xcode(Swift 5.5)
- 업무
  - Modular 아키텍쳐 설계
  - Preview를 이용하여 디바이스에 빌드를 하지 않고 UI를 확인하며 개발 할 수 있도록 함
  - Preview를 이용하여 가시적으로 확인 가능한 UI Test 코드 작성
  - 내가 오픈한 반띵 목록 개발
  - 내가 참여한 반띵 목록 개발
  - 리뷰 작성 페이지 개발

- 사용기술
  - Architecture: Ribs, ReactorKit, three layer architecture(clean architecture)
  - MonoRepository-Multimodule
  - 프로젝트 관리 도구: Tuist

[앱스토어](https://apps.apple.com/kr/app/%EB%B0%B0%EB%8B%AC%EC%9D%98-%EB%B0%98%EB%9D%B5/id1642060509)

### Peachy

---

피트니스 예약 어플리케이션

- 개발기간: 2021.06 ~ 2022. 05

- 역할
  - iOS 개발(iOS 어플리케이션 전체 개발)
  - 모바일 개발 리드(2022. 02 ~)
  
- 개발환경: Xcode(Swift 5.4)

- 사용기술: Clean Architecture, ReactorKit, RxSwift, SnapKit, Moya

- **대표 업무**
  
  - iOS 어플리케이션 설계
  
  - Code Templete 제작하여 사용하여 ***보일러 플레이트 코드의 작성 시간을 단축과 일관된 코드 작성***
  - 예약 캘린더의 만년달력의 속도 이슈를 해결하기 위해 프레임 기반 레이아웃 배치와 PageViewController의 페이지 리사이클링
    - ***Preview를 UIKit에 적용하여 UI 생산성 향상*** 
    - ***스토리북(UI Table) 사용으로 디자이너와의 커뮤니케이션 비용 절감 및 컴포넌트 시각화***
    - ***프레임 기반 렌더링 -> 데이터를 받아 온 후 렌더링 속도 2000ms -> 100ms대(육안으로는 데이터 받아오는 즉시 렌더링)로 향상***
    - ***페이지 리사이클링 -> 페이지마다 올라가 있는 observable 12000개 -> 200개 안팎으로 줄임***
  
- **추가 사항**

  - MCU: 20,000
  - 프로젝트 빌드업 멤버

<p>
    <img src="https://user-images.githubusercontent.com/49789441/160415602-9bda2fe3-af07-45d9-aa89-dfc304042cbf.png" width="200" height="340">
    <img src="https://user-images.githubusercontent.com/49789441/160413948-a018f148-2b50-4ede-8fc6-a984896f2b6d.png" width="200" height="340">
    <img src="https://user-images.githubusercontent.com/49789441/160413946-72ff3f35-212a-4101-a17d-306340c79445.png" width="200" height="340">
    <br><br/>
     <img src="https://user-images.githubusercontent.com/49789441/160413941-7f74997a-66e4-4485-844c-019826b51811.png" width="200" height="340">
    <img src="https://user-images.githubusercontent.com/49789441/160413936-02bae79e-1a8b-4a1f-9df3-524b5d55830e.png" width="200" height="340">
    <img src="https://user-images.githubusercontent.com/49789441/160413920-c9ba0446-1f5f-48f6-a81b-0a2a06a3625b.png" width="200" height="340">
</p>

[앱스토어 링크](https://apps.apple.com/kr/app/%ED%94%BC%EC%B9%98-%EB%8B%B9%EC%8B%A0%EC%9D%98-%EC%9A%B4%EB%8F%99-%ED%8C%8C%ED%8A%B8%EB%84%88/id1589899247)

<br><br/>

### 휴먼라인

---

뇌파, 맥파, 안구운동 측정기기를 연동하여 컨디션 지표를 나타내주는 어플리케이션

- 개발기간: 2021.02 ~ 2021.05
- 역할: iOS 개발(통계자료, 상담 영역을 제외한 전 영역 개발)
- 개발환경: Xcode(Swift 5.4)
- 사용기술: ReactorKit, RxSwift, Programmatically UI(Method Chaining), Alamofire, Kingfisher, SPM, BLE Pairing, Chart
- **대표 업무**
  - BLE 연동을 통한 뇌파, 맥파 측정 개발
  - 백그라운드 동영상 플레이어 개발
  - 음악 플레이어 개발
  - 다이나믹 카운터 개발
  - Chart라이브러리를 이용한 차트 개발
  - 더블 컬렉션뷰를 이용한 리스트 개발
  - 인앱 결제 개발
- 성과
  - Code Templete 제작하여 사용하여 ***보일러 플레이트 코드의 작성 시간을 단축과 일관된 코드 작성***
  - ***영상, 음악 플레이시 메모리 및 로컬 스토리지 캐싱을 이용한 최적화***
  - ***빌드 시간을 단축하기 위하여 SPM 도입하여 빌드시간 1분 30초 -> 1분으로 33% 단축***

<p>
  <img src="https://user-images.githubusercontent.com/49789441/116453495-ec214c80-a899-11eb-99ff-156576293e75.png" width="200" height="340">
    <img src="https://user-images.githubusercontent.com/49789441/116453518-f2172d80-a899-11eb-9229-c19206fd38f5.png" width="200" height="340">
    <img src="https://user-images.githubusercontent.com/49789441/116453603-09561b00-a89a-11eb-9c4a-983acc0984cd.png" width="200" height="340">
      <img src="https://user-images.githubusercontent.com/49789441/116453710-2985da00-a89a-11eb-9770-66e71eaaccb7.png" width="200" height="340">
    <br><br/>
    <img src="https://user-images.githubusercontent.com/49789441/116453614-0d823880-a89a-11eb-83bf-bd142ec4a0d1.png" width="200" height="340">
    <img src="https://user-images.githubusercontent.com/49789441/116453633-14a94680-a89a-11eb-811a-3774c5a201fc.png" width="200" height="340">
        <img src="https://user-images.githubusercontent.com/49789441/116464335-d23a3680-a8a6-11eb-80e0-26307a1e7af8.png" width="200" height="340">
    <img src="https://user-images.githubusercontent.com/49789441/116453683-225ecc00-a89a-11eb-88a9-45c663a3b150.png" width="200" height="340">
</p>
<br><br/>

### 발란

---

럭셔리 쇼핑몰 어플리세이션

- 개발기간: 2020.11 ~ 2020.11

- 역할: iOS앱 유지보수

- 개발환경: Xcode(Swift 5.2)

- 대표 업무

  - 정적으로 표현 됐던 인트로 페이지 동적으로 변경

  - ***스플래쉬 이미지 캐싱 처리로 자연스러운 스플래쉬 랜더***
  - ***iOS 런치 스크린 이미지 캐싱 버그 해결***


<p>
  <img src="https://user-images.githubusercontent.com/49789441/116451503-816f1180-a897-11eb-902a-a4b015dd1549.png">
</p>

[앱스토어](https://apps.apple.com/kr/app/%EB%B0%9C%EB%9E%80-%EC%B0%B8-%EC%89%AC%EC%9A%B4-%EB%9F%AD%EC%85%94%EB%A6%AC-%EC%87%BC%ED%95%91-%EC%95%B1/id1479010008)

#### <br><br/>

### 뱅크다이어리

---

보험조회 서비스 어플리케이션

<p>
  <img src="https://user-images.githubusercontent.com/49789441/116445461-dc513a80-a890-11eb-8da2-1da81b099b2b.png">
</p>

- 개발기간: 2020.10 ~ 2020.11

- 역할: iOS 개발

- 개발환경: Xcode(Swift 5.2)

- 사용기술: MVVM-C, RxSwift, Programmatically UI

- **대표 업무**
  
  - 하이브리드 앱 개발
  - 암호화 키패드 라이브러이 연동 및 비밀번호, 주민번호 암호화 개발
  - 스크래핑을 이용한 '내 보험 다 보여' 회원가입, 로그인, 보험 조회
  
  - ***MVVM 패턴의 단점을 보완하기 위해 MVVM-C 패턴 사용***
  - ***MVVM-C 서포트 라이브러리를 사용하여 개발하던 도중 Multi POP 기능에 오류가 있어 Custom 하여 사용***

[앱스토어 링크](https://apps.apple.com/kr/app/뱅크다이어리-bankdiary/id1543640471)

<br><br/>

### 안심불빛

---

 비콘 연동을 통한 안심귀가 서비스 어플리케이션

- 개발기간: 2020.07 ~ 2020.08

- 역할: iOS 개발(기여도 100%)

- 개발환경: Xcode(Swift 5.2)

- 사용기술: MVC, Programmatically UI, FCM Push Notification, Alamofire, KakaoMap, Acceleration sensor, 블루투스 비콘 연동

- 대표 업무
  - Local Push Notification
  - 반경 1km 이내의 세이프존 마커 개발
  - 도로명 주소 API를 이용한 주소 검색 개발
  - 핸드폰 특정 강도 이상으로(강도 조절 가능) 흔들었을 시 위급상황 알림 개발
  
  - ***Code로 UI 작업을 하므로써 UI 유지보수성을 높힘***

<p>
  <img src="https://user-images.githubusercontent.com/49789441/116446105-96e13d00-a891-11eb-8601-4384c6f04c8e.png" width="200" height="340">
  <img src="https://user-images.githubusercontent.com/49789441/116446274-bed0a080-a891-11eb-9fde-ece65ce0e21b.png" width="200" height="340">
  <img src="https://user-images.githubusercontent.com/49789441/116446360-d740bb00-a891-11eb-9212-ef027d28d944.png" width="200" height="340">
  <img src="https://user-images.githubusercontent.com/49789441/116446458-f0496c00-a891-11eb-9c92-d1bf9b47d529.png" width="200" height="340">
</p>
<br><br/>

#### 그 외 다수의 하이브리드 어플리케이션 개발

<br><br/>

## Persnal Project

#### 인연
소개팅 어플리케이션

  + 안드로이드, 서버(장고) 개발

https://github.com/lwbvv/inyeon

#### 포포
인생샷 포인트 공유 어플리케이션

  + 서버(장고) 개발

https://github.com/lwbvv/spott-android

#### AlwaysAwake
Todo List 어플리케이션

  + 안드로이드 개발

https://github.com/lwbvv/AlwaysAwake2
