# トンボ大戦（Dragonfly Wars）

キューブで組まれた街や森を、トンボ型ロボで飛び回る3D空中バトルゲームです。
ブラウザですぐ遊べます（インストール不要・PC／スマホ対応）。

▶ **今すぐ遊ぶ：https://taigayanai-git.github.io/tombo-taisen/**

## 特徴
- 体当たりで撃墜数を競うバトル（背後からの一撃は「奇襲」でダメージ1.5倍）
- 分身・スロー空間・ライトニングなどのアイテム、ステージに出現する「神器」
- 9つのステージ、40種類以上のアバター
- CPU戦・オンライン対戦（ルームコードで友達と対戦）・チーム戦

## 操作
| | PC | スマホ |
|---|---|---|
| 方向転換 | マウス | 画面をドラッグ |
| ダッシュ | 左クリック / Shift | DASH |
| 急停止 | 右クリック / F | STOP |
| アイテム | E | ITEM |
| ターン | Q | TURN |
| 神器 | R | 神器ボタン |

スマホはホーム画面に追加すると、アプリのように全画面で遊べます。

## ファイル構成
| ファイル | 内容 |
|---|---|
| `index.html` | ゲーム本体 |
| `rhythm_prism.mp3` / `lounge_jazz.mp3` | BGM（バトル／メニュー） |
| `og.png` | リンク共有時の画像 |
| `icon-*.png` / `manifest.webmanifest` | ホーム画面用アイコンと設定 |
| `THIRD_PARTY_NOTICES.txt` | 使用しているオープンソースのライセンス表記 |

## クレジット
- 3D描画：[three.js](https://threejs.org/)（MIT License）
- オンライン接続：[Trystero](https://github.com/dmotz/trystero)（MIT License）

© 2026 TaigaYanai
