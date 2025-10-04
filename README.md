# shiftcrafter-weekly-2shift

ブラウザだけで動く、**二交代制（日勤/夜勤）の1週間シフト自動割当ツール**です。インストール不要・データ送信なし。

- デモ（GitHub Pages）：https://rehab-datascience.github.io/shiftcrafter-weekly-2shift/index.html
- リポジトリ：https://github.com/rehab-datascience/shiftcrafter-weekly-2shift

## 使い方
1. 上のデモURLを開く（PC推奨）
2. 週の開始日・必要人数・上限・看護師リストを入力
3. **「シフト自動作成」→「CSVダウンロード」**

## 出力結果について
本ツールは、割当結果を schedule_output.csv としてダウンロードします（UTF-8/BOM）。既定はWide形式で、各日に必要人数と配置された職員名を列で並べます。充足できない枠は空欄です。Excel/Googleスプレッドシートでそのまま閲覧・共有できます。分析用途ではLong形式（1行=1割当）の出力にも将来対応予定です。

## 免責
- 本ツールは**教育・業務補助**を目的としたクライアントサイドWebアプリです。  
- **データはブラウザ内のみで処理**され、外部サーバへ送信されません。  
- 利用による結果・損害について、作者は一切の責任を負いません。  
- 実運用は所属施設の規程・労務基準・個人情報保護方針に従ってください。

## ライセンス
MIT
