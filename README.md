# live-CC 安裝版發布專屬 repo

本 repo 僅用於發布 live-CC 的安裝版（MSI）與 GPU 預建庫（gpu-libs.zip），不含原始碼。

- **原始碼**：https://github.com/qwer2415wy/tools（`live-cc` 分支）
- **授權伺服器**：https://sun-tw.com/tools/live-cc
- **下載安裝版**：https://github.com/qwer2415wy/live-cc/releases

## 發布流程

1. 在 `qwer2415wy/tools` 的 `live-cc` 分支推 `v*` tag
2. GitHub Actions 自動 build MSI 並發布到本 repo 的 Releases
3. GPU 預建庫更新時，在 tools repo 根目錄執行 `tools/upload-gpu-libs.sh` 上傳 gpu-libs.zip
