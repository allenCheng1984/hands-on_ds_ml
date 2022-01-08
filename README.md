# Hands-On Data Science and Python Machine Learning 的筆記與程式練習

[範例程式原始碼](https://github.com/packtpublishing/hands-on-data-science-and-python-machine-learning)<br>
[原文書網址](https://www.packtpub.com/big-data-and-business-intelligence/data-science-and-machine-learning-python-hands)<br>
[中文書網址](https://www.books.com.tw/products/0010900123)

---

## 推薦理由

這本書只看觀念的說明、模型的介紹，絕對是5顆星的評價。<br>
在即將進入難懂的地方就適時的停住，帶入實作，<br>
能夠讓你迅速了解一個概念，並且不會讓你被艱難的原理卡住，<br>
非常有助於剛要進入 data science 的人學習這個領域的基礎知識，並為未來深入研究打下良好的地基。

這本書最棒的地方，所介紹的技術與知識都是基於在實際使用情境下做解說，<br>
並且分析好處、壞處、適用情境、限制，<br>
不懂原理沒關係，懂得怎麼去看待與使用它

雖然翻譯的部分有點不夠傳神, 範例程式碼混亂與一些工具已過時(畢竟原書是 2017 年出版)，<br>
但對於初學者來說是非常棒的入門書。

---

## 章節簡介

- Ch01: 基礎 & 實用 python 技巧
- Ch02: 基礎統計與基礎機率解說
- Ch03: Matplotlib 與高等機率概念
- Ch04: 迴歸模型的概念與應用
  - 用真實的汽車資訊來預測售價
- Ch05: 機器學習實作
  - 用單純貝式來實作簡易垃圾郵件分類氣
  - 用 K-Means 實作集群 (e.g. 交友配對, IMDb 電影資料)
- Ch06: 推薦系統從無到有建置
  - 用真實電影資訊製作一個陽春版的電影推薦系統
- Ch07: 更多資料探勘與機器學習技術
  - 用 KNN 預測電影評分
  - 使用 PCA(主成分分析) 做資料降維
  - 資料倉儲概念 => ETL & ELT
- Ch08: 處理真實世界的資料
  - 實作 Data Engineer 真實會遇到的工作案例
  - 各種資料預處理
- Ch09: Apache Spark
  - 實作幾個在本機端可運作的 Spark 機器學習模型，並能執行
- Ch10: 測試與實驗設計
  - A/B 測試
  - t 檢定 與 p 值
  - 各種檢驗模型結果的實戰經驗與方法


---

## Mac 安裝 Apache Spark 的步驟
ref: [Installing Apache Spark on Mac OS](https://medium.com/beeranddiapers/installing-apache-spark-on-mac-os-ce416007d79f), [Spark-mac-osx.md](https://gist.github.com/chairco/29a3fd4494e031ecdd5d5175d6df4f4a)

有 `homebrew` 直接幾行指令搞定 ... XD
- `brew upgrade && brew update` 更新 homebrew
- 安裝 java8
  - `brew tap adoptopenjdk/openjdk`
  - `brew install --cask adoptopenjdk8`
  - `java -version` 確認版本
- `xcode-select --install` 安裝 xcode-select
- `brew install scala` 安裝 Scala
- `brew install apache-spark` 安裝 Apache Spark
- (安裝完後) =>
  - `spark-shell` 進入 Spark 控制台測試是否正常運作
  - `:quit` 離開 Spark 控制台
