# Hi, I'm Art

大学で理系分野を学びながら、AIを活用した小規模な開発・業務自動化に取り組んでいます。

現在は、Pythonを使ったCLIツールや、日常作業を効率化する小さな自動化ツールを中心に制作しています。

## Focus

- Pythonによる小規模自動化
- CSV・ファイル整理などの業務効率化ツール
- CLIツール開発
- Git / GitHubを使った開発管理
- AI-assisted development

## Projects

### CSV Cleaner
複数のCSVファイルを読み込み、列名の空白削除・空行削除・列構成チェックを行ったうえで、1つのCSVに結合するCLIツールです。

- Python / pandas / pytest
- CLI引数対応
- dry-run対応
- エラー処理とテストを実装

### File Renamer
指定フォルダ内のファイルを、安全に連番形式へリネームするCLIツールです。

- Python標準ライブラリ
- dry-runをデフォルトにした安全設計
- `--apply` 指定時のみ実リネーム
- 危険なprefix / ext指定の検証
- pytestによるテスト

### Sales Report Generator
売上CSVを読み込み、商品別・日付別の集計結果をCSVとExcelで出力するPython CLIツールです。

- Python / pandas / openpyxl / pytest
- 商品別・日付別集計
- 入力CSVのバリデーション
- CSV / Excelレポート出力

### SRT to VTT Converter
SRT字幕ファイルをWebVTT形式へ一括変換するPython CLIツールです。

- Python標準ライブラリ
- dry-run / apply対応
- 入力SRTを上書きしない安全設計
- 既存VTTの上書き防止
- 不正なタイムコード行の検出
- pytestによるテスト

## Development Style

AIを使って実装を補助しつつ、仕様整理、レビュー、安全性改善、テスト、GitHub公開までを自分で確認しながら進めています。

<!--
**artssm0219/artssm0219** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
