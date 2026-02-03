# Fujikura CT-110 / CT-111｜來源紀錄（供內部存檔，不需上線揭示）

- 生成日期：2026-01-13（Asia/Taipei）
- 適用頁面：`specialty/ct-110.html`（你目前稱的「舊版」：ct-110_old.html）
- 原則：規格/功能/適用範圍僅引用「Fujikura 官方 PDF 或 Fujikura 官方網站」；若舊版文案超出官方可證範圍，於本表標示為 **NO / CONFLICT** 以利你決策。

## 官方來源清單（可作為驗證依據）

1. **Fujikura Fusion Splicer 官方產品頁：Advanced Optical Fiber Cleaver CT110/111**
   - URL：https://www.fusionsplicer.fujikura.com/products/advanced-optical-fiber-cleaver-ct110-111/
   - 用途：CT110/111 產品定位、適用光纖（silica + cladding 80–250µm）、相容 Fiber holder（FH-100/FH110/FH-70）、RFID 與張力自動設定等功能敘述。

2. **Fujikura Europe 官方產品頁：CT110 (Automatic fibre cleaver)**
   - URL：https://www.europe.fujikura.com/markets/industrial/specialty-splicers-and-accessories/ct110/
   - 用途：應用場景（universities/R&D institutes/high power laser 等）、完整技術規格欄位（tension range、weight、RFID ISO 15693、modes、temperature 等）。

3. **原廠 PDF：fujikura-ct110-cleaver-datasheet.pdf**
   - 用途：你已在 NotebookLM 表 A 中完成的規格核對矩陣（CT-110 / CT-111）。

## Claim → Source 對照表（A/B/C 稽核式記錄）

