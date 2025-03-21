# Markdownの書き方

## そもそもの書いていきかた

2025/03/22現在の執筆環境：
VSCode + Codespaceに、拡張機能として

- Markdown All in One
- Markdown PDF
- Marp for VS Code
- markdownlint

を使用。

Markdown All in Oneは、Markdownファイルの自動コンプリート(と言っても今の所効果を実感できているのはリスト表記くらい。)や、HTML化など。
Markdown PDFは作成したMarkdownファイルのPDF化。  
Marp for VS Codeは作成したMarkdownをもとに、パワポ資料みたいなものをpdfまたはHTMLとして出力してくれるみたい。  
そして、今現在入れている中で一番うるさいのはmarkdownlintで、これはMarkdownファイルの体裁をチェックしてくれる。ファイルの最初と最後、リストの開始と終了、見出し前後などに空白行を入れていないと黄色波線で怒られる。  

## 基本の書き方

`# `を使うと見出しになる。`#`の数が増えるほど見出しの大きさは小さくなる。  
文章中の改行は半角スペース２つ。もしくは文と文の間に空白行を挿入。  
エスケープ文字は`\`。
コードブロックに含めたい場合はバッククォートで挟む。こんな感じ→　\`aaa\`

## ファイルのリンクのしかた
