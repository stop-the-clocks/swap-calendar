SWAP CALENDAR v23
更新内容
- 証拠金OCR取込の整合性チェックを強化
- 預託証拠金 + 評価損益 = 有効証拠金を検証
- ポジション損益 + 未実現スワップ = 評価損益を検証
- 有効証拠金 ÷ 必要証拠金 × 100 = 有効比率を検証
- OCRで不整合がある場合、手動でチェックを入れても反映を拒否
- iPhoneを含む小画面で文字・入力欄・行の折返しと整列を改善
- 保存キー swap-calendar-v3 を維持（既存データ引継ぎ）
- PWAキャッシュを swap-calendar-v23 に更新
GitHub Pagesの同一フォルダに以下を配置してください：
index.html / sw.js / manifest.webmanifest / icon.svg / icon-192.png / icon-512.png / icon-maskable-512.png / apple-touch-icon.png
更新前にアプリ内JSONバックアップを保存してください。
