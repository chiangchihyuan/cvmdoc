---
sidebar_position: 3
title: 行為洞察
---

# 行為洞察

| 業務代碼 | 欄位名稱                    | 欄位說明                                  | MView / View | 備註 |
|------|-------------------------|---------------------------------------|--------------|----|
| CC   | CC_RECACCTNO            | 最近一張往來信用卡(信用卡卡號)                      |              |    |
| CC   | CC_RECISSUE_DT          | 最近一張信用卡發卡日                            |              |    |
| CC   | CC_RECBUY_DT            | 最近一次信用卡消費日                            |              |    |
| CC   | CC_FIRSTBUY_DT          | 第一次信用卡消費日                             |              |    |
| CC   | CC_TXNREC1M_AMT         | 近一期本行簽帳金額                             |              |    |
| CC   | CC_TXNREC6M_AMT         | 近半年期本行簽帳金額                            |              |    |
| CC   | CC_TXNREC1Y_AMT         | 近一年期本行簽帳金額                            |              |    |
| CC   | CC_EAPPLY_IND           | 是否曾線上辦卡                               |              |    |
| CC   | CC_APPLY1M_IND          | 近一個月有辦卡                               |              |    |
| CC   | CC_EACCT_IND            | 信用卡帳單e化註記                             |              |    |
| CC   | CC_BILLAUTOACCT_IND     | 是否有辦信用卡帳單自動扣繳                         |              |    |
| CC   | CC_PERMLIMIT            | 本行信用卡額度_上月                            |              |    |
| CC   | CC_OUCARD_IND           | OU點點卡註記                               |              |    |
| CC   | CC_UNIVERSECARD_IND     | 寰宇現金回饋卡註記                             |              |    |
| DD   | DD_MD                   | 數位存款帳戶註記(台幣)                          |              |    |
| DD   | DD_MY                   | 數位存款帳戶註記(外幣)                          |              |    |
| FD   | FD_CPA                  | 最近一筆台幣定存金額                            |              |    |
| FD   | FD_START                | 最近一筆台幣定存起始日                           |              |    |
| FD   | FD_END                  | 最近一筆台幣定存到期日                           |              |    |
| FX   | FX_WEBTXN_BUYCNT        | 近一個月有網銀買外幣次數                          |              |    |
| FX   | FX_WEBTXN_BUYTWDAMT     | 近一個月有買外幣金額                            |              |    |
| FX   | FX_WEBTXN_SELLCNT       | 近一個月有網銀賣外幣次數                          |              |    |
| FX   | FX_WEBTXN_SELLTWDAMT    | 近一個月有網銀賣外幣金額                          |              |    |
| FX   | FX_APPTXN_BUYCNT        | 近一個月有行銀買外幣金額                          |              |    |
| FX   | FX_APPTXN_BUYTWDAMT     | 近一個月有行銀買外幣金額                          |              |    |
| FX   | FX_APPTXN_SELLCNT       | 近一個月有行銀賣外幣次數                          |              |    |
| FX   | FX_APPTXN_SELLTWDAMT    | 近一個月有行銀賣外幣金額                          |              |    |
| FX   | FX_BRANCHTXN_BUYCNT     | 近一個月有臨櫃買外幣次數                          |              |    |
| FX   | FX_BRANCHTXN_BUYTWDAMT  | 近一個月有臨櫃買外幣金額                          |              |    |
| FX   | FX_BRANCHTXN_SELLCNT    | 近一個月有臨櫃賣外幣次數                          |              |    |
| FX   | FX_BRANCHTXN_SELLTWDAMT | 近一個月有臨櫃賣外幣金額                          |              |    |
| FX   | FX_WITHDRAW_CNT         | 近一個月有提領現鈔次數                           |              |    |
| FX   | FX_WITHDRAW_TWDAMT      | 近一個月有提領現鈔金額                           |              |    |
| FX   | FX_DEPOSIT_CNT          | 近一個月有現鈔存入次數                           |              |    |
| FX   | FX_DEPOSIT_TWDAMT       | 近一個月有現鈔存入金額                           |              |    |
| FX   | FX_TRANS_BUYDT          | 最近一筆結構外幣時間                            |              |    |
| FX   | FX_CHANNEL_BUYNAME      | 最近一筆結構外幣對應之通路                         |              |    |
| FX   | FX_CURRENCY_BUYCODE     | 最近一筆結構外幣對應之幣別                         |              |    |
| FX   | FX_CURRENCY_BUYAMT      | 最近一筆結構外幣對應之折台金額                       |              |    |
| FX   | FX_TRANS_SELLDT         | 最近一筆結售外幣時間                            |              |    |
| FX   | FX_CHANNEL_SELLNAME     | 最近一筆結售外幣對應之通路                         |              |    |
| FX   | FX_CURRENCY_SELLCODE    | 最近一筆結售外幣對應之幣別                         |              |    |
| FX   | FX_CURRENCY_SELLAMT     | 最近一筆結售外幣對應之折台金額                       |              |    |
| FY   | FY_CUR                  | 最近一筆外幣定存商品(幣別)                        |              |    |
| FY   | FY_CPA                  | 最近一筆外幣定存金額(換算台幣)                      |              |    |
| FY   | FY_START                | 最近一筆外幣定存起始日                           |              |    |
| FY   | FY_END                  | 最近一筆外幣定存到期日                           |              |    |
| INS  | INS_NAME                | 最近一個保險往來商品(商品名稱)                      |              |    |
| INS  | INS_RECENT_DT           | 最近一個保險商品往來日                           |              |    |
| LN   | LN_HU_DT                | 最近一筆房貸往來日                             |              |    |
| LN   | LN_HU_AMT               | 最近一筆房貸往來金額                            |              |    |
| LN   | LN_HU_RATE              | 最近一筆房貸往來利率                            |              |    |
| LN   | LN_UN_DT                | 最近一筆信貸往來日                             |              |    |
| LN   | LN_UN_AMT               | 最近一筆信貸往來金額                            |              |    |
| LN   | LN_UN_RATE              | 最近一筆信貸往來利率                            |              |    |
| LN   | LN_CAR_DT               | 最近一筆車貸往來日                             |              |    |
| LN   | LN_CAR_AMT              | 最近一筆車貸往來金額                            |              |    |
| LN   | LN_CAR_RATE             | 最近一筆車貸往來利率                            |              |    |
| LN   | LN_SUBHU_DT             | 最近一筆副擔保往來日                            |              |    |
| LN   | LN_SUBHU_AMT            | 最近一筆副擔保往來金額                           |              |    |
| LN   | LN_SUBHU_RATE           | 最近一筆副擔保往來利率                           |              |    |
| LN   | LN_SB_DT                | 最近一筆SB往來日                             |              |    |
| LN   | LN_SB_AMT               | 最近一筆SB往來金額                            |              |    |
| LN   | LN_SB_RATE              | 最近一筆SB往來利率                            |              |    |
| LN   | LN_TOLUPL_AMT           | 行內無擔保總餘額                              |              |    |
| LN   | LN_TOLPL_AMT            | 行內有擔保總餘額                              |              |    |
| MD   | MD_LASTSTART            | 最近台幣帳戶開戶日                             |              |    |
| MY   | MY_LASTSTART            | 最近外幣帳戶開戶日                             |              |    |
| WM   | WM_GDSTART_DT           | 黃金存摺帳戶開戶日                             |              |    |
| WM   | WM_GD_TWDAMT            | 目前黃金存摺餘額(折合台幣)                        |              |    |
| WM   | WM_OUTDOORBO_TWDAMT     | 目前海外債餘額(折合台幣)                         |              |    |
| WM   | WM_ETF_TWDAMT           | 目前海外股票/ETF餘額(折合台幣)                    |              |    |
| WM   | WM_SN_TWDAMT            | 目前SN餘額(折合台幣)                          |              |    |
| WM   | WM_INS_TWDAMT           | 目前保險餘額(折合台幣)                          |              |    |
| WM   | WM_LASTGDTXN_AMT        | 最近一日黃金存摺交易總金額交易包含:買/賣、提領現貨、轉帳、定期定額扣款" |              |    |
| WM   | WM_LASTGDTXN_DT         | 最近一筆黃金存摺交易日期交易包含:買/賣、提領現貨、轉帳、定期定額扣款   |              |    |
| WM   | WM_PRODNAME             | 最近一個基金往來商品(商品名稱)                      |              |    |
| WM   | WM_TXN_DT               | 最近一個基金往來日                             |              |    |
| WM   | WM_                     | 最近一個基金金額                              |              |    |
| WM   | WM_LASTOUTDOORBO_NAME   | 最近一個海外債商品名稱                           |              |    |
| WM   | WM_LASTOUTDOORBO_TWDAMT | 最近一個海外債商品金額                           |              |    |
| WM   | WM_LASTOUTDOORBO_DT     | 最近一個海外債商品往來日                          |              |    |
| WM   | WM_LASTETF_NAME         | 最近一個ETF商品名稱                           |              |    |
| WM   | WM_LASTETF_DT           | 最近一個ETF商品往來日                          |              |    |
| WM   | WM_LASTETF_TWDAMT       | 最近一個ETF商品金額                           |              |    |
| WM   | WM_LASTSN_NAME          | 最近一個SN名稱                              |              |    |
| WM   | WM_LASTSN_DT            | 最近一個SN往來日                             |              |    |
| WM   | WM_LASTSN_TWDAMT        | 最近一個SN金額                              |              |    |
| WM   | WM_LASTPSTOCK_NAME      | 最近一個優先股名稱                             |              |    |
| WM   | WM_LASTPSTOCK_DT        | 最近一個優先股往來日                            |              |    |
| WM   | WM_LASTPSTOCK_TWDAMT    | 最近一個優先股金額                             |              |    |
| WM   | WM_FBUY_TIMES           | 近一年基金新申購筆數(首扣)                        |              |    |
| WM   | WM_FBUY_TWDAMT          | 近一年基金新申購金額(首扣)                        |              |    |
| WM   | WM_FBUYFEE_TWD          | 近一年基金新申購手收(首扣)                        |              |    |
| WM   | WM_FDBUY_TIMES          | 近一年線上基金新申購筆數(首扣)                      |              |    |
| WM   | WM_FDBUY_TWDAMT         | 近一年線上基金新申購金額(首扣)                      |              |    |
| WM   | WM_FDBUYFEE_TWDAMT      | 近一年線上基金新申購手收(首扣)                      |              |    |
| WM   | WM_ABUY_TIMES           | 近一年基金新申購筆數(續扣)                        |              |    |
| WM   | WM_ABUY_TWDAMT          | 近一年基金新申購金額(續扣)                        |              |    |
| WM   | WM_ABUYFEE_TWD          | 近一年基金新申購手收(續扣)                        |              |    |
| WM   | WM_ADBUY_TIMES          | 近一年線上基金新申購筆數(續扣)                      |              |    |
| WM   | WM_ADBUY_TWDAMT         | 近一年線上基金新申購金額(續扣)                      |              |    |
| WM   | WM_ADBUYFEE_TWD         | 近一年線上基金新申購手收(續扣)                      |              |    |
| WM   | WM_TRAN_TIMES           | 近一年基金轉換筆數                             |              |    |
| WM   | WM_TRAN_TWDAMT          | 近一年基金轉換金額                             |              |    |
| WM   | WM_TRANFEE_TWD          | 近一年基金轉換手收                             |              |    |
| WM   | WM_DTRAN_TIMES          | 近一年線上基金轉換筆數                           |              |    |
| WM   | WM_DTRAN_TWDAMT         | 近一年線上基金轉換金額                           |              |    |
| WM   | WM_DTRANFEE_TWD         | 近一年線上基金轉換手收                           |              |    |
|      | PROD_NUM                | 目前產品往來數(台幣、外幣、基金、保險、房貸、信貸、信用卡)        |              |    |
|      | GOV_AUTO_IND            | 是否辦理公共事業費代扣繳_上月                       |              |    |


### 剛買房
### 有房人士 
### 剛買車
### 有車人士
### (機車、汽車)
### 早起人士
### 夜貓子
### 旅遊達人
### 經常登入行網銀
### 新婚
### 剛裝潢 
### 懷孕或剛生子
### 家中小孩幼齡
### 家中小孩求學階段
### 大眾運輸通勤
### 騎車通勤族
### 開車通勤族
### 叫車平台族
### 叫外送族
### 自煮人士
### 便利商店常客
### 網購族
### 減重健身族
### 保養狂熱族
### 精品一哥一姊
### 運動達人
### 文青人士
### 追劇人士
### 電玩愛好者
### 寵物奴
### 哈日族
### 哈韓族
### 愛車如命
### 3C科技愛好
### 吃飯不手軟
### 自我進修
### 關注匯市
### 外匯意圖
### 理財意圖
### 貸款意圖
### 保險意圖
### 辦卡意圖
### 開戶意圖
### 理財生活家
### 理財大戶