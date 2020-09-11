# 勉強会で使うコマンドなど
資料のやついちいち写経するのめんどくさいと感じたらこちらを使ってください。

## ファイルのアップロード
```
mkdir test
cd test
touch a.txt
git init 
git add a.txt
git commit -m "first commit" 
git remote add origin ~
git push origin master
```
↑~のところはQuick setupのところに書いてあるURLをコピペしてください。

## 変更の反映
```
git add a.txt
git commit -m ”wrote" 
git push origin master
```

## （共同開発の流れの）実習
```
mkdir test2
cd test2
git clone https://github.com/Chirhata/kyoudoukaihatu.git
cd kyoudoukaihatu
touch ~.txt
git branch ~
git checkout ~
git add ~.txt
git commit –m “make”
git push origin ~
```
↑の~は自分の学生証番号に置き換えてください

# URL
勉強会のおまけコーナーで紹介したやつ
## gitignore
https://github.com/github/gitignore/blob/master/Unity.gitignore
## Sourcetree
https://www.atlassian.com/ja/software/sourcetree
