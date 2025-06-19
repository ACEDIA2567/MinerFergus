<div align="center">
<h1> MinerFergus </h1>
</div>

# 목차    
* [개요](#개요)
* [게임 설명](#게임-설명)
* [게임 플레이 방식](#게임-플레이-방식)

## 개요    
<div align="center">
<h3>MinerFegus</h3>

</div>

### ⚡ 빌드 파일
**● PC : 빌드 파일**  

### ⚙️ 개발 환경
- 언어 : `C#`
- IDE : `Visual Studio 2022`
- 엔진 : `Unity 2022.3.52f1`

### 🧑‍🤝‍🧑 팀 구성 및 역할
|역할|이름|GitHub|
|---|---|---|
|팀장|이재형|<a href="https://github.com/dudgus818" target="_blank">https://github.com/dudgus818</a>|
|팀원|이석천|<a href="https://github.com/rlarhdal" target="_blank">https://github.com/rlarhdal</a>|

### 🕐 개발 기간


## 게임 설명
### 게임 
* 장르: 2D, 시뮬레이션

|시작 화면|스테이지|
|---|---|
|<img src=https://github.com/user-attachments/assets/c55b6174-f4bf-4195-805d-5ed1c727a5ad width="500" height="300">|<img src=https://github.com/user-attachments/assets/f4354ed2-49ea-4118-b822-4413ea7681a4 width="500" height="300">|

* 📖 다양한 광물을 채광해보자
  새로운 

* 🎲 아이템을 제작
  적마다 공격 패턴을 가지고 있기 때문에 패턴을 확인하고 공략을 해나가야한다.

* 💜  
  마왕이 직접 사람들을 쓰러트리고 영혼을 수확하여 여러 장비를 구매 또는 강화를 하거나
  자신의 능력치를 상승 시킬 수 있습니다.

</br>

## 게임 플레이 방식
### 🎮 조작 방법
|이동|상호작용|
|---|---|
|<img src=https://github.com/user-attachments/assets/972cc722-1793-41e8-97e3-c50493144b01 width="500" height="300">|<img src=https://github.com/user-attachments/assets/6bebfd7c-9389-4dd9-9192-0b5380299ef6 width="500" height="300">|
* WASD키를 입력하여 이동을 할 수 있다.
* 상호작용 가능한 오브젝트에 가까워지면 F키 입력를 입력하여 상호작용이 가능하다.


### 컨텐츠
|채광|퀘스트|
|---|---|
|<img src=https://github.com/user-attachments/assets/e47974b5-59cf-4e23-8e80-3207557df5fb width="500" height="300">|
* 채광: 광산에 입장하여 광물을 채광할 수 있습니다.
* 퀘스트: NPC로부터 다양한 아이템을 전달하는 퀘스트를 받을 수 있습니다.

### 🧙‍♂ NPC 소개
|길드 NPC|잡화점 NPC|
|---|---|
|||
* 길드 NPC: 플레이어가 스토리를 진행하기 위한 퀘스트를 내주는 역할을 가진다.
* 잡화점 NPC: 플레이어가 획득, 제작한 아이템을 판매하게 해주는 역할을 가진다.

### 🔨 작업 활동
|주조|제작|강화|
|---|---|---|
|<img src=https://github.com/user-attachments/assets/d8364d91-2cc0-4624-bfff-37bb306db90d width="500" height="300">|
* 주조: 플레이어가 채광한 광물을 녹여 주괴로 만드는 작업 
* 제작: 레시피에 따라서 아이템을 이용하여 새로운 아이템을 만드는 작업
* 강화: 장비를 성능이 높은 장비로 업그레이드 해주는 작업

### 💖 플레이어
|정보창||
|---|
||
* 

### 🎯 클리어 조건
|클리어|
|---|
|<img src=https://github.com/user-attachments/assets/27be574d-3a31-490f-9681-1c7112fd7029 width="500" height="200">|
* 현재 기획 단계에서 메인 퀘스트를 구현하지 않아 테스트용으로 목표 아이템을 제출하는 형식으로 나타냄


### 📑 맵
|대장간|
|---|
||

|대장간|
|---|
||

|잡화점|
|---|
||
* 맵마다 적들이 생성이 되고 적을 모두 처치해야 다음 맵으로 향하는 벽이 사라지게 됩니다.
* 맵의 끝에는 보스맵이 존재하며 보스맵 입장시 보스가 등장하게 됩니다.

</br>


<details>
  <summary>스크립트 트리</summary>
  
📦Scripts    
 ┣ 📂0_Util ▶ 유틸     
 ┃ ┣ 📜AudioClips.cs    
 ┃ ┣ 📜Define.cs    
 ┃ ┣ 📜Extension.cs    
 ┃ ┣ 📜Interfaces.cs    
 ┃ ┣ 📜SceneChanger.cs    
 ┃ ┣ 📜UIBase.cs    
 ┃ ┗ 📜Util.cs    
 ┣ 📂1_Managers ▶ 게임 관리    
 ┃ ┣ 📜CameraManager.cs    
 ┃ ┣ 📜DataManager.cs    
 ┃ ┣ 📜GameManager.cs    
 ┃ ┣ 📜GuideArrow.cs    
 ┃ ┣ 📜ItemManager.cs    
 ┃ ┣ 📜LoadingManager.cs    
 ┃ ┣ 📜LoadSceneManager.cs    
 ┃ ┣ 📜Managers.cs    
 ┃ ┣ 📜PlayerData.cs    
 ┃ ┣ 📜Poolable.cs    
 ┃ ┣ 📜PoolManager.cs    
 ┃ ┣ 📜ReadSpreadSheet.cs    
 ┃ ┣ 📜ResourceManager.cs    
 ┃ ┣ 📜SoundManager.cs    
 ┃ ┣ 📜UIInputManager.cs    
 ┃ ┗ 📜UIManager.cs    
 ┣ 📂2_Scene ▶ 씬의 실행 세팅    
 ┃ ┣ 📜BaseScene.cs    
 ┃ ┣ 📜Battle.cs    
 ┃ ┣ 📜Maintenance.cs    
 ┃ ┣ 📜StartScene.cs    
 ┃ ┗ 📜Tutorial.cs    
 ┣ 📂3_Tutorial ▶ 튜토리얼 관련    
 ┃ ┣ 📜DialogSystem.cs    
 ┃ ┣ 📜TutorialBase.cs    
 ┃ ┣ 📜TutorialCamChange.cs    
 ┃ ┣ 📜TutorialController.cs    
 ┃ ┣ 📜TutorialDestroyTagObjects.cs    
 ┃ ┣ 📜TutorialDialog.cs    
 ┃ ┣ 📜TutorialEyeBlink.cs    
 ┃ ┣ 📜TutorialEyeOpen.cs    
 ┃ ┣ 📜TutorialFadeEffect.cs    
 ┃ ┣ 📜TutorialGenerateUI.cs    
 ┃ ┣ 📜TutorialMovement.cs    
 ┃ ┣ 📜TutorialNarration.cs    
 ┃ ┣ 📜TutorialTouchScreen.cs    
 ┃ ┣ 📜TutorialTrigger.cs    
 ┃ ┣ 📜TutorialUseSoul.cs    
 ┃ ┗ 📜UI_Player_Tutorial.cs    
 ┣ 📂4_MaintananceScene ▶ 정비씬    
 ┃ ┣ 📂Items ▶ 아이템 관련    
 ┃ ┃ ┣ 📜Item.cs    
 ┃ ┃ ┣ 📜ItemSkills.cs    
 ┃ ┃ ┗ 📜PotionSkill.cs    
 ┃ ┣ 📂NPC ▶ NPC 관련     
 ┃ ┃ ┣ 📜CharacterNPC.cs    
 ┃ ┃ ┣ 📜ForgeNPC.cs    
 ┃ ┃ ┣ 📜MapNPC.cs    
 ┃ ┃ ┣ 📜NPC.cs    
 ┃ ┃ ┣ 📜PotalExit.cs    
 ┃ ┃ ┗ 📜StoreNPC.cs    
 ┃ ┣ 📂Player ▶ 플레이어 관련    
 ┃ ┃ ┣ 📂Behaviours  ▶ 플레이어 행동        
 ┃ ┃ ┃ ┣ 📂Input ▶ 플레이어 입력 관련    
 ┃ ┃ ┃ ┃ ┣ 📜InputAttack.cs    
 ┃ ┃ ┃ ┃ ┣ 📜InputBase.cs    
 ┃ ┃ ┃ ┃ ┣ 📜InputInteract.cs    
 ┃ ┃ ┃ ┃ ┣ 📜InputMove.cs    
 ┃ ┃ ┃ ┃ ┣ 📜InputPotion.cs    
 ┃ ┃ ┃ ┃ ┣ 📜InputSkill.cs    
 ┃ ┃ ┃ ┃ ┗ 📜PlayerInputHandler.cs    
 ┃ ┃ ┃ ┣ 📂StageSkill ▶ 플레이어 스테이지 스킬    
 ┃ ┃ ┃ ┃ ┗ 📜StageSkill.cs    
 ┃ ┃ ┃ ┣ 📂State ▶ 플레이어의 상태머신     
 ┃ ┃ ┃ ┃ ┣ 📜PlayerStateHandler.cs    
 ┃ ┃ ┃ ┃ ┣ 📜StateAttack.cs    
 ┃ ┃ ┃ ┃ ┣ 📜StateBase.cs    
 ┃ ┃ ┃ ┃ ┣ 📜StateDie.cs    
 ┃ ┃ ┃ ┃ ┣ 📜StateHide.cs    
 ┃ ┃ ┃ ┃ ┣ 📜StateHit.cs    
 ┃ ┃ ┃ ┃ ┣ 📜StateIdle.cs    
 ┃ ┃ ┃ ┃ ┣ 📜StateInteract.cs    
 ┃ ┃ ┃ ┃ ┣ 📜StateMachine.cs    
 ┃ ┃ ┃ ┃ ┣ 📜StateMove.cs    
 ┃ ┃ ┃ ┃ ┗ 📜StateSkill.cs    
 ┃ ┃ ┃ ┣ 📜BehaviourAttack.cs    
 ┃ ┃ ┃ ┣ 📜BehaviourBase.cs    
 ┃ ┃ ┃ ┣ 📜BehaviourInteract.cs    
 ┃ ┃ ┃ ┣ 📜BehaviourMove.cs    
 ┃ ┃ ┃ ┣ 📜BehaviourPotion.cs    
 ┃ ┃ ┃ ┣ 📜BehaviourSkill.cs    
 ┃ ┃ ┣ 📜Player.cs    
 ┃ ┃ ┣ 📜PlayerAnimationEvents.cs    
 ┃ ┃ ┣ 📜PlayerInteraction.cs    
 ┃ ┃ ┣ 📜PlayerInventory.cs    
 ┃ ┃ ┗ 📜PlayerStatHandler.cs    
 ┣ 📂5_BattleScene    
 ┃ ┣ 📂Enemy ▶ 적 관련    
 ┃ ┃ ┣ 📂Boss ▶ 적(보스) 정보    
 ┃ ┃ ┃ ┣ 📜BossAnimator.cs    
 ┃ ┃ ┃ ┣ 📜BossEnemy.cs    
 ┃ ┃ ┃ ┣ 📜BossMovement.cs    
 ┃ ┃ ┃ ┗ 📜BossSkill.cs    
 ┃ ┃ ┣ 📂Citizen ▶ 적(시민) 정보     
 ┃ ┃ ┃ ┣ 📜CitizenAnimator.cs    
 ┃ ┃ ┃ ┣ 📜CitizenEnemy.cs    
 ┃ ┃ ┃ ┗ 📜CitizenMovement.cs    
 ┃ ┃ ┣ 📂EnemyAttack ▶ 적의 공격     
 ┃ ┃ ┃ ┣ 📜Explosion.cs    
 ┃ ┃ ┃ ┣ 📜LineAtoB.cs    
 ┃ ┃ ┃ ┣ 📜MeleeAttack.cs    
 ┃ ┃ ┃ ┣ 📜ProjectileController.cs    
 ┃ ┃ ┃ ┗ 📜ProjectilePool.cs    
 ┃ ┃ ┣ 📂Normal ▶ 적(일반) 정보    
 ┃ ┃ ┃ ┣ 📜MeleeEnemy.cs    
 ┃ ┃ ┃ ┣ 📜NormalEnemy.cs    
 ┃ ┃ ┃ ┣ 📜NormalEnemyMovement.cs    
 ┃ ┃ ┃ ┗ 📜RangedEnemy.cs    
 ┃ ┃ ┣ 📂Spawner ▶ 적의 스폰      
 ┃ ┃ ┃ ┣ 📜BossSpawner.cs    
 ┃ ┃ ┃ ┗ 📜EnemySpawner.cs    
 ┃ ┃ ┣ 📜Enemy.cs    
 ┃ ┃ ┣ 📜EnemyAnimator.cs    
 ┃ ┃ ┣ 📜EnemyStatus.cs    
 ┃ ┃ ┗ 📜Soul.cs    
 ┃ ┣ 📂Map ▶ 전투 맵 관련    
 ┃ ┃ ┣ 📜BossMap.cs    
 ┃ ┃ ┣ 📜CitizenPortal.cs    
 ┃ ┃ ┣ 📜EntrancePortal.cs    
 ┃ ┃ ┣ 📜Escape.cs    
 ┃ ┃ ┣ 📜MapGenerator.cs    
 ┃ ┃ ┣ 📜NavMeshBuild.cs    
 ┃ ┃ ┗ 📜NormalMapManager.cs    
 ┃ ┗ 📜DMGtxt.cs    
 ┣ 📂UI ▶ UI 관련    
 ┃ ┣ 📂Effect ▶ UI 효과    
 ┃ ┃ ┣ 📜ArrowBlink.cs    
 ┃ ┃ ┣ 📜EyeBlink.cs    
 ┃ ┃ ┣ 📜TypingEffect.cs    
 ┃ ┃ ┣ 📜UpdateColorAlpha.cs    
 ┃ ┃ ┗ 📜ZoomToUI.cs    
 ┃ ┣ 📂Item ▶ UI 아이템    
 ┃ ┃ ┣ 📜UI_CharacterForce_Item.cs    
 ┃ ┃ ┣ 📜UI_EquipmentForce_item.cs    
 ┃ ┃ ┗ 📜UI_Store_Item.cs    
 ┃ ┣ 📂Popup ▶ UI 활성화    
 ┃ ┃ ┣ 📜UI_BackToMain.cs    
 ┃ ┃ ┣ 📜UI_CharacterForce.cs    
 ┃ ┃ ┣ 📜UI_CharacterInfo.cs    
 ┃ ┃ ┣ 📜UI_EquipmentForce.cs    
 ┃ ┃ ┣ 📜UI_Exit.cs    
 ┃ ┃ ┣ 📜UI_Map.cs    
 ┃ ┃ ┣ 📜UI_MiniMap.cs    
 ┃ ┃ ┣ 📜UI_Options.cs    
 ┃ ┃ ┣ 📜UI_PopUp.cs    
 ┃ ┃ ┣ 📜UI_Respawn.cs    
 ┃ ┃ ┣ 📜UI_Result.cs    
 ┃ ┃ ┣ 📜UI_StageClear.cs    
 ┃ ┃ ┣ 📜UI_Store.cs    
 ┃ ┃ ┗ 📜UI_StoreBuy.cs    
 ┃ ┣ 📂Scene ▶ 씬마다 UI 설정    
 ┃ ┃ ┣ 📜UI_Battle.cs    
 ┃ ┃ ┣ 📜UI_Boss.cs    
 ┃ ┃ ┣ 📜UI_HUD.cs    
 ┃ ┃ ┣ 📜UI_Maintenance.cs    
 ┃ ┃ ┣ 📜UI_Player.cs    
 ┃ ┃ ┣ 📜UI_Scene.cs    
 ┃ ┃ ┣ 📜UI_Start.cs    
 ┃ ┃ ┣ 📜UI_Tutorial.cs    
 ┗ ┗ ┗ 📜ParallaxBackground.cs    
 
</details>
