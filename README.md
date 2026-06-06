# 📇 iGSvcard — Patricia Hsue 數位名片

> **新學智科技有限公司 iGrowth Solutions Co., Ltd.**  
> 精密量測解決方案 · Semiconductor Test & Measurement

---

## 🌐 Live Links

| 頁面 | 說明 | 連結 |
|------|------|------|
| 🏠 **Design Selector** | 選擇名片設計入口 | [menu.html](https://pattyhsue.github.io/iGSvcard/menu.html) |
| 📄 **Design A — Classic** | 經典金線版 | [index.html](https://pattyhsue.github.io/iGSvcard/) |
| ✨ **Design C — Premium** | 流星鑽石動態版 | [index_design_c.html](https://pattyhsue.github.io/iGSvcard/index_design_c.html) |
| 📥 **vCard File** | 直接下載聯絡資料 | [PatriciaHsue_iGrowth.vcf](https://pattyhsue.github.io/iGSvcard/PatriciaHsue_iGrowth.vcf) |

---

## 👤 Contact Information

| Field | Value |
|-------|-------|
| **Name** | Patricia Hsue 徐桂梅 |
| **Title** | Senior Marketing Manager |
| **Company** | 新學智科技有限公司 iGrowth Solutions Co., Ltd. |
| **Mobile** | +886-926-185-085 |
| **Email** | igrowth.gai@gmail.com |
| **Website** | https://www.igrowthgai.com/ |
| **Address** | 新竹市東區力行一路1號1樓(B5-8), Taiwan |
| **VAT No.** | 28115572 |

---

## 🎨 Design Overview

### Design A — Classic (`index.html`)
- 深藍底色 Navy background with gold gradient accents
- 英文姓名 → 中文姓名 → 金色漸層裝飾線 → 職稱
- Gold shimmer name animation
- QR Code + 儲存名片 button

### Design C — Premium (`index_design_c.html`)
- 英文姓名 → 中文姓名 → 職稱 → 流星鑽石裝飾
- **🌠 Shooting Star Animation**: meteor flies left → right with tapered cone tail, micro-particle debris, and bow-shock flares
- **💎 Diamond Impact Flash**: `diamondImpact` keyframe synced to meteor arrival (42% @ 3.5s cycle)
- **Gradient ghost track**: faint orbital path beneath the meteor
- **10-round hardened**: cubic-bezier physics, tapered polygon tail, responsive mobile scaling

### 🏠 Menu Selector (`menu.html`)
- Dark navy starfield background with animated shooting stars
- Side-by-side preview thumbnails of both designs
- Feature tags + CTA buttons
- Fully responsive

---

## 📁 File Structure

```
igrowth_vcard/
├── menu.html                  # 🏠 Design selector landing page
├── index.html                 # 📄 Design A — Classic gold line
├── index_design_c.html        # ✨ Design C — Shooting star + diamond
├── PatriciaHsue_iGrowth.vcf   # 📥 vCard contact file (v3.0)
├── igs_logo.jpg               # Company logo
├── index_design_a.html        # (draft)
└── index_design_b.html        # (draft)
```

---

## 🛠 Tech Stack

- Pure **HTML5 + Vanilla CSS + SVG**
- Google Fonts: `Playfair Display` + `Inter`
- SVG animations: `@keyframes`, `feGaussianBlur`, radial/linear gradients
- QR Code: [goqr.me API](https://api.qrserver.com)
- No frameworks, no dependencies

---

## 📅 Changelog

| Date | Update |
|------|--------|
| 2026-06-06 | Add `menu.html` design selector page |
| 2026-06-06 | Add `index_design_c.html` — Shooting Star + Diamond (10-round hardened) |
| 2026-06-06 | Update VCF: `TITLE` → Senior Marketing Manager, add `EMAIL` field |
| 2026-06-06 | Initial release — `index.html` Classic Design A |

---

*Precision · Intelligence · Growth*  
*© 2026 新學智科技有限公司 iGrowth Solutions Co., Ltd.*
