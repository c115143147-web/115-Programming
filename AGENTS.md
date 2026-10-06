# AGENTS.md

## 通用規定
- 所有回應都使用繁體中文。
- 專案所使用的程式語言為 Python。
- 使用 conda 管理 Python 套件。
- Conda 環境名稱為 `iem_python`。

## Verified state
- Python 專案：使用預設 Python `.gitignore`（尚無其他工具設定）。
- 追蹤檔案：`README.md`、`LICENSE`、`.gitignore`。
- Branch：`main`（已追蹤 origin）。
- 初始提交：`3bc7d9b`。

## Working with this repo
- 視為綠地（greenfield）Python 課程專案。尚無 build、test、lint、typecheck 或其他開發指令。
- 不要自行新增指令或設定檔；如果新增程式碼時需要最小化的工具設定，請同時在本檔記錄正確的執行指令。
- 新增程式碼前，先檢查是否存在 `AGENTS.md`、`CLAUDE.md`、`.cursor/rules/`、`.cursorrules`、`.github/copilot-instructions.md` 或 `opencode.json`，避免假設慣例。

## Quick sanity checks
- 執行 `git status --short`，避免誤改動不相關檔案。
- 若未來新增課程結構（week/exercise 等），且有必要指定執行順序或限定範圍的指令，再更新本檔；不需要記錄顯而易見的操作。
