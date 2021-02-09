
# KFP工程組

## 分支

main - 主要開發者分支, 必須使用pull request
staging - 測試驗收用分支, 將由CI自動更新
release - 最新雲端版本, 將由CI自動更新

### 代碼合併流程
main -> staging -> release

## 檔案夾
python -> 利用python寫的代碼, 預設python 3.9.0

.circleci -> 利用CircleCI免費服務做成的CI (Continuous Integration: 持續整合)服務, 目前用來保證每個pull request都能通過測試並且能正常運行

