# terminal-teach

**英文版教學徵求可直接用pull request**

## 最基本的要求

### 問答時間 

1. 
    到底為甚麼要用終端機?***可以用最少的容量來做事(圖形介面還要讀取圖片)***
    
1.
    是不是打指令很難用而且很難學?***並不會，指令才能讓電腦發揮最大功用***
    
1.
	怎樣打開終端機?***windows選單查詢cmd,powershell其他則是搜尋terminal***
    
---

### 開始玩轉指令
***以下指令都是非常重要的，所以要背熟喔***

#### mkdir

今天，假如我要新增資料夾，一般人就會按右鍵然後按新增資料夾，這種情況你可以帥氣的拿出終端機，輸入
   
```
mkdir <你的資料夾名或位置>
```

例如我要在**C:\user\user\desktop**新增一個名為**abc**的資料夾，那我可以輸入(記得按enter歐)

```
mkdir C:\user\user\desktop\abc
```

就是這樣子，很簡單

#### cd

有沒有覺得每次都要輸入檔案的位置很麻煩，的確沒有人會每次花很多時間輸入儲存位置，所以，大家都發現了吧，輸入框的前面總是出現一個奇怪的東西
ex:
```
PS C:\user\user>
```
如果你的跟我不一樣事正常的，會因為作業系統的不一樣而影響，他前面那串字就是說明**現在的位置**，就是目前終端機在此資料夾執行，這樣一來，就可以不用打那麼長的地址了，通常一按進去terminal預設到家目錄，家目錄就是
```
C:\user\<使用者名字>
```
在Windows和Mac都是這樣的(除非有調過)，現在我們的任務就是要把它切換資料夾，假設我們要切換至底下的Deskpot資料夾那我們就輸入
```
cd ./des
```
你有沒有發現我沒有打完呢，其實我們只要打出資料夾的前三到四個字(只要沒有其他的資料夾也是這幾個字開頭)，我們這時候就可以按下tab鍵來補齊
```
cd ./desktop
```
補充一下剛剛的
```
./  
```
表示同一層資料夾的意思
然後
```
../
```
表示上一層資料夾
所以輸入
```
cd ..
```
就表示你要回到上一層資料夾

2021/10/10紀錄
待續...
