## autumn_backend_A

### メンター制を始めるための準備
#### ①作業用フォルダの作成＋移動
```
$ mkdir autumn && cd autumn
```
#### ②課題提出用リポジトリをCloneする
```
$ git clone https://github.com/autumn-backend/autumn_backend_A.git
```
#### ③ cloneしたフォルダに移動
```
$ cd autumn_backend_A
```
#### ④ 現状のブランチを確認
```
$ git branch
* master
//*のついているブランチにいます
```
#### ⑤ mentorブランチに移動
```
$ git checkout mentor
```
#### ⑥ mentorを親として、自分のブランチを切る
##### younameを自身のブランチ名としてください
```
$ git checkout -b yourname mentor
```
#### ⑦一応ブランチの状態を確認
```
$ git branch
 master
 mentor
*yourname
```
#### ⑧作成したブランチをリモートブランチとして登録
```
$ git push -u origin yourname
```
## 完成！

### その後の作業についての注意事項
##### ①フォルダをIDEで開く場合は、自身のフォルダ名のみ開くこと
##### ②コードに対して、「何をしているか」というコメントを残すこと
##### ③自身のコードに統一性を持たせること
##### ④プルリクエストは、「mentor」ブランチに向けて投げてください。
