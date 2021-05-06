# MEDICI_2021
메디치 혁신성장 VR/AR/MR 융합 콘텐츠 개발 과정


### 프로그래밍 기초

### 유니티 기초

- [프로젝트 리소스](https://github.com/IndieGameMaker/UnityBook)
- [SpaceShooter 프로젝트](https://github.com/IndieGameMaker/SpaceShooter_2021_K)
- [Musa 프로젝트](https://github.com/IndieGameMaker/Musa2021)
- [Flight 프로젝트](https://github.com/IndieGameMaker/Flight2021)
- [Inventory 프로젝트](https://github.com/IndieGameMaker/Inventory2021)
- [Photon TankAttack 프로젝트](https://github.com/IndieGameMaker/TankAttack2021)
- [Vuforia 프로젝트](https://github.com/IndieGameMaker/VuforiaDemo2021)
- [ARCore 프로젝트](https://github.com/IndieGameMaker/ARCoreDemo2021)
- [ARF 프로젝트](https://github.com/IndieGameMaker/ARFoundation2021)
---

### Git ignore 파일
- [Git .gitignore](https://www.toptal.com/developers/gitignore/api/unity)
- [Git .gitattrributes](https://gist.githubusercontent.com/nemotoo/b8a1c3a0f1225bb9231979f389fd4f3f/raw/dc3e8cab80fc62d1c60db70c761b1ffa636aa796/.gitattributes)

### Git 참조문서

- [간편 안내서](https://rogerdudler.github.io/git-guide/index.ko.html)
- [Pro Git 책](http://git-scm.com/book/ko/v2)

### ARCore 설치 패키지

com.unity.multiplayer-hlapi

com.unity.xr.legacyinputhelpers

---

### 유니티 기초과정 개인과제

- 과제 주제 : 미니 슈팅게임 만들기 
- 과제 마감 : 2021년 4월 19일 오후 6:00 까지
- 과제 업로드 : [메디치 카페] - [2021 혁신 가산 VR/AR] - [IITP_과제/실습]
- 카메라 시점 
    - 1인칭
    - 3인칭
    - Top Down 관계 없음

- 사용할 리소스
    - 에셋스토어에서 리소스 다운로드 후 사용
    - 자체 제작 리소스도 사용가능

- 반드시 포함되어야 할 사항
    - 3D 캐릭터 2종류 이상 포함
    - 동작 애니메이션 2종류 이상 포함(예시: Idle, Walk, Run, Jump, Die, ...)
    - 애니메이션 타입은 레거시 또는 메카님 관계 없음

- 구현 내용
    - 스테이지 생성 구현 : 텍스처가 적용되어야 함
    - 주인공 캐릭터의 이동 및 회전 처리(WASD 또는 Arrow Key로 이동)
    - 시네머신을 활용한 카메라 추적로직 적용
    - 총알 발사로직 구현 : 총알의 형태는 관계 없음
    - 적 캐릭터 구현 : 주인공을 향해서 추적을 해야함 (내비게이션 사용)
    - 적 캐릭터의 HP 구현해 0이하이면 삭제 처리함
    - 오브젝트 풀링은 제외

---

### 유니티 포톤 개인과제

- 과제 주제 : 이전 제작 게임 또는 신규 게임 
- 과제 마감 : 2021년 5월 3일 오후 6:00 까지
- 과제 업로드 : [메디치 카페] - [2021 혁신 가산 VR/AR] - [IITP_과제/실습]
- 사용할 리소스
    - 에셋스토어에서 리소스 다운로드 후 사용
    - 자체 제작 리소스도 사용가능

- 반드시 포함되어야 할 사항
    - 소스코드는 Git으로 관리 (CLI 만 사용 - GUI 툴 사용 금지)
    - Github에 원격 리포지토리에 백업
    - 로비 구현 생성 (유저ID, 룸생성 로직, 룸 목록(옵션사항))
    - 로비 씬, 베틀 씬으로 구성함
    - OnPhotonSerializeView 콜백 함수 사용
    - RPC로 구현한 로직 하나 이상 구현










## AR 프로젝트

### 프로젝트 전체 일정

* 전체 기간 : 2021/05/07 ~ 2021/05/21

* 개발 마감 : 2021/05/18

* 최종 발표 : 2021/05/21

### 프로젝트 팀 구성

|     **프로젝트 명**     |     **팀명**     |        **팀원**         | **팀장** |
| :---------------------: | :--------------: | :--------------------: | :------: |
|  프로젝트 1   |  팀명 | 팀원1, 팀원2  | 팀장1  |
|     |   |  |      |
|     |   |  |      |

### 프로젝트 진행 방식

- 소스코드 백업 관리 : Git, Github
- 소스코드 GUI 툴 사용은 선택 사항
- 팀장은 매일 작업종료 후 별도의 압축파일로 백업
- 작업시작 : Pull , 작업종료 : Push
- 핵심로직 개발 마감 : 2021/05/14 까지
- 신규로직 개발 금지 : 2021/05/18 부터
- 발표문서 양식 : PPT 고정 양식 or 자유 양식
- 발표 리허설 : 2021/05/20 시간은 추후 공지


### 프로젝트 세부 일정

|      구분      |     기간      | 05/07 | 05/10 | 05/11 | 05/12 | 05/13 | 05/14 | 05/17 | 05/18 | 05/20 | 05/21 |
| :------------: | :-----------: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
|    총 기간     | 05/10 ~ 05/21 |   #   |   #   |     |     |     |     |     |     |     |     | 
|   팀 빌딩, 기획 | 05/07 | # |    |    |     |     |     |     |     |     |     | 
|    1차 개발    | 05/10 ~ 05/14  |     |   #   |  #  |  #   |  #   |  #   |     |     |     |     | 
|   중간 점검    |     05/14      |      |       |       |       |      |   #    |       |       |       |        |
|   개발 완료    |     05/20     |       |       |       |       |       |       |       |       |   #   |        |
| 발표문서 작성  |    05/17    |       |       |       |       |       |       |    #   |    #   |    #   |       |
|  발표 리허설   |     05/20     |       |       |       |       |       |       |       |       |    #   |       |
| 시연 및 발표회 |     05/21     |       |       |       |       |       |       |       |       |       |   #    |

---