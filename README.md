# MinecraftModule

下載 [**Git LFS**](https://git-lfs.github.com)

## 初始化git

```javascript
cd {模組存放路徑}

git init
git remote add origin https://github.com/Sam-0403/MinecraftModule.git

git lfs install
git lfs track *
git add .gitattributes
git commit -m "Pre-Commit to prevent error"
git push -u origin master

git add .
git commit -m "First Commit"
git push -u origin master

```

## 複製大文件git
```javascript
cd {模組存放路徑}
git lfs clone https://github.com/Sam-0403/MinecraftModule.git
```

## 拉取git
```javascript
cd {模組存放路徑}
git pull
```

## 上傳git
```javascript
cd {模組存放路徑}
git add .
git commit -m "{相關說明}"
git pull
git push -u origin master
```
