# Running Man (made by unity3D)
런닝맨 게임 제작에 추가될 기능 기술

## 현황
진행도 : 93
완성도 : 127
진행률 : 73.23%

## 캐릭터 (13/17)
- 이동 (4/5)
    - [X] 제자리 점프할 때 앞으로 이동할 수 있게 수정
    - [X] 첫 발걸음을 내딛을 때 점프를 입력하면 강력한 도약이 가능하도록 추가
    - [X] 도약 도중에 전진 키를 입력하면 공중에서 브레이크 걸리도록 추가
    - [X] 앉은 상태에서 점프 시 더 높게 점프할 수 있도록 기능 추가
    - [ ] 'shift'키를 누를 경우 달릴 수 있도록 수정

- 옮기기 (3/5)
    - [X] G키로 물건 잡기 추가
    - [X] 잡고 있는 물건에 대해 키보드 입력을 통한 'Rotation'변경 기능 추가
    - [X] 잡은 물건을 놓을 때 일시적으로 중력의 영향을 받도록 추가
    - [ ] 잡고 있는 물체를 전방으로 던지는 기능 추가
    - [ ] 플레이어가 물건을 들고 있을 때, 이동속도가 느려지도록 추가
    
- 스탯 (6/7)
    - [X] 캐릭터 텍스쳐 입히기
    - [X] 플레이어 생명력 추가
    - [X] 낙하 시간에 따른 낙하 데미지 추가
    - [X] 'crouch'를 하고있을 때 생명력이 서서히 회복되도록 추가
    - [ ] 플레이어가 jump/crouch/grab 할 때 사운드 추가
    - [X] 생명력 0이되면 라운드 재시작 추가
    - [X] 맵 밖으로 떨어지면 체력을 감소시키고 초기 위치로 이동하도록 추가
    
## 아이템 (13/19)
- 오브젝트 (3/5)
    - [X] 아이템 추가
    - [X] 아이템 움직이는 모션 추가
    - [ ] 아이템 획득 시 이펙트 추가
    - [X] 아이템 획득 시 해당 오브젝트 파괴되도록 추가
    - [ ] 아이템 획득 시 효과음 추가
    
- 아아템 (7/8)
    - [X] 체력을 일정시간동안 재생시켜주는 아이템 추가
    - [X] 이동속도를 일정시간동안 상승시켜주는 아이템 추가
    - [X] 점프력을 일정시간동안 상승시켜주는 아이템 추가
    - [X] 일정시간동안 무적이되는 아이템 추가
    - [X] 일정시간동안 화염방사를 활 수 있는 필살기 아이템 추가
        - [X] 우클릭으로 화염방사 할 수 있도록 추가
        - [X] 화염 효과에 'collsion'을 추가하여 이펙트 닿을 시 체력감소 추가
    - [ ] 아이템 사용 상태일 때 배경음악이 빠르게 재생되도록 추가
    
- 플레이어 (3/6)
    - [X] 플레이어 피격 시 사운드 추가
    - [X] 플레이어 체력 감소 시 피격 효과 추가
    - [ ] 플레이어 공격 시 공격 사운드 추가
    - [ ] 아이템 인벤토리 추가
    - [ ] 아이템을 소지하며 버튼을 누를 경우 아이템을 사용하도록 추가
    - [X] 아이템 효과가 지속될 때 플레이어에게 이펙트 효과가 지속되게 추가
    
## 카메라 (1/2)
- 보정 (1/2)
    - [ ] 카메라 시점 변경 1인칭, 3인칭
    - [X] 벽에 등을 맞닿았을 때 3인칭 카메라가 벽을 통과하지 않도록 시점 변환

## 특수 블록 (6/8)
- 함정 (4/4)
    - [X] 함정 블록 추가
    - [X] 함정 블록위에 올라가서 함정이 발동될 경우 생명력이 감소되도록 추가
    - [X] 피해를 입고 있을 때 사운드 추가
    - [X] 피해를 입고 있을 때 출혈 효과 추가

- 특수 블록 (2/4)
    - [X] 점프 대 블록을 추가하여 위에 서있을 경우 점프력이 순간적으로 향상되도록 추가
    - [ ] 미끄러지는 블록을 추가하여 밟을 시 전방으로 빠르게 미끄러지도록 추가
    - [ ] 느려지는 블록을 추가하여 위에 있을 시 느려지도록 추가
    - [X] 물 블럭에 착지 시 낙하데미지 제거
    
## 라운드 (15/24)
- 라운드 (2/6)
    - [X] 라운드 추가
    - [ ] 라운드 시작 시 몇 라운드인지, 맵 이름 알려주도록 추가
    - [ ] 라운드 시작 시 카메라를 1초간 지진효과가 나도록 추가
    - [X] 라운드 클리어 시 해당 라운드까지의 총 점수를 도합하여 화면에 표시
    - [ ]라운드 클리어 시 폭죽 이펙트가 화면에 나오도록 추가
    - [ ]라운드 클리어 시 축하 사운드가 나오도록 추가
    
