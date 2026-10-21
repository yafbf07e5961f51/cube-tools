# Cube Tools

ルービックキューブ練習用のWebツール集。

| ツール | パス | 内容 |
|---|---|---|
| EO Trainer | `/eotrainer/` | 選択したエッジから2本を反転させた状態のスクランブルを生成し、タイムを計測する |
| FTO LBT Trainer | `/fto-lbt/` | FTOのLBT練習用トレーナー（スクランブルはcsTimerで事前生成） |
| Sq1 EP Trainer | `/sq1ep/` | Square-1で、選択したEPケース（U層×D層の組み合わせ）のスクランブルを生成し、タイムを計測する |

## ローカルで使う

各フォルダの `index.html` をブラウザで開くだけで動作します（外部ファイルへの依存なし）。

## クレジット・ライセンス

EO Trainer のスクランブル生成には [csTimer](https://github.com/cs0x7f/cstimer) の `min2phase.js`（3x3x3ソルバ）を、Sq1 EP Trainer には `scramble_sq1_new.js`（Square-1ソルバ）を使用しています。FTO LBT Trainer のスクランブルは csTimer で生成したものです。
csTimer は GNU General Public License v3.0 で公開されているため、本リポジトリも GPL-3.0 で公開します。詳細は [LICENSE](LICENSE) を参照してください。
