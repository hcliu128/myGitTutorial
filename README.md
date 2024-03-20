# myGitTutorial
This is my note about using Git. 

## Initialize
```
mkdir myGitTutorial
cd myGitTutorial
git init
```

## When you adding some file to this repo...
### 將所有檔案 (含子目錄的檔案) 加入到工作目錄索引中
```
git add . 
```
### 新增所有「點」開頭的檔案
```
git add .*
```
### COMMIT

```
git commit
git commit -m "版本紀錄的說明文字"
```

### 查看歷史紀錄
```
git log
```

### 更名
```
git mv old_name new_name
```

### 顯示工作目錄的索引狀態
```
git status
```