- 라운드 내 기능 (13/18)
    - 별 (5/6)
        - [X] 별을 모두 수집하면 라운드 클리어 되도록 추가
        - [X] 별의 수집 개수를 화면에 출력
        - [X] 수집한 별이 제거되도록 추가
        - [X] 별을 획득 시 효과 추가
        - [X] 별을 획득 시 사운드 추가
        - [ ] 별을 획득 시 생명력 회복 추가
    - 영혼 (6/6)
        - [X] 영혼을 모두 해방하면 라운드 클리어 되도록 추가
        - [X] 영혼의 수집 개수를 화면에 출력
        - [X] 영혼과 닿으면 영혼이 제거되도록 추가
        - [X] 영혼을 해방 시 효과 추가
        - [X] 영혼을 해방 시 사운드 추가
        - [X] 영혼을 해방 시 해당 위치에서 스켈레톤이 소환되도록 추가
    - 포탈 (2/6)
        - [X] 포탈에 도달 시 다음 라운드로 도달하도록 추가
        - [X] 포탈 이펙트 추가
        - [ ] 포탈 사운드 추가
        
## 무기 (9/13)
- 오브젝트 (9/9)
    - [X] E키로 무기 주울 수 있도록 추가
    - [X] Q키로 무기 버릴 수 있도록 추가
    - [X] 무기 아이템 주워서 플레이어 머리 위에 떠있도록 추가
    - [X] 무기 아이템의 회전 모션 추가
    - [X] 무기 아이템 이펙트 추가
    - [X] 무기 아이템 사운드 추가
    - [X] 무기 획득 시 획득한 무기 정보를 자막에 
    - [X] 우클릭 누르면 무기 발사
    - [X] 무기를 들고 있을 때 몬스터를 타격할 수 있도록 추가

- 총알 (0/4)
    - [ ] 무기 발사 사운드 추가
    - [ ] 무기 타격 시 이펙트 추가
    - [ ] 무기 중력 추가
    - [ ] 발사된 무기가 오브젝트와 부딪히면 파괴되도록 추가

## 몬스터 (18/22)
- 오브젝트 (14/18)
    - [X] 몬스터 추가
    - [ ] 몬스터 중력추가
    - [X] 플레이어가 공격 범위 내에 있을 때 공격 상태 추가
    - [X] 공격 시 공격 모션 추가
    - [X] 플레이어가 공격 범위 밖에 있을 때 플레이어 추격 추가
    - [X] 추격 시 걸어가는 모션 추가
    - [X] 몬스터 체력 추가
    - [X] 플레이어의 공격관련 기술을 맞을 시 체력 감소
    - [X] 몬스터 피격 시 피격 애니메이션 추가
    - [X] 몬스터 사망 시 사망 모션 추가
    - [X] 몬스터 사망 시 사망한 자리에 아이템 소환 추가
    - [ ] 몬스터를 처치 시 아이템 드롭기능 추가
    - [X] 몬스터에게 부딪힐 시 체력 감소
    - [X] 몬스터의 공격에 맞을 시 체력 감소
    - [X] 몬스터 사운드 추가
    - [X] 몬스터마다 Pitch 값을 랜덤으로 스폰되도록 추가
    - [ ] 몬스터가 마법을 사용할 때 이펙트 추가
    - [ ] 몬스터의 남은 체력 상태를 머리 위에 표시
    
        
- [X] 소라게 추가 (2/2)
    - [X] 소라게가 일정한 루트로 왕복이동 하도록 추가
    
- [X] 스켈레톤 추가 (1/1)

- [X] 오크보스 추가 (1/1)

## 튜토리얼 (5/8)
- 안내 (3/5)
    - [X] 튜토리얼 라운드 추가
    - [ ] 기본 설정된 키보드 버튼의 기능을 알려주는 UI 추가
    - [X] 튜토리얼 방 마다 안내문 추가
    - [X] 튜토리얼 안내문 애니메이션 추가
    - [ ] 튜토리얼 안내문 사운드 추가
     
- 설정 (2/3)
    - [ ] 최초 실행 시 플레이어가 원하는 키로 설정할 수 있도록 UI 추가
    - [X] 캐릭터의 회전감도를 '[, ]'키로 설정할 수 있도록 추가
    - [X] 'PageUp, PageDown'으로 라운드 스킵기능 추가

## UI (10/14)
- 화면 출력 (4/7)
    - [ ] 랭킹 페이지 추가
    - [ ] 신기록 달성 시 축하음과 새로운 기록을 새웠다는 메세지 출력 추가
    - [X] 처치할 몬스터 수 화면에 출력
    - [X] 플레이어의 체력 상태를 화면에 출력
    - [ ] 아이템의 남은 유효시간을 표시
    - [X] 감도 조절 시 현재 감도 수치를 알림
    - [x] 라운드 실패 시(사망) 실패 메세지 출력
    
- 게임 메인 (4/5)
    - [X] 카메라 이동 애니메이션 추가
    - [X] 스타트 버튼 추가
    - [X] 스타트 버튼 깜빡이는 애니메이션 추가
    - [ ] 버튼입력 시 사운드 추가
    - [X] 버튼 입력 시 튜토리얼로 이동 추가
    
- 게임 엔딩 (2/2)
    - [X] 게임 클리어 시 크레딧 화면 출력
    - [X] 뒤로가기 버튼 추가
    
