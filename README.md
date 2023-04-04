# CyberpunkGame.dev

## 사이버 펑크 게임개발일지


### 1주차 (목표)
* 플레이어 이동, 공격, 기본 UI 구현
* 무한 스크롤 배경 구현

[23.03.14 (플레이어 이동, 공격 구현)](https://github.com/seungdo1234/CyberpunkGame.dev/blob/main/23.03.14%20~%2023.03.20%20(1%EC%A3%BC%EC%B0%A8)/23.03.14%20(%ED%94%8C%EB%A0%88%EC%9D%B4%EC%96%B4%20%EC%9D%B4%EB%8F%99%2C%20%EA%B3%B5%EA%B2%A9%20%EA%B5%AC%ED%98%84).md)  <br/>
[23.03.15 (무한 스크롤 배경 구현)](https://github.com/seungdo1234/TIL/blob/main/23.03.14%20~%2023.03.20%20(1%EC%A3%BC%EC%B0%A8)/23.03.15%20(%EB%AC%B4%ED%95%9C%20%EC%8A%A4%ED%81%AC%EB%A1%A4%20%EB%B0%B0%EA%B2%BD%20%EA%B5%AC%ED%98%84).md)
<br/>
[23.03.16 (콤보 어택 구현, 히팅 박스 수정)](https://github.com/seungdo1234/TIL/blob/main/23.03.14%20~%2023.03.20%20(1%EC%A3%BC%EC%B0%A8)/23.03.16%20(%EC%BD%A4%EB%B3%B4%EC%96%B4%ED%83%9D%20%EA%B5%AC%ED%98%84%2C%20%ED%9E%88%ED%8C%85%EB%B0%95%EC%8A%A4%20%EC%88%98%EC%A0%95).md) <br/>
[23.03.17 (수리검 투척 스킬 구현)](https://github.com/seungdo1234/TIL/blob/main/23.03.14%20~%2023.03.20%20(1%EC%A3%BC%EC%B0%A8)/23.03.17%20(%EC%88%98%EB%A6%AC%EA%B2%80%20%ED%88%AC%EC%B2%99%20%EA%B5%AC%ED%98%84).md) <br/>
[23.03.20 (Enemy 이동 구현)](https://github.com/seungdo1234/TIL/blob/main/23.03.14%20~%2023.03.20%20(1%EC%A3%BC%EC%B0%A8)/23.03.20%20(Enemy%20%EC%9D%B4%EB%8F%99%20%EA%B5%AC%ED%98%84).md) <br/>

#### 구현
* 플레이어 이동, 기본 공격, 나이프 던지기
* 배경 무한 스크롤
* Enemy 이동
#### 피드백
* 컴포넌트에 대한 개념이 확실히 잡혀있지 않아 nullreferenceexception 오류가 많이 뜸


### 2주차 (목표)
* 플레이어 스페셜 어택 구현
* 기본 UI (플레이어, Enemy) 구현
  * ex) 체력바, 스킬 아이콘, 데미지 이펙트 등등


[23.03.21 (나이프 플립, SpawnPoint 수정)](https://github.com/seungdo1234/TIL/blob/main/23.03.21%20~%2023.03.27%20(2%EC%A3%BC%EC%B0%A8)/23.03.21%20(%ED%94%8C%EB%A0%88%EC%9D%B4%EC%96%B4%20%EC%8A%A4%ED%8E%98%EC%85%9C%20%EC%96%B4%ED%83%9D%20%EA%B5%AC%ED%98%84).md) <br/>
[23.03.22 (스페셜 어택 모션 , 콤보 공격 로직 수정)](https://github.com/seungdo1234/CyberpunkGame.dev/blob/main/23.03.21%20~%2023.03.27%20(2%EC%A3%BC%EC%B0%A8)/23.03.22%20(%EC%BD%A4%EB%B3%B4%20%EA%B3%B5%EA%B2%A9%20%EB%A1%9C%EC%A7%81%20%EC%88%98%EC%A0%95%2C%20%EC%8A%A4%ED%8E%98%EC%85%9C%20%EC%96%B4%ED%83%9D%20%EB%AA%A8%EC%85%98%20%EA%B5%AC%ED%98%84).md) <br/>
[23.03.23 (점프 버그 수정)](https://github.com/seungdo1234/CyberpunkGame.dev/blob/main/23.03.21%20~%2023.03.27%20(2%EC%A3%BC%EC%B0%A8)/23.03.23%20(%EC%A0%90%ED%94%84%20%EB%B2%84%EA%B7%B8%20%EC%88%98%EC%A0%95).md) <br/>
[23.03.24 (Enemy 피격 로직 수정, 스페셜 어택 데미지 구현)](https://github.com/seungdo1234/CyberpunkGame.dev/blob/main/23.03.21%20~%2023.03.27%20(2%EC%A3%BC%EC%B0%A8)/23.03.24%20(Enemy%20%ED%94%BC%EA%B2%A9%20%EB%A1%9C%EC%A7%81%20%EC%88%98%EC%A0%95,%20%EC%8A%A4%ED%8E%98%EC%85%9C%20%EC%96%B4%ED%83%9D%20%EB%8D%B0%EB%AF%B8%EC%A7%80%20%EA%B5%AC%ED%98%84).md) <br/>
[23.03.27 (Player HP바 구현)](https://github.com/seungdo1234/CyberpunkGame.dev/blob/main/23.03.21%20~%2023.03.27%20(2%EC%A3%BC%EC%B0%A8)/23.03.27%20(Player%20HP%EB%B0%94%20%EA%B5%AC%ED%98%84).md) <br/>
#### 구현
* 스페셜 어택
* Player HP UI  
* 버그가 잠재돼있던 로직 수정


### 3주차 (목표)
* 플레이어 점프 어택 구현
* 플레이어 기본 공격 시 움직임 구현

[23.04.02 (플레이어 점프 어택 구현)](https://github.com/seungdo1234/CyberpunkGame.dev/blob/main/23.03.25%20~%2023.04.03%20(3%EC%A3%BC%EC%B0%A8)/23.04.02%20(%ED%94%8C%EB%A0%88%EC%9D%B4%EC%96%B4%20%EC%A0%90%ED%94%84%20%EA%B3%B5%EA%B2%A9%20%EA%B5%AC%ED%98%84).md) <br/>
