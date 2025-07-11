# プライバシーポリシー

最終更新日：2025-06-22

リプポップ（以下「当アプリ」）は、ユーザーのプライバシーを尊重し、以下の方針で個人情報を取り扱います。本ポリシーは App Store プライバシー表示ガイドラインおよび Apple「App Privacy Details」要件に準拠しています。:contentReference[oaicite:2]{index=2}

---

## 1. 収集するデータ

| 区分 | データ | 収集タイミング | 用途 |
| --- | --- | --- | --- |
| ユーザー生成コンテンツ | チャットやプロフィールのスクリーンショット画像（EXIF を自動削除） | 返信生成時 | OpenAI API での解析 |
| アプリ使用情報 | 生成要求回数、エラーログ、クラッシュログ | 操作時 | 品質向上・不正利用防止 |
| 購入情報 | サブスクリプション取引 ID（匿名化） | 購入・復元時 | 購入確認・復元処理 |

> **追記**：画像に未成年を含む場合や第三者の顔写真を含む場合はアップロードしないでください（OpenAI 画像ポリシー §1.1）:contentReference[oaicite:3]{index=3}。

---

## 2. データの保存期間

- 画像と生成テキストは **サーバー上に永続保存しません**。OpenAI API 転送後、当社サーバーログから即時削除し、OpenAI 側でも 30 日以内に自動削除されます。  
- 購入トランザクション ID は法令上必要な期間保存する場合があります。

---

## 3. データの第三者提供

当アプリは以下の第三者にデータを送信します。その他の第三者提供は行いません。

| 送信先 | 目的 | 共有データ |
| --- | --- | --- |
| OpenAI, L.L.C. | 画像・テキスト解析 | スクリーンショット画像（Base64 化）、モード番号、追加プロンプト |
| Apple（StoreKit） | 購入処理 | トランザクション ID 等 |

---

## 4. セキュリティ対策

- 通信は TLS 1.3 により暗号化されます。  
- リクエストはレートリミットで保護し、画像サイズ上限は 8 MB に制限しています。  
- GitHub Pages では HTTPS を強制し、中間者攻撃を防ぎます。:contentReference[oaicite:4]{index=4}

---

## 5. ユーザーの権利

- 収集データの開示・削除を希望する場合は、下記メールアドレスまでご連絡ください。  
- サブスクリプションは iOS 設定アプリ > Apple ID > サブスクリプション からいつでも解約可能です。:contentReference[oaicite:5]{index=5}

---

## 6. 未成年者のプライバシー

- 13 歳未満の方は利用できません。18 歳未満の方は保護者の同意を得てください（OpenAI TOS 整合）。:contentReference[oaicite:6]{index=6}  

---

## 7. ポリシーの変更

法令改正やサービス内容の変更に応じて本ポリシーを改定することがあります。重要な変更がある場合はアプリ内通知またはリポジトリの Release Notes でお知らせします。

---

## 8. お問い合わせ

taroiwai@gmail.com