
# Project: ImitationTrigger

Dedicated Server 기반 멀티플레이어 PVP 3인칭 슈팅 배틀로얄 게임 개발 프로젝트입니다.
팀프로젝트로 진행했으며, 이 저장소는 개인 기여 내용을 부가 설명하기 위한 사본 저장소 입니다.

- 개발 기간: 2025.09.05 - 2025.10.16
- 역할: 리드 프로그래머

<img width="512" alt="image" src="https://github.com/user-attachments/assets/79913ed4-e309-4861-ac7a-4b535ce9f3f7" />

## 주요 외부 링크

| 링크 | 설명 |
|:--|:--|
| [원본 저장소](https://github.com/NbcampUnreal/3rd_4th-Team14-CH4-Project) | 실제로 프로젝트를 진행한 저장소입니다. 이 저장소에서 commit 내역과 PR 내역을 확인할 수 있습니다. |
| [플레이 영상](https://www.youtube.com/watch?v=qm7sJvVWLm8) | 실제 게임 플레이 영상을 확인할 수 있습니다. |
| [프로젝트 설명](https://15danpancake.atlassian.net/wiki/spaces/portfolio/pages/157384712/Project+Imitation+Trigger) | 프로젝트에 대한 설명, 문제 해결 과정, 구현 내용을 확인할 수 있는 기술 블로그입니다. |


## PR 리뷰 사례

더 많은 PR 사례는 원본 저장소의 [Pull Request](https://github.com/Team-Fairy-pitta/ProjectGunRogue/pulls?q=is%3Apr+is%3Aclosed) 페이지를 참고 바합니다.

### 꼼꼼한 코드 리뷰 사례

https://github.com/NbcampUnreal/3rd_4th-Team14-CH4-Project/pull/31

<img width="803" height="349" alt="image" src="https://github.com/user-attachments/assets/0d0c1925-8434-4c03-aed8-e8d46fe13ed1" />

<img width="811" height="480" alt="image" src="https://github.com/user-attachments/assets/5364ef08-8c76-4c8c-b281-f1d855bd95f8" />

<img width="809" height="527" alt="image" src="https://github.com/user-attachments/assets/9cba8d55-9bd0-4ea9-9850-5008a8bbf4a8" />


### PR 리뷰 및 테스트를 통해 버그를 발견한 사례

https://github.com/NbcampUnreal/3rd_4th-Team14-CH4-Project/pull/23

<img width="818" height="578" alt="image" src="https://github.com/user-attachments/assets/960946e5-1b15-4f3e-9217-5a4bfc643542" />



## 프로젝트 소스 코드 구성 설명

```
Source
└─ImitationTrigger/
    ├─AbilitySystem/            # GAS 관련 클래스
    ├─Camera/                   # Lyra-like 카메라 제어 관련 클래스
    ├─Character/                # 캐릭터 핵심 클래스
    ├─Cosmetics/                # 캐릭터의 외형을 담당하는 클래스
    ├─GameModes/                # 핵심 게임 모드
    ├─Input/                    # 입력 제어 클래스
    ├─Item/                     # 아이템 관련 클래스
    │  ├─Fragment/                 # 아이템의 기능(ex. 장착 가능)을 정의하는 Fragment 클래스 모음
    │  ├─Spawn/                    # 아이템 스포너 관련 클래스 모음
    │  └─Weapon/                   # 무기 클래스
    ├─NetWork/                  # 네트워크, 서버 관련 클래스
    ├─Player/                   # 플레이어 컨트롤러와 스테이트 
    ├─System/                   # 게임 시스템 관련
    └─UI/                       # Widget 클래스
```
