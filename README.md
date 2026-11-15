## Soichiro Sunago

Webデザイナーとして約8年、中小企業のWebサイト約200件のデザインとコーディングを担当したあと、
2025年からフロントエンドエンジニアとして業務システムの開発に携わっています。

- Figma での UI 設計から、React / TypeScript での実装、デザインシステムの構築まで一貫して担当
- 利用状況の分析をもとに画面の導線を見直し、主要業務の作業時間を約50%削減（業務システムのUI刷新）
- Claude Code で React と Rails の既存コードを横断的に調べ、改修要件を開発チケットにまとめています

## 主なリポジトリ

### [ticket-evidence](https://github.com/s1ros75/ticket-evidence)
要件を調べて開発チケットにまとめるときに、「確認済み・不明点・仮定」とその根拠を分けて残すアプリ。
実務で感じた「確認したはずの根拠がたどれない」という課題から作りました。
- React 19 / TypeScript ＋ Rails 8.1（APIモード）＋ PostgreSQL
- テストを先に書く進め方（RSpec 135件、Vitest 66件）、GitHub Actions で Brakeman・bundler-audit も実行
- DBで管理するセッション、CSRF対策、ログイン試行の制限、ロックによる二重処理の防止
- 一覧はキーセット方式のページ送り。100万件で測り、どの位置でも 0.2 ms 以内
- デモ：https://ticket-evidence.onrender.com/

### [the-routine-plate](https://github.com/s1ros75/the-routine-plate)
高タンパク・低塩分の食事プランニングと栄養管理を、少ない操作で続けられるようにするアプリ。
- React / TypeScript ＋ Rails 7.2（APIモード）＋ PostgreSQL
- デモ：https://the-routine-plate.vercel.app

## 技術
- **Frontend**：React / TypeScript / JavaScript / HTML / CSS
- **Backend**：Ruby on Rails / PostgreSQL
- **Tools**：Figma / Docker / GitHub Actions / Claude Code
