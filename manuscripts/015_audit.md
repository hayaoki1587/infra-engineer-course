# 第15講 独立品質監査（2026-11-23）

正本：運用マスターv1.2、カリキュラム全18編224講の正式第15講、進捗14/224を照合。

## 技術監査
- [x] UEFI Forum 2.11 Boot Manager、UEFI Forum FAQ、Microsoft Learn Secure Boot（2026年3月更新）の該当公開資料を実際に確認。
- [x] BIOSとUEFI、ファームウェアとOS、GPTとESP、UEFIとGRUBを区別。
- [x] POST→BootOrder→OS loader→kernel/initramfs→systemd→業務確認の因果を明示。
- [x] Secure Bootの範囲と限界、NVRAM、BootOrder、ESPを説明。
- [x] Apple Silicon Macの起動経路はx86 UEFI/GRUBと同一視しない。
- [x] Linuxコマンドは未実行。ディストリビューション固有動作・メーカーPOSTコードは未照合と明記。
- [x] ログは架空。危険な設定変更・ファームウェア更新を実施させない。

## 独立読者理解監査
- [x] 初出用語を日本語で説明し、OS起動と業務起動を区別。
- [x] 起動フローと故障段階のSVG図を使い、各矢印を本文で説明。
- [x] POST・UEFI・カーネル・DBの症状を対比して初動を示す。
- [x] 架空ログの事実と未確定の原因を区別。
- [x] Oracle/JP1/NetBackupと自宅3層Dockerラボへ接続。

## 理解度チェック監査
- [x] 基礎5問各1点、応用3問各2点、障害・設計2問各2点。
- [x] 各問の一意性、誤答の適用条件、正答位置の偏りを確認。

## 公開・保存検証
原稿・監査・図・HTML・一覧・ナビの保存後に再取得一致検証を行う。GitHub Pagesの実ブラウザ表示は未確認。
