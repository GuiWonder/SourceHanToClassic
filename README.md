# 思源中文字型轉為傳承字形（舊字形）
* [思源中文字型](https://github.com/adobe-fonts)（日版）轉為傳承字形，思源黑體、思源宋體、思源等寬均可使用 
* [思源中文字体](https://github.com/adobe-fonts)（日版）转为传承字形，思源黑体、思源宋体、思源等宽均可使用
## 預覽
![image](./pic/Pic01.png)  
## 下載字型
可從 [Releases](https://github.com/GuiWonder/SourceHanToClassic/releases) 頁面下載字型。
## 使用說明
### 1.執行命令
執行命令`python sourcehantocl.py`
* 選項1：是否合併多個編碼的漢字，例如：青-靑 尚-尙 兑-兌 温-溫等？，輸入Y/N
* 選項2：標點選擇：1.日本 2.簡體中文 3.正體中文（居中）
* 選項3：簡化字字形選擇：1.日本 2.中國大陸
* 選項4：是否移除未使用的字形，輸入Y/N
### 2.執行帶引數命令
將輸入輸出檔案與上述選項作為引數執行，例如：<br /> `python sourcehantocl.py SourceHanSans-Regular.otf SourceHanSans-cl-Regular.otf y 3 2 y`
