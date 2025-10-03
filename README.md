# kadai1 - 学習記録アプリ

Next.js 15とReact 19を使用したモダンな学習記録管理Webアプリケーションです。学習内容と時間を記録・管理できます。

## 機能概要

- 学習記録の作成・表示
- 学習時間の合計表示
- リアルタイムな入力値確認

## 技術スタック

- **フロントエンド**: Next.js 15, React 19, TypeScript
- **UIライブラリ**: Tailwind CSS, Radix UI, shadcn/ui
- **状態管理**: React Hooks (useState)
- **ビルドツール**: Turbopack
- **コード品質**: Biome (Linter/Formatter)
- **パッケージマネージャー**: pnpm

## 環境設定

### 1. リポジトリをクローン

```bash
git clone https://github.com/mkiin/kadai1.git
cd kadai1
```

### 2. 依存関係のインストール

```bash
pnpm install
```

## 起動方法

### 開発サーバーの起動

```bash
pnpm dev
```

アプリケーションは http://localhost:3000 で起動します。

### 本番ビルド

```bash
pnpm build
```

### 本番サーバーの起動

```bash
pnpm start
```

### その他コマンド

```bash
# リント実行
pnpm lint

# フォーマット実行
pnpm format
```

## プロジェクト構造

```
kadai1/
├── src/
│   ├── app/
│   │   ├── layout.tsx          # アプリケーション全体のレイアウト
│   │   └── page.tsx            # メインページ（学習記録アプリ）
│   ├── components/ui/          # UIコンポーネント（shadcn/ui）
│   ├── hooks/                  # カスタムフック
│   └── lib/                    # ユーティリティ関数
├── public/                     # 静的ファイル
├── biome.json                  # Biome設定
├── components.json             # shadcn/ui設定
├── next.config.ts              # Next.js設定
├── tailwind.config.ts          # Tailwind CSS設定
├── tsconfig.json               # TypeScript設定
└── README.md                   # このファイル
```

