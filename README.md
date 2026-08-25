# 講習受講確認票 OCR 一覧化サイト

今回の「2026年度 夏期講習受講確認票」のレイアウトを前提にした、ブラウザ内OCRツールです。

## できること

- スキャン画像を複数枚選択
- 画像を自動回転してOCR
- 番号・名前・クラスを抽出
- 2つのチェック欄から「変更：あり／なし」を判定
- 読み取り結果を画面上で修正
- CSVダウンロード

## GitHub Pagesへの公開

1. GitHubで新しいリポジトリを作る
2. `index.html` と `.nojekyll` をアップロード
3. Settings → Pages
4. Sourceを `Deploy from a branch`
5. Branchを `main`、Folderを `/ (root)` にしてSave
6. 数分後に表示されたURLを開く

GitHub Pagesはリポジトリ内の静的なHTML/CSS/JavaScriptを公開できます。

## 注意

- この版は今回の帳票レイアウト専用です。
- OCR結果は必ず確認してください。
- 生徒情報をGitHubリポジトリに保存しないでください。
- OCRエンジン（Tesseract.js）はCDNから読み込みます。そのため公開サイトでOCRを使うときはインターネット接続が必要です。
- 画像自体はブラウザ内で処理し、サイト側へ保存・送信しません。
