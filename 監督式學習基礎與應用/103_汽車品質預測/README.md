![圖](103_汽車品質預測.jpg)
## 特別注意
 - 末兩題小數點後第四位為 "**無條件捨去**" !

## 解題提示
 - "2." 的參數是給 RandomForestClassifier 用的
 - LabelEncoder 實例只能分類一批數值，不可連續使用
 - 單一筆測試資料（一維）與表格資料（二維）不同，要留意是否要新增維度並轉置
 - 雖然有緩衝誤差，無條件捨去與進位至指定位數作法還是不同
