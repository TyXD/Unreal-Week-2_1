# [내일배움캠프 Unreal] 사전캠프 - 레벨 생성 및 기본 오브젝트 배치

## 1. 오늘 배운 개념 요약 

>### 레벨

언리얼 엔진에서 **레벨**은 **게임 안에서 하나의 맵 또는 공간**을 의미합니다.

하나의 프로젝트 안에 **여러 개의 레벨**들이 있을 수 있고, 각각 **독립된 씬**처럼 작동합니다.

>### 스태틱 메시란?

스태틱 메시는 움직이지 않는 *3D 오브젝트**(예 : 벽, 바닥, 건물 등)을 의미합니다.

모든 레벨 구성은 다양한 **Static Mesh를 조합**해서 완성합니다.

## 2. 구현 과정 요약 (스크린샷 + 간단 설명)

<img width="2559" height="1503" alt="Image" src="https://github.com/user-attachments/assets/b8bd1a1c-25d7-4e07-85a3-e95b1c668e4c" />

<img width="2557" height="1522" alt="Image" src="https://github.com/user-attachments/assets/a648b38b-f22f-47b3-8e58-ebc0f32b3757" />

<img width="2537" height="1537" alt="Image" src="https://github.com/user-attachments/assets/4770d6cc-7d2d-4526-94d6-e323e33910ac" />

빈 레벨을 만들고 레벨을 다른 이름으로 저장하였다

<img width="2546" height="1584" alt="Image" src="https://github.com/user-attachments/assets/a986324c-d8d7-4a15-876d-0ab368118b43" />

큐브를 생성하고 스케일을 조정해 바닥으로 만들었다

<img width="2559" height="1599" alt="Image" src="https://github.com/user-attachments/assets/4268d4ff-865b-43f6-a74b-a8bbce4d7eea" />

큐브를 복제하고 스케일을 조정해 벽으로 만들었다

<img width="2559" height="1599" alt="Image" src="https://github.com/user-attachments/assets/fd5d43ff-8912-4387-b617-caf95868261d" />

큐브와 실린더의 스케일과 위치를 조정하여 테이블과 의자로 보이게 만들었다.

<img width="2559" height="1599" alt="Image" src="https://github.com/user-attachments/assets/3b350eaa-65a5-408c-a649-eacaf912745f" />

카메라를 움직여 다른 각도에서 테이블과 의자를 확인하였다.


## 3. 느낀 점 & 개선하고 싶은 점

간단한 큐브를 가지고 스케일을 조정해 여러 오브젝트로 표현할 수 있는 모습이 신기했다.

# [내일배움캠프 Unreal] 사전캠프 - 조명과 머티리얼 기본 적용

## 1. 오늘 배운 개념 요약 

>### 조명(Light) 종류

Directional Light: 현실의 **태양 빛**처럼 **전체 씬에 영향**을 준다.

Point Light: 현실의 **전구**처럼 **특정 위치에서 빛을 방사**한다.

Spot Light: 현실의 **스포트라이트**처럼 **특정 방향으로 빛을 집중**시킨다.

>### 머티리얼(Material)이란?

**오브젝트에 적용되는 재질**로, **색상만 아니라 반사, 광택, 질감** 등 표현할 수 있다.

Material Instance를 사용하면 **기존 머티리얼을 빠르게 커스터마이징**이 가능하다.

## 2. 구현 과정 요약 (스크린샷 + 간단 설명)
<img width="2559" height="1599" alt="Image" src="https://github.com/user-attachments/assets/726179cf-0d20-4e75-981d-3f2a7484ba2a" />

<img width="2559" height="1599" alt="Image" src="https://github.com/user-attachments/assets/90347b16-9e52-4474-b524-b58b4087c012" />

Directional Light를 추가해 씬 전체에 조명효과가 적용되게 하였다.

<img width="2559" height="1599" alt="Image" src="https://github.com/user-attachments/assets/9544ceb8-7f77-4b0c-b6b5-8b67c2c36cab" />

Point Light를 추가해서 지붕으로 덮인 안쪽 부분에 조명을 추가하였다.

<img width="2559" height="1599" alt="Image" src="https://github.com/user-attachments/assets/19aa7d31-f4e0-4003-a783-df1be1398fed" />

조명 광량 조절

<img width="2559" height="1599" alt="Image" src="https://github.com/user-attachments/assets/65912a0f-8ec5-494f-b254-7c5ef0380bb4" />

조명색 조절

