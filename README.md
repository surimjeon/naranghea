
![로고](https://github.com/surimjeon/Algorithm-practice/assets/122578934/9d57368b-b322-4280-8560-cd81dae8185a)
<h3>바다쓰레기는 이제 그만! 캠페인 참여는, 나랑해!</h3>

<h4>아픈 바다를 깨끗하게</h4>

<h4>'나랑해'와 함께 지켜주세요!😃</h4> <br>

# 🔎 소개
나랑해 서비스는 지루하다고 여겨질 수 있는 해양환경 정화 캠페인을
사람들과 함께 __`소통`__ 하고, __`게임처럼 즐기면서 참여`__ 하는 통합 플랫폼입니다.

### 기획배경
1. 해양쓰레기 양 증가
해양수산부가 발표한 자료에 따르면, '23 해양쓰레기 양은 약 12만톤에 달하는 수치로, 매년 증가하는 추세

2. 통합 플랫폼 부재
각 지자체와 정부기관에서는 국민들이 해양정화활동에 참여할 수 있도록 캠페인을 진행 중이지만, 주관하는 기관이 달라, 참여자들은 캠페인 정보를 한번에 통합 제공받을 수 없음

3. 캠페인 참여자들의 흥미요소 제공 및 지속적 참여 독려 필요
캠페인 담당자의 자문에서 "참가자 대부분이 아이가 있는 가족들이지만, 아이들의 흥미를 끌만한 요소가 없어 이목을 끌기 어렵고, 참여가 일회성에 그친다"는 문제점을 인식

=> 해양환경 정화 캠페인을
사람들과 함께 __`소통`__ 하고, __`게임처럼 즐기면서 참여`__ 하는 통합 플랫폼 '나랑해' 기획

# 💡 세부기능 소개
1. 메인페이지
<img src="https://github.com/surimjeon/naranghea/assets/122578934/d5160009-9ba9-424e-bf5c-51911ee5a4d9" width=200 height=500/>

2. 게시판
- 자유/함께/신고 게시판
<img src="https://github.com/surimjeon/naranghea/assets/122578934/aa6b0600-d422-4403-af65-c3e90c4300ff" width=200 height=500/>

  - 자유: 자유롭게 사용자 간 소통할 수 있는 게시판
<img src="https://github.com/surimjeon/naranghea/assets/122578934/59ab0a75-d5c5-4728-bf44-985b79bd3d59" width=200 height=500/>

  - 함께: 캠페인에 함께 참여하고 싶은 사용자를 모집하는 게시판
     * 카카오톡 오픈채팅방 링크나 같이 참여하고 싶은 캠페인 링크 첨부 및 모집상태 변경 가능

  - 신고: 민원게시판 성격의 관리자에게 쓰레기가 많이 있는 위치를 신고할 수 있는 게시판
     * 지도핀으로 사용자가 쓰레기 많은 위치를 지정할 수 있음
  

3. 캠페인정보 확인 및 캐릭터 잡기
- 전국 지도에서 캠페인이 진행되고 있는 위치로 이동하면, 관련 캠페인정보와 해당 캠페인을 많이 참여한 사람 순으로 랭킹정보를 제공
- 해당 해변에 잡을 수 있는 캐릭터 랜덤으로 띄어줌
- AR기능으로 들어가서 캐릭터 잡기 모드를 ON 후 반경 50m내로 들어오면 AR이 켜지고, 쓰레기를 주운 후 간단한 환경 OX퀴즈를 풀면 캐릭터를 잡을 수 있음
- 캐릭터는 내가 원하는 이름으로 커스텀이 가능하며, 잡은 캐릭터는 내 도감에 저장할 수 있음
   

5. 도감
<img src="https://github.com/surimjeon/naranghea/assets/122578934/28e596c7-c8d5-45a4-9a82-1294e2501b8f" width=200 height=500/>

- 캠페인 참여와 AR기능으로 잡은 캐릭터는 나만의 도감에서 확인할 수 있음
- 아직 잡지 않은 캐릭터와 잡은 캐릭터를 구분하여 볼 수 있음
- 각 캐릭터를 누르면, 레벨, 해양생물 소개, 커스텀한 이름정보를 볼 수 있음
- 대표캐릭터로 지정하여, 해당 캐릭터의 레벨을 올려서 캐릭터를 키울 수 있음

6. 데잍리 미션
- 해양환경과 관련된 간단한 퀴즈를 풀고, 캐릭터 레벨을 올릴 수 있는 기능(1일 1회 참여가능)
- 출석체크 / OX퀴즈 / 4지선다 퀴즈 제공
- 1달기준 출석체크률과 미션달성률 제공
 

# ⚒ 백앤드

### 아키텍처
<img src="https://github.com/surimjeon/Algorithm-practice/assets/122578934/2855e606-da95-4280-b344-87dc6f5515a5" width=600 height=300/>

### 스킬
<img src="https://github.com/surimjeon/Algorithm-practice/assets/122578934/fb125012-e60b-42a2-9fb3-7bdc185edd38" width=500 height=300/>


# ⚒ 모바일 아키텍처
### 아키텍처
<img src="https://github.com/surimjeon/Algorithm-practice/assets/122578934/d083f103-94b0-4d68-aca9-98d568ff1cf2" width=600 height=300/>

### 스킬
<img src="https://github.com/surimjeon/Algorithm-practice/assets/122578934/993f4209-6fe1-44c5-b88d-a13a9717f3b2" width=400 heigth=300/>

# ⛏ 협업 툴
<img src="https://github.com/surimjeon/Algorithm-practice/assets/122578934/3a6b48c2-aa13-4509-9b42-89db8e865c21" width=300 heigth=300/>

# 👨‍👩‍👧 팀 소개
## 팀 멤버

> 나랑해팀 멤버들을 소개합니다!

|Android|Android|Android|Back end|Back end|Back end|
| :-: | :-: | :-: | :-: | :-: | :-: |
| ![김주용](/uploads/3a8c6bed088bff9f6ba53d641a5fe994/김주용.png) | ![박준후](/uploads/162b65523374ade6f12b69dcfcc8fa6c/박준후.png) | ![황신운](/uploads/7291266a035a0efa783a13cfc87af3f5/황신운.png) | ![김수민](/uploads/972f2b0e5cd0908693728bbe0e127b19/김수민.png) | ![전수림](/uploads/4c48c5d87da097c8b9712a6ff471318e/전수림.png) | ![정진욱](/uploads/bf74f49b02cb42cf7534c1eebc6c91aa/정진욱.png)
|김주용(팀장)|박준후|황신운|김수민|전수림|정진욱
