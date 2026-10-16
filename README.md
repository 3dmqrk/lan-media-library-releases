# LAN Media Library — Android アプリ

このリポジトリは、LAN Media Library の配布用 APK と更新情報をまとめています。ソースコードは非公開です。

## どのアプリを選ぶ？

| アプリ | 接続方法・用途 | 現行版 | リリース |
|---|---|---:|---|
| **スマホ版 — Tailscale** | アプリ内の Tailscale 接続で、自宅サーバーへ安全に接続 | 0.4.56 | [Phone v0.4.56](https://github.com/3dmqrk/lan-media-library-releases/releases/tag/phone-v0.4.56) |
| **スマホ版 — Direct / Funnel** | Funnel 経由で接続。スマホに別の VPN アプリを入れずに使う | 1.0.4 | [Phone Direct v1.0.4](https://github.com/3dmqrk/lan-media-library-releases/releases/tag/phone-direct-v1.0.4) |
| **Fire TV — LAN** | 家の Wi-Fi など、サーバーと同じローカルネットワークで使う | 0.9.14 | [Fire TV v0.9.14](https://github.com/3dmqrk/lan-media-library-releases/releases/tag/v0.9.14) |
| **Fire TV — Funnel** | Tailscale Funnel 経由で Fire TV から接続 | 1.0.4 | [Fire TV Funnel v1.0.4](https://github.com/3dmqrk/lan-media-library-releases/releases/tag/v1.0.4) |

### 迷ったとき

- スマホで使うなら、普段の接続方法に合わせて **スマホ版 — Tailscale** または **スマホ版 — Direct / Funnel** を選びます。
- Fire TV を家の中だけで使うなら **Fire TV — LAN**、Funnel 経由で使うなら **Fire TV — Funnel** を選びます。
- スマホ版の APK は端末の CPU アーキテクチャ別です。一般的な近年の Android 端末は `arm64-v8a` を選んでください。Fire TV 版は各リリースにある APK を使います。

## アプリ内の更新確認

アプリの「更新を確認」は、そのアプリ専用の APK を確認します。更新が見つかると確認メッセージを表示し、承認後にダウンロードします。

## リリース履歴について

公開一覧には各アプリの現行版を掲載しています。以前のリリースは削除せず Draft に保管しており、通常のダウンロード一覧やアプリ内の更新確認には表示されません。