<img width="2559" height="1599" alt="Image" src="https://github.com/user-attachments/assets/9192015e-f559-4f33-8274-be053ab284f9" />

Point Light를 하나 더 추가해서 서로 다른 분위기를 대비하여 보이게 만들었다.

<img width="2559" height="1599" alt="Image" src="https://github.com/user-attachments/assets/cf45ce1b-4dcd-45ec-aa44-7187c7017611" />

바닥과 벽에 기존 콘텐츠에 있는 머테리얼을 부여 하였다.

<img width="2559" height="1599" alt="Image" src="https://github.com/user-attachments/assets/d3d94c97-326e-4ead-b87c-c6d1d552d986" />

M_Mint 머테리얼을 새로 만들어 테이블 오브젝트 윗면에 부여 하였다.

<img width="2559" height="1599" alt="Image" src="https://github.com/user-attachments/assets/4e87dd07-b7c9-4154-b386-11289d5f8356" />

<img width="2559" height="1599" alt="Image" src="https://github.com/user-attachments/assets/2f46c98d-7770-4d18-9e57-a5bd22e7dca0" />

Directional Light의 각도를 변화시켜서 낮과 저녁, 밤을 연출하였다.
|제목|내용|
|---|---|
|바닥|M_Metal_Gold|
|벽_1|M_Concrete_Poured|
|벽_2|M_Concrete_Tiles|
|벽_3|M_Concrete_Grime|
|벽_4|M_Concrete_Pannels|
|테이블|M_Mint|

3. 느낀 점 & 개선하고 싶은 점
조명의 조절에 따라 레벨의 분위기와 특정 공간의 감성을 변화시킬 수 있다는 사실을 알았습니다.

# [내일배움캠프 Unreal] 사전캠프 - 에셋 다운로드 및 커스터마이징 실습

## 1. 오늘 배운 개념 요약 

>### 에셋(Asset)이란?

3D 모델, 머티리얼, 애니메이션, 사운드 등 콘텐츠 구성 요소의 총칭

언리얼에서는 .uasset 형식으로 사용

>### 대표적인 에셋 플랫폼

Fab (공식, Unreal Engine 통합)

> Fab은 Unreal Engine Marketplace, Sketchfab, Quixel, Artstation Marketplace를 결합한 플랫폼입니다.

다양한 에셋을 쉽게 검색하고 다운로드할 수 있습니다.

Sketchfab, TurboSquid, Free3D 등 (FBX 등 외부 포맷)

> 외부 포맷으로 제공되는 에셋을 Unreal Engine에서 사용하려면 적절한 포맷으로 변환해야 합니다.

>### 에셋 구매 및 다운로드 공식 문서

https://dev.epicgames.com/documentation/ko-kr/fab/purchasing-and-downloading-assets-in-fab


## 2. 구현 과정 요약 (스크린샷 + 간단 설명)

<img width="2556" height="1583" alt="Image" src="https://github.com/user-attachments/assets/dd37f98b-28b8-4bf1-a6bb-48d28433d9ee" />

콘텐츠 브라우저 상단의 Fab 버튼 클릭

<img width="2533" height="1365" alt="Image" src="https://github.com/user-attachments/assets/beca7ad4-9d51-4522-8626-af21e35c3d5a" />

마음에 드는 오브젝트를 Add to My Library 클릭하여 내 라이브러리에 추가

<img width="2559" height="1599" alt="Image" src="https://github.com/user-attachments/assets/95f27292-67de-4f46-8931-a46a33134386" />

원하는 에셋을 Add to Project 버튼으로 프로젝트에 임포트

<img width="2217" height="1359" alt="Image" src="https://github.com/user-attachments/assets/c337eaf9-d462-4e99-9e76-c2295a35a9b5" />

씬에 에셋을 배치

이동, 회전, 크기 조정(Transform Tool) 기능으로 위치 정리

<img width="2559" height="1599" alt="Image" src="https://github.com/user-attachments/assets/abc27923-eac8-496d-ba10-28dd35f46993" />

<img width="2559" height="1587" alt="Image" src="https://github.com/user-attachments/assets/a2e9c249-0e1d-4b77-b60d-5e8461bd3422" />

<img width="2559" height="1599" alt="Image" src="https://github.com/user-attachments/assets/e065779d-7a71-4fc2-a159-6893d041f461" />

<img width="2559" height="1599" alt="Image" src="https://github.com/user-attachments/assets/c0db88e2-35d6-45ea-9536-77f225870028" />

폴더 구조를 머테리얼, 텍스쳐, 메쉬로 나누어 깔끔하게 정돈

