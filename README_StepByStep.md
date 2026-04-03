状況ありがとうございます。  
ここまで **正しい初動** ができています 👍  
（Fork → Settings → Issues 有効化 → Issue 内容確認）

では、**「Using GitHub Copilot CLI」** を  
**迷わず・詰まらず進めるための“次にやること”を順番に**整理します。

※ 以降は **コードを理解できなくてもOK / Copilotに任せる前提** で書いています。

***

# ① Using GitHub Copilot CLI：これからやること（順番）

## ✅ Step 0（完了済みの確認）

あなたはすでにここまで完了しています ✅

*   ✅ リポジトリを Fork 済み
*   ✅ **Settings → Issues が ON**
*   ✅ Issue の内容を確認済み

👉 この時点で **準備は100%整っています**

***

## ✅ Step 1：Codespaces を起動する

1.  Fork した自分のリポジトリを開く  
    例：  
    `https://github.com/MICHIKOMIZ/mslearn-copilot-codespaces-python/settings`

2.  上部メニュー  
    **Code → Codespaces → Create codespace on main**

3.  **待つ（数分）**

✅ 成功すると  
→ **VS Code（Web版）っぽい画面** が開きます

> 💡 ここでは  
> **「環境を自分で作る」理解は不要**  
> 「開いた＝成功」でOKです

***

## ✅ Step 2：ターミナルを開く（重要）

Codespaces が開いたら：

1.  画面上部メニュー  
    **Terminal → New Terminal**

2.  画面下に
    ```text
    $
    ```
    のような **コマンド入力欄** が出ればOK

👉 ここが **GitHub Copilot CLI の主戦場** です。

***

## ✅ Step 3：GitHub Copilot CLI が使えるか確認する

ターミナルにそのまま入力：

```bash
gh copilot --help
```

### 期待される結果

*   エラーが出ない
*   help メッセージが表示される

✅ これが出たら **CLI は使える状態**

> ❌ `command not found` が出た場合  
> → Codespaces の起動が途中のことがほとんど  
> → Codespaces を再起動すればOKなケースが多い  
> （この時点では深追い不要）

***

## ✅ Step 4：Issue に書かれている「最初の指示」を読む

ここで **必ず Issue に戻ります**。

Issue にはだいたい以下のような構成があります：

*   ✅ 目的（What you’ll learn）
*   ✅ やること（Tasks）
*   ✅ 使うコマンドのヒント

👉 **重要ポイント**

> ❗ まだ自分で考えてはいけません  
> ❗ そのまま Copilot に投げます

***

## ✅ Step 5：Copilot CLI に「日本語で」お願いする

### 例（そのまま使ってOK）

```bash
gh copilot suggest "Issueに書かれている最初のタスクを完了するために、次に実行すべきコマンドを教えて"
```

✅ すると Copilot が：

*   実行すべきコマンド候補
*   なぜそれを実行するか
*   警告や注意点

を **文章で説明してくれます**

👉 **まだ実行しません**

***

## ✅ Step 6：Copilot の提案を「承認して実行」

Copilot CLI は次のように聞いてきます：

```text
Do you want to run this command? (y/n)
```

ここで：

*   内容をざっくり眺める
*   危なそうでなければ **y**

✅ **失敗してもOK**  
→ 学習用 Codespaces なので壊れても問題なし

***

## ✅ Step 7：Issue のチェックリストを1つだけ進める

Issue には ✅ / ⬜ のチェック項目があります。

*   ☑ 1つ完了したら OK
*   **一気に進めない**

👉 ポイントは：

> 「Issue を1行進める」  
> ＝ 成功

***

## ✅ Step 8：詰まったら “考えずに Copilot に聞く”

例：

```bash
gh copilot explain "今のエラーメッセージの意味を説明して"
```

または：

```bash
gh copilot suggest "このIssueの次のステップを教えて"
```

✅ 自分で調べる必要なし  
✅ 正確でなくてもOK

***

# 🌱 このコースでの「正しいゴール」

あなたの場合、ゴールはこれです：

*   ❌ コマンドを覚えること
*   ❌ Pythonを理解すること

### ✅ これができれば合格

*   Copilot CLI に **自然言語で頼めた**
*   提案されたコマンドを **実行できた**
*   Issue を **1つ以上クローズできた**

***

## 次の一手（ここまで読んだら）

今すぐやるなら：

👉 **Step 1：Codespaces を起動**

そのあとで：

*   Step 3 でエラーが出たか
*   Step 5 で Copilot がどんな提案を出したか

を教えてください。  
**そこから先は、あなたの画面状況に合わせて“完全にナビ”します。**

「自分で判断」は不要です。
