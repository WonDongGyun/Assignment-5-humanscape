# 🔥 Assignment_Humanscape (with NestJS)

이 Read.me에는 제가 무엇을 했는지만 적혀있습니다. 팀 전체가 무엇을 했는지 궁금하시다면 하단의 링크를 참조해주세요.    
[Assignment_5_HumanScape 팀 Repository](https://github.com/preOnboarding-Team13/Assignment-5-humanscape)

<br/>

<br>

## 🌎 배포

주소 : http://3.38.126.250:3000

<br>

## 🛠 프로젝트 빌드 및 서버 실행 방법

1. 상단의 Code 버튼을 눌러 경로를 복사한 후 클론 받습니다.

```
$ git clone https://github.com/preOnboarding-Team13/Assignment-5-humanscape.git
```

1. 패키지를 설치합니다.

```
$ npm install
```

1. 서버를 실행해 줍니다.

```
$ npm start
```

1. 정해진 API에 접근하여 서비스를 이용합니다.

<br>

## 📝 과제 요구사항

### [필수 포함 사항]

- READ.ME

   작성

  - 프로젝트 빌드, 자세한 실행 방법 명시
  - 구현 방법과 이유에 대한 간략한 설명
  - 완료된 시스템이 배포된 서버의 주소
  - 해당 과제를 진행하면서 회고 내용 블로그 포스팅

- Swagger나 Postman을 이용하여 API 테스트 가능하도록 구현

✔️ **확인 사항**

- **ORM 사용 필수**
- **데이터베이스는 SQLite로 구현**
- secret key, api key 등을 레포지토리에 올리지 않도록 유의
  - [README.md](http://README.md) 에 관련 설명 명시 필요

✔️ **도전 과제: 스스로에게도 도움이 되는 내용 + 추가 가산점**

- 배포하여 웹에서 사용 할 수 있도록 제공
- 임상정보 검색 API 제공

✔️  **과제 안내**

다음 사항들을 충족하는 서비스를 구현해주세요.

- 임상정보를 수집하는 batch task
  - 참고: https://www.data.go.kr/data/3074271/fileData.do#/API 목록/GETuddi%3Acfc19dda-6f75-4c57-86a8-bb9c8b103887
- 수집한 임상정보에 대한 API
  - 특정 임상정보 읽기(키 값은 자유)
- 수집한 임상정보 리스트 API
  - 최근 일주일내에 업데이트(변경사항이 있는) 된 임상정보 리스트
    - pagination 기능
- **Test 구현시 가산점이 있습니다.**


## 🧬 DB 모델링

![Untitled (2)](https://user-images.githubusercontent.com/60311404/141983542-3da3d782-2730-4f52-8bea-3c40a438eb6c.png)

<br>

## 🏫 사용 기술

- Backend : [![img](https://camo.githubusercontent.com/cb0c26ab83b212946400b29c325debd89d07f0c36e3568c840dc6ae07127ca1b/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4e6573744a532d4530323334453f7374796c653d666c6174266c6f676f3d4e6573744a53266c6f676f436f6c6f723d7768697465)](https://camo.githubusercontent.com/cb0c26ab83b212946400b29c325debd89d07f0c36e3568c840dc6ae07127ca1b/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4e6573744a532d4530323334453f7374796c653d666c6174266c6f676f3d4e6573744a53266c6f676f436f6c6f723d7768697465) [![img](https://camo.githubusercontent.com/17131306fc490286432e1148ea92ac1754363621a9d185bf613ad6e0f4d33a96/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f547970655363726970742d3331373843363f7374796c653d666c6174266c6f676f3d54797065536372697074266c6f676f436f6c6f723d7768697465)](https://camo.githubusercontent.com/17131306fc490286432e1148ea92ac1754363621a9d185bf613ad6e0f4d33a96/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f547970655363726970742d3331373843363f7374796c653d666c6174266c6f676f3d54797065536372697074266c6f676f436f6c6f723d7768697465)
- DataBase : [![img](https://camo.githubusercontent.com/93b7b220122f943f4de91262b7aa6109a0fa4dd601e115d1b7c8bfa906e166ab/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f53514c6974652d3030334235373f7374796c653d666c6174266c6f676f3d53514c697465266c6f676f436f6c6f723d7768697465)](https://camo.githubusercontent.com/93b7b220122f943f4de91262b7aa6109a0fa4dd601e115d1b7c8bfa906e166ab/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f53514c6974652d3030334235373f7374796c653d666c6174266c6f676f3d53514c697465266c6f676f436f6c6f723d7768697465)
- Collaboration : [![img](https://camo.githubusercontent.com/493683d1e69c600dc04bb375ab588466c554471ea28f7326b390b5103c401058/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4769742d4630353033323f7374796c653d666c6174266c6f676f3d476974266c6f676f436f6c6f723d7768697465)](https://camo.githubusercontent.com/493683d1e69c600dc04bb375ab588466c554471ea28f7326b390b5103c401058/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4769742d4630353033323f7374796c653d666c6174266c6f676f3d476974266c6f676f436f6c6f723d7768697465) [![img](https://camo.githubusercontent.com/779ecf5e6059fd906fca2099015186945f91679f22da6bf05f37f52e69e86e8a/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4769744875622d3138313731373f7374796c653d666c6174266c6f676f3d476974487562266c6f676f436f6c6f723d7768697465)](https://camo.githubusercontent.com/779ecf5e6059fd906fca2099015186945f91679f22da6bf05f37f52e69e86e8a/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4769744875622d3138313731373f7374796c653d666c6174266c6f676f3d476974487562266c6f676f436f6c6f723d7768697465) [![img](https://camo.githubusercontent.com/1b756736e374960a174cb6f65083804b2052cd6f6e997af84206794e2ca77f71/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f506f73746d616e2d4646364333373f7374796c653d666c6174266c6f676f3d506f73746d616e266c6f676f436f6c6f723d7768697465)](https://camo.githubusercontent.com/1b756736e374960a174cb6f65083804b2052cd6f6e997af84206794e2ca77f71/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f506f73746d616e2d4646364333373f7374796c653d666c6174266c6f676f3d506f73746d616e266c6f676f436f6c6f723d7768697465)
- Deploy : [![img](https://camo.githubusercontent.com/f9e746416cf54181ba668cfe6e2861d1932c619847382646703a583ea89f249f/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f416d617a6f6e204157532d3233324633453f7374796c653d666c6174266c6f676f3d416d617a6f6e20415753266c6f676f436f6c6f723d7768697465)](https://camo.githubusercontent.com/f9e746416cf54181ba668cfe6e2861d1932c619847382646703a583ea89f249f/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f416d617a6f6e204157532d3233324633453f7374796c653d666c6174266c6f676f3d416d617a6f6e20415753266c6f676f436f6c6f723d7768697465)

<br>

## 📂 폴더 구조

```
📁 src
├── 📁 domain
│  ├── 📂 entities
│  │  ├── 📄 trials.entity.ts
│  │  ├── 📄 updatedBundles.entity.ts
│  │  └── 📄 updatedTrials.dto.ts
│  ├── 📂 search
│  │  ├── 📄 search.controller.spec.ts
│  │  ├── 📄 search.controller.ts
│  │  ├── 📄 search.module.ts
│  │  ├── 📄 search.repository.ts
│  │  ├── 📄 searchPage.repository.ts
│  │  ├── 📄 search.service.spec.ts
│  │  └── 📄 search.service.ts
│  ├── 📂 trials
│  │  ├── 📄 trials.module.ts
│  │  ├── 📄 trials.repository.ts
│  │  ├── 📄 trials.service.spec.ts
│  │  ├── 📄 trials.service.ts
│  │  ├── 📄 updatedTrialBundles.repository.ts
│  │  └── 📄 updatedTrials.repository.ts
├── 📂 global
│  ├── 📂 common
│  │  ├── 📄 CommonResponse.ts
│  │  ├── 📄 ErrorCode.ts
│  │  └── 📄 ErrorResponse.ts
│  ├── 📂 exception
│  │  └── 📄 ErrorHandler.ts
│  ├── 📂 util
│  │  ├── 📄 encryption.ts
│  │  └── 📄 date.ts
├── 📂 utils
│  └── 📄 batchFunction.ts
├── 📄 app.module.ts
└── 📄 main
📁 test
├── 📄 app.e2e-spec.ts
└── 📄 jest-e2e.json
📄 .env
📄 nest-cli.json
📄 package.json
📄 package-lock.json
📄 tsconfig.json
📄 tsconfig.build.json
📄 README.md
```



## 🔗 구현 기능

### Check List

- 임상 정보

  ✅ 특정 임상 정보 읽기 API

  ✅ 업데이트된 임상정보 리스트 API

  ✅ 임상정보를 수집하는 batch task

- 테스트 코드

  ✅ Unit Test

- 추가 고려 사항

  ✖️ 임상정보 검색 API 

<br/>

#### [설계 논의 사항](https://github.com/preOnboarding-Team13/Assignment-5-humanscape/wiki/설계-회의-내용)
#### [오픈 API 조회 방식, For Loop VS Promise.all](https://github.com/preOnboarding-Team13/Assignment-5-humanscape/wiki/오픈-API-조회-방식,-For-Loop-Vs-Promise.all)
#### [Functional Test 결과](https://github.com/preOnboarding-Team13/Assignment-5-humanscape/wiki/Functional-Test-결과)

<br/>

🧪 내가 이번 프로젝트에서 무엇을 했지?
-----------------  

**1) Pair Programming (짝 코딩)**

지난 프로젝트들에서도 2명 혹은 3명씩 짝을 지어서 pair programming을 진행했었습니다.

이번 과제에서는 batch task가 핵심이었기 때문에, 첫 날에 batch task의 틀을 짤 때 6명이 함께 pair programming을 진행했습니다.

![image](https://user-images.githubusercontent.com/43634786/142021494-9a783af8-d5d0-4462-b63b-4e415c502f32.png)

<br/>

**2) 검색 API 구현 및 pagination 성능 향상**

검색 API를 구현하는건 그렇게 어렵지 않았습니다. 문제는 pagination이었죠. 4번째 과제 때 `typeorm-cursor-pagination`을 사용해서 limit offset 방식의 pagination을 cursor pagination으로 바꿨었는데요. 처음 사용하는 것이다 보니 생각보다 잘 사용하지 못한것 같고, 코드 부분에서도 아쉬운 점이 많았어서 요번에는 직접 개발해 보는걸로 했습니다. cursor pagination으로 구현하면 순차적으로 페이징 되는 성질이 있기 때문에 count 쿼리는 굳이 필요가 없으나, 전체 데이터 수를 알고 싶어서 넣어보았습니다. 보통 cursor pagination은 페이스북에서 화면스크롤을 밑으로 내렸을 때 자동으로 페이징 되는 기능에 사용되거나 해서, 이 방식으로 pagination을 구현하면 1페이지에서 갑자기 11페이지로 가는 등의 기능을 할 수가 없습니다. 때문에 만약 이런 방식의 pagination을 하고 싶다면 커버링 인덱스 방식을 사용하거나 기타 다른 방식을 사용한다고 하는데, 그런 방법들은 나중에 한번 도전해봐야 할 것 같습니다.      

<br>

1편은 지난 프로젝트에 성능을 비교하며 작성했던 문서이고, 2편은 `typeorm-cursor-pagination`을 사용하지 않고 pagination에 도전하며 작성한 문서입니다.

<br>

[TypeOrm 페이지 향상기(1)](https://github.com/preOnboarding-Team13/Assignment-4-8percent/wiki/TypeOrm-%ED%8E%98%EC%9D%B4%EC%A7%80-%EC%84%B1%EB%8A%A5-%ED%96%A5%EC%83%81-%EB%8F%84%EC%A0%84%EA%B8%B0)

#### [TypeOrm 페이지 향상기(2)](https://github.com/preOnboarding-Team13/Assignment-5-humanscape/wiki/TypeOrm-%ED%8E%98%EC%9D%B4%EC%A7%80-%EC%84%B1%EB%8A%A5-%ED%96%A5%EC%83%81-%EB%8F%84%EC%A0%84%EA%B8%B0(2))

<br>


## 🐾 API

[Postman 주소-링크](https://documenter.getpostman.com/view/12074893/UVCB9PXL)

<br>

## 🐾 API Test 방법

#### 1. 위의 Postman 주소 링크를 클릭하여 Postman으로 들어갑니다.

#### 2. Search Information API 를 이용하여 trial_id에 대한 임상 정보를 확인 할 수 있습니다. 데이터가 없으면 404에러를 반환합니다.

![image](https://user-images.githubusercontent.com/41619081/142034527-fca7a5ee-2c71-4b34-9786-9e992701d6bc.png)

#### 3. Search Updated Information API 를 이용하여 변경된 임상 리스트 확인을 할 수 있습니다. 변경된 데이터가 없으면 404에러를 반환합니다.

![image](https://user-images.githubusercontent.com/41619081/142034850-721c2427-902c-48b3-ab1f-c4eccf0d6f08.png)


<br>

## 🍭 TIL 주소



| 김바다 | 김효민 | 원동균 | 이나영 | 장희진 | 조재복 |
| ------ | ------ | ------ | ------ | ------ | ------ |
|        |[티스토리 블로그](https://baejjang.tistory.com/9)        |[티스토리 블로그](https://tristy.tistory.com/48)        |        |        |        |
