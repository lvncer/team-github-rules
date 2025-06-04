# 🌟 Team GitHub Rules

このリポジトリは、チームでの効率的な Git 作業のためのガイドラインとテンプレートを提供します。

## 📁 プロジェクト構造

```bash
your-project-root/
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   └── default.md          # イシューテンプレート
│   ├── PULL_REQUEST_TEMPLATE/
│   │   ├── default.md          # PRテンプレート
│   │   └── review_template.md  # レビューテンプレート
│   ├── CONTRIBUTING.md         # コントリビューションガイド
│   ├── COMMIT_CONVENTION.md    # コミットメッセージ規約
│   ├── CODE_OF_CONDUCT.md      # 行動規範
│   └── SECURITY.md             # セキュリティポリシー
│
├── docs/                       # ドキュメント
│   ├── requirements/
│   │   └── requirement_spec.md # 要件定義書
│   └── design/
│       └── architecture.md     # アーキテクチャ設計書
│
├── .editorconfig               # エディタ設定
├── .gitignore                  # Git無視ファイル
├── CHANGELOG.md                # 変更履歴
├── LICENSE                     # ライセンス
└── README.md                   # プロジェクト概要
```

## 🔄 作業の流れ

1. 📝 **イシューの作成**

   - [イシューテンプレート](./.github/ISSUE_TEMPLATE/default.md)に従って作成
   - 作業内容を明確に記述

