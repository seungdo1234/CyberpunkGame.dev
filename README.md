# TIL
## 사이버 펑크 게임개발일지

### 23.03.14
플레이어 이동 및 공격 구현
* OverlapBoxAll를 활용하여 공격키를 눌렀을 때 파란색 박스에 충돌한 오브젝트의 태그가 Enemy일 경우 EnemyHP를 --하는 방식으로 만들었습니다. <br/>
* 코루틴을 활용하여 공격 딜레이 구현 <br/>
<img width ="80%" src="https://user-images.githubusercontent.com/86179438/225191867-1efc3fd6-63fd-4f35-ac1f-85939d8b8f97.mp4"/>
이동, 점프, 공격, 공격시 EnemyHP가 -1

<hr/>

### 23.03.15
무한 스크롤 배경 구현 <br/>
* 플레이어가 이동할 때 방향에 맞춰서 배경이 스크롤 됨
* MeshRenderer를 이용하여 Material의 offset를 변경하는 방법을 사용 <br/>

<img width ="80%" src="https://user-images.githubusercontent.com/86179438/225326408-24218789-f258-43b5-9bca-f7179001eb17.mp4"/><br/>
#### 피드백 <br/>
* 배경 오브젝트를 플레이어 스크립트에 넣지 않아 nullreferenceexception 발생 
