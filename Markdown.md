# 標題
'＃'後面要空格
# H1
## H2
### H3
#### H4
##### H5
###### H6

# 強調語法
### 粗體
`**內容**`  
**Hello World**  

### 斜體
`*內容*`  
*Hello World*

### 刪除線
`~~內容～～`  
~~Hello World~~

# 段落
`如果要換下一個段落就在段落間插入空行,如果要強至換行就在結尾處插入兩個空格`

Part 1  
'空行'  
Part 2 '空兩格'  
Line 1 '空兩格'  
Line 2 '空兩格'

# 區塊  
用 `` 把東西框起來

`小區塊`

```
'```'
大區塊
大區塊
大區塊
'```'
```

# 階層
用 > 表示階層
>First '>'
>>Second '>>'
>>>Third '>>>'

# 項目符號
## 符號
項目前加上 *  
```
* one
* two
* three
```
## 數字  
項目前加上 1. 2. 3.  
```
1.
2.
3.
```
## 水平線  
用 - - - 即可

---

# 超連結

* [Github](https://github.com/)  

```
[說明]（網址）
```

* 這裡有兩個網址[Google][1],[Yahoo][2]
[1]:Google.com.tw
[2]:Yahoo.com.tw
```
內容[說明1][數字1].....[說明2][數字2]  
[數字1]:網址  
[數字2]:網址
```  

* Google:<http://google.com>
```
<網址>
```

# 表格
```
| 標頭 | 標頭 | 標頭 | 標頭 ｜
| 對齊 | 對齊 | 對齊 | 對齊 ｜
| 內容 | 內容 | 內容 | 內容 ｜  
| 內容 | 內容 | 內容 | 內容 ｜

對齊：以'：'決定靠左中右
```  
| 123 | 456 | 789 |
| :-- | --: | :-: |
| 4   | 5   | 6   |
| 7   | 8   | 9   |

# 程式碼
像寫大區塊,用三個反單引號包起來,記得在開頭三個反單引號後面加語言名稱
```
` ` `語言名稱
程式碼......
p.s 三個反單引號不需要空格
` ` `
註： Markdown 支援的語言可以參考:<http://support.codebasehq.com/articles/tips-tricks/syntax-highlighting-in-markdown>

```  
*Python  
```py
print('Hello World')
```

# 圖片
```
![圖片描述](圖片連結)
```
![Markdown](https://upload.wikimedia.org/wikipedia/commons/thumb/4/48/Markdown-mark.svg/208px-Markdown-mark.svg.png)

# HTML
在 Github 中可以直接使用 HTML  
<h5>HTML</h3>
`<h5>被包在區塊中不會背執行</h3>`

# 跳脫字元
`在特殊符號輸入'\'就好`
