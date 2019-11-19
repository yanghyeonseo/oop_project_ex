# 2019-2 객체지향 프로그래밍 프로젝트 - **{SPAM}**
구성원: 2-2 지원호 | 2-3 양현서 | 2-4 여주현

## 1. 주제
 SASA를 배경으로 한 gun mayhem을 응용한 다인용 플래시 게임 제작.

## 2. 동기
SASA의 많은 학생들이 PC 게임을 즐기고 있지만 2명 이상의 친구들이 모여 같이 게임을 즐기기에는 번거로운 부분이 많다. 보통의 온라인 게임은 플레이하기 위해서는 인터넷에 접속되어야 하고, 실행시키는데 걸리는 대기시간이 길어 틈틈히 짬을 내어 플레이하기에는 불편한 점이 많다. 따라서 인터넷 없이 하나의 PC로 여러 명이 플레이할 수 있는 게임을 제작함으로써 SASA 학생들의 친밀감을 높이고 스트레스를 풀 수 있도록 하고자 한다.

## 3. 프로그램 사용 대상
기존의 건 메이헴을 사사를 배경으로 재구성한 게임을 오프라인으로 즐기고 싶은 게임 플레이어

## 4. 목적
 이미 온라인 상에서 2인 이상이 플레이 할 수 있는 게임은 많이 존재하고 있다. 하지만, 2인 이상 플레이 가능한 게임을 진행하기 위해서는 인터넷이 있는 곳에서만 가능하다는 점이 있었기 때문에 조금 불편한 점이 존재했다. 또한, 온라인으로 하는 다인용 게임은 우리 말고도 플레이하는 사람이 많기 때문에, 대기해야 하는 시간이나 딜레이들이 생기기 마련이며, 또한 서버를 점검해야 하는 탓에 몇번씩 게임이 닫히기도 한다. 그렇기 때문에 이런 문제점들을 해결하면서도 다인용 플레이가 가지고 있는 장점들을 끌고 가기 위해 오프라인에서도 실행할 수 있는 다인용 게임을 제작해 보려고 함이 그 목적이다. 

## 5. 주요기능
### 1. 스테이지

   : 스테이지는 뒷 배경과 보드, 배경음악으로 구성된다. 플레이어, 총알, 아이템은 스테이지 내에서 생성되고, 관리된다.
 + 뒷 배경
   - 뒷 배경은 SASA인들에게 친숙한 장소를 바탕으로 한다. 게임 시작 화면에서 선택할 수 있다.
 + 보드
   - 스테이지에는 보드들이 있으며, 플레이어와 아이템은 보드에게 받쳐진다. 보드 위에 있지 않은 플레이어 및 아이템은 중력의 영향을 받아 추락한다.

### 2. 플레이어

   : 다양한 디자인의 캐릭터 이미지가 있지만, 모든 플레이어의 능력은 동일하다. 플레이어는 생명을 가지며, 생명을 모두 소진하면 패배한다. 처음에는 5개의 생명을 가지고 시작하며, 화면 밖으로 추락할 경우 하나의 생명이 감소하고, 생명 아이템을 획득할 경우 하나의 생명이 증가한다. 플레이어는 좌우 이동, 2단 점프, 보드 통과, 총 발사 등의 동작을 할 수 있다. 이때, 총알 업그레이드 아이템을 획득한 경우 이후에 발사하는 총알은 일정 개수 상대 플레이어를 더 많이 밀어낼 수 있다.
 + 플레이어 동작
   + 좌우 이동
     - 보드 위에 있는지 여부와 관계없이 일정한 속력으로 좌우로 이동할 수 있다.
   + 점프
     - 일정한 초기 속력으로 최대 2번 점프할 수 있으며, 2번 점프한 경우 보드에 닿을 때까지는 점프할 수 없다.
   + 보드 통과
     - 현재 자신이 밟고 있는 보드를 통과하여 아래로 이동할 수 있다.
   + 총 발사
     - 

판에서 추락하면 목숨을 잃으며 하늘에서 떨어지며 부활한다. 선택에 따라 다양한 디자인의 배경이 적용된다.
플레이어는 게임 시작 전 다양한 종류의 캐릭터를 선택할 수 있다. 캐릭터는 지형 위를 걷거나 점프할 수 있다. 캐릭터는 총을 지니고 있으며, 총알을 발사할 수 있다. 캐릭터는 총알을 맞을 시 뒤로 말려나게 된다. 총 5개의 생명이 있으며, 한번 떨어질 때 마다 줄게 1개씩 감소하게 되고 다 없어지게 되면 지는 것으로 게임이 종료되게 된다. 

3. 총알

총에서 발사된다. 

4. 아이템 시스템

생명 아이템을 먹으면 생명이 1개 증가한다. 총 아이템을 먹으면 일정 시간 동안 총알의 데미지가 증가한다. 방패 아이템을 먹으면 일정 시간 동안 총알을 맞아도 데미지를 입지 않는다.

5. 음향 효과

배경 음악과 함께 여러 효과음이 있다. 총을 쏠 때 총소리와 플레이어가 죽을 때 소리와 아이템을 획득했을 때 소리가 있다.

## 6. 프로젝트 핵심
 

## 7. 구현에 필요한 라이브러리나 기술
{pygame}
{random}


## 8. **분업 계획**
1. 양현서: 움직임, 총알 등과 같은 캐릭터 및 요소의 동작 제어하기
2. 여주현: 캐릭터의 동작에 따라 움직이는 이미지 입히기
3. 지원호: 스테이지 및 아이템 요소들 만들기


## 9. 기타



#### readme 작성관련 참고하기 [바로가기](https://heropy.blog/2017/09/30/markdown/)

#### 예시 계획서 [[예시 1]](https://docs.google.com/document/d/1hcuGhTtmiTUxuBtr3O6ffrSMahKNhEj33woE02V-84U/edit?usp=sharing) | [[예시 2]](https://docs.google.com/document/d/1FmxTZvmrroOW4uZ34Xfyyk9ejrQNx6gtsB6k7zOvHYE/edit?usp=sharing) | [[예시 3]](https://github.com/goldmango328/2018-OOP-Python-Light) | [[예시4]](https://github.com/ssy05468/2018-OOP-Python-lightbulb) | [[모두보기]](https://github.com/kadragon/oop_project_ex/network/members)
