# Skill 格式與可攜性

本頁是對 Agent Skills 官方格式的簡短改寫說明，不是規格全文。其餘本包的工作流程與模板為獨立原創。

一個 Skill 可以用資料夾組織，入口為 SKILL.md。該純文字檔以 YAML 前置欄位描述 name 與 description，後方放工作指引。格式允許額外參考資源；本包刻意只放文字，不附腳本或可執行資源。

本包的兩個名稱使用小寫英文字、數字與連字號，與資料夾一致。工具是否支援自動探索與延遲載入，由各工具實作決定；本包通用讀取方式仍為顯式讀檔或手動提供文字。

格式可攜不等於工具可攜。工具名稱、權限與執行器不能因為複製 SKILL.md 就一併取得。

出處與授權：Agent Skills contributors，Specification，https://agentskills.io/specification ，查閱日期 2026-11-15。[來源 S-01](../governance/SOURCES.md)。本頁以繁體中文改寫並精簡，適用 CC BY 4.0；授權連結 https://creativecommons.org/licenses/by/4.0/ ，[離線授權全文](../licenses/CC-BY-4.0.txt)。無官方背書。這是格式說明的授權，不把第三方產品或軟體授權改為 CC BY。
