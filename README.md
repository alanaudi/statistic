- [Date: 20201222](#orgb260106)
- [Type: Homework](#orgbf41435)
- [Department: 東吳經濟](#orgd37f663)
- [Language: \`python\`](#org28a24ea)
- [Task: Complete homework](#orgd4d8574)
- [Data Source:  [yahoo finance](https://finance.yahoo.com)](#org5623ee6)
- [Cost: 800 NTD](#orgf814304)
- [Due](#orgb2a9478)
  - [20201229](#org04a0f7b)
  - [20210105](#orgdf2f702)
- [Reference](#orgacb0caf)
  - [[[Week14][1] 計量回歸分析 理論介紹](https://youtube.com/watch?v=RIMZ88AZ71U)](#orgd5be579)
  - [[[Week14][2] 計量回歸分析 散布圖](https://youtube.com/watch?v=DvZCWhjjNH4)](#org6bc3c11)
  - [[[Week14][3] 計量回歸分析 回歸視覺化](https://youtube.com/watch?v=Twya4tff_jE)](#org759df6b)
  - [[[Week14][4] 計量回歸分析 估計結果判讀](https://youtube.com/watch?v=pojC36DrzcU)](#org4ffa75c)
  - [[[Week14][5] 計量回歸分析 估計結果再判讀](https://youtube.com/watch?v=dEEM-adfeG0)](#org1523a14)
  - [VIX指數 (Volatility Index) 又稱波動指數， 是由 CBOE(芝加哥選擇權交易所) 在1993年推出，為指數選擇權隱含波動率加權平均後所得之指數](#orgeceba24)
- [HW1](#org72e4212)



<a id="orgb260106"></a>

# Date: 20201222


<a id="orgbf41435"></a>

# Type: Homework


<a id="orgd37f663"></a>

# Department: 東吳經濟


<a id="org28a24ea"></a>

# Language: \`python\`


<a id="orgd4d8574"></a>

# Task: Complete homework


<a id="org5623ee6"></a>

# Data Source:  [yahoo finance](https://finance.yahoo.com)


<a id="orgf814304"></a>

# Cost: 800 NTD


<a id="orgb2a9478"></a>

# Due


<a id="org04a0f7b"></a>

## TODO 20201229


<a id="orgdf2f702"></a>

## TODO 20210105


<a id="orgacb0caf"></a>

# Reference


<a id="orgd5be579"></a>

## [[Week14][1] 計量回歸分析 理論介紹](https://youtube.com/watch?v=RIMZ88AZ71U)


<a id="org6bc3c11"></a>

## [[Week14][2] 計量回歸分析 散布圖](https://youtube.com/watch?v=DvZCWhjjNH4)


<a id="org759df6b"></a>

## [[Week14][3] 計量回歸分析 回歸視覺化](https://youtube.com/watch?v=Twya4tff_jE)


<a id="org4ffa75c"></a>

## [[Week14][4] 計量回歸分析 估計結果判讀](https://youtube.com/watch?v=pojC36DrzcU)


<a id="org1523a14"></a>

## [[Week14][5] 計量回歸分析 估計結果再判讀](https://youtube.com/watch?v=dEEM-adfeG0)


<a id="orgeceba24"></a>

## VIX指數 (Volatility Index) 又稱波動指數， 是由 CBOE(芝加哥選擇權交易所) 在1993年推出，為指數選擇權隱含波動率加權平均後所得之指數


<a id="org72e4212"></a>

# DONE HW1

根據 [yahoo finance](https://finance.yahoo.com) 網站資料，我們考慮樣本期間 ****2019/01/01 - 2020/11/30**** 討論 COVID-19 期間。根據 HW8 的結果，我們得到美國與台灣股市報酬率與其匯率報酬率之間的關係， 現在我們單純考慮股票市場，題目如下：

1.  請試著對 ****波動率指數 (Volatility Index，VIX)**** 變化量 與 ****S&P500 指數日報酬率**** 做出敘述統計。
    -   平均數、標準差、偏態、峰態
    -   根據上述結果，討論此兩變數是否符合常態分佈
    -   相關係數，一階自相關係數
    -   根據上述結果，討論此兩變數的資料結構
2.  請試著做出以下分析得到VIX變化量與S&P500指數報酬率的關係為正相關、負相關、無相關。
    -   相關係數
    -   散布圖
    -   迴歸分析
3.  請試著做出以下分析得到S&P500指數股價報酬與移動平均(\`MA5\`與\`MA20\`)的關係為正相關、負相關、無相關。
    -   相關係數
    -   散布圖
    -   回歸分析
4.  請利用迴歸分析結果，討論移動平均和VIX報酬率對於S&P500報酬的預測能力。
