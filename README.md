# README
## 環境構築メモ
* git管理
```
rm -rf backend/.git
rm -rf frontend/.git
git init
```
※`.gitignore`に以下2つ
```
/frontend/node_modules/
.DS_Store
```
この後`git add .`