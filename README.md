# ASRIR FIX ウェブサイト

## 概要
ASRIR FIXは、不動産コンサルティングとシステム開発を軸に、法人企業の資産価値向上と業務効率化を支援する総合パートナーです。

## 事業内容
- **不動産コンサルティング**：オフィス移転・収益改善・CRE戦略
- **システム開発**：Python・Java・Laravel を活用したDX推進
- **人材育成・家電修理**：研修とOJTで未来のエンジニアを育成

## 技術仕様
- **フロントエンド**：HTML5, CSS3, JavaScript (Vanilla)
- **レスポンシブデザイン**：モバイル・タブレット・デスクトップ対応
- **SEO最適化**：メタタグ、Open Graph、Twitter Card、構造化データ
- **検索エンジン最適化**：robots.txt、sitemap.xml
- **ホスティング**：Vercel（静的サイトホスティング）

## ファイル構成
```
HP/
├── public/
│   ├── works.html          # メインコンテンツ（トップページ、会社概要、事例等）
│   ├── robots.txt          # 検索エンジンクローラー制御
│   ├── sitemap.xml         # サイトマップ
│   └── assets/             # 画像・ロゴ等のアセット
├── vercel.json             # Vercel設定ファイル
├── package.json            # プロジェクト設定
├── .gitignore              # Git除外設定
└── README.md               # プロジェクト説明
```

## セットアップ

### ローカル開発環境
1. XAMPPをインストール
2. プロジェクトを `C:\xampp\htdocs\HP\` に配置
3. Apacheを起動
4. ブラウザで `http://localhost/HP/public/works.html` にアクセス

### Vercelでのデプロイ
1. GitHubリポジトリをVercelに接続
2. **Framework Preset**：`Other` または `Static Site`
3. **Root Directory**：`public`
4. **Build Command**：空欄（静的サイトのため不要）
5. **Output Directory**：空欄
6. 「Deploy」をクリック

## 開発環境
- **ローカルサーバー**：XAMPP (Apache)
- **本番ホスティング**：Vercel
- **エディタ**：任意のテキストエディタ
- **ブラウザ**：Chrome、Firefox、Safari、Edge

## SEO最適化
- **メタタグ**：タイトル、説明、キーワード最適化
- **Open Graph**：Facebook・LinkedIn対応
- **Twitter Card**：Twitter対応
- **構造化データ**：JSON-LD（Organization、WebSite）
- **サイトマップ**：XML形式でページ構造を明示

## Vercel設定
- **静的サイトホスティング**：高速なCDN配信
- **自動デプロイ**：GitHubプッシュ時に自動更新
- **カスタムドメイン**：独自ドメインでの運用可能
- **HTTPS対応**：SSL証明書の自動設定
- **セキュリティヘッダー**：XSS、CSRF対策

## 今後の展開
- Next.jsへの移行対応
- コンポーネント化
- TypeScript対応
- パフォーマンス最適化
- 多言語対応

## ライセンス
© 2025 ASRIR FIX. All rights reserved.
