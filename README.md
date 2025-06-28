# <div align="center"> ROR-Simulation-based-on-Asset-Ratio </div>
### <div align="center"> 2-1 Probability Statistics - Finale PR </div>
### <div align="center"> 자산유형별 비율에 따른 <br> 몬테카를로 시뮬레이션 기반 수익률 분석 </div>
---
> #### *[PR env](https://drive.google.com/drive/folders/1-ziNXdecsTjw-T17IKImwwwJrNrxXHDi)* - 프로젝트 구글 드라이브 링크 <br> *[Docs](https://www.notion.so/_-1f9cd6ef7d31808fa92be5e23ad3c264)* - 프로젝트 설명 노션 독스 <br> *[PPT](https://docs.google.com/presentation/d/1-qup7TXIC3zu4KL89WLc8fOdLdAALM0j/edit?usp=drive_link&ouid=112894487230611332678&rtpof=true&sd=true)* - 발표 자료
---
## 🧪 Experiment Result

#### – 자산량에 따른 수익률 차이 有. 

<img src='https://github.com/slowerthan5cmpersec/ROR-Simulation-based-on-Asset-Ratio/blob/main/src/asset135.png'> </img>
- 자산 분위 높아질수록 수익률 높아지는 추세 확인함. 
- 이는 구매 가능한 <u>자산의 다양성 차이</u>로 인한 결과로 해석 가능하였음. 

<img src='https://github.com/slowerthan5cmpersec/ROR-Simulation-based-on-Asset-Ratio/blob/main/src/rowdif.png'> </img>

- 1 iteration 시 자산 매도관리표 6년간의 총 매매 행 수 차이. 


---
#### – 존버는 실패한다

<img src='https://github.com/slowerthan5cmpersec/ROR-Simulation-based-on-Asset-Ratio/blob/main/src/zoneburr.png'></img>

- 실험 기간은 `2019-01-01` - `2024-12-31` 로 설정하였음. 
- 존버는 `sell` 을 구현만 하고 아무것도 안넣어서 개발함. 
- `2024-12-31`은 고금리 맞을 대로 다 맞고 난 이후, 이 전부터 계속 자산을 처분했다면 웬만해서는 더 이익을 보았을 가능성 多. 이 기조가 반영된 결과로 해석. 
- `2019-01-01` - `2022-12-31`로 설정 시 유의미한 결과는 아니지만 둘이 서로 비슷한 결과 획득 가능하였음. 

---
#### – Infographs
<img src='https://github.com/slowerthan5cmpersec/ROR-Simulation-based-on-Asset-Ratio/blob/main/src/1.png'></img>
<img src='https://github.com/slowerthan5cmpersec/ROR-Simulation-based-on-Asset-Ratio/blob/main/src/2.png'></img>
<img src='https://github.com/slowerthan5cmpersec/ROR-Simulation-based-on-Asset-Ratio/blob/main/src/3.png'></img>
<img src='https://github.com/slowerthan5cmpersec/ROR-Simulation-based-on-Asset-Ratio/blob/main/src/4.png'></img>
<img src='https://github.com/slowerthan5cmpersec/ROR-Simulation-based-on-Asset-Ratio/blob/main/src/5.png'></img>

---
#### – [실제 결과](https://docs.google.com/spreadsheets/d/111HeX0oTfrZ7gNsAuyOJnrfOcrZsutrzbhpTUQqtE_A/edit?gid=0#gid=0)

## ↔️ final state dif
- 주가 데이터 전부 삭제. 
- 기존 구글 스프레드시트 링크 전부 삭제. 
- 실험 결과 전부 삭제. 
- 이 외 

위 사항들 다시 충족시키면서 진행하면 재실험가능. 

## 💭 회고
#### 협업 - 실패
- 독스 작성에 평소보다 많은 시간 할애, 독스트링도 모든 객체에 작성해보았지만 부족...
- 오히려 정보가 너무 많았나를 고민해보아야.
- 회의를 늘리는 방식도 고려해야. 나라는 인간의 접근성은 높은가 고민. 
- 시험기간 긍정긍정 유지 실패. 힘들어도 긍정긍정 하자!!! 
- 열심히하는 친구들만 열심히 하고 안하는 사람은 끝까지 안함. 난이게싫다고

#### 새로 배운거 - 만족
#### `import_ipynb`
- 코랩 작업환경은 경험 多지만 코랩에서 <u>ipynb로 객체지향</u> 해본거는 처음. 
- `import_ipynb` 모듈 활용. 다만 import한 ipynb 내 객체에서 에러 시 로그 출력이 안됨...
- 머 나중에 더 개선되겠지

#### `yfinance` 
- 주식 데이터 받는 모듈. 그냥 막 쓰면 될듯. 


#### `pandas`+`Google Workspace`
- 온라인의 구글 스프레드시트를 판다스로 접근 가능
- 공동 작업할 때 사기적
- 데이터 관리도 매우 편리
- 단점: 데이터가 대량이라면 안쓰겠지... 대량 데이터는 csv로 다루고 관리용 시트는 이걸루할듯 ㄷㄷ うまい

#### 스퀴즈 모멘텀 - 지나간것은지나간대로~
- 왜 내가 자꾸 돈을 잃는지 깨달았다
- 응축 타이밍 놓치면 그냥 버려야
