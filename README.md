# 기말 미션 5 - 15조 카르다르의 제임스

## 제작 의도 

- 생존을 위한 수단과 기술을 스스로 터득해 가는 재미를 준다. 단순한 생존을 위한 게임이 아닌 탈출을 할 수 있는 요건 등 개성있는 시나리오를 작성하여 게임의 엔딩을 제시함으로써 성취감을 얻어 게임을 지속할 수 있도록 하였다.

## 설명서
- 개발환경 :Unity 3D (PC, Mac & Linux Standalone)

- 사용 라이브러리 : C#

- 설치환경 : Window10 x64

- 개발 멤버 : 왕정현, 양희진

#### 게임의 기능(FPS 생존게임)

- FPS는 1인칭을 뜻하며 허기짐과 목마름, 갈등의 요소와 채집과 농사, 건축, 사냥 등의 생존요소와 밤이되면 몬스터가 공격하는 디펜스가 더하여진 1인칭 생존게임.

- 낮에는 생존을 위한 활동을 하고 밤에는 몬스터의 공격으로부터 생존을 위한 활동.

- 생존을 위해서는 생존 기술과 생존용 키트 두 가지의 생존 수단이 존재함.
- 생존 기술로는 도구와 무기, 건축물들을 제작하여 건축물을 건설하고 불을 피우고, 함정과 트랩 등을 설치하며 수집도구 제작 등을 통해서 생존을 위한 기술을 터득하고 익혀나감. 
- 생존용 키트의 경우 포션제작 키트, 조리 키트, 무기제작 키트, 연구 키트 등 생존기술을 업그레이드 할 수 있는 키트와 생존 및 생존 기술에 사용되며 이를 통해 안전하고 지속적인 생존을 해나갈 수 있음.

- 스테이터스(게이지)를 통해서 체력과 방어력, 배고픔, 목마름 등의 스테미나를 생존 기술 활용에 따라 증가 및 감소 시켜 생존 가능 여부 및 생존 불가 위험을 알림.

- 생존 과정에 있어 평범한 동물과 생김새의 차이가 없는 미지의 동물을 포획하게 됨.

- 미지의 동물 5마리를 모두 포획할 시 탈출할 수 있는 배가 주어지며 카르다르에서 탈출함으로써 게임은 종료하게 됨.


## 기획의도
### 이름 : < 카르다르의 제임스 >

### 개요

- 연구원 제임스가 미지의 동물을 포획하기 위해 전설의 섬 카르다르에서의 생존을 시작하게 된다. 제임스가 되어 방향키를 활용해 캐릭터를 움직이며 섬 내에서 생존을 위한 활동을 하게 된다. 기본적으로 아이템 및 인벤토리 시스템과 숫자 키를 활용한 퀵슬롯 시스템을 무기교체 및 크로스헤어 시스템을 지닌다. E키를 활용하여 아이템 수집 및 사냥한 동물의 해체 그리고 제일 중요한 미지의 동물 포획을 통해서 아이템을 수집과 생존 및 탈출을 위해 움직인다.

- 낮에는 생존을 위한 채집으로는 나무를 베고 광석을 채굴하며 나뭇가지를 베는 등의 시스템과 사냥으로 동물AI를 사냥하고 고기를 불에 익혀 먹는 시스템을 지닌다. 밤에는 몬스터로 부터의 공격을 받게 되는데 밤을 안전하게 보내기 위해서 건축을 통해서 안전 가옥인 집을 건설 한다. 그 곳에서 낮에 생존 키트와 포션 테이블을 제작하고 불을 설치하여 생존에 필요한 것을 지닌다. 또한 몬스터의 공격을 방어하기 위한 함정 및 트랩을 설치하고 방어타워를 건설한다.

- 이러한 생존 활동과 미지의 동물 포획을 위한 과정을 거쳐 전설의 섬 카르다르에서의 생존을 위한 활동과 탈출을 위한 포획과정을 반복해 나가며 미지의 동물 포획이 완료되는 시점에 배가 주어지면서 탈출에 성공하게 됨.

## 시나리오  

- 캐릭터 이름 : 제임스 올리버 왓슨

![james2](https://user-images.githubusercontent.com/84564086/120948444-29bca380-c77d-11eb-8a65-2efd1de6d56d.jpg)

- 캐릭터 특징 : 33세 영국의 고대 동물 연구소 LAA 수석연구원 

- 장소 : 미지의 섬 카르다르

- 스토리  

고대 동물을 연구하고 있던 연구원 제임스, 이야기로만 들리던 미지의 동물 5마리가 전설의 섬 카르다르에 살고 있다는 소식을 들었다. 이 동물들이 고대 동물의 습성을 그대로 가지고 있다는 말에 반드시 포획하여 연구할 계획으로 카르다르에 왔다. 이곳에서 3개월간 머물면서 동물을 포획하고 무사히 영국으로 다시 돌아가야 한다. 연구비를 명목으로 대기업의 후원을 받아 온 그는 이번 미션에 실패할 시 탈출할 배를 제공받지 못한다. 과연 제임스는 카르다르에서 죽지 않고 살면서 미지의 동물을 포획에 성공할 것인가?

- 오브젝트 설정

미지의 동물들은 생김새는 평범한 동물과 별 차이가 없다. 대신 이 동물임을 알아볼 수 있는 단서는 생포한 후 알 수 있다.
