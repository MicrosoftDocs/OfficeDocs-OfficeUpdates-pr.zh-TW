---
title: Beta 版通道的版本資訊
ms.author: anankani
author: anankani
manager: anankani
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: 為「測試人員 - 快」對象提供新功能、修正或已知問題的最新清單
ms.openlocfilehash: 06051d34b4c3537f0b6f957cdb4d681297390cc5
ms.sourcegitcommit: 387e4010f06f33bc9b100ed4fa2ced2598d3b167
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 07/10/2021
ms.locfileid: "53364080"
---
# <a name="release-notes-for-beta-channel"></a>Beta 版通道的版本資訊

本文包含 Word、Excel、PowerPoint、Outlook、Access 和適用於 Windows 電腦的 Project 的 Beta 版通道組建版本資訊。 每週，我們都會強調有趣的新功能、重要修正，以及我們想讓您知道的重大問題。 請注意，我們通常每隔一段時間會推出 Beta 版通道新功能 (某些時候還有修正)。 這樣可讓我們確保功能都運作順利，然後才推出給更廣泛的對象。 因此，如果您沒有在以下描述的內容中看到某些項目，請不用擔心，您最終還是會看到它。  

> [!IMPORTANT]
> 我們會變更 Microsoft 365 應用程式的更新通道，包括新增新的更新通道 (每月企業通道)，並變更現有的更新通道名稱。 如需深入了解，[請閱讀本文](/DeployOffice/update-channels-changes)。

> [!NOTE]
> - 版本資訊會每週發佈，可能是多個組建的編譯。
> - 版本資訊發佈日期可能與實際組建發行日期不相符。