## 3. 느낀 점 & 개선하고 싶은 점

FAB을 활용해서 다른 제작자가 만든 내가 원하는 스타일의 오브젝트를 쉽게 구할 수 있어서 

제작할 떄 어느 정도 게임의 틀이 명확하게 보여 좋았습니다.

# [내일배움캠프 Unreal] 사전캠프 - 캐릭터 Blueprint 생성 및 이동 설정

## 1. 오늘 배운 개념 요약 

### 블루프린트(BluePrint)란?

언리얼 엔진의 **비주얼 스크립팅 시스템**

**코드 없이 로직을 구성**할 수 있음 (클래스 설계 가능)

### Input Mapping이란?

키보드/마우스/패드 등의 **입력**을 게임 안의 **행동(이동, 점프 등)**과 **연결하는 시스템**

## 2. 구현 과정 요약 (스크린샷 + 간단 설명)

<img width="2550" height="1588" alt="Image" src="https://github.com/user-attachments/assets/7c7c353b-4ae8-4f05-9aa8-21964b3518b6" />

새로운 언리얼 프로젝트 생성, Third Person Template 선택하기

Starter Content 포함되게 설정

<img width="2559" height="1599" alt="Image" src="https://github.com/user-attachments/assets/5684692d-a862-4405-9b1f-11ac504a5eca" />

Content > ThirdPerson > Blueprints > BP_ThirdPersonCharacter 열기

<img width="2559" height="1599" alt="Image" src="https://github.com/user-attachments/assets/6dbbc06b-a1a6-4bb4-9007-71bf1b446e54" />

BP_ThirdPersonCharacter를 복제하여 MyCharacter로 이름 변경

<img width="2559" height="1539" alt="Image" src="https://github.com/user-attachments/assets/d2e0ece5-1574-45c1-ac54-4c8cef1c57ae" />

Content > ThirdPerson > Input > IMC_Default 확인하기

<img width="2180" height="1376" alt="Image" src="https://github.com/user-attachments/assets/22fbca21-f4e4-4e12-985b-8993d0cf919e" />

Project Settings > Maps & Modes > Default Pawn Class를 MyCharacter로 변경

<img width="1454" height="1130" alt="Image" src="https://github.com/user-attachments/assets/d2b520ba-e74a-40f6-913c-8dc6d43f1033" />

<img width="1519" height="1119" alt="Image" src="https://github.com/user-attachments/assets/aaa00c25-5ecd-443c-82e1-f2eac7a08359" />

캐릭터가 키보드 입력에 따라 이동하는지 확인하기

> ### 영상

