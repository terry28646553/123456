# 使用方式

速成版

## 第零步

到github開一個帳號, 開一個倉庫，接下一段

## 教室的電腦（每個禮拜來上課時），以及未設定的新電腦

```
git config --global user.name "自己的帳號名稱"
git config --global user.email "自己的Email"
```

切換到工作資料夾, 順便清空原內容，然後複製倉庫到本地端

```
git clone 遠端倉庫的路徑 [複製到資料夾]
```

例如複製此倉庫到目前所在資料夾

```
git clone https:github.com/FilitovDemo/test2018.git .
```

工作中，每到一個階段，可記錄一個版本，隨時可供追蹤或回溯：

```
git add 檔案們
git commit -m "做了甚麼"
```

工作完成後，將階段性成果推送到遠端github倉庫：

```
git push
```

若有帳號密碼的提示，請輸入 github 的帳號密碼

## 自己的隨身碟，或自己的電腦，無需每次都設定的

### 第一次設定同上

### 第二次以後

若是沒在其他電腦工作過，不用做其他操作。

若是曾在其他電腦工作，並且在他處將倉庫推送到遠端github倉庫中，拉回新的版本：

```
git pull
```

### 其他同上
