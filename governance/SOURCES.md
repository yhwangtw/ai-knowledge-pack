# 公開官方來源與授權登錄

編製／核對日期：2026-11-15。這是本次製作時查閱的書目與短摘要，離線使用不需要開啟網址。未鏡像任何官方網站，也不保證動態頁面將來內容不變；來源 URL 的 main／網頁版本可能更新，不視為永久鎖版。

所有工作流程、PRD、架構評估、模板、測試、虛構情境與計算，除明確標示之處外，均為本包獨立編寫，不是從官方模板翻譯或複製。沒有下載或分發模型、套件、映像及供應商 SDK。

## S-01：Agent Skills 格式

- 作者／發布者：Agent Skills contributors。
- 標題：Specification。
- 內容：https://agentskills.io/specification
- 官方專案：https://github.com/agentskills/agentskills
- 文件授權證據：https://github.com/agentskills/agentskills/blob/main/docs/LICENSE
- 授權：docs 文件為 CC BY 4.0；官方專案程式碼另採 Apache-2.0，不能把程式碼與文件授權混為一談。
- 使用範圍：[knowledge/04-skill-format.md](../knowledge/04-skill-format.md) 對資料夾、SKILL.md 與前置欄位作短篇繁體中文改寫。未複製官方範例或程式。該頁單獨標 CC BY 4.0 並註明改寫；兩個工作 Skill 的程序與模板為本包原創。
- 離線授權副本：[CC BY 4.0](../licenses/CC-BY-4.0.txt)。
- 來源版本：查閱當日公開規格，未鎖定 commit；本包只依最低限度格式，不依賴自動探索。

## S-02：Nexus repository 類型

- 發布者：Sonatype。
- 標題：Repository Types。
- 內容：https://help.sonatype.com/en/repository-types.html
- 頁面可見最後修改日期：2026-05-13；查閱日 2026-11-15。
- 授權狀態：頁面顯示 © 2026 Sonatype；本次未確認文件全文的公開再散布授權。不能從產品軟體或程式碼授權推論文件授權。
- 使用範圍：[knowledge/02-offline-enterprise.md](../knowledge/02-offline-enterprise.md) 只以本包語句說明 hosted／proxy／group 的一般角色；不複製官方段落、表格、圖片、操作指令或完整頁面。
- 衍生建議：完整相依項、缺件阻擋與匯入檢核是本包建議，不宣稱官方強制規範或公司現況。產品版本、edition、repository 格式與實際權限必須另核對。
- 再散布處置：本包不包含 Sonatype 文件副本；日後要加入全文，須先取得或確認適用授權。

## S-03：Harbor 離線 installer 的範圍

- 發布者：Harbor project／goharbor。
- 標題：Download the Harbor Installer，Harbor docs 2.14.0。
- 內容：https://goharbor.io/docs/2.14.0/install-config/download-installer/
- 官方網站來源授權：https://github.com/goharbor/website/blob/main/LICENSE
- 授權證據：網站原始碼 repository 的 LICENSE 為 Apache License 2.0；公開頁面及第三方素材仍應逐項核對，不能延伸為所有依賴或產品商標授權。
- 使用範圍：[knowledge/02-offline-enterprise.md](../knowledge/02-offline-enterprise.md) 只短述 offline installer 含預建 Harbor 映像的功能界線；未轉載官方文章、指令、截圖、程式或映像。
- 本包建議：獨立盤點工作負載映像、digest、平台與掃描資料；這些是本包設計建議，不等同官方安裝程序。
- 版本：只參考指定 2.14.0 文件，不表示推薦安裝此版本，也不宣稱其為最新或適合公司的版本。
- 離線授權參考副本：[Apache 2.0](../licenses/APACHE-2.0.txt)，供核對來源條款，不表示本包包含 Harbor 軟體。

## S-04：風險管理高層概念

- 發布者：National Institute of Standards and Technology（NIST）。
- 標題：AI RMF Core，摘自 AI Risk Management Framework 1.0（2023）。
- 內容：https://airc.nist.gov/airmf-resources/airmf/5-sec-core/
- 版次：AI RMF 1.0（2023）；查閱時官網另提示修訂進行中，本包沒有套用未發布修訂。
- 授權／使用聲明：https://www.nist.gov/open/copyright-fair-use-and-licensing-statements-srd-data-software-and-technical-series-publications
- 狀態：NIST 員工著作在美國通常不受著作權保護；官方對技術系列的海外權利與重刊另有聲明，第三方作品可能另有權利。不能籠統寫成「NIST 所有內容全球公有領域」。
- 使用範圍：[knowledge/03-evidence-and-risk.md](../knowledge/03-evidence-and-risk.md) 只以自身語句提及四個風險管理面向與持續治理的概念；未重刊報告、圖表、分類清單、評分或認證條件。所有具體風險表與驗收門檻是本包建議。
- 本包不是 NIST 認證、稽核結論或官方建議書。

## S-05：本包授權所用文本

- MIT 授權標準文本：https://opensource.org/license/mit
- CC BY 4.0 授權全文：https://creativecommons.org/licenses/by/4.0/legalcode.txt
- Apache 2.0 授權全文：https://www.apache.org/licenses/LICENSE-2.0.txt
- 使用範圍：MIT 文本用於 [LICENSE.txt](../LICENSE.txt)；另兩份保存於 licenses，讓接收者離線閱讀第三方授權。授權文本是條款副本，不是產品內容或工具。
- 這些授權不替未提供的模型、套件、商標、私有資料或未獲授權素材授權。

## 更新來源時

由維護角色在公司核准環境核對來源、版次、授權與適用範圍，保留必要證據，修改 CHANGELOG，重新驗證與審查。隔離環境不自動刷新來源，也不因本頁含網址而自動連線。

## S-06：依使用者指定的 Anthropic 固定版本授權查核

- 發布者：Anthropic／anthropics/knowledge-work-plugins。
- 指定 commit：e91a134584eb798bac7fb0379358006a2b63b965。
- 查核檔案：https://github.com/anthropics/knowledge-work-plugins/blob/e91a134584eb798bac7fb0379358006a2b63b965/LICENSE
- 查閱日期：2026-11-15。
- 觀察：該檔含 Apache License 2.0 條款；末尾另有非標準文字。本包未把這些尾段文字納入或當作額外授權，也未以該檔替原創內容授權。
- 使用方式：僅依使用者指定作來源與授權核對；本包的 PM／架構 Skill、模板與測試均自行撰寫，沒有複製、翻譯或改寫該 repository 的 Skill、模板或程式。不宣稱是 Anthropic 官方或衍生發行包。
- 已隨包保存標準 [Apache 2.0 全文](../licenses/APACHE-2.0.txt)。因未移植該 repository 內容，沒有需附在兩個原創 SKILL.md 上的上游作者或修改標記；本包作者與版本修改見 [第三方聲明](THIRD-PARTY-NOTICES.md) 與 [CHANGELOG](CHANGELOG.md)。
- 未來若移植上游內容：先檢查該檔與相鄰素材的實際授權／NOTICE，保留適用 Apache 2.0、作者／權利通知，在修改檔明示來源 commit、修改日期及內容；不可直接把其內容改標本包 MIT。