| Claim（舊版頁面出現/暗示的句子） | Verified? | Correct value / 建議表述 | Official source | Location | Evidence quote（短摘錄） | Notes |
|---|---|---|---|---|---|---|
| 適用光纖包層直徑 80–250µm（silica fiber） | YES | Designed for cleaving silica fiber with 80 to 250µm cladding diameter. | Fusionsplicer.fujikura.com（CT110/111 產品頁） | Product intro | “designed for cleaving silica fiber with 80 to 250µm cladding diameter” |  |
| CT-111 支援角度切割（Angle cleaving） | YES | CT111 支援 angled cleaving；CT110 不支援（依 datasheet/規格表）。 | Fusionsplicer.fujikura.com（CT110/111 產品頁） | Product Variation | “Angle cleaving ― ✔” | CT110/CT111 差異細節以 datasheet 為準。 |
| 角度切割範圍約 0°–15°（CT-111） | YES | CT-111: Approx. 0° to 15°（CT-110: -）。 | Fujikura Europe（CT110 規格頁 / 或 datasheet） | Technical specification / Specs | “In addition … angled cleaving from approximately 0 to 15 degrees” | 若要引用範圍數字，優先用 datasheet 的對照表欄位。 |
| 相容 Fiber holder：FH-100 series / FH110 series / FH-70 series | YES | FH-100 series / FH110 series / FH-70 series（部分需轉接板）。 | Fusionsplicer.fujikura.com（CT110/111 產品頁） | Product Variation | “Fiber holder FH-100 series / FH110 series / FH-70 series” | FH-70 需 AD-CT110-FH70（同頁 footnote）。 |
| RFID：可辨識 fibre holder 並自動選擇 cleave program（需先用 PC 軟體設定） | YES | RFID tag + cleaving program assignment；需先用附帶 PC software 預先設定。 | Fusionsplicer.fujikura.com（CT110/111 產品頁） | Features / Wireless communication by RFID | “RFID tag … choose proper cleaving program… necessary … using the attached PC software” |  |
| Cleaving tension：自動設定（automatic setting / motorised auto tension) | YES | Cleaving tension automatic setting / motorised auto tension setting。 | Fusionsplicer.fujikura.com（CT110/111 產品頁） | Features / Cleaving tension automatic setting | “Cleaving tension automatic setting” | 細節/數值（如 0–900gf）以 datasheet 或 EU 規格頁記錄。 |
| Blade position：自動變換/自動調整（automatic changing） | YES | Blade position automatic changing / motorised blade position change。 | Fusionsplicer.fujikura.com（CT110/111 產品頁） | Features / Blade position automatic changing | “Blade position automatic changing” |  |
| 應用場景：universities / R&D optical institutes / high power laser / photonics / medical | YES | 可用於大學、R&D 光學研究機構、高功率雷射、光子產業與醫療應用等場景。 | Fujikura Europe（CT110 產品頁） | Applications | “universities, R&D optical institutes, high power laser, photonics … medical applications” | 屬定位/場景，不屬規格；但仍需官方可證。 |
| 張力設定範圍：0–900gf | YES | 0 to 900gf（tension setting range）。 | Fujikura Europe（CT110 產品頁） | Technical specification / TENSION SETTING RANGE | “0 to 900gf” |  |
| 典型切割角度：Avg 0.3°（125µm cladding） | YES | Avg 0.3°, cladding dia. 0.125mm。 | Fujikura Europe（CT110 產品頁） | Technical specification / CLEAVE ANGLE | “Avg 0.3°, cladding dia. 0.125mm” |  |
| 刀片壽命：約 200,000 次（250µm cladding） | YES | Approx. 200,000 fibre cleaves at cladding dia. 0.250mm。 | Fujikura Europe（CT110 產品頁） | Technical specification / BLADE LIFE | “Approx. 200,000 fibre cleaves … 0.250mm” | 與你 NotebookLM 表 A 一致。 |
| 尺寸：140(W)×106(D)×103.5(H) mm | YES | 140 [W] x 106 [D] x 103.5 [H]。 | Fujikura Europe（CT110 產品頁） | Technical specification / DIMENSION | “140 [W] x 106 [D] x 103.5 [H]” |  |
| 重量：CT110 約 810g（不含電池） | YES | Approx. 810g without battery。 | Fujikura Europe（CT110 產品頁） | Technical specification / WEIGHT | “Approx. 810g without battery” | CT111 重量需用 datasheet/對照表欄位。 |
| 無線通訊：RFID（ISO 15693） | YES | RFID: Compliant with ISO 15693。 | Fujikura Europe（CT110 產品頁） | Technical specification / WIRELESS COMMUNICATION | “RFID: Compliant with ISO 15693” |  |
| 切割模式：可儲存 10 組（switch 可選 3 組） | YES | 10 cleave modes can be saved; 3 can be selected by switch。 | Fujikura Europe（CT110 產品頁） | Technical specification / FIRMWARE CLEAVEMODE | “10 cleave modes can be saved … 3 … selected by the switch” |  |
| 操作溫度：0°C–40°C | YES | 0°C to 40°C。 | Fujikura Europe（CT110 產品頁） | Technical specification / OPERATING TEMPERATURE | “0°C to 40°C” |  |
| （SEO meta）專為 FSM-100 設計 | NO | 若要保留，需找到 Fujikura 官方來源明確寫「designed for FSM-100」。目前官方 CT110/111 頁未見此句。 | Fujikura 官方頁（已查 CT110/111 + EU CT110） | n/a | n/a | 此句目前在舊版 `<meta name="description">` 中出現，屬高風險宣稱。 |
| 『是 FSM-100 系列的最佳拍檔』 | PARTIAL | 可改成較可證的版本：『可與 FSM-100 系列同 FH-100/FH110 夾具系統搭配使用』。 | Fusionsplicer.fujikura.com（CT110/111 產品頁） | Product Variation | “Fiber holder FH-100 series / FH110 series …” | 『最佳拍檔』屬主觀語氣；若保留，建議至少在內部紀錄鏈到 FH-100 相容性證據。 |
| 支援大管徑光纖（LDF） | CONFLICT | 官方 CT110/111 明載 cladding 80–250µm；若你要宣稱 LDF（通常 >250µm），可能與官方規格衝突。 | Fusionsplicer.fujikura.com（CT110/111 產品頁） | Product intro / Product Variation | “80 to 250µm cladding diameter” | 舊版頁面 tag/hero bullet/首頁卡片有『LDF』字樣；但目前官方資料更像是 CT114/115/116 才對應 LDF。 |
| 支援 PM 保偏光纖（PM） | NO | CT110/111 官方頁未明列 PMF；若要宣稱 PMF，需找到 CT110/111 官方資料明確列出。 | Fusionsplicer.fujikura.com（CT110/111）+ EU CT110 | n/a | n/a | 若你有 datasheet 其他段落或 Fujikura 另一官方頁面列 PMF，才可改為 YES。 |
| 『低反射率應用首選』 | NO | 屬性能/應用主張；需官方資料有明確低反射/ORL 等敘述才可用。 | 目前未在官方 CT110/111 與 EU CT110 頁找到 | n/a | n/a |  |
| 『防止特殊光纖碎裂』『解決 LDF 易碎問題』 | NO | 屬效能/問題解決型主張；需官方資料明確寫出（例如對特定 fiber 類型/直徑/製程的改善）。 | 目前未在官方 CT110/111 與 EU CT110 頁找到 | n/a | n/a |  |
| 『光纖界的精密鑽石切割機』『不靠暴力敲擊…完美無瑕端面』 | OK (Marketing) | 可作為修辭，但避免搭配可量化效能（例如“完美無瑕/零缺陷”）以免被解讀為性能保證。 | 不需來源（純比喻） | n/a | n/a | 建議把『完美無瑕』改成『更一致的端面品質』會更安全。 |
| CT-111 重量：約 850g（不含電池） | YES | Approx. 850g without battery（CT111）。 | fujikura-ct110-cleaver-datasheet.pdf | Specifications（CT111 欄位） | “Weight [CT111] Approx. 850g without battery” | 此條以你 NotebookLM 表 A 為準；本檔作留存。 |
| CT-111 Twister：Equipped；CT-110：- | YES | CT111 Equipped / CT110 -。 | fujikura-ct110-cleaver-datasheet.pdf | Specifications / Fiber twister | “Fiber twister [CT110: -, CT111: Equipped]” |  |
| 標配 AC Adapter 料號：ADC-21 | YES | AC Adapter ADC-21。 | fujikura-ct110-cleaver-datasheet.pdf | Standard Package | “AC Adapter ADC-21” |  |
| 更換用刀片料號：CB-06A | YES | Blade for Replacement CB-06A。 | fujikura-ct110-cleaver-datasheet.pdf | Options | “Blade for Replacement CB-06A” |  |

## 舊版頁面中「需要你特別確認是否要承擔風險」的句子清單（快速索引）

- NO / CONFLICT 的條目若你仍要保留，建議至少在內部紀錄中留下『為何仍保留』的決策理由。
- 目前最關鍵的風險點是：**LDF/PM 的直接適用宣稱** 與 **“專為 FSM-100 設計”** 這兩類字眼。
