# engineering-quality-templates-ja

エンジニアリング品質業務で使える、日本語優先の Markdown テンプレート集です。
機械設計レビュー、品質問題分析、RCA、8D、技術文書レビュー、
仕入先との技術連絡、車両改造確認を対象にしています。

## 利用原則

- 個人を責めず、工程、設計、文書、検証、運用の改善に集中する
- 確認済みの事実、推定、未確認事項を分けて記録する
- 結論だけでなく、判断根拠と確認方法を残す
- 暫定処置と恒久対策を区別し、再発防止まで追跡する
- 公開前に必ず機密情報と識別情報を除去する

## 収録内容

| 用途 | ファイル |
| --- | --- |
| 8D レポート | [8d-report-template-ja.md](templates/8d-report-template-ja.md) |
| 5Why による RCA | [rca-5why-template-ja.md](templates/rca-5why-template-ja.md) |
| 機械設計レビュー | [design-review-checklist-ja.md](templates/design-review-checklist-ja.md) |
| 技術質問票 | [technical-question-sheet-ja.md](templates/technical-question-sheet-ja.md) |
| 車両改造確認 | [vehicle-modification-checklist-ja.md](templates/vehicle-modification-checklist-ja.md) |
| 文書整合性確認 | [document-consistency-checklist-ja.md](templates/document-consistency-checklist-ja.md) |

詳しい使い方は [使用ガイド](docs/usage-guide-ja.md)、公開前の確認方法は
[公開時マスキングガイド](docs/public-redaction-guide-ja.md) を参照してください。

## 使い方

1. 目的に合うテンプレートを複製する。
2. 角括弧内の説明を、確認済みの内容に置き換える。
3. 不明な項目は推測で埋めず、「未確認」として確認方法を記載する。
4. 関係する役割の担当者とレビューし、根拠資料と完了条件を確認する。
5. 公開または共有の前に、マスキングチェックを実施する。

### 使用例: 8D レポート

品質問題の封じ込めから再発防止までを管理する場合は、
[8D テンプレート](templates/8d-report-template-ja.md) を複製します。
記入イメージは [架空の 8D 記入例](examples/sample-8d-report.md) で確認できます。

### 使用例: 技術質問票

仕様や検証条件を相手と確認する場合は、
[技術質問票](templates/technical-question-sheet-ja.md) を複製します。
質問は一項目一論点とし、背景、事実、質問、希望する回答形式を分けます。
[架空の技術質問例](examples/sample-technical-question.md) も参照してください。

## 公開前の注意

このリポジトリの例はすべて架空です。実務で作成した文書を公開する場合は、
会社名、顧客名、仕入先名、個人情報、図面番号、車両 ID、製造番号、
契約・法務情報、健康情報、職歴情報、その他の機密情報を含めないでください。
本文だけでなく、画像、添付ファイル、リンク、メタデータ、Git 履歴も確認します。

## ライセンス

[MIT License](LICENSE)