![Image](https://github.com/user-attachments/assets/d6ab9af0-9d3e-4c02-b0ae-d4d4daca669d)

## 3. 느낀 점 & 개선하고 싶은 점

블루 프린트를 활용하면 간단하게 키보드 키 맵핑하고 마우스 연결해서 플레이어를 조종할 수 있다는 게 너무 편했습니다.

# [내일배움캠프 Unreal] 사전캠프 - 캐릭터 이동 구현 (Part 2)

## 1. 오늘 배운 개념 요약 

### Character Movement Component란?

언리얼의 기본 캐릭터 클래스에는 **움직임을 제어하는 컴포넌트**가 기본 탑재되어 있다.

**이동 속도, 점프 높이, 중력 설정** 등 다양한 조절이 가능하다.

### Spring Arm + Camera 세팅

Spring Arm은 **카메라와 캐릭터 간 거리를 부드럽게 유지**해 준다.

카메라가 **캐릭터를 따라다니며 회전**하게 만들 수 있다.

## 2. 구현 과정 요약 (스크린샷 + 간단 설명)

<img width="1460" height="1069" alt="Image" src="https://github.com/user-attachments/assets/39dd4942-c4ba-47d1-9faa-a76a56c28e6f" />

Content > ThirdPerson > Input > IMC_Default에서 Jump 액션 확인 (기본: Spacebar)

MyCharacter 블루프린트에서 Jump 입력 이벤트 연결

MyCharacter 블루프린트 → Event Graph

우클릭 → InputAction Jump 검색 → Event → Jump() 노드 연결

InputAction StopJumping → StopJumping() 연결

<img width="573" height="1183" alt="Image" src="https://github.com/user-attachments/assets/3898e83a-266c-4717-b0ed-9e5b50636203" />

MyCharacter > Character Movement 컴포넌트 선택

Max Walk Speed: 기본 500 → 800 

Jump Z Velocity: 기본 700 → 600

<img width="736" height="1210" alt="Image" src="https://github.com/user-attachments/assets/8c599f16-fc41-490f-bd23-1613e98f6d60" />

MyCharacter > SpringArmComponent 선택

Use Pawn Control Rotation: 체크

<img width="768" height="1280" alt="Image" src="https://github.com/user-attachments/assets/7bb1ce2d-9eb1-429d-bb78-c0f8a41c337a" />

CameraComponent 선택해서

Use Pawn Control Rotation: 체크 해제

<img width="1043" height="1373" alt="Image" src="https://github.com/user-attachments/assets/5e5d2782-012e-451d-ba82-6607aa8c148c" />

MyCharacter 블루프린트의 Class Defaults에서

Use Controller Rotation Yaw: 체크

![Image](https://github.com/user-attachments/assets/ccb6fc1d-2b5c-4766-82b4-119647059131)

WASD + 마우스 회전 + 점프 조합으로 캐릭터 조작

자연스럽게 회전하며 걷고 점프하는지 확인

## 3. 느낀 점 & 개선하고 싶은 점

플레이어 세팅에 따라서 카메라도 플레이어 움직임에 관여할 수 있는 부분이 흥미로웠다.

# [내일배움캠프 Unreal] 사전캠프 - 에셋 내비게이션 및 간단한 게임 씬 구성

## 1. 오늘 배운 개념 요약 

### 내비게이션(Navigation)이란?

캐릭터가 **씬 안에서 자연스럽게 이동할 수 있는 공간**을 의미합니다.

**지나갈 수 없는 곳은 막고, 통과 가능한 구조를 명확히** 해야 게임이 부드럽게 동작합니다.

### 충돌(Collision)이란?

**오브젝트와 캐릭터가 실제로 닿는지 아닌지를 판별**해 주는 시스템입니다.

**벽을 뚫고 지나가지 않도록** 설정하는 데 사용됩니다.

## 2. 구현 과정 요약 (스크린샷 + 간단 설명)

<img width="2559" height="1389" alt="Image" src="https://github.com/user-attachments/assets/71575147-e565-47c1-b505-f9b1be15e545" />

일본풍 방을 만들기로 계획하고 

배경이 되는 바닥과 벽 오브젝트를 FAB에서 구해 배치

<img width="2559" height="1599" alt="Image" src="https://github.com/user-attachments/assets/cc984ba2-05d4-454e-90d3-5b5f45347034" />

에셋에서 다양한 Static Mesh 배치

Transform 조절을 활용해 다양하고 자연스럽게 배치

[Step 3] 캐릭터 내비게이션 확인

<img width="1578" height="1318" alt="Image" src="https://github.com/user-attachments/assets/afe7d119-6988-4e88-b498-63ba64f7bf98" />

<img width="2038" height="1422" alt="Image" src="https://github.com/user-attachments/assets/9e7b824c-f6e6-4968-8c41-bbaca2dc9633" />

<img width="1654" height="1195" alt="Image" src="https://github.com/user-attachments/assets/66b6c22c-5fa9-4ff6-97b3-2d0899e3c907" />

<img width="1621" height="1335" alt="Image" src="https://github.com/user-attachments/assets/6a872bd3-ea98-4898-92d0-d7a29ba54e4b" />

캐릭터가 부드럽게 돌아다닐 수 있도록 충돌 영역 조정

지나가지 못해야 할 벽/장애물에는 Collision을 없애고 정확한 Collision 다시 설정

https://youtu.be/rAG1MoQRUp4

WASD로 걷고, 마우스로 둘러보고, 점프하면서 이동성 확인

좁은 길, 계단 등 다양한 경로를 시도해보기

## 3. 느낀 점 & 개선하고 싶은 점

FAB을 통해 내가 원하는 컨셉의 에셋 모음을 발견하고, 에셋을 적절히 배치해서

내가 원하는 레벨을 만들었고, 에셋의 콜리전을 수정하여 플레이어가 통로들을 지나다닐 수 있게 만들었습니다. 

# [내일배움캠프 Unreal] 사전캠프 - 문 열기 또는 아이템 줍기

## 1. 오늘 배운 개념 요약 

### Line Trace란?

눈앞에 있는 **오브젝트를 탐지하는 “레이저 광선”** 같은 기능

마우스나 키보드로 **상호작용 대상 탐지** 시 사용됨

### 인터랙션 키 바인딩

**키보드 입력을 통해 특정 이벤트** 실행

일반적으로 **E 키나 마우스 클릭**에 매핑

## 2. 구현 과정 요약 (스크린샷 + 간단 설명)

<img width="2559" height="1500" alt="Image" src="https://github.com/user-attachments/assets/e03a2da3-ecb3-47ca-8159-94421882426a" />

Content > ThirdPerson > Input > Action에 IA_Interact(키: E) 추가

<img width="2559" height="1599" alt="Image" src="https://github.com/user-attachments/assets/5001dbca-b121-4fec-9675-98e0e62887cf" />

Content > ThirdPerson > Input > IMC_Default에 IA_Interact(키: E)에 등록하여

E 키 이벤트를 블루프린트에서 찾기 위함.

<img width="1845" height="1534" alt="Image" src="https://github.com/user-attachments/assets/8b095d83-22cd-4f98-9c61-e74e972ede05" />

<img width="2276" height="1599" alt="Image" src="https://github.com/user-attachments/assets/5729d528-ded7-44cd-a236-9927c3b6206a" />

새 Actor 블루프린트 생성 (BP_InteractableDoor와 BP_PickupItem)

Static Mesh 추가 (문 / 아이템 등으로 보이게 설정)

생성한 BP_InteractableDoor/BP_PickupItem 에디터에서

Components 탭의 Static Mesh 선택

Collision Presets → BlockAll 설정

Line Trace가 오브젝트를 정확히 감지합니다.

<img width="1691" height="893" alt="Image" src="https://github.com/user-attachments/assets/78012659-9329-4a50-a7c1-12c505c34e5f" />

MyCharacter 블루프린트에 Line Trace by Channel 노드 추가

E 키 입력 → Line Trace → Hit된 오브젝트 태그 확인 → 이벤트 실행

<img width="1667" height="995" alt="Image" src="https://github.com/user-attachments/assets/d7996a6c-783b-448d-b5a5-6f8caa2f9cc5" />

문이면: Timeline으로 Location값 이동

<img width="1647" height="1072" alt="Image" src="https://github.com/user-attachments/assets/4b522465-fd1f-474e-b463-3fb21e53c10b" />

아이템이면: Destroy Actor로 사라지게 처리

<img width="2513" height="1545" alt="Image" src="https://github.com/user-attachments/assets/7f13c696-656f-4236-a30e-edaa2fd12eb1" />

<img width="2536" height="1446" alt="Image" src="https://github.com/user-attachments/assets/fe06a553-061e-414c-bec9-1448784bfe00" />

<img width="2537" height="1444" alt="Image" src="https://github.com/user-attachments/assets/3e1452f4-b7df-49a7-9bb3-462a1aaa724a" />

상호작용 대상 블루프린트에 Tag: Interactable 설정

https://youtu.be/FTXvtOonzyM

게임에서 캐릭터가 E 키를 눌러 상호작용 되는지 테스트

## 3. 느낀 점 & 개선하고 싶은 점 

여닫이를 쓸 때 타임라인을 썼는데 잘못된 위치에 코딩해서인지 문이 2개 이상 있을 때 

이미 열린 문이 있으면 다른 문이 타임라인을 무시하고 바로 열리는 버그가 있긴 하다. 

그걸 개선하고 트레이싱 되는 물체의 윤곽선을 뚜렷하게 하는 기능을 넣고 싶다.

# 🎮 [Day6 Mini Project] - 나만의 이사

## 1. 주제 소개

- 일본풍의 나만의 방에서 물건 상자를 정리하는 것이 목표

- 캐릭터가 문과 상호작용해서 다른 구역으로 넘어가는 것이 가능

## 2. 구현 기능

- 캐릭터 이동 + 회전
- `E` 키를 누르면 문이 열리는 상호작용 구현
- `E` 키를 누르면 오브젝트가 사라지는 상호작용 구현

## 3. 결과물
- 🎥 영상
- https://youtu.be/QPmOjhdpyrs
- 🖼️ 스크린샷 Top View
- 
<img width="1265" height="988" alt="Image" src="https://github.com/user-attachments/assets/842e6741-8c7d-40bc-b849-3df28d30ea8c" />

<img width="2537" height="1418" alt="Image" src="https://github.com/user-attachments/assets/4e0f0334-94c2-452f-b6bb-0cd209f8ae73" />

## 4. 소감
- 실제로 물건 치우는 게임 같은 걸 만들어내서 재미있었습니다. 그리고 미닫이문 만드는 게 고려할 게 많아서 오랜만에 새로운 걸 배웠다는 느낌이 좋았습니다.
