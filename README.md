# optionChangeTab
## 0. 前言
* 版本：第一版‧2017/3/16
* 作者：mi70
* 套用後可以把select轉換成擁有tab的功能

## 1. 使用方式

#### 1.0 
首先引入Jquery ,目前我使用的為3.2.0 版本 ，最新版本和之前版本的也沒問題
```
<script src="js/jquery/jquery.min.js"></script>
```
or 線上引入也可以再來引入
optionChangeTab.js
```
<script src="js/optionChangeTab.js"></script>
```

#### 1.1
在切換後要顯示隱藏的標籤上取類別名後面接上數字(數字開頭為0,前面類別名稱要一致)
>例如
```
<div class="tabWrap">
  <div class="tab0">這是第一組的資料</div>
  <div class="tab1">這是第二組的資料</div>
  <div class="tab2">這是第三組的資料</div>
</div>
```

#### 1.2
在js裡面建構出optionTabCheck 然後指定兩個值分別為(目標select,切換的類別名稱)
在呼叫方法changing()
>例如
```
var callChange = new optionTabCheck(".main",".tab");
callChange.changing();
```

##### 其餘部分可以參考範例檔案 index.html 和 main.js
