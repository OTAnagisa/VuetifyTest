# Vuetify (デフォルト)

これはVuetifyの公式スキャフォールディングツールで、新しいVuetifyアプリケーションの構築を素早く始められるように設計されています。必要なすべての設定と標準的なディレクトリ構造を備えた基本テンプレートをセットアップし、プロジェクトをゼロから設定する手間なく開発を開始できます。

## ❗️ 重要なリンク

- 📄 [ドキュメント](https://vuetifyjs.com/)
- 🚨 [Issues](https://issues.vuetifyjs.com/)
- 🏬 [ストア](https://store.vuetifyjs.com/)
- 🎮 [プレイグラウンド](https://play.vuetifyjs.com/)
- 💬 [Discord](https://community.vuetifyjs.com)

## 💿 インストール

お好みのパッケージマネージャーを使用してプロジェクトをセットアップしてください。対応するコマンドを使用して依存関係をインストールします：

| パッケージマネージャー                                                | コマンド        |
|---------------------------------------------------------------|----------------|
| [yarn](https://yarnpkg.com/getting-started)                   | `yarn install` |
| [npm](https://docs.npmjs.com/cli/v7/commands/npm-install)     | `npm install`  |
| [pnpm](https://pnpm.io/installation)                          | `pnpm install` |
| [bun](https://bun.sh/#getting-started)                        | `bun install`  |

インストールが完了すると、Vuetify開発環境の準備が整います。

## ✨ 機能

- 🖼️ **最適化されたフロントエンドスタック**: 最新のVue 3とVuetify 3を活用し、モダンでリアクティブなUI開発体験を実現します。[Vue 3](https://v3.vuejs.org/) | [Vuetify 3](https://vuetifyjs.com/en/)
- 🗃️ **状態管理**: [Pinia](https://pinia.vuejs.org/)と統合されており、Vueのための直感的でモジュラーな状態管理ソリューションを提供します。
- 🚦 **ルーティングとレイアウト**: SPAナビゲーションにはVue Routerを、Vueファイルのレイアウト整理にはvite-plugin-vue-layoutsを使用しています。[Vue Router](https://router.vuejs.org/) | [vite-plugin-vue-layouts](https://github.com/JohnCampionJr/vite-plugin-vue-layouts)
- ⚡ **次世代ツール**: Viteを搭載し、高速なコールドスタートと即座のHMR（ホットモジュールリプレースメント）を体験できます。[Vite](https://vitejs.dev/)
- 🧩 **自動コンポーネントインポート**: unplugin-vue-componentsにより、使用するコンポーネントを自動的にインポートし、ワークフローを効率化します。[unplugin-vue-components](https://github.com/antfu/unplugin-vue-components)

これらの機能は、セットアップからデプロイまでシームレスな開発体験を提供し、Vuetifyアプリケーションが強力かつ保守可能であることを保証するために厳選されています。

## 💡 使い方

このセクションでは、開発サーバーの起動方法とプロダクション用のプロジェクトのビルド方法について説明します。

### 開発サーバーの起動

ホットリロード機能付きの開発サーバーを起動するには、次のコマンドを実行します。サーバーは [http://localhost:3000](http://localhost:3000) でアクセス可能になります：

```bash
yarn dev
```

（npm、pnpm、bunの場合も、それぞれのコマンドで同様に実行できます。）

> Vuetifyのインポートマッピングの一部として発生するJSONインポート警告を抑制するには、NODE_OPTIONS='--no-warnings'を追加してください。Node [v21.3.0](https://nodejs.org/en/blog/release/v21.3.0) 以降を使用している場合は、NODE_OPTIONS='--disable-warning=5401'に変更できます。警告が気にならない場合は、package.jsonのdevスクリプトからこれを削除できます。

### プロダクション用ビルド

プロジェクトをプロダクション用にビルドするには、次のコマンドを使用します：

```bash
yarn build
```

（npm、pnpm、bunの場合も、それぞれのコマンドで同様に実行できます。）

ビルドプロセスが完了すると、アプリケーションはプロダクション環境へのデプロイの準備が整います。

## 💪 Vuetify開発をサポート

このプロジェクトは、包括的なVueコンポーネントコレクションを持つUIライブラリである[Vuetify](https://vuetifyjs.com/en/)で構築されています。VuetifyはMITライセンスのオープンソースプロジェクトで、[スポンサーとバッカー](https://vuetifyjs.com/introduction/sponsors-and-backers/)の皆様からの寛大な貢献により実現されています。このプロジェクトのサポートにご興味がある方は、以下をご検討ください：

- [エンタープライズサポートのリクエスト](https://support.vuetifyjs.com/)
- [GithubでJohnをスポンサー](https://github.com/users/johnleider/sponsorship)
- [GithubでKaelをスポンサー](https://github.com/users/kaelwd/sponsorship)
- [Open Collectiveでチームをサポート](https://opencollective.com/vuetify)
- [Patreonでスポンサーになる](https://www.patreon.com/vuetify)
- [Tideliftでサブスクライバーになる](https://tidelift.com/subscription/npm/vuetify)
- [Paypalで一度限りの寄付をする](https://paypal.me/vuetify)

## 📑 ライセンス
[MIT](http://opensource.org/licenses/MIT)

Copyright (c) 2016-present Vuetify, LLC
