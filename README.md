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
使用経験：Go / Python

## Development Focus

- 不明・未設定・エラーを含めて、ユーザーが状態を理解できる画面設計
- 認証とデータの所有権を分けて考えるAPI・データベース設計
- テストとドキュメントを通じて、変更後の動作を確かめやすくすること
