[README.md](https://github.com/user-attachments/files/33298879/README.md)
# スタンプ工房（Slack-Stamp-kobo）

Slackのスタンプ（カスタム絵文字）を気軽に作れるページです。いまは文字のスタンプだけ作れます。

**▶ ページを開く：https://sueyasutomihiro-hub.github.io/Slack-Stamp-kobo/**

インストールもログインも不要です。パソコンでもスマホでも、ブラウザで開くだけで使えます。

## 使い方

1. **選ぶ**：見本から選ぶか、伝えたい言葉を入れます。
2. **仕上げて保存**：色や名前を確かめて、画像を保存します。
3. **Slackに登録**：パソコンのSlack（またはブラウザの絵文字一覧ページ）から追加します。

くわしい手順は、ページの ③ に画面つきで載っています。

## 特長

- **丁寧語の見本**：「了解です」「感謝です」「嬉しいです」など、学校のコミュニティで使いやすい言葉を集めています。
- **小さくても読める**：Slackではスタンプがとても小さく表示されます（リアクション・メッセージの中・絵文字だけの3つの場面）。場面ごとに読みやすさを ◎○△ で確かめられます。
- **流れる文字**：「ありがとうございます」のような長い言葉は、文字が右から左へ流れる動くスタンプ（GIF）にできます。
- **名前の自動入力**：文字から、Slackで探すときの名前（例：`ryokai-desu`）を自動で付けます。
- **Slack向けの形式**：128×128px、128KB以内で保存します。

## しくみ

- `index.html` 1ファイルだけで動きます（画像も中に入っています）。
- スタンプの画像は、使う人のブラウザの中で作られます。**入力した文字や画像が、どこかに送られたり保存されたりすることはありません。**
- このリポジトリには、ツールそのもの（`index.html`）だけが入っています。みんなが作ったスタンプは、Slackのワークスペースの絵文字一覧に集まります。**スタンプを作る人がGitHubで何かをする必要はありません。**

## 更新のしかた（管理する人向け）

1. このリポジトリで「Add file」→「Upload files」を押します。
2. 新しい `index.html` をドラッグして、「Commit changes」を押します。
3. 数分でページに反映されます。古いまま見えるときは、ページで **Ctrl + Shift + R** を押して読み込み直してください。

リンクのプレビュー（カード）の説明文は、`index.html` の先頭にある `description` に書いてあります。変えたあとにリンクを共有するときは、URLの最後に `?v=2` などを付けると新しい説明文が表示されます。

## クレジット

- フォント：[M PLUS Rounded 1c](https://fonts.google.com/specimen/M+PLUS+Rounded+1c)、[Noto Sans JP](https://fonts.google.com/noto/specimen/Noto+Sans+JP)、[Dela Gothic One](https://fonts.google.com/specimen/Dela+Gothic+One)、[RocknRoll One](https://fonts.google.com/specimen/RocknRoll+One)、[Zen Kaku Gothic New](https://fonts.google.com/specimen/Zen+Kaku+Gothic+New)（Google Fonts、SIL Open Font License）
- 見本の言葉の参考：[Slack公式ブログ](https://slack.com/intl/ja-jp/blog/productivity/some-of-the-ways-we-use-emoji-at-slack)、[社内の雰囲気を良くするSlackカスタム絵文字集（Qiita）](https://qiita.com/devmatsuko/items/b6807edb15a218320293)、[@DIME](https://dime.jp/genre/2040341/)、[Slackカスタム絵文字（無料配布）](https://slack-emoji.webflow.io/)
