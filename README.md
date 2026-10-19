# Kaito Iwase

名城大学で情報工学を学びながら、Webアプリを開発しています。  
TypeScript / React / Next.jsを中心に、画面・API・データベースをつなぐ実装に取り組んでいます。

## Selected Projects

### [ClearAllergy](https://github.com/Kaito-Iwase/ClearAllergy)
**個人開発 · アレルゲン情報を確認するWebアプリ**

飲食店が管理するメニューごとのアレルゲン情報を、利用者に分かりやすく伝えるプロトタイプです。

- 「含む」「含まない」「含む可能性」「未確認」を分け、未確認の情報を安全と受け取らせない表示を設計
- 公開画面と管理画面を分離し、店舗データの所有者をサーバー側で確認して更新を制御
- テスト・型チェック・ビルドと、公開画面のブラウザ回帰テストをCIに組み込み

`Next.js` `React` `TypeScript` `Prisma` `PostgreSQL`

<sub>架空店舗・架空メニューを使った実運用前のデモです。食品の安全性や摂取可否を判定・保証するものではありません。</sub>

### [Future ROI](https://github.com/FutureROI-DevTeam/Future-ROI)
**チーム開発 · 今日の行動による目標達成の見通しを可視化するWebアプリ**

🏆 **JOGI HACK 2026 — CARTA企業賞受賞**

日々の行動記録から、「今日取り組む場合／取り組まない場合」の目標達成の見通しを比較し、行動のきっかけをつくるアプリです。

- マルコフモデルとベイズ推定を用い、行動の継続・再開の傾向と、その不確かさを予測に反映
- 予測エンジンを画面・DBから分離し、同じ条件で計算結果を再現・検証できる構成に設計

**担当・貢献**
- 予測エンジンの開発、計算手法の比較・検証
- Issue・PRを軸としたチームの開発フローの整備
- AIが仕様・設計理由を参照できるドキュメント構成と開発指示の整備（コンテキスト設計）
- フロントエンド・バックエンドの一部修正とコードレビュー

`React` `TypeScript` `Vite` `TanStack Query` `Fastify` `TypeBox` `PostgreSQL / Neon`

<sub>表示する見通しは、記録と設定条件に基づく推定です。目標の達成時期を保証するものではありません。</sub>

### [KIGEN404](https://github.com/naoki820-askamiya/syshack2026)
**チーム開発 · 会話や出来事から感情傾向を整理するAI Webアプリ**

相手の返信や背景情報をもとに、複数の受け取り方と次の行動のヒントを返すハッカソン作品です。

- 担当：AIに渡す入力形式、プロンプト、APIレスポンスの整理
- 文面と実際の出来事を分けて扱い、ネガティブ・ポジティブの両面から整理

`React` `TypeScript` `Node.js`

<sub>AIの出力は参考情報です。相手の感情を断定するものではありません。</sub>

## Tech Stack

[![TypeScript, React, Next.js, Prisma, PostgreSQL](https://skillicons.dev/icons?i=ts,react,nextjs,prisma,postgres&theme=dark&perline=5)](https://github.com/tandpfun/skill-icons)

主に使用：TypeScript / React / Next.js / Prisma / PostgreSQL  
使用経験：Python

## Development Focus

- 不明・未設定・エラーを含めて、ユーザーが状態を理解できる画面設計
- 認証とデータの所有権を分けて考えるAPI・データベース設計
- テストとドキュメントを通じて、変更後の動作を確かめやすくすること
