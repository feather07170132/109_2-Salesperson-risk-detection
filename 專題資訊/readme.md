# 109_2-Salesperson-risk-detection
* 南山人壽題目_第二組 【業務員風險偵測】
* Team Member : 林宇哲 張恩瑞 邱冠瑋 林雨蓁 王隆欣
* 指導教授:石百達、蔡芸琤 業師mentor: 賴昌作 助教: 黃湘閔、陳偉傑

### 資料與解說欄位
- 資料: 30000筆，390個欄位

  [👉🏻HERE👈🏻](https://drive.google.com/file/d/1-PVkXhUxyZRgCb7w1QwyXwmEoQ6TFyzC/view)
- 欄位解說
  [👉🏻HERE👈🏻](https://github.com/feather07170132/109_2-Salesperson-risk-detection/blob/main/%E6%A5%AD%E5%8B%99%E5%93%A1%E8%88%9E%E5%BC%8A%E9%A2%A8%E9%9A%AA%E6%A8%A1%E5%9E%8B.xlsx)
- 困難點:
  + 資料屬於imbalanced data，預測變數y:舞弊發生率僅為0.69，即195筆
  + 不僅要正確率高時，也要求解釋性合理
### 專案目標
> 運用機器學習於業務員風險偵測
1. 精準建模 : 
  + 考量準確性/穩定性/可解釋性，運用傳統迴歸/決策樹，或DL/ML方法建構更精確之業務員風險舞弊模型。
2. 發覺未知 :
  + 搭配視覺化工具探索並歸納未知的業務員pattern和不當行為手法
> 預計建模成果
  1. 準確性: 模型預測風險最高前5%業務員，即能有效捕捉到 ? %以上bad業務員
  2. 穩定性: 資料驗證，維持 ? %以上捕捉率
  3. 解釋性: **Bussiness Insight**

