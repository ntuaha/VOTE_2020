# VOTE_2020
分析相關資料

確認資料驗證狀況 https://docs.google.com/spreadsheets/d/1NCyfHUvsYUatmse_q5SBm7P63INQlJca8cbPjluvvhM/edit?usp=sharing


### 資料

1. P1s.csv 總統得票狀況
2. L1s.csv 區域立委得票狀況
3. L2s.csv 平地原住民得票狀況
4. L3s.csv 山地原住民得票狀況
5. L4s.csv 不分區立委得票狀況
6. FP1.csv 總統投票狀況
7. S1.csv 區域立委投票狀況
8. S2.csv 平地原住民立委投票狀況
9. S3.csv 山地原住民立委投票狀況
10. S4.csv 不分區立委投票狀況


### 欄位說明 P & L
| names      | dtypes  |
|------------|---------|
| 註記       | object  |
| 號次       | int64   |
| 總統名字   | object  |
| 總統性別   | object  |
| 副總統名字 | object  |
| 副總統性別 | object  |
| 得票數     | int64   |
| 得票率%    | float64 |
| 登記方式   | object  |
| 行政區1    | object  |
| 行政區3    | object  |
| 行政區4    | object  |
| 連結       | objec   |


### 欄位說明 FP & S

| columns  | dtypes |
|----------|--------|
| 行政區3  | object |
| 投票率%  | float  |
| 選舉人數 | int64  |
| 投票數   | int64  |
| 有效票數 | int64  |
| 無效票數 | int64  |
| 行政區1  | object |
| 連結     | object |
| 行政區4  | object |