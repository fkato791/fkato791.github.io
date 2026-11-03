# Fumiya Kato — Personal website

A lightweight, bilingual personal website for GitHub Pages. Original pixel illustrations, English / Japanese content, light / dark themes, and a printable CV. No build tools or external services are required.

## Publish on GitHub Pages

1. Create a **public** repository named **`fkato791.github.io`** under the `fkato791` account.
2. Upload `index.html` and `.nojekyll` to the root of its `main` branch.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, then **main** and **/ (root)**, and click **Save**.
5. Your site will be available at **https://fkato791.github.io/** after GitHub completes deployment.

If you use a different repository name, your address will be `https://fkato791.github.io/REPOSITORY/`. Update the canonical and Open Graph URL metadata in `index.html` accordingly. All navigation uses relative hash links and works under a project path.

## 内容を編集する

- `index.html` 内の本文を編集します。`data-en` が英語、`data-ja` が日本語です。初期表示の英語本文も同じ内容にそろえてください。
- 学歴・職歴・プロジェクト説明は、これまで共有された内容に基づく初稿です。公開前に氏名の表記、担当範囲、所属の英語表記を確認してください。
- 正式な氏名表記を未確認のため、初稿では日本語ページも `Fumiya Kato` と表示しています。
- 個人のメールアドレス、電話番号、家族情報、社内資料、プロジェクトの費用や工期は掲載していません。
- 外部リンクは GitHub プロフィールと note です。SoundScript / HELIOS の公開URLは未設定のため、紹介文のみ掲載しています。
- プロフィール写真を加える場合は、写真ファイルを追加し、About ページに配置できます。現在のイラストはすべて独自にコードで描画しています。
- CV の「Print / Save as PDF」で、現在の言語の略歴を印刷・PDF保存できます。

## 構成

| セクション | 内容 |
| --- | --- |
| About | 自己紹介・関心分野 |
| Experience | 日本・東南アジアでの建設プロジェクト経験 |
| Projects | SoundScript / HELIOS |
| Research & Learning | 国際建設・省エネ建築・建設AI |
| Writing & Travels | note の記事・RV旅の紹介 |
| CV | 学歴・職歴・専門分野の略歴 |

## 更新

GitHub で `index.html` を開き、編集して **Commit changes** を実行すると、Pages が再公開します。

Reference for the interaction concept: https://diane-richard.github.io/ . This implementation uses its own source code and original canvas illustrations; no reference-site code, illustrations, or personal content is included.

Official GitHub Pages setup documentation: https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site