[//]: # (DO NOT REMOVE)

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

## <a name="version-2108-july-09"></a>版本 2108：7 月 09 日
*版本 2108 (組建 14301.20004)*


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="outlook"></a>Outlook

- **關閉建議回覆：** Outlook [使回覆更為簡單快速](https://insider.office.com/blog/reply-faster-using-suggested-replies-in-outlook) 透過提供僅需幾個字回覆的簡短建議回覆郵件，讓回覆電子郵件更為快速。 部分使用者可能不想看到此選項，因此現在可以關閉此功能。 若要這麼做，請選取檔案 > 選項> 郵件，前往回覆和轉寄區段，然後清除顯示建議的回覆核取方塊。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 我們已修正當來源 .xlsx 檔案已在背景執行，且兩個檔案都是從 ODB 本地同步處理資料夾開啟時，PowerPoint 連結檔案無法使用的問題。


- 我們已修正開啟 CSV 檔案時，現在可以識別當地語系化函數名稱的問題。


### <a name="word"></a>Word

- 我們已修正 Word Mobile 中與列印尺寸太小相關的問題。


- 我們已修正新增到 SharePoint 文件庫的檔案在開啟後立即繼承設定「ShowDocument 資訊面板」的問題，如果檔案從 SharePoint 中移除，它也會保留。


- 我們已修正 URL 剖析器不正確地解譯未以「/」 結尾的資料夾名稱的問題。


### <a name="office-suite"></a>Office 套件

- 我們已修正在搜尋方塊上新增 DropShadow 屬性時，導致標題列太高，導致版面配置錯誤的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2107-july-02"></a>版本 2107：7 月 02 日
*版本 2107 (組建 14228.20044)*


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **另存新檔案例支援的其他檔案類型：** 除了儲存檔案之外，您還可以將檔案儲存到其他檔案類型。

### <a name="outlook"></a>Outlook

- **REST 轉寄會議要求：** 允許使用者轉寄先前拒絕的 REST 共用日曆會議。

- **大聲朗讀功能變得更好：** 大聲朗讀工具列提供全新、聽起來很自然的語音選項

### <a name="powerpoint"></a>PowerPoint

- **另存新檔案例支援的其他檔案類型：** 除了儲存檔案之外，您還可以將檔案儲存到其他檔案類型。

### <a name="word"></a>Word

- **使用您的語音搜尋：** 點一下或按一下搜尋欄中的麥克風，以在 Word 中使用您的聲音來尋找命令、內容等等。

- **大聲朗讀的更自然語音選項：** 在大聲朗讀工具列中試用全新、更自然的聲音。 [深入了解](https://support.office.com/article/5a2de7f3-1ef4-4795-b24e-64fc2731b001)

- **另存新檔案例支援的其他檔案類型：** 除了儲存檔案之外，您還可以將檔案儲存到其他檔案類型。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 我們已修正 CFR 執行發生例外情況的問題。


### <a name="outlook"></a>Outlook

- 我們已修正導致某些使用者的翻譯選項遭到停用的問題。  遇到此錯誤的客戶在瀏覽至檔案 -> 選項 -> 語言時，會看見其翻譯選項已遭停用。 有鑑於此，他們可能無法變更其偏好的翻譯語言和其他翻譯相關設定。


- 我們已修正與「無法載入」回應狀態相關的問題。 預設的回應標幟已設定為「無」。 將游標停留在我們沒有編輯權限的行事曆上，無法在 UI 中顯示任何字串。


- 我們已修正預設的文字放大包含了文字縮放比例的問題，因此不需要再呼叫 LayoutChanged。


- 我們已修正單次位址的寄件提醒未顯示的問題。


- 我們新增了一個登錄機碼，允許語音信箱表單在 Outlook 電腦版 UI 中顯示，因為 Exchange Online 中的 Unified Messaging 中止服務 (https://techcommunity.microsoft.com/t5/exchange-team-blog/retiring-unified-messaging-in-exchange-online/ba-p/608991)。 對於想要語音信箱表單顯示的使用者、企業和組織，必須設定下列登錄機碼： [HKEY_CURRENT_USER\SOFTWARE\Microsoft\Office\Outlook\Addins] "AllowVoicemailForm"=dword:00000001


### <a name="word"></a>Word

- 我們修正了改善 Word 和 JAWS 中新註解窗格的整合，這是一種熱門的螢幕助讀軟體。


- 我們已修正使用與 lTagNil 不同的 CommentId 進行清除選取和醒目提示的問題。


- 我們已修正未上傳佇列變得沒有回應的問題。


### <a name="office-suite"></a>Office 套件

- 我們已修正 en-gb、fr-ca 和 es-mx 現在會與各自的父版本相符的當地語系化問題。


- 我們已修正 OMEX 與 ExCatalog 之間無法再共用設定的問題，例如建立了新 webextension 檔案之後，Web 增益集設定會更新至 webextension.xml。 只有在以原始方法部署該增益集，或將新的解決方案參考比較關閉時，才能存取前一個。



[//]: # (請勿移除 BUGDETAILS 內容尾)

## <a name="version-2107-june-25"></a>版本 2107：6 月 25 日
*版本 2107 (組建 14217.20002)*


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 我們已修正如果千位和小數分隔符號都使用相同的符號，圖表座標軸值無法變更的問題。


### <a name="powerpoint"></a>PowerPoint

- 我們已修正與 SmartArt 節點停用 [變更圖形] 功能相關的問題。


### <a name="project"></a>Project

- 我們已修正如果資源名稱具有特殊字元 (例如分號)，在 Project Web App 中建立之約定可能無法在 Project 桌面用戶端中正確載入的問題。


- 我們已修正當停用專案選項「專案應該計算成本」時，然後時間階段性成本值可能尚未正確地為成本型資源設定基準的問題。


- 我們已修正具有查詢表格的專案層級企業自訂欄位未在 Project 桌面用戶端中顯示值的問題。


- 我們已修正將本機專案儲存至 Project Web App 會變更先前已儲存的基準問題。


### <a name="word"></a>Word

- 我們已修正啟用自動儲存會導致最新的編輯暫時消失的問題。


- 我們已修正註解窗格中捲動的問題。


- 我們已修正當 Office 佈景主題設定為黑色時，在預覽列印中無法清楚顯示標頭/頁尾文字的問題。


### <a name="office-suite"></a>Office 套件

- 我們已修正在 Outlook 中使用從右至左書寫的語言撰寫郵件時，含有數字的超連結會中斷的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2107-june-18"></a>版本 2107：6 月 18 日
*版本 2107 (組建 14210.20004)*


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="outlook"></a>Outlook

- **上次登入/可疑的登入：** Outlook 現在會告知您上次登入帳戶的時間及位置，並警示您是否偵測到任何可疑的登入活動

- **在干擾較少的情況下閱讀訊息：** 開啟沈浸式閱讀程式，以自訂文字間距、頁面色彩、欄寬和行聚焦，讓您更輕鬆地專注於訊息。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 修正可能導致使用 Access 資料庫引擎 OLEDB API 的應用程式搭配的資料庫包含 SharePoint 清單連結時，會意外關閉的問題。

- 修正可能導致使用 Access 資料庫引擎 ODBC API 的應用程式意外關閉的問題。

### <a name="word"></a>Word

- 我們已修正註解在共同作業期間變成唯讀的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2107-june-11"></a>版本 2107：6 月 11 日
*版本 2107 (組建 14204.20006)*


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 已修正部分使用者在 Excel 增益集清單中顯示額外項目的問題。


- 我們已修正在儲存至 SPO 文件庫時，儲存的活頁簿會顯示在最近清單頂端的問題。


### <a name="onenote"></a>OneNote

- 我們已修正在複製段落連結時，不一定會重新導向到正確頁面的問題。


### <a name="word"></a>Word

- 我們已修正使用 Microsoft Word Paper 增益集時出現方塊的問題。


- 我們已修正預覽列印中的部分頁面為空白的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2106-june-04"></a>版本 2106：6 月 04 日
*版本 2106 (組建 14131.20008)*


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **資料類型偵測設定：** 在 Excel 中使用Power Query 從未結構化來源匯入資料時，設定資料類型偵測行為


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="powerpoint"></a>PowerPoint

- 我們已修正確保使用匯流排的‘重試儲存’按鈕儲存的檔案會新增至 [最近的清單] 的問題。


### <a name="word"></a>Word

- 我們已修正當特殊字元旋轉 90 度時，特殊字元的間距增加問題。


- 我們已修正多位使用者在共同撰寫時，有時會遺失註解回覆的問題。


### <a name="office-suite"></a>Office 套件

- 我們已修正 CLP 功能先前導致了自動儲存至 SyncBacked 檔案 (由 OneDrive 同步檔案) 的問題。


- 我們已修正使用者無法編輯儲存於 OnPrem 伺服器中的檔案問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2106-may-28"></a>版本 2106：5 月 28 日
*版本 2106 (組建 14122.20004)*


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="outlook"></a>Outlook

- **組織總管：** 檢視並瀏覽組織結構。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel
- 我們已從 Range.valueTypes 移除 "RichValue"。 [連結的資料類型] 現在會傳回 "Error"，以符合 "#VALUE!" 的值 由 Range.values 傳回。
### <a name="outlook"></a>Outlook

- 我們已修正使用者無法在「非商務」授權 Outlook 版本中跨資料夾移動項目的問題。


- 此登錄機碼會停用新會議室尋找工具體驗 (與 Outlook 網頁版相同的體驗)，並啟用具有建議的時間的傳統會議室尋找工具。

  登錄機碼:
  
  > HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Options\Calendar </br>
  > REG_DWORD “ShowLegacyRoomFinder”</br></br>
  > 0 (預設值) - 當使用者按一下 [會議室尋找工具] 按鈕以搜尋可用的會議室時，Outlook 會使用新會議室尋找工具 OWA 提供的體驗  </br>
  > 1 - Outlook 使用舊版會議室尋找工具 UI 來搜尋可用的會議室</br>


### <a name="project"></a>Project

- 我們已修正手動排程工作上的指派可能會移至不正確日期的問題。


- 我們已修正資源資料庫沒有回應且無法開啟的問題。


- 我們已修正當您建立使用具有特定日期或時間參數之 ProjectDate */ProjectDur* 函數的自訂欄位公式時，產生錯誤的問題。


### <a name="word"></a>Word

- 我們已修正將文件匯出為 PDF 時，某些註解未儲存的問題。


- 我們已修正在套用 [限制編輯] 時，於文件未受保護的區域中無法編輯新註解的問題。


- 我們已修正不需要的捲動動畫相關的問題。


- 我們已修正導致註解窗格意外關閉的問題。


- 我們已修正導致 [編輯器] 窗格佈景主題與系統佈景主題不一致的問題。


- 我們已修正與處理大型文件相關的效能問題。



[//]: # (請勿移除 BUGDETAILS 內容結尾)

## <a name="version-2106-may-21"></a>版本 2106：5 月 21 日
*版本 2106 (組建 14117.20000)*


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="outlook"></a>Outlook

- **上次登入/可疑的登入：** Outlook 現在會告知您上次登入帳戶的時間及位置，並警示您是否偵測到任何可疑的登入活動


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 我們已修正在 RealTimeData 函數參照時，會導致動態陣列無法更新儲存格值的問題。


- 我們已修正在填滿大量資料時，會影響 VLOOKUP 和 INDEX/MATCH 效能的問題。


- 我們已修正使用凍結窗格時，與使用雙指捲動相關的問題。


- 我們已修正在大型印表機上列印時，記憶體不足的相關問題。


### <a name="powerpoint"></a>PowerPoint

- 我們已修正在唯讀模式中，會導致無法從演講者備忘稿窗格複製的問題。


### <a name="word"></a>Word

- 我們已修正即使在使用者選擇捨棄變更之後，還是顯示另存新檔錯誤訊息的問題。


- 我們已修正會使得影像無法在新式註解中張貼的問題。


- 我們已修正檢閱窗格可能會捲動或似乎捲動，但未與選取的註解一致的問題。


- 我們已修正在按一下新建立的註解外部時，會導致文件中的選取範圍無法清除的問題。


- 我們已修正選取註解時，註解不會強調顯示的問題。


- 我們已修正在執行巨集時，如果已套用編輯限制，會將錯誤的欄位更新的問題。


- 我們已修正部分 Word 檔案因為書籤損毀而無法開啟的問題。


### <a name="office-suite"></a>Office 套件

- 我們已修正使用不同帳戶來登入可能會導致當機的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2106-may-14"></a>版本 2106：5 月 14 日
*版本 2106 (組建 14107.20000)*


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 我們已修正以下問題：在 [僅下載標題] 模式下執行時，使用者看到可行動的訊息在下載後不斷重新整理或回復為標題。


- 我們已修正導致 Outlook 中的人員選擇器針對擁有永久授權的使用者向上展開，而不是向下展開的問題。


- 我們已修正導致自訂網域使用者在將連結貼到電子郵件時，看到權限警告訊息的問題。


### <a name="word"></a>Word

- 我們已修正按下 ctrl + shift + @ 等按鍵組合時，不會產生預期的重音符號 (在此案例中為 'å') 的問題。


- 我們已修正與影像壓縮相關的問題。


- 我們已修正如果檔案名稱包含 DBCS 字元，將郵件附件複製到 Word 之外的應用程式會失敗的問題。


- 我們已修正 Word 有時會在應該不存在的文字周圍顯示邊框的問題。


### <a name="office-suite"></a>Office 套件

- 我們已修正當確實沒有合併衝突時，OneDrive 會顯示合併錯誤訊息的問題。


- 我們已修正 SVG 物件轉換成圖形時 Z 順序的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2106-may-07"></a>版本 2106：5 月 7 日
*版本 2106 (組建 14029.20000)*


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 修正了阻止名稱管理員開啟包含大量隱藏名稱之書籍的問題。


### <a name="outlook"></a>Outlook

- 修正了導致使用者看到所有寄件備份複本出現在其寄件匣資料夾中的問題。


- 修正了在其他版本 Windows 中使用大聲朗讀功能時導致 Outlook 意外關閉的問題。


### <a name="word"></a>Word

- 修正了在其他版本 Windows 中使用大聲朗讀功能時導致 Word 意外關閉的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2105-april-30"></a>版本 2105：4 月 30 日
*版本 2105 (組建 14026.20000)*


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="outlook"></a>Outlook

- **將電子郵件傳送給大型 DL、外部使用者時，協助工具檢查程式會進行微調：** 我們新增了功能，以在撰寫電子郵件給大量對象、外部使用者等時，透過郵件提示自動收到協助工具違規的提示。這些設定放在輕鬆存取中

### <a name="visio"></a>Visio

- **AWS 樣版和圖形：** 我們現在的樣版包含最新的 AWS 圖形，可協助您建立圖表。 [深入了解](https://support.office.com/article/138206bf-d10f-4583-9f31-885ce706af49)

### <a name="word"></a>Word

- **寫作目標：** WinWord 的寫作目標


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 我們已修正在 [註解] 窗格中的註解間移動時，會導致 Excel 意外關閉的問題。


- 我們已修正在使用增益集時，會導致某些語言的日期格式顯示不正確的問題。


- 我們已修正在某些情況下，使用選擇性貼上搭配格式時可能會導致 Excel 意外關閉的問題。


### <a name="project"></a>Project

- 我們已修正透過規劃精靈完成的變更不一定會由變更事件擷取的問題。


- 我們已修正使用者無法從資源資料庫移除專案的問題。


### <a name="word"></a>Word

- 我們已修正在移除超連結後，文字格式仍會保留的問題。


- 我們已修正在依人員篩選後，不會顯示註解的問題。


- 我們已修正 Word 無法使用 Access 資料庫執行合併列印的問題。


- 我們已修正摺疊文件中邊緣的功能，會導致包含可供使用的多個欄位的問題。


- 我們已修正當文件中有註解時，表格儲存格中某些字元無法正確顯示的問題。


- 我們已修正在啟用 AIP 增益集的情況下儲存文件時，會發生檔案格式變更的問題。


- 我們已修正在編輯欄位時 Word 會變得沒有回應的問題。


- 我們已修正使用命令 (而不是 CTRL+S 鍵盤快速鍵) 來儲存文件時，系統不會提示使用者儲存文件的問題。


- 我們已修正將檔案上傳到 SharePoint Online 之後，敏感度標籤會從 Word 中的檔案消失的問題。


### <a name="office-suite"></a>Office 套件

- 我們已修正將註解新增至文件時，會導致 [聽寫] 按鈕對齊不當的問題。


- 我們已修正長時間使用高對比模式會導致 Outlook 意外關閉的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2105-april-23"></a>版本 2105：4 月 23 日
*版本 2105 (組建 14014.20002)*


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **從動態陣列匯入資料**：您現在可以從目前活頁簿中的動態陣列中，匯出、連結及重新整理資料。 [深入了解](https://support.office.com/article/205c6b06-03ba-4151-89a1-87a7eb36e531)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 我們已修正支援舊版 Excel 的回溯相容性的問題。此問題可能會導致於較新版 Excel 中儲存的檔案無法正確載入舊版 Excel，因為自 Office 2007 之後已將 IFERROR 和 XLOOKUP 等函數新增至 Excel。


- 我們已修正某些檔案偶爾無法以受保護的檢視開啟的問題。


- 我們已修正導致狀態列未針對某些使用者指出就緒狀態的問題。


### <a name="outlook"></a>Outlook

- 我們已修正在代表另一個使用者進行傳送，並且針對非全域通訊清單的通訊錄進行解析時，造成名稱解析失敗的問題。


### <a name="word"></a>Word

- 我們已修正使用從右至左語言時，在註解中裁剪預留位置文字的問題。


### <a name="office-suite"></a>Office 套件

- 我們已修正在 Outlook 中以從右至左語言撰寫郵件時，包括數字的超連結會中斷的問題。


- 我們已修正某些可縮放向量圖形 (SVG) 無法正確轉譯的問題。



[//]: # (請勿移除 BUGDETAILS 內容結尾)

## <a name="version-2105-april-16"></a>版本 2105：4 月 16 日
*版本 2105 (組建 14007.20002)*


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 我們修正了在 64 字元 Windows 上使用 32 字元 Office 時導致 Excel 當機的問題。


- 我們已修正導致 [朗讀程式] 錯誤讀取 [版面設定] 對話方塊中 [頁首/頁尾] 索引標籤上兩個按鈕的内容之問題。


### <a name="powerpoint"></a>PowerPoint

- 我們已修正與連結圖片相關的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2105-april-09"></a>版本 2105：4 月 9 日
*版本 2105 (組建 14002.20000)*


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **[協助工具] 功能區：** 在一個地方找到建立無障礙內容所需的所有工具 - [協助工具] 功能區！

### <a name="word"></a>Word

- **校訂現在可用於文件中的已選取文字：** 有了這些變更，您現在可以僅檢閲已選取文字的拼字、文法和其他智慧型撰寫建議。 此外，您還可以檢閲對整個文件的建議。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

## <a name="version-2104-april-02"></a>版本 2104：4 月 2 日
*版本 2104 (組建 13929.20016)*


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="outlook"></a>Outlook

- **Windows 的 Outlook 中的建議回覆：** 當您收到可以簡短回覆的電子郵件訊息時，Outlook 可以建議三個回應，只要按幾下滑鼠即可回覆。

- **開啟共用行事曆改良功能：** 針對 Office 365 中的共用行事曆，Outlook 可以使用 REST API 更新這些行事曆。 開啟預覽，以更快速且更可靠地更新共用行事曆。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 我們已修正當外部應用程式要求協助工具介面時，它會防止我們關機，直到它們釋出其參考為止的問題。


### <a name="word"></a>Word

- 在此錯誤中，Office 未遵守特定原則 (在首頁上顯示了一組範本，但它們應該已遭到停用)。透過此修正，將會遵守原則。


- 我們已修正 [自動儲存] 中的問題。


- 我們在 Application.OnTime 中修正了可能無法正確觸發的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2104-march-26"></a>版本 2104：3 月 26 日
*版本 2104 (組建 13919.20002)*


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 我們已修正導致某些使用者在同步處理資料夾階層變更時遇到 Outlook 意外關閉的問題。


### <a name="word"></a>Word

- 我們已修正貼上文字中的複製和貼上樣式可能不同的問題。


### <a name="office-suite"></a>Office 套件

- 已修正與文字反覆項目相關的效能問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2104-march-19"></a>版本 2104：3 月 19 日
*版本 2104 (組建 13913.20000)*


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 此變更可修正在某些情況下，執行 SQL Server 傳遞查詢時，可能會導致錯誤訊息指出「無效的 Cursor 狀態」的問題。


### <a name="excel"></a>Excel

- 我們已修正會導致無法以公式形式貼上到受保護工作表的問題。


### <a name="project"></a>Project

- 已修正如果日期格式為 W4/4，日期選擇器可能會顯示錯誤的日期和年份的問題。


### <a name="office-suite"></a>Office 套件

- 已修正在 Office 中支援 GDI+ LineJoinMiterClipped 的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2104-march-12"></a>版本 2104：3 月 12 日
*版本 2104 (組建 13906.20000)*


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="powerpoint"></a>PowerPoint

- **在 PowerPoint 中插入 Flipgrid 影片：** PowerPoint 現在支援在投影片中插入 Flipgrid 影片。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 我們已修正當檔案儲存為 PDF 文件時，使用 [超連結] 函數所建立的超連結無法運作的問題。


### <a name="word"></a>Word

- 我們已修正共同撰寫時的註解問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2103-march-05"></a>版本 2103：3 月 5 日
*版本 2103 (組建 13901.20036)*


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **自動儲存並在敏感性加密文件上進行共同撰寫：** 不要為了安全性而犧牲生產力。 有了 Microsoft 資訊保護，使用敏感度標籤加密的文件現在可以自動儲存，並與他人進行即時共同撰寫，就彷彿文件未加密一樣便利。 需要租用戶選擇加入 (詳細資訊： https://aka.ms/mipcoauth)。

### <a name="powerpoint"></a>PowerPoint

- **自動儲存並在敏感性加密文件上進行共同撰寫：** 不要為了安全性而犧牲生產力。 有了 Microsoft 資訊保護，使用敏感度標籤加密的文件現在可以自動儲存，並與他人進行即時共同撰寫，就彷彿文件未加密一樣便利。 需要租用戶選擇加入 (詳細資訊： https://aka.ms/mipcoauth)。

### <a name="word"></a>Word

- **自動儲存並在敏感性加密文件上進行共同撰寫：** 不要為了安全性而犧牲生產力。 有了 Microsoft 資訊保護，使用敏感度標籤加密的文件現在可以自動儲存，並與他人進行即時共同撰寫，就彷彿文件未加密一樣便利。 需要租用戶選擇加入 (詳細資訊： https://aka.ms/mipcoauth)。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 已修正在日文字型中使用乘法或除號時，字型會意外改變的問題。 我們現在會繼續使用相同的字型 (如果支援該字元)。


- 我們已修正在存檔為 .xls 或 .xlt 格式時，會導致某些樞紐分析表格式化，導致該活頁簿損壞的問題。


- 我們已修正開啟活頁簿時，會意外顯示某些記事的問題。


### <a name="outlook"></a>Outlook

- 我們已修正在匯出至 CSV 時，會導致非 ASCII 字元錯誤匯出的問題。


- 我們已修正導致使用者在撰寫郵件時無法使用 [檢查名稱] 查詢連絡人群組的問題。


### <a name="powerpoint"></a>PowerPoint

- 我們已修正在 PowerPoint 投影片放映模式中，線條圖中的箭號未如預期顯示的問題。


### <a name="word"></a>Word

- 我們已修正開啟受 Microsoft 資訊保護 (MIP) 標籤保護的檔案時，如果使用者未登錄可存取 MIP 受保護標籤的身分識別，則可能會無限期擱置的問題。 使用者必須取消開啟以顯示登錄提示，且開啟作業只會在這之後才成功。 允許在開啟/下載期間顯示登錄提示，以修正此問題。


- 我們已修正在新的 Word 註解中使用 [聽寫] 時的問題，[註解] 卡片中的 [聽寫] 按鈕現在可以正確開啟和關閉。


- 已修正當使用者在文件中進行聽寫時，文字之間沒有空格隔間的問題。


- 我們已修正在 RTL 中張貼多行註解時，會導致第 2 行和開始行對齊左邊而非右邊的問題。


- 我們已修正拼字檢查在兩個不同的拼字校正操作功能表之間切換的問題。


- 我們已修正欄位可能有重迭文字的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2103-february-26"></a>版本 2103：2 月 26 日
*版本 2103 (組建 13819.20006)*


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 我們已修正會導致使用者無法將 Excel 活頁簿匯出至 PDF 的問題。


- 我們已修正在共同撰寫的同時複製工作表時，某些格式可能會遺失的問題。


### <a name="outlook"></a>Outlook

- 我們已修正導致使用者在移除 DRM 保護時看到附件重複的問題。


### <a name="project"></a>Project

- 已修正從 Project Web App 將專案存到本機檔案時，可能會錯誤建立任務分割的問題。 如果使用非標準工作時間的任務行事曆，就會發生此情況。


- 修正此問題：如果指標欄不在第一欄位置，當您剪下摘要任務時，系統不會警告您也會移除子任務。


- 修正以下問題：如果使用者在時程表上選取 [將您本身加入至任務] 功能，則建立的工作指派可能不會使用正確的資源可用性單位。


### <a name="word"></a>Word

- 我們已修正多個註解的對齊問題。


- 我們已修正 [大聲朗讀] 工作窗格鍵盤快速鍵的問題。


### <a name="office-suite"></a>Office 套件

- 系統現在會按照群組原則設定適當篩選出 OneDrive 位置。


- 修正載入 EMF 影像時可能會發生的無回應問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2103-february-19"></a>版本 2103：2 月 19 日
*版本 2103 (組建 13811.20002)*


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 我們已修正導致使用者在移除 DRM 保護時看到附件重複的問題。


### <a name="project"></a>Project

- 修正此問題：如果指標欄不在第一欄位置，當您剪下摘要任務時，系統不會警告您也會移除子任務。


- 修正以下問題：如果使用者在時程表上選取 [將您本身加入至任務] 功能，則建立的工作指派可能不會使用正確的資源可用性單位。


### <a name="word"></a>Word

- 我們已修正 [大聲朗讀] 工作窗格鍵盤快速鍵的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2103-february-12"></a>版本 2103：2 月 12 日
*版本 2103 (組建 13806.20000)*


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="outlook"></a>Outlook

- **Microsoft 搜尋支援的撰寫 (收件者/副本/密件副本) 建議**：將人員新增至收件者/副本行，現在會由 Microsoft 搜尋提供支援。

- **聽寫提供更多語言：** 聽寫現在支援 7 個新的語言：印地文、俄文、波蘭文、葡萄牙文 (葡萄牙)、韓文、泰文、中文 (台灣)

### <a name="word"></a>Word

- **聽寫提供更多語言：** 聽寫現在支援 7 個新的語言：印地文、俄文、波蘭文、葡萄牙文 (葡萄牙)、韓文、泰文、中文 (台灣)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 已修正因為無法擷取影像，所以 Excel 有時候會在嘗試顯示「資料類型」卡的時候意外關閉的問題。

### <a name="powerpoint"></a>PowerPoint

- 已修正迴圈動畫和音訊書籤的問題。

### <a name="project"></a>Project

- 已修正 100% 完成的工作可能會回復為 99% 完成的問題。

- 已修正當您執行 JAWS 並且移至任務資訊對話方塊時 Project 意外關閉的問題。

### <a name="word"></a>Word

- 我們已修正「自動儲存」的問題。


- 我們已修正共同撰寫時衝突的問題。




[//]: # (請勿移除 BUGDETAILS 內容結尾)

## <a name="version-2102-february-05"></a>版本 2102：2 月 5 日
*版本 2102 (組建 13801.20004)*


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 您現在會在 Access 中看到已選取的索引標籤。


### <a name="excel"></a>Excel

- 我們已修正在圖表中選取資料數列之後，Excel 停止回應的問題。


- 我們已修正當您在 Android 上使用特定鍵盤按下 Enter 鍵時，會新增一行而不是移至下一個儲存格的問題。


- 已修正在裁剪作業期間，保持圖片長寬比的相關問題。


### <a name="outlook"></a>Outlook

- 我們已修正會導致郵件在使用者取消選取該選項之後，以數位簽章方式傳送的問題。


### <a name="powerpoint"></a>PowerPoint

- 已修正在裁剪作業期間，保持圖片長寬比的相關問題。


### <a name="word"></a>Word

- 已修正在裁剪作業期間，保持圖片長寬比的相關問題。


- 我們已修正註解可能會因連結而被截斷的問題。


- 我們已修正共同撰寫時衝突模式的問題。


- 我們已修正儲存至 SharePoint Online 的問題


- 我們已修正將 Word 文件匯出為 PDF 的問題。


### <a name="office-suite"></a>Office 套件

- 已修正 Office 在某些情況下在應該呈現某個已登入帳戶的敏感度標籤時，卻呈現不同已登入帳戶的敏感度標籤的問題。




[//]: # (請勿移除 BUGDETAILS 內容結尾)

## <a name="version-2102-january-29"></a>版本 2102：1 月 29 日
*版本 2102 (組建 13721.20008)*


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 我們已修正當您在 [定義名稱] 對話方塊中新增名稱時，Excel 會意外結束的問題。


### <a name="outlook"></a>Outlook

- 我們已修正會導致加密圖示無法對使用 [僅加密] 選項傳送的電子郵件顯示的問題。

### <a name="project"></a>Project

- 修正含有長斯拉夫文名稱的專案，無法透過專案中心開啟的問題。


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2102-january-22"></a>版本 2102：1 月 22 日
*版本 2102 (組建 13714.20000)*


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **政府客戶：將敏感度標籤套用至您的文件和電子郵件：** 敏感度標籤功能目前可供 GCC 和 GCC-H 環境中的客戶取得。 [深入了解](/microsoft-365/compliance/sensitivity-labels)

### <a name="outlook"></a>Outlook

- **政府客戶：將敏感度標籤套用至您的文件和電子郵件：** 敏感度標籤功能目前可供 GCC 和 GCC-H 環境中的客戶取得。 [深入了解](/microsoft-365/compliance/sensitivity-labels)

### <a name="powerpoint"></a>PowerPoint

- **政府客戶：將敏感度標籤套用至您的文件和電子郵件：** 敏感度標籤功能目前可供 GCC 和 GCC-H 環境中的客戶取得。 [深入了解](/microsoft-365/compliance/sensitivity-labels)

### <a name="word"></a>Word

- **政府客戶：將敏感度標籤套用至您的文件和電子郵件：** 敏感度標籤功能目前可供 GCC 和 GCC-H 環境中的客戶取得。 [深入了解](/microsoft-365/compliance/sensitivity-labels)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 修正重新開啟檔案時，使用非連續儲存格範圍的特定圖表無法載入的問題。


- 修正當使用特定 Windows 安全性漏洞防護設定 (SimExec、CallerCheck) 時，Excel 無法啟動或非預期當機的問題。


### <a name="powerpoint"></a>PowerPoint

- 修正與顯示有色彩的表情符號相關的問題。


### <a name="word"></a>Word


- 這會修正在失去網際網路連線一段時間後，會防止即時輸入和目前狀態還原的問題。


- 我們已修正共同撰寫的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2102-january-15"></a>版本 2102：1 月 15 日
*版本 2102 (組建 13707.20008)*


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="outlook"></a>Outlook

- **共用至 Teams：** 將 Outlook 中的電子郵件或交談共用至 Teams 中的某個人員或頻道。

### <a name="visio"></a>Visio

- **圖表的現成圖形**：從可新增至 Visio 繪圖中的圖示、相片庫影像、人像紙板和圖戳的大型文件庫中進行選擇。 [深入了解](https://support.office.com/article/0ab844a5-289b-47f2-ba92-eeda168bc381)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="project"></a>Project

- 修正了將成本資源指派給里程碑工作時，比較基準成本沒有正確彙總的問題。


### <a name="word"></a>Word

- 修正了執行 VBA 巨集 ExportAsFixedFormat2 失敗，錯誤為「Presentation (未知成員) 不合法值」的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2102-january-08"></a>版本 2102：1 月 8 日
*版本 2102 (組建 13704.20000)*


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="outlook"></a>Outlook

- **聽寫功能變得更完善：** 有了新的聽寫工具列、語音命令及自動標點符號支援，要使用您的語音來建立內容現在更為容易

### <a name="word"></a>Word

- **聽寫功能變得更完善：** 有了新的聽寫工具列、語音命令及自動標點符號支援，要使用您的語音來建立內容現在更為容易


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 我們已修正 PowerPoint 中內嵌的 Excel 範圍預覽會顯示不正確大小的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2101-january-01"></a>版本 2101：1 月 1 日
*版本 2101 (組建 13624.20002)*


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **強制標籤：** 使用者若已設定強制標籤原則，其系統管理員將需要標記其文件和電子郵件。

### <a name="powerpoint"></a>PowerPoint

- **強制標籤：** 使用者若已設定強制標籤原則，其系統管理員將需要標記其文件和電子郵件。

### <a name="word"></a>Word

- **強制標籤：** 使用者若已設定強制標籤原則，其系統管理員將需要標記其文件和電子郵件。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="onenote"></a>OneNote

- 此變更可解決影響 OneNote 的呈現問題。


### <a name="outlook"></a>Outlook

- 此變更使得 Outlook 可以利用能夠向使用者隱藏 Exchange Online 封存信箱顯示的 Exchange Server 設定。


### <a name="powerpoint"></a>PowerPoint

- 此變更可解決合併圖案處理文字時的問題。


### <a name="word"></a>Word

- 修正問題以讓新式註解更穩定。


- 修正編輯具有 @提及的註解文章時的問題。


- 建立新的 Word 執行個體時註解草稿會消失。


- 修正註解窗格中巢狀捲軸的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2101-december-25"></a>版本 2101：12 月 25 日
*版本 2101 (组建 13617.20002)*


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 更新以便在從 Excel 複製圖表並貼上到 Word 中時保留小數點和千位分隔符號設定


- 修正了當開啟具有無效檔案内容 (建立時間、修改時間等) 的 UNC 檔案時，Excel 會意外關閉的問題


- 此變更解决了與變更 SVG 影像的外框顏色有關的問題。


### <a name="outlook"></a>Outlook

- 我們已修正以下問題：導致使用者無法指定在從 Word 啟動合併列印時允許存取時長，從而導致他們取得過多提示的問題。


- 我們已修正導致基於兌換的增益集的使用者意外關閉 Outlook 的問題。


### <a name="powerpoint"></a>PowerPoint

- 此變更解决了與變更 SVG 影像的外框顏色有關的問題。


### <a name="word"></a>Word

- 此變更解决了與變更 SVG 影像的外框顏色有關的問題。


- 修正了註解卡片上的回覆方塊不在螢幕上的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2101-december-18"></a>版本 2101：12 月 18 日
*版本 2101 (組建 13610.20002)*


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **將敏感度標籤的相關稽核資料傳送給 M365 系統管理員：** 當使用者套用、變更或移除其檔案和電子郵件上的靈敏度標籤時，Office 會將稽核資料發送到 M365 稽核後端，供系統管理員查看。 此項幕後功能 (無 UI) 為系統管理員權益。

### <a name="outlook"></a>Outlook

- **將敏感度標籤的相關稽核資料傳送給 M365 系統管理員：** 當使用者套用、變更或移除其檔案和電子郵件上的靈敏度標籤時，Office 會將稽核資料發送到 M365 稽核後端，供系統管理員查看。 此項幕後功能 (無 UI) 為系統管理員權益。

### <a name="powerpoint"></a>PowerPoint

- **將敏感度標籤的相關稽核資料傳送給 M365 系統管理員：** 當使用者套用、變更或移除其檔案和電子郵件上的靈敏度標籤時，Office 會將稽核資料發送到 M365 稽核後端，供系統管理員查看。 此項幕後功能 (無 UI) 為系統管理員權益。

### <a name="word"></a>Word

- **將敏感度標籤的相關稽核資料傳送給 M365 系統管理員：** 當使用者套用、變更或移除其檔案和電子郵件上的靈敏度標籤時，Office 會將稽核資料發送到 M365 稽核後端，供系統管理員查看。 此項幕後功能 (無 UI) 為系統管理員權益。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 在樞紐分析表中套用格式設定樣式時，進行效能改進。


### <a name="outlook"></a>Outlook

- 我們已修正造成使用者無法選取多個類別進行搜尋的問題。


- 我們已修正當活動是從另一個約會複製而來時，造成部分行事曆項目的開始時間發生意外變更的問題。


### <a name="project"></a>Project

- 我們已修正預期使用者開啟的專案應已儲存更新的資訊，但發現遺漏更新的問題。


### <a name="word"></a>Word

- 當您在註解卡片底部輸入文字時，請修正動畫。


- 我們已修正將文件儲存為含有隱藏文字的 PDF 時，Word 停滯的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2101-december-11"></a>版本 2101：12 月 11 日
*版本 2101 (組建 13604.20000)*


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="outlook"></a>Outlook

- **雲端中的 Outlook 設定：** 選擇您的 Windows 版 Outlook 設定，例如自動回復、焦點收件匣和隱私權，並在任何電腦上使用這些功能。

### <a name="word"></a>Word

- **以新式註解更輕鬆地進行共同作業：** 新增註解到物件、@提及 同事，並解決註解執行緒，以獲得更佳的共同作業體驗。 [深入了解](https://support.office.com/article/8d3f868a-867e-4df2-8c68-bf96671641e2)<br />在[部落格文章](https://insider.office.com/zh-TW/blog/modern-commenting-in-word)中查看詳細資料


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 修正以下問題：Excel 錯誤地顯示檔案新版本可用的訊息列，並強制使用者將變更儲存到活頁簿的副本中或捨棄變更。


- 修正了 Selection.Parent.Copy 通話后切換分隔符號的問題。


### <a name="outlook"></a>Outlook

- 解決了當純文字 S/MIME 郵件在傳送時發生亂碼的問題。


### <a name="powerpoint"></a>PowerPoint

- 此變更解决了在投影片放映中迴圈播放背景影片的問題。


- 我們已修正在 QAT 中新增的字型大小命令在更新時自動完成到最近定義的字型大小的問題。


### <a name="word"></a>Word

- 我們已修正在內容控制項中删除標記為不可編輯的新式註解的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2012-december-04"></a>版本 2012：12 月 4 日
*版本 2012 (組建 13530.20000)*


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="outlook"></a>Outlook

- **在連續會議之間置入時間：** 將會議預設為延後 5-10 分鐘開始，讓出席者有時間休息，或前往下一個地點。 [深入了解](https://support.office.com/article/be84396a-0903-4e25-b31c-1c99ce0dacf2)

### <a name="visio"></a>Visio

- **新 Azure 樣板和圖案：** 我們新增了更多的樣板來協助您建立最新的 Azure 圖表。 [深入了解](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 已修正在覆寫模式下編輯時，使用需要使用 IME 的語言進行編輯時表現不佳的問題。


- 已修正在自動儲存被停用時通知中的說明文章的超連結錯誤。


- 已修正在公式檢視中複製和貼上資料時 Excel 意外關閉的問題。


### <a name="outlook"></a>Outlook

- 我們已修正導致 SmartLinks 在儲存至草稿時格式遺失的問題。


### <a name="project"></a>Project

- 已修正開啟具有大量資源的專案時，花費時間很長的問題。


- 已修正如果特定專案在負載的特定部分發生問題，可能會開啟特定專案的問題。


### <a name="word"></a>Word

- 貼上為純文字通常優於貼上為 RTF 文字。 此快顯功能表修正功能可讓使用者貼上純文字格式。 否則，使用者必須複製至純文字編輯器 (如 [記事本])，然後從 [記事本] 複製到所要的目標應用程式



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2012-november-27"></a>版本 2012：11 月 27 日
*版本 2012 (組建 13519.20000)*


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 修正 Power Pivot 無法正確匯入定位字元分隔的文字檔案的問題。


### <a name="outlook"></a>Outlook

- 我們已修正導致使用者在從 Outlook 以外的應用程式傳送 Outlook 郵件時遇到一些問題的問題。


### <a name="powerpoint"></a>PowerPoint

- 此變更解決筆跡分析期間發生的逾時問題。


- 此變更解決 [建立動畫 GIF 使用者介面] 中的文法錯誤。


- 已修正無法正確開啟部分損壞的 PowerPoint 檔案 (即使在文件修復之後) 的問題。


### <a name="project"></a>Project

- 已修正使用者可能會看到與任務關聯的多個未指派作業的問題。


- 已修正在大型專案中，輸入任務名稱的速度可能非常緩慢的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2012-november-20"></a>版本 2012：11 月 20 日
*版本 2012 (組建 13512.20000)*


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="outlook"></a>Outlook

- **每個線上會議：** 使用新設定將所有會議預設設定為線上，讓您輕鬆安排線上會議。

### <a name="powerpoint"></a>PowerPoint

- **影片庫：** 在應用程式內使用精選的免版稅影片素材庫來提升您的文件


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="powerpoint"></a>PowerPoint

- 修正無法完全重新整理未知共同作者的目前狀態指示器的問題，只要有更多關於共同作者的資訊。


### <a name="word"></a>Word

- 我們已修正將文件儲存為含有隱藏文字的 PDF 時，Word 停滯的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2012-november-13"></a>版本 2012：11 月 13 日
*版本 2012 (組建 13510.20004)*


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 我們已修正從 OneDrive 本機同步處理資料夾插入檔案時，[插入物件] 命令沒有顯示正確圖示的問題。


### <a name="outlook"></a>Outlook

- 我們已修正會導致「收件者:」欄位在工作狀態報告中空白的問題。


### <a name="powerpoint"></a>PowerPoint

- 我們已修正 Slide.Shapes.AddMediaObject2 會對舊版影片格式 (MPG-1、Mpeg-2) 發生當機的 VBA 問題。


### <a name="project"></a>Project

- 我們已修正若交付項目相關聯的 SharePoint 網站已不再存在時，無法刪除交付項目的相依性的問題。


- 我們已修正預期使用者開啟的專案應已儲存更新的資訊，但發現遺漏更新的問題。


### <a name="word"></a>Word

- 我們已修正在縮放圖片時，圖片變得模糊的相關問題。


- 我們已修正長超連結被截斷的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2012-november-06"></a>版本 2012：11 月 6 日
*版本 2012 (組建 13430.20000)*


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **同時取消隱藏多個工作表：** 不再需要一次取消隱藏一個工作表，可以一次取消隱藏多個隱藏的工作表。 [深入了解](https://support.office.com/article/69f2701a-21f5-4186-87d7-341a8cf53344)

### <a name="outlook"></a>Outlook

- **所有裝置都有相同的簽章：** 在雲端中儲存簽章。 只要建立一次，就能在所有使用 Outlook 的位置使用。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 我們已修正部分功能區元素未以簡體中文進行當地語系化的問題。


- 我們已修正更新時 Excel 意外終止的問題。


### <a name="outlook"></a>Outlook

- 我們已修正將附件新增到從 zip 檔案開啟的郵件時會失敗的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2011-october-30"></a>版本 2011：10 月 30 日
*版本 2011 (組建 13426.20004)*


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **改善條件式格式設定對話方塊：**[條件式格式設定] 對話方塊現在可以調整大小，且現在您只要按一下就能複製規則。 [深入了解](https://support.office.com/article/fed60dfa-1d3f-4e13-9ecb-f1951ff89d7f)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 我們已修正從非 Office 應用程式使用 DAO 時，會導致應用程式意外關閉的問題。


### <a name="excel"></a>Excel

- 修正 Power Pivot 使用 Oracle 資料庫連線時的問題。


- 我們已修正觸發 MTR 計算和群組原則物件更新 (例如，透過遠端群組原則重新整理) 時，Excel 會異常終止的問題。


- 此變更可修正會在嘗試載入 atomsvc 檔案時導致 Excel 發生錯誤的錯誤。


- 我們已修正將 Excel 活頁簿插入 Word 文件時，Word 似乎停滯的問題。


### <a name="outlook"></a>Outlook

- 我們已修正信箱擁有者無法管理自己行事曆的共用權限的問題，因為該選項呈現灰色停用狀態。


- 我們已修正將電子郵件範本儲存為 .OFT 時，會將中文字元變更為問號的問題。


- 我們已修正 Outlook 無法使用受限制的權限建立郵件的問題。


- 解決在新增或儲存附件時，會導致 Outlook 停止運作的問題。


### <a name="powerpoint"></a>PowerPoint

- 我們已修正關閉設計窗格時，投影片的格線移位的問題。


- 我們已修正投影片在選取項目窗格開啟的情況下停止螢幕錄製後，投影片中的捲軸會自行開始調整的問題。


### <a name="project"></a>Project

- 修正當您將專案從 PWA 儲存到本機 mpp 檔案時，ProjectBeforeTaskChangeEvent 會對實際上未由使用者變更的資料觸發的問題。


- 修正資源預訂依名稱 (而不是 GUID) 搜尋資源時，如果有多個名稱相同的資源，會導致問題的問題。


### <a name="word"></a>Word

- 我們已修正按一下註解提示時，註解提示不會放大以在檢視中顯示註解卡片的問題。


- 我們已修正欄位之間的線條可能已移位的版面配置問題。


- 我們已修正將 Excel 活頁簿插入 Word 文件時，Word 似乎停滯的問題。


### <a name="office-suite"></a>Office 套件

- 我們已修正 Office 部署工具中的一個問題，該問題是，在 Microsoft Office 2007 [Microsoft 應用程式錯誤回報工具] 產品存在的情況下使用 RemoveMSI 功能時設定失敗。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2011-october-23"></a>版本 2011：10 月 23 日
*版本 2011 (組建 13415.20002)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="powerpoint"></a>PowerPoint

- **利用簡報者教練排練簡報：** 取得有助於維持對象參與的項目方面的意見反應，例如節奏、語調、填充字詞、敏感詞語等等。 [深入了解](https://support.office.com/article/cd7fc941-5c3b-498c-a225-83ef3f64f07b)

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 修正某些使用者在嘗試從其同步處理的 OneDrive 資料夾匯出査詢時看到「系統資源滿載」錯誤的問題。

- 我們已修正表單視窗之間的「自動」切換，發生切換到另一個表單的問題。

### <a name="outlook"></a>Outlook

- 我們已修正將從會議位置複製的 URL 貼上到其他位置 (例如瀏覽器) 時，URL 的結尾會包含分號的問題。

### <a name="powerpoint"></a>PowerPoint

- 我們已修正將投影片放映複製到次要監視器時，投影片可能會隱藏在其他視窗後面的問題。

### <a name="project"></a>Project

- 我們已修正在開啟以特定方式指定資源分佈的檔案時，Project 可能會意外終止的問題。

### <a name="word"></a>Word

- 我們已修正有時開啟 Word 文件可能會顯示錯誤對話方塊的追蹤修訂問題。

- 我們已修正套用具有浮水印的敏感度標籤時的列印問題。


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2011-october-16"></a>版本 2011：10 月 16 日
*版本 2011 (組建 13408.20000)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **SVG 剪貼簿支援：** 您現在可以將 SVG 內容從 Office 貼上協力廠商應用程式。 [深入了解](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

### <a name="outlook"></a>Outlook

- **SVG 剪貼簿支援：** 您現在可以將 SVG 內容從 Office 貼上協力廠商應用程式。 [深入了解](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

### <a name="powerpoint"></a>PowerPoint

- **SVG 剪貼簿支援：** 您現在可以將 SVG 內容從 Office 貼上協力廠商應用程式。 [深入了解](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

### <a name="word"></a>Word

- **SVG 剪貼簿支援：** 您現在可以將 SVG 內容從 Office 貼上協力廠商應用程式。 [深入了解](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 我們已修正使用者無法在 [基本驗證] 中刪除 Microsoft 365 群組行事曆中的約會之問題。


- 我們已修正載入暱稱快取時啟動 Outlook 失敗的問題。


### <a name="powerpoint"></a>PowerPoint

- 我們已修正 [圖片] 旁的內容預留位置圖示沒有工具提示的問題。


- 我們已修正 pptsx 檔案所顯示的投影片放映之受保護檢視，允許受 IRM 保護的文件螢幕擷取之問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2011-october-09"></a>版本 2011：10 月 9 日
*版本 2011 (組建 13406.20000)*


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **從查詢建立 Power Platform 資料流程：** 您現在可以將查詢匯出至 Power Query 範本，以建立新的 Power Platform 資料流程

### <a name="powerpoint"></a>PowerPoint

- **匯出範圍中的動畫 GIF：** 當匯出成動畫 GIF 時， 選取投影片的範圍

- **使用透明背景建立 GIF：** 當匯出成動畫 GIF 時，您可以使用新選項讓背景變透明。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 我們已修正啟用 COM 增益集的 SaveAs 操作之後，未變更檔案名的問題。


- 我們已修正當 Excel 資料模型中有錯誤的度量定義，自動儲存會失敗且顯示出錯/誤解的錯誤訊息。


- 我們已修正放大和縮小簡報區域會造成縮放選取選框和滑鼠指標之間的間隙的問題。


### <a name="outlook"></a>Outlook

- 我們已修正影像附件的快速列印會導致「Windows 找不到這張圖片。請檢查位置，然後再試一次」錯誤的問題。


- 已修正會導致某些使用者看到 Outlook 在離線狀態中啟動，直到他們手動選擇線上工作為止的問題。


### <a name="powerpoint"></a>PowerPoint

- 我們已修正放大和縮小簡報會造成縮放選取跑馬燈和滑鼠指標之間間隙的問題。


### <a name="project"></a>Project

- 已修正了如果工作表單類型視圖中的延隔時間變更，ProjectBeforeTaskChagne 事件中的 NewVal 會是不正確的值。


- 已修正如果您在專案網站中有工作清單並將工作清單分組，您將無法快速編輯工作清單的問題。


- 修正如果您透過 CSOM 更新企業資源，可能會遺失資源最大單位。


### <a name="word"></a>Word

- 我們已修正放大和縮小簡報區域會造成縮放選取選框和滑鼠指標之間的間隙的問題。


### <a name="office-suite"></a>Office 套件

- 我們已修正 SSO API 互動式登入傳回錯誤碼的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2010-october-02"></a>版本 2010：10 月 2 日
*版本 2010 (組建 13328.20000)*


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **使用 [進階對話方塊] 來 [建立資料類型]:** [進階對話方塊] 可讓您手動選取合併您正在建立的 [資料類型] 欄位。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="onenote"></a>OneNote

- 我們已修正使用者無法從 [外部空間檔案] > [資訊] 的文字方塊中選取及複製筆記本 URL 的問題。


### <a name="outlook"></a>Outlook

- 已解決當主旨為空白時，會導致傳送的自動產生電子郵件含有空白內文的問題。


- 我們已修正資料夾中快取錯誤資料夾 guid 的問題。


- 當使用者將電子郵件地址複製貼上到顯示名稱的 [收件者] 欄位時，電子郵件地址不一定可被正確分析，並導致出現了一個顯示電子郵件地址無效的警告。  已修正此問題，可正確分析名稱和電子郵件地址，因此不會再顯示警告。


- 我們已修正線上共用資料夾未傳回母資料夾名稱的問題。 它並非失敗，而是傳回了不正確地移至主要帳戶的空白路徑。


- 我們已修正從唯讀預覽窗格中重新開啟 [草稿] 之後開啟 [追蹤修訂] 的問題。


- 我們已修正傳統附件無法使用 [另存為] 選項的問題。


- 我們已修正讓使用者能在覆寫原則時自訂調整文字的問題。


### <a name="powerpoint"></a>PowerPoint

- 我們已修正 PowerPoint 在匯出為 PDF 時，無法匯出矩形專案符號的問題。


- 我們已修正若您在最後一張投影片上，且您在按 [結束工作模式] 之後和顯示摘要之前，滑向下一張投影片，則會在 [摘要] 頁面上看到 [結束工作模式] 對話方塊。


### <a name="project"></a>Project

- 修正了如果您將群組套用到 [資源使用狀況] 或 [工作表] 視圖，然後插入欄位，Project 可能會當機的問題。


- 修正了如果您的自訂欄位包含公式，且正在使用實獲值分析，您可能會發現效能延遲切換檢視並開啟專案/工作詳細資料的問題。


- 修正了如果您嘗試多次新增同一專案，且將 AttachToSources 設定為 false 時，ConsolidateProjects VBA 方法可能會發生出錯的問題。


- 修正若您的事件程式碼執行中，並嘗試透過工作 [表單檢視] 進行變更，按一下 [確定] 按鈕可能不會提交變更的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2010-september-25"></a>版本 2010：9 月 25 日
*版本 2010 (組建 13318.20000)*


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **使用 Power Query 建立資料類型：** 使用任何資料來源中的 Power Query 建立豐富的資料類型

### <a name="outlook"></a>Outlook

- **工作的使用者體驗更新：** 工作項目的視覺效果更新

- **撰寫郵件時節省時間：** Outlook 會顯示書寫建議，協助您快速撰寫郵件。 若要接受建議，只需使用 Tab 鍵。

### <a name="word"></a>Word

- **電腦版 Word 中的 Microsoft 編輯器窗格已更新：** 我們已將電腦版 Word 用戶端中編輯器窗格目前的體驗升級。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 我們已修正載入儲存的查詢/關聯視窗在捲動時，捲軸位置未正確設定的問題。


- 我們已修正 [新增表格] 工作窗格未正確顯示包含 '&' 名稱的問題。


### <a name="excel"></a>Excel

- 我們已修正多層次類別的手動間隔在圖表中無法運作的問題。


- 我們已修正重新整理 OLAP 樞紐分析表時，可能會導致當機的問題。


- 我們已修正新增至用於資料驗證之表格，並未更新活頁簿中所有工作表選項的問題。


### <a name="onenote"></a>OneNote

- 我們已修正 OneNote 在自訂主題的畫布中不會採用高對比色彩的問題。


- 我們已修正當您將游標移至筆記本色彩選擇器的綠色色彩上方時，快顯會顯示「紅粉色」的問題。


### <a name="powerpoint"></a>PowerPoint

- 我們已修正當使用者將來源路徑變更為本機 OneDrive 資料夾時，連結的 Excel 圖表不正確變更為 Excel 工作表的問題。


### <a name="word"></a>Word

- 我們己修正已啟用工作流程檔案的連結無法如預期開啟的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2010-september-18"></a>版本 2010：9 月 18 日
*版本 2010 (組建 13312.20006)*


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="outlook"></a>Outlook

- **使用 [編輯工具] 校訂您的郵件** 您現在可以在 Outlook 64 位元 使用者的電子郵件中取得文法和其他樣式的建議。 尋找加上底線的文字，查看 [編輯工具] 的建議以讓您的書寫更為精進。

- **使用內建翻譯工具打破語言障礙：** 不再需要翻譯的增益集！ 在電子郵件中，按一下滑鼠右鍵以翻譯特定的文字、片語或整個郵件。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 修正在使用 2D 地圖圖表時，無法使用 VBA 設定系列中最大值、中間值和最小值顏色的問題。


- 修正當 Office 語言設定為西班牙文時，其中資料驗證清單可能無法顯示清單中所有項目的問題。


- 修正可能會導致「嘗試計算一個或多個公式時，Excel 資源不足」的錯誤問題。


- 修正在使用資料編輯列輸入公式時，在某些情況下 ChartSheet 出現當機的問題。


### <a name="outlook"></a>Outlook

- 當使用者將電子郵件地址複製貼上到顯示名稱的 [收件者] 欄位時，電子郵件地址不一定可被正確分析，並導致出現了一個顯示電子郵件地址無效的警告。  已修正此問題，可正確分析名稱和電子郵件地址，因此不會再顯示警告。


### <a name="word"></a>Word

- 修正當使用者在點擊追蹤的變更（插入/刪除）時，會彈出註解的問題。


- 我們已修正 Word 中刪除註解圖說文字的問題。


- 我們已修正 Outlook 有關將郵件設定為 [不要轉寄] 的問題。


- 我們已修正有關儲存含有引文和方程式的 Word 文件問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2010-september-11"></a>版本 2010：9 月 11 日
*版本 2010 (組建 13304.20000)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="access"></a>Access

- **Office 可以遵循您的 Windows 10 深色模式設定：** 在深色模式中使用 Windows 10？ Office 現在可以切換佈景主題以自動相符，只要選擇 [使用系統設定] 做為您的 Office 佈景主題即可。

### <a name="excel"></a>Excel

- **Office 可以遵循您的 Windows 10 深色模式設定：** 在深色模式中使用 Windows 10？ Office 現在可以切換佈景主題以自動相符，只要選擇 [使用系統設定] 做為您的 Office 佈景主題即可。

### <a name="onenote"></a>OneNote

- **Office 可以遵循您的 Windows 10 深色模式設定：** 在深色模式中使用 Windows 10？ Office 現在可以切換佈景主題以自動相符，只要選擇 [使用系統設定] 做為您的 Office 佈景主題即可。

### <a name="outlook"></a>Outlook

- **Office 可以遵循您的 Windows 10 深色模式設定：** 在深色模式中使用 Windows 10？ Office 現在可以切換佈景主題以自動相符，只要選擇 [使用系統設定] 做為您的 Office 佈景主題即可。

### <a name="powerpoint"></a>PowerPoint

- **Office 可以遵循您的 Windows 10 深色模式設定：** 在深色模式中使用 Windows 10？ Office 現在可以切換佈景主題以自動相符，只要選擇 [使用系統設定] 做為您的 Office 佈景主題即可。

### <a name="project"></a>Project

- **Office 可以遵循您的 Windows 10 深色模式設定：** 在深色模式中使用 Windows 10？ Office 現在可以切換佈景主題以自動相符，只要選擇 [使用系統設定] 做為您的 Office 佈景主題即可。

### <a name="publisher"></a>發行者

- **Office 可以遵循您的 Windows 10 深色模式設定：** 在深色模式中使用 Windows 10？ Office 現在可以切換佈景主題以自動相符，只要選擇 [使用系統設定] 做為您的 Office 佈景主題即可。

### <a name="visio"></a>Visio

- **Office 可以遵循您的 Windows 10 深色模式設定：** 在深色模式中使用 Windows 10？ Office 現在可以切換佈景主題以自動相符，只要選擇 [使用系統設定] 做為您的 Office 佈景主題即可。

### <a name="word"></a>Word

- **Office 可以遵循您的 Windows 10 深色模式設定：** 在深色模式中使用 Windows 10？ Office 現在可以切換佈景主題以自動相符，只要選擇 [使用系統設定] 做為您的 Office 佈景主題即可。

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 修正在啟用「分頁預覽」時，在含有大量資料的工作表之間切換時，可能會發生明顯延遲的問題。

### <a name="outlook"></a>Outlook

- 我們已修正關閉 [焦點收件匣] 並執行排序之後，電子郵件遭隱藏的問題。

### <a name="powerpoint"></a>PowerPoint

- 我們已修正 GIF 在編輯器和投影片放映中的動畫只會執行一次的問題。

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2010-september-04"></a>版本 2010：9 月 4 日
*版本 2010（組建13301.20004）*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="outlook"></a>Outlook

- **釘選電子郵件**：這項功能可協助使用者追蹤所需的郵件，或是將郵件存放在郵寄清單頂端作為提醒。

- **依人員搜尋時收到電子郵件的建議：** 當您在 Outlook 中輸入搜尋字詞時，您會收到建議中顯示的最相關的電子郵件。

- **依人員搜尋時收到電子郵件的建議：** 當您在 Outlook 中輸入搜尋字詞時，您會收到建議中顯示的最相關的電子郵件。

- **Microsoft Corporation 編輯器針對Word和Outlook桌面客戶端進行了升級:** 我們正為編輯器的拼寫，文法和高級樣式建議引入一種新的點擊查看模型。。 此變更也包含用於審核建議的新的專用卡外觀。

### <a name="word"></a>Word

- **Microsoft Corporation 編輯器針對Word和Outlook桌面客戶端進行了升級:** 我們正為編輯器的拼寫，文法和高級樣式建議引入一種新的點擊查看模型。。 此變更也包含用於審核建議的新的專用卡外觀。

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 我們已修正一個問題, 即如果您開啟包含LET 函數的檔案，它會顯示警示：”我們在您的檔案.xlsx 中發現內容有問題”。 您想要我們儘量嘗試復原嗎？ 如果您信任這個活頁簿的來源，請按一下 [是]。
- 我們已修正與 XLAM 增益集參照和命名範圍相關的問題。
- 我們已修正使用者無法修改樞紐分析表篩選的問題，因為它已設定為Analysis Services數據庫中不再存在的值。
- 我們已修正如果使用者將自訂樣式套用至動態陣列，就會收到「您不能只改變一個陣列中的一部分」錯誤的問題。這是已移除的舊版限制。
- 我們已修正 Excel 公式列與設備失去連線後無法完全呈現的問題，例如遠端會話的連線/斷線或監視器變更。

### <a name="outlook"></a>Outlook

- 我們已修正一個問題, 讓您可透過群組政策來啟用/停用預設的登入選項。
- 我們已修正電子郵件草稿在助理和經理權限移動時, 寄件者的舊網域名稱仍被保留和顯示的問題。
- 我們已修正一個問題，其導致某些使用者看到 Outlook 在離線狀態下啟動，直到他們手動選擇線上工作。
- 我們已修正在啟用單行功能區（SLR）後，執行 VBA 程式碼 ActiveInspector （"ShowSchedulingPage"）會導致執行階段錯誤的問題。
- 我們已修正一個問題, 即Automatic Replies自動回復對話方塊上的確定和取消按鈕以高解析度 (例如 1750 x 1920) 及較大文字 (例如 175%) 顯示的系統上的錯誤。
- 我們修正一個情況, 即將會議請求從空的聯繫人群組發送到另一個聯繫人組會導致當機。
- 我們解決了導致使用者在打開某些很大的電子郵件時發生當機的問題。
- 我們已修正一個問題, 它使的群組政策要求始終啟用增益集, 則 監視增益集的功能則無法使用，以防止使用者禁用增益集,。

### <a name="powerpoint"></a>PowerPoint

- 我們已修正簡報無法自動播放影片的問題。
- 我們已修正啟動 PowerPoint 之後，插入投影片並開啟和關閉批註窗格的問題，縮圖窗格中的投影片會顯示為重疊。

### <a name="project"></a>Project

- 我們已修正如果資源有多個成本費率表的問題，則剩餘成本可能無法被正確計算.
- 我們已修正了與Microsoft SharePoint Online 專案相關的專案清單, 專案完成日期無法更新的問題。

### <a name="word"></a>Word

- 我們已修正一個問題, 即使用者點擊註解，註解卡將在註解文周圍顯示邊框。
- 我們已修正一個問題, 即如將文件縮放到160％或更高, 且註解窗格不可見，焦點將不會移至註解窗格。
- 我們已修正一個問題，即在多個打開的文件之間切換後，一個文件的註解會顯示在其他打開的文檔上。
- 我們已修正一個問題，即如果使用者建立的評論草稿, 錨定在已包含提交的評論行上，則在SideTrack與提交評論相關的草案則以錯誤的順序排列。
- 我們已修正將檔案儲存成 HTML 格式時, 無法包含入長的連結的問題。
- 我們已修正 AutoOpen 會在 AutoExec 之前執行的巨集問題。

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2009-august-28"></a>版本 2009：8 月 28 日
*版本 2009 (組建 13219.20004)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 解決一個問題，該問題導致使用者在選擇多個訊息時，能夠傳送 OneNote 所套用的「不可轉寄」原則的電子郵件內容。

### <a name="powerpoint"></a>PowerPoint

- 我們已修正插入影片的功能已停用的問題。

### <a name="word"></a>Word

- 我們已修正使用者在選取註解時無法退出頁首/頁尾的問題。
- 我們已修正一個問題，該問題造成使用者無法看到超出邊界的註解，因為在邊界中無法下拉。
- 我們已修正在邊界窗格中，搜尋已解決的註解無法正常運作的問題。

### <a name="office-suite"></a>Office 套件

- 我們已修正 Office 部署工具中的一個問題，該問題是，在 Microsoft Office 2007 [Microsoft 應用程式錯誤回報工具] 產品存在的情況下使用 RemoveMSI 功能時設定失敗。
- 我們在 [壓縮圖片] 對話方塊中，修正了某些使用者選取的 DPI 設定無法保留的問題。

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2009-august-21"></a>版本 2009：8 月 21 日
*版本 2009 (組建 13212.20000)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **Excel 中的動作手寫筆：** 手寫筆工具可協助您手寫並快速編輯資料

### <a name="outlook"></a>Outlook

- **依訊息擁有者刪除交談：** 此功能可讓您依訊息擁有者刪除交談。

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 我們已修正 ODBC 資料庫的連線對協力廠商應用程式沒有作用的問題。

### <a name="excel"></a>Excel

- 我們已修正使用巨集來設定某個範圍的 FormulaR1C1 屬性時，如果圖表工作表為作用中工作表，則儲存格參考會不正確的問題。
- 我們已修正筆跡會導致 Excel 無法回應的問題。

### <a name="outlook"></a>Outlook

- 我們已修正一個問題，使用者現在可以停用 Outlook 的 IRM (資訊版權管理)，而不需要為其餘 Office 應用程式停用它。

### <a name="word"></a>Word

- 我們已修正刪除註解之後 Word 可能會當機的問題。
- 我們已修正在某些情況下，項目符號無法在電子郵件中正確顯示的問題。

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2009-august-14"></a>版本 2009：8 月 14 日
*版本 2009 (組建 13205.20000)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 我們已修正如果用戶鍵入包含括號的公式名稱並通過F1調用了協助，則該特定於公式的說明主題將不會顯示。
- 修復了還原文件的舊版本後分配給按鈕的巨集被破壞的問題。

### <a name="outlook"></a>Outlook

- 此變更解決了在用戶將索引標籤從會議頁面切換到排程小幫手頁面後，會議頁面將繼續顯示的問題。

### <a name="word"></a>Word

- 我們已修正項目符號圖片無法正確顯示的問題。

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2009-august-07"></a>版本 2009：8 月 7 日
*版本 2009 (組建 13130.20000)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 我們已修正 Active Directory 中的 "otherTelephone" 和 "otherHomePhone" 使用者帳戶屬性未對應到對應的 Outlook LDAP 屬性的問題。

### <a name="powerpoint"></a>PowerPoint

- 我們已修正使用者在特定情況下看到功能區/標題列未顯示的問題。

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2008-july-31"></a>版本 2008：7 月 31 日
*版本 2008 (組建 13127.20002)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **將您的 iPhone 相片直接插入 Office：** 來自您手機的 HEIC 圖片現在可無縫地插入 Office。 不需要轉換。<br />在[部落格文章](https://insider.office.com/zh-TW/blog/insert-apple-photos-into-office-easily)中查看詳細資料

### <a name="outlook"></a>Outlook

- **將您的 iPhone 相片直接插入 Office：** 來自您手機的 HEIC 圖片現在可無縫地插入 Office。 不需要轉換。<br />在[部落格文章](https://insider.office.com/zh-TW/blog/insert-apple-photos-into-office-easily)中查看詳細資料

### <a name="powerpoint"></a>PowerPoint

- **將您的 iPhone 相片直接插入 Office：** 來自您手機的 HEIC 圖片現在可無縫地插入 Office。 不需要轉換。<br />在[部落格文章](https://insider.office.com/zh-TW/blog/insert-apple-photos-into-office-easily)中查看詳細資料

### <a name="word"></a>Word

- **將您的 iPhone 相片直接插入 Office：** 來自您手機的 HEIC 圖片現在可無縫地插入 Office。 不需要轉換。<br />在[部落格文章](https://insider.office.com/zh-TW/blog/insert-apple-photos-into-office-easily)中查看詳細資料

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 此修正會解決嘗試執行之前會產生「查詢太複雜」錯誤訊息的特定查詢的問題。

### <a name="excel"></a>Excel

- 我們已修正若圖表數列順序已變更，與該數列對齊的對應核取方塊未隨著該數列重新排序的問題。
- 我們已修正具有放射狀漸層填滿的影像複本與原始不符的問題。

### <a name="outlook"></a>Outlook

- 這解決了當使用者從檢查程式視窗回覆受到數位版權管理的郵件，卻沒有所回覆郵件的擁有者權限時，會導致使用者會無法新增簽名的問題。
- 此修正會解決導致 Outlook 無法在 markdown 內容中正確顯示換行符號的問題。

### <a name="powerpoint"></a>PowerPoint

- 我們已修正具有放射狀漸層填滿的影像複本與原始不符的問題。
- 我們已修正 PowerPoint 中的 [表單] 按鈕在不允許存取 Office 市集時不會允許建立表單的問題。

### <a name="project"></a>Project

- 我們已修正針對 SharePoint 工作清單，第二個索引標籤上的功能區按鈕可能會停用的問題。

### <a name="word"></a>Word

- 我們已修正具有放射狀漸層填滿的影像複本與原始不符的問題。
- 我們已修正如果新增註解來追蹤變更，將會意外開啟 [修訂] 窗格的問題。
- 我們已修正文件連結未透過 [插入] > [連結] 下拉式功能表插入 [註解] 方塊的問題。
- 我們已修正 VBA 超連結集合中的超連結計數，在新增包含超連結的影像之後，未正確反覆運算的問題。

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2008-july-24"></a>版本 2008：7 月 24 日
*版本 2008 (組建 13117.20000)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **在 Excel 中製作精美的 Visio 圖表：** 將資料放在工作表上，以建立流程圖或組織圖。 [深入了解](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="onenote"></a>OneNote

- 我們已修正當應用程式視窗調整為小尺寸時，[搜尋] 編輯方塊中的預留位置文字發生溢出的問題。

### <a name="word"></a>Word

- 我們已修正當應用程式視窗調整為小尺寸時，[搜尋] 編輯方塊中的預留位置文字發生溢出的問題。
- 我們已修正 [追蹤修訂] 中的 [特定人員] 選項已停用的問題。
- 我們已修正了開啟 HTML 檔案時偶爾停止回應的問題。

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2008-july-17"></a>版本 2008：7 月 17 日
*版本 2008（組建13115.20000）*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 我們已修正只要儲存並重新開啟含有隱藏前置字元的樞紐分析表，即會顯示前置字元的問題。

- 我們已修正當透過 VBA 啟用活頁簿的 [ForceFullCalculation] 時，圖表不一會更新的問題。

### <a name="outlook"></a>Outlook

- 我們已修正從相同的電子郵件域在 Outlook 中建立多個設定檔會產生的問題。
- 解決會導致在 S/MIME 加密郵件的頁首中無法顯示鎖定圖示的問題。
- 解決當傳送未加密郵件時，會導致附件從 S/MIME 郵件中剝離出來的問題。
- 解決當純文字 S/MIME 郵件在傳送時發生亂碼的問題。
- 解決當傳送未加密的 S/MIME 電子郵件時，會導致附件損毀的問題。
- 解決選取安全性對話方塊上的 [儲存] 選項時，會導致使用者無法將來自其租用戶外部的 OneDrive 附件儲存至其本機電腦的問題。
- 解決當寄件者授與 [另存為] 許可權時，會導致收件者無法儲存許可權保護郵件的問題。
- 解決某些 [進階搜尋] 選項標籤在某些語言中會被截斷的問題。

### <a name="project"></a>Project

- 我們已修正 [工作委員會] 畫面中列出的工作未與 [指派資源] 對話方塊中的任務同步處理的問題。
- 我們已修正當您複製並貼上具有多個相關性的工作，並非所有相關性都能正確複製的問題。

### <a name="word"></a>Word

- 我們已修正當焦點位於註解文字方塊中時，[編輯器] 命令會被停用的問題。
- 我們已修正當焦點位於註解文字方塊中時，[顯示標記] 命令會被停用的問題。
- 我們已修正自訂 XML 中的註解狀態在開啟文件時可能會遺失的問題。

### <a name="office-suite"></a>Office 套件

- 我們已修正使用者從工作列開啟新應用程式視窗，並建立新的空白檔時，會造成額外檔案建立的問題。
- 我們已修正當使用者在編輯文件，但是許可權遺失時，我們並未通知使用者必須重新驗證的問題。

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2008-july-10"></a>版本 2008：7 月 10 日
*版本 2008 (組建 13102.20002)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 我們已修正，如果未核取 [下載共用資料夾]，共用行事曆會議 [回覆選項] 中缺少 [允許轉寄] 選項的問題。
- 我們已修正，即使使用者具有適當的列印權限也會在停用狀態下顯示列印按鈕的問題。

### <a name="project"></a>Project

- 我們已修正如果您嘗試從 Project 將 PDF/XPS 儲存至 SharePoint 文件庫，沒有發生任何動作的問題。

### <a name="word"></a>Word

- 我們已修正將某些文字及影像貼到 [註解] 方塊之後，Word 停止回應的問題。
- 我們已修正刪除最後一個註解後，[新增批註] 按鈕停用的問題。

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2007-july-03"></a>版本 2007：7 月 3 日
*版本 2007 (組建 13029.20006)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="outlook"></a>Outlook

- **在 Outlook 中使用 [快速投票] 建立投票：** 輕鬆建立投票，收集投票，並查看電子郵件中的結果 [深入了解](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)

- **新的會議室尋找工具：** 依不同功能搜尋會議室。

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 我們修正以下問題：在特定版本 Excel 中建立的資料模型表格無法在 [表格預覽] 中看到，即使與該表相關聯的查詢尚未編輯。
- 我們已修正在 [定義名稱\套用名稱] 對話方塊中停用 [忽略相對/絕對] 參照會導致公式無法使用的問題。
- 我們已修正清除 [進階資料篩選] 可能會遺失表格格式設定的問題。
- 我們已修正嵌入式 PDF 文件的完整路徑顯示在文件標題，而不只是檔案名稱的問題。
- 我們已修正停用 Wolfram 雲端連接器之後，儲存並重新開啟 Excel 活頁簿可能會導致當機的問題。
- 我們已修正啟動 Excel 時啟用 [規劃求解] 增益集將導致當機的問題。

### <a name="outlook"></a>Outlook

- 我們已修正如果在 [收件者] 行上有超過 130 個收件者，Outlook 會當機的問題，且我們也改善了呈現文字的效能。
- 我們已修正「待辦事項列」中跨越兩天以上的活動，在後續的所有日期中顯示相同結束時間的問題。
- 我們已修正導致 Outlook 使用者在使用共用行事曆後，在幾分鐘內訊息清單停止更新的問題。

### <a name="powerpoint"></a>PowerPoint

- 我們已修正將 HTML 貼到投影片上的文字區域時，會改為貼上投影片最上方所建立的文字方塊中的問題。
- 我們已修正在 [簡報者檢視畫面] 中選取所有投影片、使用 Alt+Tab 退出 [簡報者檢視畫面] 並返回投影片放映，然後按一下 [結束放映] 時，將導致未處理例外狀況的問題。

### <a name="project"></a>Project

- 我們已修正 Project 在開啟特定 XML 檔案時可能當機的問題。
- 我們已修正如果文件庫處於新式模式，您無法從 SharePoint 文件庫開啟 Project 檔案的問題。
- 我們已修正 URL 以 '.com' 結尾時，無法從 Project Web App 在 Project 傳統型用戶端開啟專案的問題。

### <a name="word"></a>Word

- 我們已修正在共同撰寫模式期間，當發生合併衝突且使用者已選取放棄變更時，我們不再顯示儲存或捨棄變更選項的問題。
- 我們已修正一個問題，當嘗試使用新名稱儲存包含巨集的檔案時，無論使用者輸入什麼名稱，都會導致該檔案以 .docx 副檔名和檔案名稱 'WRO0004.docx' 儲存，進而導致文件無法使用。

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2007-june-26"></a>版本 2007：6 月 26 日
*版本 2007 (組建 13020.20004)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 我們已修正在重新整理連結的 SQL 資料表時，連結資料表管理員會提示您輸入主要索引鍵的問題。
- 我們已修正 [查詢編輯器] 中的查詢捲出畫面的問題。
- 我們已修正執行查詢的時間大約比預期完成時間兩倍久的問題。

### <a name="outlook"></a>Outlook

- 我們已修正使用者無法使用通訊群組清單中的「傳送為」或「代理傳送者」的問題。
- 我們已修正在郵件中插入影像內嵌，然後將郵件儲存為草稿將會重新調整影像大小的問題。
- 我們已修正在編輯主旨之後，導致 NDR 郵件的本文從 Unicode 變更為 ASCII 的問題。

### <a name="project"></a>Project

- 我們已修正政府社群雲端中的 Project Planner 連結已停用的問題。

### <a name="office-suite"></a>Office 套件

- 我們已修正將插入可縮放向量圖形 (SVG) 中的文字插入到 Word、Excel 或 PowerPoint 檔案、儲存並關閉檔案，然後重新開啟檔案後，難以辨識的問題。

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2007-june-19"></a>版本 2007：6 月 19 日
*版本 2007 (組建 13012.20000)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 我們已修正將活頁簿儲存至 SharePoint/OneDrive 時，會導致自訂功能區索引標籤 CustomUI XML 遭移除的問題。
- 我們已修正當建議以唯讀方式使用檔案時，活頁簿處於唯讀狀態的問題。

### <a name="outlook"></a>Outlook

- 我們已修正以下問題：當使用多個不同解析度的監視器時，輸入法編輯器 (IEM) 視窗會覆蓋透過 IME 輸入的文字。
- 我們已修正會導致使用者在關閉先前儲存的約會時看到下列錯誤的問題：「項目無法儲存，因為已被其他使用者或已在其他視窗中變更過。您要在預設資料夾為這個項目建立複本?」
- 我們已修正迷你行事曆中的日期無法針對日本使用者顯示粗體的問題。
- 我們已修正行事曆提醒無法針對一週內即將到來的會議顯示確切時間的問題。

### <a name="powerpoint"></a>PowerPoint

- 我們已修正在即時共同撰寫工作階段期間，使用者的目前狀態色彩指示器無法在共同撰寫文件庫中重新整理的問題。

### <a name="project"></a>Project

- 我們已修正以下問題：如果固定工期的任務已 100% 完成，但未指定 [實際完成日期]，則任務的完成 % 將顯示為低於 100%。

### <a name="word"></a>Word

- 我們已修正 HTML 超連結色彩無法正確呈現的問題。

### <a name="office-suite"></a>Office 套件

- 我們已修正非 HTTP 或 HTTPS 型 URL 未顯示在 [最近用過的] 清單中的問題。

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2007-june-12"></a>版本 2007：6 月 12 日
*版本 2007 (組建 13006.20002)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **使用資料類型從 Power BI 取得組織資料：** 現在，來自 Power BI 的 Excel 資料類型將推出給使用 Office 365 E5/A5 或 Microsoft 365 E5/A5 之組織的測試人員使用。 取得您所需的資訊，輕鬆地重新整理，對許多日常工作流程而言至關重要。 我們允許您透過 Excel 中的資料類型從 Power BI 存取公司或組織資訊，從而擴充您在試算表中引入連結資訊的能力。 [深入了解](https://support.office.com/article/cd8938ce-f963-444d-b82a-7140848241e9)<br />在[部落格文章](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)中查看詳細資料

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 我們已修正導致 Microsoft Access 無法識別連結的 SQL Server 資料表中的識別資料行的問題，這可能會導致不正確地將資料列報告為已刪除。

### <a name="excel"></a>Excel

- 我們已修正雷達圖的主要格線無法正確設定格式的問題。

### <a name="project"></a>Project

- 我們已修正當專案摘要工作，或專案 [開始/工作] 欄位變更時，ProjectBeforeTaskChange 事件無法觸發的問題。
- 我們已修正以下問題：比較基準重設或更新可能會變更時間分段預算成本/工時資源，且比較基準反映不正確的預算值。

### <a name="word"></a>Word

- 我們已修正使用 Office 功能區中的 [清除格式設定] 按鈕清除 [註解] 窗格中的格式設定時，無法運作的問題。
- 我們已修正當尺規未顯示時變更表格大小，導致在背景中執行其他應用程式開始閃爍的問題。
- 我們已修正在共同撰寫模式中，註解回覆有時候不會顯示在 [註解] 窗格中，而是顯示在 [修訂] 窗格中的問題。
- 我們已修正以下問題：如果 Word 經常開啟的文件清單多於 50 個，然後儲存並開啟文件後，即使該文件沒有進行任何修訂，也會顯示歷程記錄。

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2006-june-05"></a>版本 2006：6 月 5 日
*版本 2006 (組建 13001.20002)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **在 Excel 中進行共同作業時排序/篩選：** 您現在可以在與其他人共同作業時，同時排序和篩選您的 Excel 檔案。 這項新功能可防止您在共同撰寫文件時，受到其他使用者的排序和篩選的影響。

- **在 Excel 中建立來自 Power BI 資料的樞紐分析表：** 您可以在 Excel 中建立樞紐分析表，只要按幾下滑鼠，就能連線到儲存在 Power BI 的樞紐分析表。  如此一來，您就能獲得樞紐分析表和 Power BI 的最佳效果。 使用安全 Power BI 資料集的樞紐分析表以計算、摘要及分析資料。 [深入了解](https://support.office.com/article/31444a04-9c38-4dd7-9a45-22848c666884)

### <a name="outlook"></a>Outlook

- **快速重新開啟上一個工作階段的項目：** 我們新增了一個選項，可快速重新開啟上一個 Outlook 工作階段的項目。 不管 Outlook 當機或您將其關閉，您現在可以在重新開啟應用程式時快速重新啟動項目。 這項功能預設為啟用。 若要將它關閉，請移至 [選項] > [一般] > [啟動選項]。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 我們已修正圖表座標軸上的自訂值無法正確套用的問題。
- 我們已修正包含多個含有定義名稱的公式會導致儲存檔案時間加長的問題。

### <a name="outlook"></a>Outlook

- 我們已修正以下問題：當使用多個不同解析度的監視器時，輸入法編輯器 (IEM) 視窗會覆蓋透過 IME 輸入的文字。
- 我們已修正在撰寫新電子郵件訊息時，檢視範本會導致當機的問題。
- 我們已修正在 Outlook 版本 1911之後，使用者無法使用 Exchange 2010 公用資料夾的問題。
- 我們已修正在 Office 功能區中，群組行事曆的 [分類] 按鈕已停用的問題。
- 我們已修正具有衝突連絡人的使用者在 Outlook 中遇到當機的問題。
- 我們已修正導致高 DPI 監視器上的使用者遺失資料夾屬性中的 [線上封存] 下拉式功能表的問題。
- 我們已修正當處理純文字電子郵件中的超連結時，導致使用者遇到 Outlook 當機的問題。
- 我們已修正會導致 Outlook 無法剖析使用 RFC2231 編碼的長檔名的問題。
- 我們已修正導致 Outlook 使用者在使用螢幕助讀程式時遇到間歇性當機的問題。

### <a name="powerpoint"></a>PowerPoint

- 我們已修正使用表單型驗證開啟伺服器設定的檔案時發生的問題。
- 我們已修正具有內嵌圖表/活頁簿的 PowerPoint 檔案可能會導致儲存檔案失敗的問題。
- 我們已修正使用者關閉的 [註解] 窗格會自動重新開啟的問題。
- 我們已修正某張投影片的投影片編輯工具會在下一張投影片上重疊的問題。

### <a name="project"></a>Project

- 我們已修正在刪除孤立工作的父計畫之後，無法刪除或重新指派孤立工作的問題。

### <a name="word"></a>Word

- 我們已修正 [註解] 窗格中的時間戳記不是根據系統地區設定時間的問題。
- 我們已修正網頁應用程式與傳統型應用程式之間的註解未同步處理的問題。

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)


## <a name="version-2006-may-29"></a>版本 2006：5 月 29 日
*版本 2006 (組建 12920.20000)*

### <a name="feature-updates"></a>功能更新
### <a name="outlook"></a>Outlook

- **新增至 Outlook 快顯通知的其他按鈕：** [快速動作] 按鈕，現在會於在 Windows 10 上執行 Outlook 時顯示在 Outlook 快顯通知中。

### <a name="powerpoint"></a>PowerPoint

- **PowerPoint 中改善的 Steam 影片效能：** 我們改善了 Microsoft Stream 影片的播放效能，將影片載入時間減至最少，以建立流暢的觀賞體驗。  您可以在 Microsoft Stream 上使用公司影片來建立更完善的簡報。

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題

### <a name="excel"></a>Excel

- 我們已修正在使用 OneDrive 時，Excel 偶爾會關閉的問題。
- 我們已修正在相同活頁簿中按一下加入書籤的超連結會導致活頁簿隱藏的問題。
- 我們已修正某些複製和貼上的圖表連結使用的是映射磁碟機位址，而不是通用位址的問題。
- 我們已修正當透過 Teams 共用 Excel 視窗時，使用 Ctrl+Shift+方向鍵捲動後，Excel 可能會無法回應的問題。

### <a name="powerpoint"></a>PowerPoint

- 我們已修正使用滑鼠滾輪縮放後，投影片並未置中的問題。

### <a name="word"></a>Word

- 我們已修正在 [註解] 窗格中複製及貼上文字無法顯示的問題。
- 我們已修正註解提示泡泡在100% 縮放比例中顯示模糊的問題。
- 我們已修正啟用原則 Word 2007 及更新版本的二進位檔案和範本會導致部分共同撰寫案例失敗的問題。
- 我們已修正具長路徑名稱 (大於 32K) 的檔案無法開啟，且未顯示適當的錯誤訊息的問題。

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)


## <a name="version-2006-may-22"></a>版本 2006：5 月 22 日
*版本 2006 (組建 12914.20000)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **儲存至釘選資料夾：** 釘選資料夾可讓您更輕鬆地儲存 Office 檔案。 我們收到了意見反應，使用者想更進一步控制儲存新檔案時可用的資料夾。 我們很高興地能為您提供新功能：在 [儲存] 對話方塊中釘選您的資料夾。 這項新功能可讓您更輕鬆地儲存 Word、Excel 和 PowerPoint 檔案。<br />在[部落格文章](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)中查看詳細資料

### <a name="powerpoint"></a>PowerPoint

- **儲存至釘選資料夾：** 釘選資料夾可讓您更輕鬆地儲存 Office 檔案。 我們收到了意見反應，使用者想更進一步控制儲存新檔案時可用的資料夾。 我們很高興地能為您提供新功能：在 [儲存] 對話方塊中釘選您的資料夾。 這項新功能可讓您更輕鬆地儲存 Word、Excel 和 PowerPoint 檔案。<br />在[部落格文章](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)中查看詳細資料

### <a name="word"></a>Word

- **儲存至釘選資料夾：** 釘選資料夾可讓您更輕鬆地儲存 Office 檔案。 我們收到了意見反應，使用者想更進一步控制儲存新檔案時可用的資料夾。 我們很高興地能為您提供新功能：在 [儲存] 對話方塊中釘選您的資料夾。 這項新功能可讓您更輕鬆地儲存 Word、Excel 和 PowerPoint 檔案。<br />在[部落格文章](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)中查看詳細資料

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 我們已修正因為增益集是以字母順序載入，而不是以使用者指定的順序載入，而顯示 [這個活頁簿目前正由其他活頁簿所參考中，不可關閉] 錯誤訊息的問題。
- 我們已修正管理 Excel 與部分協力廠商輔助技術應用程式之間的字型時發生記憶體損毀的問題。
- 我們已修正當增益集要求工作表 (包含使用 noSelect 鎖定的圖形) 上的主機項目時，Excel 可能當機的問題。

### <a name="outlook"></a>Outlook

- 我們已修正當使用者在資料夾之間移動項目時，Folder.BeforeItemMove 事件未正確觸發的問題。
- 我們已修正使用者在橫跨午夜臨界值的行事曆項目中看到顯示為 [全天] 事件的問題。
- 我們已修正當兩個增益集將按鈕新增到功能區中的相同群組時，Outlook 發生當機的問題。
- 我們已修正使用者無法與來賓使用者共用行事曆的問題。

### <a name="powerpoint"></a>PowerPoint

- 我們已修正放大和縮小簡報會造成縮放選取跑馬燈和滑鼠指標之間間隙的問題。

### <a name="project"></a>Project

- 我們已修正在按一下 [選項] 之後 Project 會當機的問題。

### <a name="word"></a>Word

- 我們已修正註解中的超連結無法正常運作的問題。
- 我們已修正放大和縮小簡報會造成縮放選取跑馬燈和滑鼠指標之間間隙的問題。
- 我們已修正無法將 HTML 貼入行事曆的 WordMail 的問題。
- 我們已修正在共同撰寫工作階段中回覆註解有時會導致 Word 凍結的問題。

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2006-may-15"></a>版本 2006：5 月 15 日
*版本 2006 (組建 12905.20000)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **建立 PDF 連線：** 連線至、匯入、重新整理 PDF 中的資料。 [深入了解](https://support.office.com/article/9967afd8-85ee-4df3-aa06-753bcc1a2724)

- **[自動套用] 或 [建議敏感度] 標籤：** Office 可以根據偵測到的敏感性內容來推薦或自動套用靈敏度標籤。

### <a name="outlook"></a>Outlook

- **找到您所需的資訊：** 使用資料夾、寄件者、日期、附件資訊等選項來縮小搜尋範圍。

### <a name="powerpoint"></a>PowerPoint

- **不需要簡報導覽裝置：有耳塞式耳機就夠了：** 使用您的 Surface Earbuds 控制 PowerPoint 簡報。 重要：您必須在 Windows 10 的 Surface 音訊應用程式中配對 Surface Earbuds，才能使用手勢來控制簡報。 在此取得 Windows 10 上 Surface 音訊應用程式入門的指示。 [深入了解](https://support.office.com/article/6319a6f3-ad69-44e6-a8ff-e79676423e4a)

- **[自動套用] 或 [建議敏感度] 標籤：** Office 可以根據偵測到的敏感性內容來推薦或自動套用靈敏度標籤。

### <a name="word"></a>Word

- **[自動套用] 或 [建議敏感度] 標籤：** Office 可以根據偵測到的敏感性內容來推薦或自動套用靈敏度標籤。

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題

### <a name="excel"></a>Excel
- 我們已修正在使用者刪除合併的欄時，造成執行時間增加的問題。
- <div>我們已修正導致印表機名稱在可用印表機清單中重複的問題。</div>

### <a name="powerpoint"></a>PowerPoint
- 我們已修正使用英文 (瑞士) (QWERTZ) 鍵盤時鍵盤快速鍵和拼字檢查無法正常運作的問題。

### <a name="word"></a>Word
- 我們已修正在空白文件中新增註解卻未執行任何動作的問題。
- 我們已修正在含有一百個以上專案的檔中插入或更新索引的問題會導致應用程式當機。
- 我們已修正具有自訂 xml 值的檔案在開啟時速度極度緩慢的問題。

### <a name="office-suite"></a>Office 套件
- 我們已修正 Microsoft Office 中 Visual Basic for Applications 中的問題，其中特定 VBA 專案參考了程式庫名稱或程式庫路徑中有 DBCS 字元的程式碼程式庫，因而在載入時被 Office 應用程式視為損毀。


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2006-may-08"></a>版本 2006：5 月 8 日
*版本 2006 (組建 12829.20000)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **使用動畫 GIF 分享您的故事：** Office 編輯器現已支援動畫 GIF，讓您的文件更加時髦。

### <a name="outlook"></a>Outlook

- **更好的結果—瞬間：** 我們更新了搜尋體驗，讓這個版本比以往更聰明、更快速，且更可靠。 [深入了解](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- **使用動畫 GIF 分享您的故事：** Office 編輯器現已支援動畫 GIF，讓您的文件更加時髦。

### <a name="powerpoint"></a>PowerPoint

- **使用動畫 GIF 分享您的故事：** Office 編輯器現已支援動畫 GIF，讓您的文件更加時髦。[深入了解](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01)

### <a name="word"></a>Word

- **使用動畫 GIF 分享您的故事：** Office 編輯器現已支援動畫 GIF，讓您的文件更加時髦。

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="office-suite"></a>Office 套件

- 我們已經研究並解決了在作業系統關閉後，透過 InTune 進行的 Office 365 專業增強版部署會暫停的問題。

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2005-may-01"></a>版本 2005：5 月 1 日
*版本 2005 (組建 12827.20030)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="outlook"></a>Outlook

- **電子郵件中的改良連結：** 當您包含檔案的連結時，檔案名會取代 URL。 您可以變更權限，讓所有收件者都能存取。 [深入了解](https://support.office.com/article/02040f47-bd56-4806-8311-fc913fed54c0)

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 修正圖表資料表無法正確呈現日期座標軸中的值的問題。
- 修正使用 [頁面配置] 或 [分頁預覽] 之後無法停用分頁符號的問題。
- 修正隱藏和取消隱藏具有系列資料的欄之後，圖表線條樣式可能會遺失的問題。
- 在已篩選清單中插入欄的時間會比預期更長。
- 當您使用舊版的「共用活頁簿」模式，嘗試為活頁簿的新工作表列出變更時，就會發生當機。
- 修正啟用 [負值以補色顯示] 選項後，可能無法儲存樞紐分析表中的自訂格式設定的問題。
- 修正如果選取 [負值以補色顯示] 選項，可能無法儲存樞紐分析表中單一資料點的自訂格式設定的問題。
- 這項變更修正在 CSV 檔案中上傳 '@' 字元時，會導致將 '@' 字元之後的字串轉換成公式的問題。
- 修正無法正確捨入 SEQUENCE 函數中十進位值的問題。

### <a name="outlook"></a>Outlook

- 解決導致使用者在 Outlook 桌面用戶端中按一下非常長的安全連結時，由於截斷而無法載入的問題。
- 修正當與伺服器同步處理時，名稱中包含 DBCS (雙位元組字元集) 字元的 Outlook 資料夾會間斷消失的問題。 為此，必須為 Outlook 設定 IMAP 帳戶，並在地區設定設定為日文的系統上執行。

### <a name="powerpoint"></a>PowerPoint

- 已修正問題：如果使用者建立了註解，但未張貼就關閉 [註解] 窗格，然後開啟新視窗、瀏覽多張投影片並關閉視窗，最後再開啟原始簡報中的 [註解] 窗格，將導致無法使用草稿註解。

### <a name="project"></a>Project

- 修正問題：如果 Project 連線至 Project Web App，且小數分隔符號是逗號，當新增延遲時，TaskDependencies Add 方法會失敗的問題。

### <a name="word"></a>Word

- 修正在 [共同作業] 模式時，在文件中插入註解並不總是成功的問題。
- 此變更修正在按一下 @ 提及時，[人員卡片] 會閃動的問題。
- 修正在關閉具有草稿註解的文件時，會提示使用者是否要在未儲存草稿註解的情況下關閉文件的問題。取消該提示會關閉文件，而非讓文件保持開啟。
- 修正翻譯已張貼的註解將導致「插入翻譯的文字失敗」錯誤的問題。
- 在 Web 檢視/沉浸式閱讀程式中，即使是在檢視中，按一下提示也會捲動到最上方。已修正此問題。
- 我們已修正一個問題，當嘗試使用新名稱儲存包含巨集的檔案時，無論使用者輸入什麼名稱，都會導致該檔案以.docx 副檔名和檔案名稱 WRO0004.docx 儲存，進而導致文件無法使用。

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)


## <a name="version-2005-april-24"></a>版本 2005：4 月 24 日
版本 2005 (組建 12816.20006)

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel
- 這項變更修正了即使 LINEST 函式傳回正確的值，圖表趨勢線的 R 平方值 (在強制 y 截距的情況下) 仍然不正確的問題。
- 此變更修正了自訂圖表趨勢線格式不一定會儲存的問題。

### <a name="outlook"></a>Outlook
- 修正了 Office 功能區中群組行事曆分類按鈕已停用的問題。
- 修正了企業客戶沒有執行或無法使用群組資料夾的問題，該問題會導致 Outlook 顯示「沒有回應」的訊息。

### <a name="powerpoint"></a>PowerPoint
- 修正了將滑鼠游標移到星號 (*) 符號，但不會顯示上一次更新文件的日期和使用者姓名。

### <a name="word"></a>Word
- 啟用 [顯示書籤] 選項不會顯示書籤。已修正此問題。
- 此變更修正了下列問題：如果已啟用 [顯示功能變數代碼，而非其值] 選項，則含有超連結的文字可能不會顯示。

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)


## <a name="version-2005-april-17"></a>版本 2005：4 月 17 日
*版本 2005 (組建 12810.20002)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel
- 已增加搭配圖表使用的 [自訂誤差線] 對話方塊上儲存格參照 [編輯] 控制項的大小。
- 在 Excel 2016 中使用數位簽章所儲存的活頁簿，會在於目前版本的 Excel 中開啟時導致簽章失效。
- 修正列印時表單控制項的核取方塊縮放問題。
- 在某些情況下，Application.Evaluate (VBA) 無法在使用者定義的函數中運作。
- 此變更會修正設定格式化的條件 (CF) 資訊無法正確儲存到 XLSB 檔案的問題。

### <a name="onenote"></a>OneNote
- 修正將分行符號儲存為垂直 Tab 的問題。

### <a name="outlook"></a>Outlook
- 解決會導致使用者無法將個人連絡人群組新增為會議出席者的問題。
- 解決會導致還有 2 個月時間的會議，無法在排程小幫手中顯示會議主題的問題。
- 解決會導致使用者在轉寄大型 HTML 郵件時看到郵件內文截斷的問題。
- 新增透過群組原則強制執行 S/MIME 預設登入設定的功能。
- 解決會導致為使用者主要信箱以外的信箱所建立的刪除規則變得無效的問題。
- 解決在轉寄加密郵件時導致捨棄附件的問題。

### <a name="project"></a>Project
- 在表單檢視中編輯前置/後續任務資料時，會觸發額外的 ProjectBeforeTaskChange 事件。
- 修正變更連結至 SharePoint 工作清單之專案的面板狀態欄位時，Project 可能當機的問題。
- 修正儲存使用舊版 Project 建立的專案時，Project 可能當機的問題。

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)


## <a name="version-2004-april-10"></a>版本 2004：4 月 10 日
*版本 2004 (組建 12730.20024)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="access"></a>Access

- **略過 [顯示資料表] 對話方塊，直接移至工作窗格，以及將資料表新增至關係和查詢的程序簡化：** 只要按一下四個索引標籤、將名稱多重選取、依文字搜尋，並從在您工作時維持開啟的工作窗格拖曳，即可新增資料表和查詢。

### <a name="excel"></a>Excel

- **M365 進階版內容選擇器：** 讓您的文件栩栩如生！ 探索數千個免費圖庫影像、圖示和貼圖 [深入了解](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)

### <a name="outlook"></a>Outlook

- **M365 進階版內容選擇器：** 讓您的文件栩栩如生！ 探索數千個免費圖庫影像、圖示和貼圖 [深入了解](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)

- **將圖片作為電子郵件的一部分傳送時，讓圖片保持高畫質：** 一個新 Outlook 設定，可讓您在隨著電子郵件內容傳送圖片時限制圖片壓縮

### <a name="powerpoint"></a>PowerPoint

- **M365 進階版內容選擇器：** 讓您的文件栩栩如生！ 探索數千個免費圖庫影像、圖示和貼圖 [深入了解](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)

- **在簡報時同步處理變更：** 即使簡報處於投影片放映模式，仍可即時同步處理所做的變更。

### <a name="word"></a>Word

- **M365 進階版內容選擇器：** 讓您的文件栩栩如生！ 探索數千個免費圖庫影像、圖示和貼圖 [深入了解](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)

- **標註私人複本：** 製作共用文件的私人複本，以建立只有您本人能夠看到的手寫筆記。 若要開始使用，請移至 [檢視] > [建立私人複本]。

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 修正工作窗格中表格的重新調整及重新整理問題。

### <a name="excel"></a>Excel

- 修正在工作表上選取儲存格範圍會導致只選取單一儲存格的問題。

- 修正在為含有 X 軸範圍的圖表縮減大小時，可能會導致 Excel 停止回應的問題。

- 修正插入使用者定義的圖表範本來作為預設值會導致其儲存為直條圖的問題。

- 修正當基礎資料儲存格沒有標題時，圖表上的資料標籤會以空白顯示的問題。

- 修正已啟用 R1C1 儲存格參照且正在共同撰寫/共用的 Excel 工作表，在將游標移到 [使用者目前狀態] 圖示上方時不會以 R1C1 模式顯示作用中儲存格的問題。

### <a name="outlook"></a>Outlook

- 解決會導致類別有時候會從電子郵件訊息中消失的問題。

- 解決會導致代理人在不同機器上所看到的共用信箱有不同資料夾階層的問題。

- 解決在嘗試檢視組織表單的屬性時，會導致使用者遇到當機的問題。

- 解決在變更機器上的時區時，會導致某些提醒無法觸發的問題。

### <a name="powerpoint"></a>PowerPoint

- 此變更修正了在 PowerPoint 或 Word 中呈現內嵌為 OLE 物件的舊版 Excel 圖表時可能不會永遠顯示圖表標題的問題。

- 我們已修正將文字從 Excel 複製到 PowerPoint 時可能會導致其格式設定發生變更的問題。

- 此變更修正了使用 [全字拼寫須相符] 來尋找特殊字元時，不一定能正常運作的問題。

### <a name="project"></a>Project

- 修正了當開啟保護實際工作的設定時，使用者無法輸入分時期基準工時的問題。

### <a name="word"></a>Word

- 此變更修正了將游標暫留在提示上不會醒目提示其卡片的問題。

- 此變更修正了使用套索選取工具時，群組圖形中的文字會暫時消失的問題。

- 此變更修正了在 PowerPoint 或 Word 中呈現內嵌為 OLE 物件的舊版 Excel 圖表時可能不會永遠顯示圖表標題的問題。

- 此變更修正了在雙頁檢視中建立註解時，註解錨點不一定會顯示的問題。

- 修正如果段落的樣式是連結至清單的樣式上階，則該清單的編號可能會遺失的問題。

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2004-march-27"></a>版本 2004：3 月 27 日
*版本 2004 (組建 12718.20010)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="outlook"></a>Outlook

- **在撰寫郵件時有新的選項可停用 @ 提及建議：** 您是否覺得 @ 提及的選擇器很煩人，一點都不好用？ 現在您可以視需要將其關閉了。

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook
- 解決了會讓 [附件工具] 中的 [儲存至雲端] 按鈕不見的問題。
- 解決了以下問題：當使用者從檢查程式視窗回覆受到數位版權管理的郵件，卻沒有所回覆郵件的擁有者權限時，使用者會無法新增簽名。
- 解決了以下問題：使用者無法從網頁位置將其他附件新增到先前建立的會議。

### <a name="powerpoint"></a>PowerPoint
- 此變更修正了會導致包含 emojis 的 PowerPoint 檔案在儲存時發生失敗的錯誤。

### <a name="project"></a>Project
- 修正了以下問題：如果執行 ' CustomFieldValueListGetItem' 且自訂欄位的查閱資料表不存在，系統會建立一個不應建立的空白查閱資料表。

### <a name="word"></a>Word
- 此變更修正了以下問題：從 [檢視] 功能表選取多個頁面時，其中的 [註解] 窗格會顯示為空白。

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2004-march-20"></a>版本 2004：3 月 20 日
*版本 2004 (組建 12711.20000)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="outlook"></a>Outlook

- **行事曆新版視覺效果：** 去年，我們提供了全新的郵件體驗，而今年將為您帶來嶄新的行事曆！ 有幾項更新是新穎卻令人孰悉的，您是經驗豐富的 Outlook 使用者，可以立即使用並提高生產力。

- **協助保護群組中的資料：** 建立群組時所選擇的「敏感度」標籤會套用到群組電子郵件、文件及小組網站

### <a name="powerpoint"></a>PowerPoint

- **在投影片放映期間更新投影片：** 在簡報期間，更新由其他作者變更的投影片。

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 此變更解決了處理格式錯誤或無效通訊協定資訊影像時所導致的延遲問題。

### <a name="outlook"></a>Outlook

- 此變更解決了處理格式錯誤或無效通訊協定資訊影像時所導致的延遲問題。

- 此變更修正了電子郵件草稿最新變更未更新的問題。

- 已修正在檔案上按一下滑鼠右鍵並使用「傳送到」功能無法運作的問題。

- 已修正如果使用者有自訂的 [通訊錄] 搜尋路徑，則 Outlook 的名稱解析範圍會限制為自訂路徑，而不是包括全域通訊清單 (GAL) 的問題。

- 已修正在一組傳回的搜尋結果中，依類別結果排序不會顯示類別色彩的問題。

### <a name="project"></a>Project

- 已修正當使用者按一下 [排程群組] 內 [工作] 功能區中的 [停用] 按鈕時，不會觸發 'ProjectBeforeTaskChange' Visual Basic Applications (VBA) 事件的問題。

- 如果您在 [表單類型] 檢視中設定前置任務或後置任務詳細資訊，則 ProjectBeforeTaskChange Visual Basic Applications (VBA) 事件不會一律擷取變更。 例如，如果刪除了某個相依性，並在表單上按一下 [確定]，則不會觸發該事件。 修正此問題。

- 修正在進行變更 (例如日期變更) 之後，實際工作成本 (ACWP) 的最新值不會顯示的問題。

- 修正使用「最近使用」(MRU) 功能表開啟專案時，會使用 [讀取/寫入] 存取權開啟專案的問題。

- 這項變更修正了如果您建立包含開始日期和時間 (但無工期) 的手動工作，則時間表上的時間顯示不正確的問題。

- 已修正使用回曆列印時間表時，會導致列印檢視中略過或重複一個月的問題。

- 這項變更解決了在團隊規劃中使用 GDI 物件時，可能導致 GDI 物件分配過多並產生記憶體不足的問題。

### <a name="word"></a>Word

- 已修正張貼留言功能停用的問題。

- 此變更解決了處理格式錯誤或無效通訊協定資訊影像時所導致的延遲問題。

- 這項變更解決了帳戶管理員不會分派訊息而導致協力廠商應用程式懸置的問題。

- 這項變更修正了目錄會使用文件中未包含的標題樣式進行更新的問題。

- 已修正在寄送文件時，儲存在 Word 文件中的數位簽章會被刪除的問題。

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2004-march-13"></a>版本 2004：3 月 13 日
*版本 2004 (組建 12703.20010)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新

### <a name="excel"></a>Excel
- **敏感度標籤**：您現在可以套用組織設定、用來提示您輸入自訂權限的敏感度標籤。 [深入了解](/microsoft-365/compliance/encryption-sensitivity-labels?preserve-view=true&view=o365-worldwide#let-users-assign-permissions)

### <a name="powerpoint"></a>PowerPoint
- **敏感度標籤**：您現在可以套用組織設定、用來提示您輸入自訂權限的敏感度標籤。 [深入了解](/microsoft-365/compliance/encryption-sensitivity-labels?preserve-view=true&view=o365-worldwide#let-users-assign-permissions)

### <a name="word"></a>Word
- **敏感度標籤**：您現在可以套用組織設定、用來提示您輸入自訂權限的敏感度標籤。 [深入了解](/microsoft-365/compliance/encryption-sensitivity-labels?preserve-view=true&view=o365-worldwide#let-users-assign-permissions)

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題

### <a name="access"></a>Access
- 修正國際版 Access 在使用者介面中顯示英文字串的問題。

### <a name="excel"></a>Excel
- 修正使用者在以程式設計方式編輯大量儲存格範圍時可能遇到的效能問題。
- 修正以日文環境開啟 CSV 檔案時發生的效能問題。

### <a name="outlook"></a>Outlook
- 解決將附件新增至郵件或從郵件拖放 (與透過功能表相對) 來儲存附件時，導致檔案的「上次修改」日期更新的問題。
- 解決會導致在展開的尋找窗格中按一下 Enter 時無法開始搜尋，而是會要求使用者按一下 [搜尋] 按鈕的問題。
- 修正將 [如果有，顯示使用者的照片] 選項停用時，搜尋不會顯示有關使用者的任何資訊的問題。

### <a name="project"></a>Project
- 修正無法正確計算摘要工作日期的問題。
- 修正不先執行 OpenUndoTransaction 方法就不能觸發 OnUndoOrRedo 事件的問題。

### <a name="word"></a>Word
- 修正輸入或編輯備註然後使用 Ctrl+A 時，會導致選取畫布中的文字，而不只是選取備註卡片內文字的問題。
- 我們已修正文件中的文字對齊，在使用 [快速列印] 進行列印之後嘗試進行編輯時變得混亂的問題。
- 我們已修正將兩份文件合併成一份文件時的問題。
- 修正標示的修訂若與方程式有關，在儲存檔案時可能會導致失敗的問題。

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2003-march-06"></a>版本 2003：3 月 6 日
*版本 2003 (組建 12624.20086)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 修正使用 Outlook Web Access 建立規則時不會保存到 Exchange 伺服器，並導致衝突的問題。
- 修正 Outlook 在深色模式中不會在 [寄件者:] 欄位中顯示下拉式清單的問題。
- 解決在其他應用程式中開啟某個檔案時，導致使用者無法透過檔案總管將該檔案附加至郵件訊息的問題。

### <a name="powerpoint"></a>PowerPoint

- 修正將滑鼠移至縮圖上時，建議的縮圖閃動的問題。 在某些情況下，這可能會導致 PowerPoint 當機。

### <a name="word"></a>Word

- 修正受保護無法編輯之文件的比較功能問題。

### <a name="office-suite"></a>Office 套件

- 修正 Word/Excel/PowerPoint 中的使用者主體名稱 (UPN) 不再區分大小寫，導致在 SharePoint 上使用檔案時較少發生失敗的問題。

- 修正 [檔案]\[選項] 對話方塊上的 [確定] 按鈕顯示為灰色停用狀態，但功能並未受影響的外觀問題。

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

## <a name="version-2003-february-28"></a>版本 2003：2 月 28 日
*版本 2003 (組建 12619.20002)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="outlook"></a>Outlook

- **IT 系統管理員的事件通知：** Microsoft 365 租用戶全域系統管理員和 Office 應用程式系統會在 Windows 版 Outlook 的新右側面板中收到影響其使用者的 Outlook 和 O365 Exchange 事件通知。 [深入了解](https://support.office.com/article/46c07f08-1277-41ce-b353-4e205e9da333)

### <a name="powerpoint"></a>PowerPoint

- **改善筆跡轉換圖形圖表製作體驗：** 繪製更完善的圖表，並將它轉換成您可處理的 Office 物件。[深入了解](https://support.office.com/article/f304ef73-9514-450b-9bb9-28c6057020f2)

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 已修正交叉分析篩選器中的文字在預覽列印中無法正確縮放的問題。

### <a name="outlook"></a>Outlook

- 解決將附件新增至郵件或從郵件拖放 (與透過功能表相對) 來儲存附件時，導致檔案的「上次修改」日期更新的問題。

### <a name="word"></a>Word

- 修正按 Tab 鍵導覽註解卡片時，註解編輯方塊上的焦點無法顯示的問題。

- 在方程式中插入控制項 (例如文字內容控制項)，然後儲存再開啟檔案，便會導致內容無法讀取的錯誤。

- 修正將先前使用密碼保護的檔案儲存到雲端儲存空間無法運作的問題。

### <a name="office-suite"></a>Office 套件

- 修正在 Word/Excel/PowerPoint 中開啟來自相同 SharePoint 文件庫的多個文件時，僅掃描開啟的第一個文件是否符合原則的問題。

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2003-february-21"></a>版本 2003：2 月 21 日
*版本 2003 (組建 12615.20000)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="office-suite"></a>Office 套件

- **挑選完美色彩：** 使用十六進位色彩代碼來選擇您想要的字型色彩、文字醒目提示等。

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題

### <a name="excel"></a>Excel
- 已修正使用者在重新命名樞紐分析表度量值時可能遇到的問題。
- 已修正使用者在使用 VBA 巨集清除範圍內容時可能遇到的效能問題。
- 修正當使用者執行與功能區互動的巨集時，導致 UI 快閃的問題。
- 修正當檔案中的第一個字為 TABLE 時，CSV 檔案載入錯誤的問題。
- 已修正當您在兩個具有不同縮放比例的活頁簿之間切換時，使用者可能遇到的當機問題。

### <a name="outlook"></a>Outlook
- 已解決當持續整夜執行 Outlook 時，導致使用者無法開啟公用資料夾訊息的問題。
- 已修正在新增 Gmail 帳戶的驗證工作流程中，[權限] 頁面上的 [允許] 和 [拒絕] 按鈕停用的爭用情況。
- 已解決即使已關閉記錄，在某些情況下仍導致 Outlook 異常產生記錄輸出的問題。

### <a name="word"></a>Word
- 修正當滑鼠指標暫留在註解卡片上方時，未醒目提示註解卡片的問題。
- 在使用中的文件共同撰寫工作階段期間，直接在註解卡片中新增影像可能會導致新增標籤。已修正此問題。

### <a name="office-suite"></a>Office 套件
- 當您將 Multichoice/Lookup/Managed-metadata 屬性與 Word/Excel/PowerPoint 文件一起使用並儲存至 SharePoint 文件庫時，這些屬性之前限制為 255 個字元。 當這些屬性超過 255 個字元時，這類文件就無法儲存。 在此變更中，此限制已增加到 2048 個字元。

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2003-february-14"></a>版本 2003：2 月 14 日
*版本 2003 (組建 12607.20000)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="outlook"></a>Outlook

- **受限 WiFi 網路的新體驗：** 是否曾經加入需要登入網頁的 WiFi 網路呢？ Outlook 現在會偵測這項要求並協助您取得連結。

### <a name="word"></a>Word

- **在繪圖工具箱中找到筆跡編輯器：** 選取 [繪圖]，然後選擇 [筆跡編輯器] 手寫筆以使用手指或數位筆編輯文件。 [深入了解](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)

### <a name="office-suite"></a>Office 套件

- **更清楚的狀態列圖示：** 狀態列圖示現在更容易查看

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 已解決導致使用者無法存取「空閒/忙碌選項」行事曆權限對話方塊的問題。

- 修正了開啟某些從不同時區傳送的週期性會議執行個體時，可能會導致出現警示：「很抱歉，無法開啟這此項目」的問題。

- 已解決從該郵件拖放附件後造成使用者無法重新開啟 .msg 檔案的問題。

- 修正從 Outlook 上傳檔案附件到 OneDrive 後，造成包含括號之附件名稱的檔案名稱被變更。

### <a name="powerpoint"></a>PowerPoint

- 修正儲存包含 Excel 圖表的 PowerPoint 或 Word 文件會導致失敗的問題。

### <a name="word"></a>Word

- 修正文件中的圖片在匯出成 PDF 後，會失去透明度的問題。

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-february-07"></a>版本 2002：2 月 7 日
*版本 2002 (組建 12527.20040)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="access"></a>Access

- **在查詢設計工具、SQL 檢視和關聯視窗中工作時更具生產力：** 在資料表上按一下滑鼠右鍵即可開啟、設計、調整大小及隱藏它。 在 SQL 檢視中搜尋及取代文字。 在 [關聯圖] 視窗中選取多個資料表。

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 此更新會修正使用 ADODB 的問題。VB 程式碼中的錄製程式物件可能會不正確地報告錯誤。

- 此更新修正可能會導致 Microsoft Access 無法識別連結的 SQL Server 資料表中的識別資料行的問題，這可能會導致不正確地將資料列報告為已刪除。

### <a name="excel"></a>Excel

- 修正使用「資料剖析」搭配動態陣列時，Excel 會當機的問題。

### <a name="outlook"></a>Outlook

- 修正以月檢視在行事曆中捲動時，無法顯示之前的行事曆活動的問題。

- 解決在 Citrix 環境中檢視 30 個以上的行事曆時，導致使用者遇到當機的問題。

### <a name="powerpoint"></a>PowerPoint

- 修正關閉檔案之後，如果有任何事件處理常式正在執行，PowerPoint 就不會立即將它從 [簡報] 集合中移除的問題。 因此，物件模型報告的開啟中簡報數目會不正確，且會防止關閉 PowerPoint。

- 修正具有深色螢光筆色彩的白色文字，在灰階中會以黑色列印的螢光筆問題。

### <a name="word"></a>Word

- 更新和瀏覽目錄時，有時可能會在文件上顯示灰色區域的問題。

- 修正共同撰寫文件時，可能不會保留根註解的草稿版本的問題。

- 已修正在註解卡片之間來回切換時，有時會顯示一開始選取的註解，並將某選取範圍醒目提示的問題。

- 修正在已撰寫註解但未張貼，且使用者嘗試儲存檔案的情況下，使用 [瀏覽] 來儲存檔案沒有作用的問題。

- 將 SlideTrack 啟用且 [註解] 窗格關閉時，Ctrl+Alt+M 可能無法開啟 [註解] 窗格的問題。

- 修正在表格中新增 @提及時可能發生錯誤訊息：「文件中的表格已經毀損」的問題。

### <a name="office-suite"></a>Office 套件

- 解決可能導致挪威耐諾斯克 (nn-no) 校訂工具套件安裝不正確的問題。

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)


[//]: # (DO NOT MODIFY ADMIN CENTER METADATA CONTENT START)
[//]: # (|Win32|DevMain|Insiders| |16.0.14301.20004|version-2108-july-09|)
[//]: # (|Win32|DevMain|Insiders| |16.0.14228.20044|version-2107-july-02|)
[//]: # (|Win32|DevMain|Insiders| |16.0.14217.20002|version-2107-june-25|)
[//]: # (|Win32|DevMain|Insiders| |16.0.14210.20004|version-2107-june-18|)
[//]: # (|Win32|DevMain|Insiders| |16.0.14204.20006|version-2107-june-11|)
[//]: # (|Win32|DevMain|Insiders| |16.0.14131.20008|version-2106-june-04|)
[//]: # (|Win32|DevMain|Insiders| |16.0.14122.20004|version-2106-may-28|)
[//]: # (|Win32|DevMain|Insiders| |16.0.14117.20000|version-2106-may-21|)
[//]: # (|Win32|DevMain|Insiders| |16.0.14107.20000|version-2106-may-14|)
[//]: # (|Win32|DevMain|Insiders| |16.0.14029.20000|version-2106-may-07|)
[//]: # (DO NOT MODIFY ADMIN CENTER METADATA CONTENT END)
