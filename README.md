# 🔎 Unity Client Programmer : [Lim Sung Gyu]

"단순한 기능 구현을 넘어, 유연한 시스템 설계와 사용자 피드백이 살아있는 플레이를 지향합니다."

안녕하세요, 탄탄한 C# 기초와 Unity 엔진 활용 능력을 바탕으로 게임의 코어를 설계하는 프로그래머 [임성규]입니다. 유저의 조작이 게임 속 물리 법칙과 상호작용할 때 발생하는 디테일을 조율하는 것에 즐거움을 느끼며, 확장성 있는 코드로 팀의 생산성에 기여하고자 합니다.

Unity와 C# 을 집중적으로 공부하며 유니티 게임개발을 하고 있습니다.

## 🔍 Tech Stack
<img src="https://img.shields.io/badge/C%23-239120?style=flat-square&logo=c-sharp&logoColor=white"/> <img src="https://img.shields.io/badge/UNITY-222222?style=flat-square&logo=Unity&logoColor=white"/>

## 🛠 Tools
<img src="https://img.shields.io/badge/VISUAL%20STUDIO-5C2D91?style=flat-square&logo=visual-studio&logoColor=white"/> <img src="https://img.shields.io/badge/GITHUB-181717?style=flat-square&logo=GitHub&logoColor=white"/>

## 🚀 Last Project
---
![Project Image](https://github.com/user-attachments/assets/36753e0c-eebc-4ad5-ba02-7b247c3c0c60)
<table border="0">
  <tr>
    <td><img src="https://github.com/user-attachments/assets/cb00f118-87bc-4ccd-9013-3ec54888546a" width="100%"/><br><sub><b>오브젝트 상호작용(상세보기)</b></sub></td>
    <td><img src="https://github.com/user-attachments/assets/9cbb731f-f708-4b48-9ae9-2116476ad395" width="100%"/><br><sub><b>오브젝트 상호작용(들고 옮기기)</b></sub></td>
  </tr>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/22957eae-c2b7-4c39-b2df-c354aab215f9" width="100%"/><br><sub><b>오브젝트 상호작용(들고 옮기기)</b></sub></td>
    <td><img src="https://github.com/user-attachments/assets/8d89c691-026f-49e1-b8ef-d3eb40f22225" width="100%"/><br><sub><b>물건 상세보기 중 QTE</b></sub></td>
  </tr>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/cd064a10-26ac-418d-83ed-a861c790b05b" width="100%"/><br><sub><b>반항형 죄수 전투</b></sub></td>
    <td><img src="https://github.com/user-attachments/assets/95d6b363-072e-4422-a623-f5cabad0cbd6" width="100%"/><br><sub><b>오브젝트 상호작용(들고 옮기기) 이후 등장하는 금지물품</b></sub></td>
  </tr>
</table>


**게임 타이틀: [근무 중 이상 무(ON DUTY: ALL CLEAR)]**

**개발 인원 : 기획 1인 / 아트 1인 / 프로그래머 3인**

**개발 기간 : 25.12 ~ 26.02 **

- 게임 환경 : PC(Windows)
- 엔진 : Unity 2022.3.62f2
- 환경 : Visual Studio 2022
- 버전 관리 : Git
- 협업 툴 :  Trello  |  Notion  |  Figma  | Slack

### 🛠️ Core Systems Developed
- **Dialogue System**: 데이터 기반의 대화 시퀀스 및 분기 처리 시스템 구축 * [DialogueManager.cs](https://github.com/zlkj483/ON_DUTY_ALL_CLEAR/blob/main/01_Scripts/09_Dialogue/DialogueManager.cs)
- **Game Management**: 전역 페이즈 및 게임 상태 제어를 위한 중앙 관리 시스템 구축 * [GameManager.cs](https://github.com/zlkj483/ON_DUTY_ALL_CLEAR/blob/main/01_Scripts/05_Manager/GameManager.cs)
- **Interaction System**: 상호작용(Lift&Drop) 로직 설계 * [Player_Interation](https://github.com/zlkj483/ON_DUTY_ALL_CLEAR/tree/main/01_Scripts/01_Player/Player_Interation)
- **Tutorial System**: 유저 조작 유도 및 단계별 가이드를 위한 튜토리얼 시퀀스 개발 * [Tutorial](https://github.com/zlkj483/ON_DUTY_ALL_CLEAR/tree/main/01_Scripts/09_Dialogue/Tutorial)
- **Scene Flow Control**: 씬 전환 및 시퀀스 연출의 순차적 흐름을 제어하는 컨트롤러 설계 * [FlowController.cs](https://github.com/zlkj483/ON_DUTY_ALL_CLEAR/blob/main/01_Scripts/07_Systems/FlowController.cs)

### 프로젝트 소개

- 근무 중 이상 무(On Duty: All Clear)는 1인칭 관찰 액션 게임으로,
교도관 시뮬레이션의 성격을 가지고 있습니다.
- 플레이어는 매일 사건 사고가 발생하는 교도소 7구역에서 근무하게 된 신임 교도관으로,
매일 달라지는 다양한 미션을 해결하여 교도소의 무사고 날짜를 7일까지 갱신해야 합니다.
- 무사고 날짜는 0일부터 시작합니다.
미션을 성공하면 무사고 날짜가 늘어나고, 미션에 실패하면 0일부터 다시 시작합니다.