2. 🌿 **ブランチの作成**

   - [ブランチ命名規則](./.github/CONTRIBUTING.md#ブランチ命名規則)に準拠
   - イシューと関連付け

3. 💻 **開発作業**

   - ローカルで作業を実施
   - 定期的にコミット

4. 📤 **コミット＆プッシュ**

   - [コミットメッセージ規約](./.github/COMMIT_CONVENTION.md)に従う
   - 変更内容を明確に説明

5. 🔍 **プルリクエスト**

   - [PR テンプレート](./.github/PULL_REQUEST_TEMPLATE/bugfix_pr.md)に従って作成
   - [レビューガイドライン](./.github/PULL_REQUEST_TEMPLATE/review_template.md)を参考にレビューを依頼

6. ✅ **マージ完了**
   - レビュー承認後にマージ
   - ブランチのクリーンアップ

## 💡 重要な作業ルール

### チーム協力の原則

1. 👥 **ペアワークの推奨**

   - 可能な限り、チームメイトと協力して作業を進める
   - 知識共有を積極的に行う

2. 💬 **オープンなコミュニケーション**

   - 不明点や疑問点は遠慮なく相談
   - チーム全体での知識共有を推進

3. ⚠️ **インシデント報告**

   - 重要な問題が発生した場合は即時報告
   - 解決に向けてチームで協力

4. 👀 **コードレビュー**
   - 作業完了後は必ずプルリクエストを作成
   - [レビューガイドライン](./.github/PULL_REQUEST_TEMPLATE/review_template.md)に従って建設的なレビューを実施

## 📚 ドキュメント一覧

### GitHub テンプレート・ガイドライン

| ファイル                                               | 説明                       | 用途                         |
| ------------------------------------------------------ | -------------------------- | ---------------------------- |
| [CONTRIBUTING.md](./.github/CONTRIBUTING.md)           | コントリビューションガイド | ブランチ管理、開発フロー     |
| [COMMIT_CONVENTION.md](./.github/COMMIT_CONVENTION.md) | コミットメッセージ規約     | 統一されたコミットメッセージ |
| [CODE_OF_CONDUCT.md](./.github/CODE_OF_CONDUCT.md)     | 行動規範                   | コミュニティガイドライン     |
| [SECURITY.md](./.github/SECURITY.md)                   | セキュリティポリシー       | 脆弱性報告手順               |

### テンプレート

| ファイル                                                                 | 説明                 | 用途               |
| ------------------------------------------------------------------------ | -------------------- | ------------------ |
| [default.md](./.github/ISSUE_TEMPLATE/default.md)                        | イシューテンプレート | 課題・要望の報告   |
| [bugfix_pr.md](./.github/PULL_REQUEST_TEMPLATE/bugfix_pr.md)             | PR テンプレート      | プルリクエスト作成 |
| [review_template.md](./.github/PULL_REQUEST_TEMPLATE/review_template.md) | レビューテンプレート | コードレビュー実施 |

### プロジェクトドキュメント

| ファイル                                                       | 説明                 | 用途                   |
| -------------------------------------------------------------- | -------------------- | ---------------------- |
| [requirement_spec.md](./docs/requirements/requirement_spec.md) | 要件定義書           | プロジェクト要件の管理 |
| [architecture.md](./docs/design/architecture.md)               | アーキテクチャ設計書 | システム設計の管理     |

### 設定ファイル

| ファイル                         | 説明         | 用途                     |
| -------------------------------- | ------------ | ------------------------ |
| [.editorconfig](./.editorconfig) | エディタ設定 | コードスタイルの統一     |
| [.gitignore](./.gitignore)       | Git 無視設定 | バージョン管理対象の制御 |
| [CHANGELOG.md](./CHANGELOG.md)   | 変更履歴     | リリース管理             |
| [LICENSE](./LICENSE)             | ライセンス   | 利用条件の明示           |

## 🚀 クイックスタート

### 新しいプロジェクトでの使用方法

1. **このリポジトリをテンプレートとして使用**

   ```bash
   # GitHubでこのリポジトリを「Use this template」でコピー
   # または直接クローン
   git clone https://github.com/your-org/team-github-rules.git your-new-project
   cd your-new-project
   ```

2. **プロジェクト固有の情報を更新**

   - `README.md` のプロジェクト名と説明を更新
   - `LICENSE` の著作権者情報を更新
   - `docs/requirements/requirement_spec.md` にプロジェクト要件を記載
   - `docs/design/architecture.md` にシステム設計を記載

3. **GitHub 設定の確認**
   - ブランチ保護ルールの設定
   - 必要なレビュワーの設定
   - CI/CD パイプラインの設定

### 既存プロジェクトへの適用

1. **必要なファイルをコピー**

   ```bash
   # .githubディレクトリをコピー
   cp -r team-github-rules/.github your-existing-project/

   # 設定ファイルをコピー
   cp team-github-rules/.editorconfig your-existing-project/
   cp team-github-rules/.gitignore your-existing-project/
   ```

2. **既存ファイルとの統合**
   - 既存の`.gitignore`がある場合は内容をマージ
   - 既存のドキュメントがある場合は適切に統合

## 🔧 カスタマイズガイド

このテンプレートを使用する際に、プロジェクト固有の情報に変更が必要なファイルと箇所をまとめています。

### 📝 必須変更項目

#### 1. プロジェクト基本情報

| ファイル       | 変更箇所       | 変更内容                                 |
| -------------- | -------------- | ---------------------------------------- |
| `README.md`    | タイトル・説明 | プロジェクト名と概要を記載               |
| `LICENSE`      | 著作権者       | `[Your Name]` を実際の名前・組織名に変更 |
| `CHANGELOG.md` | リリース日     | `2024-01-XX` を実際のリリース日に変更    |

#### 2. GitHub 設定

| ファイル                  | 変更箇所       | 変更内容                                               |
| ------------------------- | -------------- | ------------------------------------------------------ |
| `.github/SECURITY.md`     | 連絡先         | `security@example.com` を実際のメールアドレスに変更    |
| `.github/SECURITY.md`     | リポジトリ URL | `[username]/[repository]` を実際のリポジトリ情報に変更 |
| `.github/CONTRIBUTING.md` | レビュワー     | レビュワー名を実際のチームメンバーに変更               |

#### 3. プロジェクトドキュメント

| ファイル                                | 変更箇所     | 変更内容                         |
| --------------------------------------- | ------------ | -------------------------------- |
| `docs/requirements/requirement_spec.md` | 全体         | プロジェクト固有の要件に書き換え |
| `docs/design/architecture.md`           | システム概要 | 実際のシステム構成に書き換え     |
| `docs/design/architecture.md`           | 技術スタック | 使用する技術に合わせて更新       |

### 🔄 推奨変更項目

#### 1. ブランチ戦略のカスタマイズ

| ファイル                  | 変更箇所         | 変更内容                                 |
| ------------------------- | ---------------- | ---------------------------------------- |
| `.github/CONTRIBUTING.md` | ブランチフロー   | プロジェクトに合わせたブランチ戦略に調整 |
| `.github/CONTRIBUTING.md` | レビュープロセス | チーム規模に応じたレビュー体制に調整     |

#### 2. テンプレートのカスタマイズ

| ファイル                                     | 変更箇所       | 変更内容                             |
| -------------------------------------------- | -------------- | ------------------------------------ |
| `.github/ISSUE_TEMPLATE/default.md`          | 項目           | プロジェクト固有の報告項目を追加     |
| `.github/PULL_REQUEST_TEMPLATE/bugfix_pr.md` | チェックリスト | プロジェクト固有のチェック項目を追加 |

#### 3. 開発環境設定

| ファイル        | 変更箇所     | 変更内容                             |
| --------------- | ------------ | ------------------------------------ |
| `.editorconfig` | 言語設定     | 使用する言語に応じて設定を調整       |
| `.gitignore`    | 除外ファイル | プロジェクト固有の除外ファイルを追加 |

### 📋 変更チェックリスト

プロジェクト開始時に以下の項目を確認してください：

- [ ] **基本情報の更新**

  - [ ] `README.md` のプロジェクト名・説明を更新
  - [ ] `LICENSE` の著作権者情報を更新
  - [ ] `CHANGELOG.md` の初期リリース日を設定

- [ ] **連絡先・URL の更新**

  - [ ] `.github/SECURITY.md` のメールアドレスを更新
  - [ ] `.github/SECURITY.md` のリポジトリ URL を更新
  - [ ] `CHANGELOG.md` のリポジトリ URL を更新

- [ ] **チーム情報の更新**

  - [ ] `.github/CONTRIBUTING.md` のレビュワー名を設定
  - [ ] レビュー体制をチーム規模に合わせて調整

- [ ] **プロジェクト固有設定**

  - [ ] `docs/requirements/requirement_spec.md` を実際の要件に更新
  - [ ] `docs/design/architecture.md` を実際の設計に更新
  - [ ] `.gitignore` にプロジェクト固有の除外ファイルを追加

- [ ] **GitHub リポジトリ設定**
  - [ ] ブランチ保護ルールの設定
  - [ ] 必要なレビュワー数の設定
  - [ ] CI/CD パイプラインの設定
  - [ ] イシュー・PR テンプレートの有効化

### 🚀 セットアップ後の確認

1. **テンプレートの動作確認**

   - イシューを作成してテンプレートが表示されるか確認
   - PR を作成してテンプレートが表示されるか確認

2. **ブランチ保護の確認**

   - main ブランチへの直接プッシュが禁止されているか確認
   - 必要なレビュー数が設定されているか確認

3. **CI/CD の確認**
   - GitHub Actions が正常に動作するか確認
   - デプロイプロセスが適切に設定されているか確認
