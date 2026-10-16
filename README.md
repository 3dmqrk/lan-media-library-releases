# LAN Media Library アプリ

Androidスマートフォン版とFire TV版の配布ページです。現在のAPKは、この環境のTailscale Funnel URLを設定した個人用ビルドです。

## 現行版

| 端末 | アプリ | 接続方法 | ダウンロード |
|---|---|---|---|
| Androidスマートフォン | Phone Direct (Funnel) v1.0.5 | FunnelのHTTPS経由。端末側にTailscaleアプリは不要です。 | [リリースとAPK](https://github.com/3dmqrk/lan-media-library-releases/releases/tag/phone-direct-v1.0.5) |
| Fire TV | Fire TV (Funnel) v1.0.4 | FunnelのHTTPS経由。アプリに表示されるQRコードをスマートフォンで読み取り、ログイン中のアカウントで承認します。 | [リリースとAPK](https://github.com/3dmqrk/lan-media-library-releases/releases/tag/v1.0.4) |

## インストール

- **スマートフォン:** リリースページから端末に合うAPKを選びます。一般的な近年のAndroid端末は `arm64-v8a` です。インストール時に許可を求められた場合は、この配布元からのAPKインストールを許可してください。
- **Fire TV:** Fire TVのリリースページにあるAPKをインストールします。

## 利用条件

サーバーが起動し、Tailscale Funnelが有効である必要があります。ログインにはサーバーで承認されたアカウントを使います。現在のAPKはこの環境専用で、別のサーバーへの接続には対応していません。

Fire TVは初回にQRコードでアカウントを連携します。スマートフォン側でログインしてからQRコードを読み取り、連携を承認してください。テレビには複数の承認済みアカウントを登録できます。

## アップデート

アプリ内の「更新を確認」は、それぞれのアプリに対応する更新だけを確認します。更新が見つかると確認メッセージが表示され、承認してからAPKをダウンロードします。手動で更新する場合は、上記のリリースページを開いてください。

## 過去のバージョン

現在の配布対象は上記のFunnel版です。旧版やTailscale接続版、LAN専用版は削除せずDraftとして保管しており、通常のリリース一覧やアプリ内の更新確認には表示されません。