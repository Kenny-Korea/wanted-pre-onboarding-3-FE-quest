# 3월 원티드 프리온보딩 프론트엔드 과정 사전과제

### 오약

- pathname이 /login인지 조건문을 사용하여 true면 헤더&사이드바 포함하고, false면 login페이지만 출력
- ProtectedRoute라는 컴포넌트를 정의하여, login이 필요한 컴포넌트를 ProtectedRoute 컴포넌트로 감싸는 방식으로 작성
  - 로그인이 필요한 다른 페이지를 추가할 경우, 추가한 페이지도 ProtectedRoute 컴포넌트로 감싸주면 되는 형식
- 로그인 상태는 contextAPI로 전역 관리
- 로그인은 개인 github repository에 올려둔 fake Id json파일과 일치하는 아이디와 비밀번호가 있는지 확인하는 방식으로 구현

---

수강생 여러분 안녕하세요!

3월 프론트엔드 프리온보딩 과정 진행을 위해, 아래의 내용을 읽고 사전 과제를 수행해 주세요.

사전 과제는 해당 레포지토리를 포크하여 진행해 주시면 됩니다.

### 만들어야 할 것

이번 프리온보딩에서는 레이아웃 패턴과 로그인에 대해서 다룹니다. 사전 과제에서는 현재 수강생 여러분이 가지고 있는 리액트 라우터 구성 및 레이아웃 구성에 대한 지식을 확인해 보고자 합니다.

사전 과제로써 다음 요구사항을 충족하는 리액트 어플리케이션을 구성합니다.

- NextJS 등의 SSR 어플리케이션이 아닌, CSR 어플리케이션을 구축한다.
- 최소 3개 이상의 페이지를 가지도록 구현한다.
- 모든 페이지에 공통으로 반복되는 헤더와 사이드바가 있도록 구성한다.

즉, 다음 이미지와 같은 형태로 구현합니다.

![sample-image](./sample.jpg)

이 때, 아래의 내용을 고민하며 과제를 진행해 주시면 더욱 도움이 됩니다.

- 3개의 페이지가 고정되는 앱이 아니라, 여러 개의 페이지가 언제든 추가될 수 있다고 생각하고 프로젝트를 수행해 보세요.
- 만들어진 페이지별로 로그인 여부를 판단하고자 한다면 어떻게 구조를 확장해야할지 고민해 보세요.

추가로, 여유가 있다면 유저네임과 비밀번호를 받아 로그인을 수행할 수 있는 페이지를 만들어 보세요. 실제 API는 연결하지 않아도 되며, 로그인 페이지는 공통 레이아웃(상단 네비게이션 바 및 사이드바)이 적용되지 않도록 만들어 주세요.

### 질문하기 & 제출하기

- 과제 관련 질문은 해당 레포지토리에 이슈로 남겨주세요! 확인하는 대로 답변 드리도록 하겠습니다.
- 과제를 완료하셨다면 해당 레포지토리에 pull request를 남겨 제출해 주세요.
