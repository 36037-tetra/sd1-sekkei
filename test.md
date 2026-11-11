#  システム設計Ⅰ
## 次の見出し
- 要件定義
- 外部設計

この授業は**ここ**が重要です

ここのサイトから調べました

[いわきコンカレ](https://www.iwaki-cc.ac.jp)

| 項目名 | 型 | 桁数 | 必須 |
|---|---|---:|:---:|
| 学籍番号 | 文字 | 5 | 〇 |
| 科目名 | 文字 | 60 | 〇 |
| 素点 | 数値 | 3 |  | 

```sql
SELECT * FROM 履修
WHERE 評価 IS NULL;
```
```java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}
```
## グラブルデイリーチェックシート
- [x] つよばは
- [x] アーカーシャ
- [ ] グランデ
- [ ] アルバハ
- [ ] ルピガチャ
- [ ] pro

![Image](img\icc-logo.png)

<label><input type="radio" name="fruit" value="apple"> りんご</label><br>
<label><input type="radio" name="fruit" value="banana" checked> バナナ</label><br>
<label><input type="radio" name="fruit" value="orange"> オレンジ</label>

```Mermaid
flowchart TD;
    A[成績を聞く]-->B{評価は確定？};
    B-->|はい|C[評価を表示];
    B-->|いいえ|D[未確定と表示];
```
```Mermaid
sequenceDiagram
    学生 ->> 画面: 成績ボタンを押す
    画面 ->> DB: 履修データを問い合わせ
    DB -->> 画面: 科目と評価を返す
    画面 -->> 学生: 成績一覧を表示
```

## gitとgitHubの使い方

- 作業ツリー
  - 変更されたファイルが保存される場所
- ステージングエリア
  - 変更をまとめてコミットする準備をする場所
- ローカルリポジトリ
  - ローカルのファイルとコミット履歴が保存される場所
- リモートリポジトリ
  - リモートのファイルとコミット履歴が保存される場所
- git add
  - 変更をステージングエリアに追加する操作
- git commit
  - 変更を記録する操作
- git push
  - コミットした変更をリモートリポジトリに送る操作
- git pull
  - リモートリポジトリの変更をローカルに取り込む操作
- git clone
  - リモートリポジトリをローカルにコピーする操作
- git branch
  - ブランチを作成・管理する操作
- git merge
  - ブランチを統合する操作
- git checkout
  - ブランチを切り替える操作
- git log
  - コミット履歴を表示する操作
- git status
  - 作業ツリーの状態を確認する操作
- git diff
  - 変更内容の差分を表示する操作
- git reset
  - 変更を取り消す操作
- git revert
  - コミットを取り消す操作
- git stash
  - 変更を一時的に退避する操作
- git tag
  - コミットにラベルを付ける操作
- git remote
  - リモートリポジトリを管理する操作
- git fetch
  - リモートリポジトリの変更を取得する操作
- git rebase
  - ブランチの基点を変更する操作
- git cherry-pick
  - 特定のコミットを別のブランチに適用する操作
- git bisect
  - バグの原因となるコミットを特定する操作