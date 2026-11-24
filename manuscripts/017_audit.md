# 第17講 品質監査

## 正本照合
- [x] 運用マスターv1.2、全18編224講のカリキュラム、進捗16/224を取得。
- [x] 正式タイトル「サーバ性能の基本指標とボトルネック」、次講第18講を照合。

## 技術監査
- [x] CPU使用率とロード、CPU平均と単一コア飽和を区別。
- [x] free/available、RSS、swap-in/out、major page fault、OOMを区別。
- [x] IOPSと転送帯域、awaitとSQL応答、%utilとNVMe飽和を区別。
- [x] ネットワーク帯域、RTT、パケット損失、p95を説明。
- [x] Linux Kernel Documentation『PSI - Pressure Stall Information』を確認。CPU fullの注意を記載。
- [x] Red Hat Enterprise Linux 10『Monitoring and managing system status and performance』のvmstat/iostat節を確認。
- [x] Oracle/JP1/NetBackup/Citrix固有の仕様は未照合と記載。
- [x] ログ・数値は架空、コマンド未実行、危険な負荷試験を勧めない。

## 独立読者理解監査
- [x] 専門語を初出で定義し、業務の遅さ→処理経路→観測値→仮説→対策の因果を説明。
- [x] 図2点の要素・矢印・軸・前提を本文で解説。
- [x] コマンドの実行環境、表示列の意味、注意点を明示。
- [x] CPU、メモリ、ディスクの障害例と対策の副作用を説明。
- [x] 自宅Docker3層ラボと実務製品へ接続。

## 問題品質
- [x] 四択10問、Q1–5各1点、Q6–10各2点。
- [x] 正解位置は分散、誤答も別条件で合理性があるよう設計。
- [x] 全選択肢を同程度の長さ・具体性に調整し、極端な断定語を誤答目印にしない。
- [x] 正解は回答前に非開示。

## 公開検証
原稿・監査・SVG・全文HTML・前講リンク・一覧を保存し、再取得一致を確認。GitHub Pagesのブラウザ表示は未確認。
