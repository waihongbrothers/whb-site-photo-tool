[README.md](https://github.com/user-attachments/files/27392307/README.md)
# WHB Site Photo Tool

Web-based replacement for **PSTC (Photo Send To Customer)** preparation. Mark up site inspection photos and download annotated images — no Adobe Illustrator needed.

> Built to replace the manual PSTC step in the Project Team SOP (page 11–21). Salesmen now produce final PSTC images directly from the field; Project Coordinator no longer needs to redraw with AI.

---

## 🔗 Live URL

**`https://waihongbrothers.github.io/whb-site-photo-tool/`**

> Open on iPad / phone / PC. No login. No install.

---

## ⚡ Quick Start (5 steps)

1. **Project Info** — type Customer Name + last 4 digits of phone (used for the filename).
2. **Upload Photos** — pick any number of site photos.
3. **For each photo:**
   - Type the Site Address (e.g. `15, JALAN IMPIAN INDAH 9`).
   - Pick a **Part** (e.g. `Water Tank`) — the colour is set automatically.
   - Pick a **Tool** — Rectangle / Polygon / Line / Number / Select.
   - Mark up the photo. Use **🔍+ / 🔍−** to zoom for precision.
4. **(Optional)** Drag/resize the **Logo** box and **Watermark** in *Select* mode.
5. **Generate PSTC Images** — downloads `.jpg` (single photo) or `.zip` (multiple).

Output filename: `PSTC <N> - <NAME> <PHONE>.jpg`

---

## 🎨 Colour Code Reference (Project Team SOP, page 12)

| Colour | Parts |
|--------|-------|
| 🔴 Red | Roof Ridge, Roof Capping |
| 🟡 Yellow | Party Wall, Wall Flashing |
| 🟢 Green | Slab, Exhaust Pipe, Membrane |
| 🔵 Blue | V Gutter, Roof Gutter, Down Pipe |
| 🩵 Light Blue | Water Tank, Bathroom |
| 🩷 Pink | Roof, PU Injection, PU Coat |
| 🟣 Purple | Others |

You don't need to memorize the colours — just pick the **Part** and the tool handles the colour for you.

---

## 📱 Device Tips

**iPad / Tablet (recommended for field use)**
- Apple Pencil works best for precise polygon points.
- Use 🔍+ to zoom in before drawing thin lines.
- In **Select** mode, drag the logo box / watermark to reposition or resize.

**PC**
- Mouse drag to draw rectangles and lines.
- Polygon: click points → click **✓ Finish Polygon** to close.

**Phone**
- Works but cramped — use landscape mode.

---

## 🛠 Tool Reference

| Tool | What it does |
|------|--------------|
| ▭ Rectangle | Drag to draw a box |
| ⬠ Polygon | Click points → click **✓ Finish** to close |
| ／ Line | Drag for a straight line |
| A Number / Text | Tap on photo, type the label (1, 2, 3…) |
| ✋ Select | Move/resize/delete existing shapes and overlays |
| ↶ Undo | Remove the last shape |
| ✕ Delete Selected | Remove the currently selected shape |
| Clear All | Remove every mark on this photo |

---

## 📦 Output

- **Single photo** → downloads `PSTC 1 - JOHN 0452.jpg` directly.
- **Multiple photos** → downloads `PSTC - JOHN 0452.zip` containing one JPG per photo.

Each image already includes:
- Site address (BOLD)
- WHB logo
- Confidentiality watermark

→ Save to NAS following the existing folder structure (refer to SOP page 10, 25, 60).

---

## 🔧 Updating the Tool

Edit `index.html` → commit to this repo → GitHub Pages auto-publishes within 1–2 minutes. All users get the update on next page reload (no re-install).

---

## 📚 Reference

- Project Team SOP (29-08-2025) — `Downloads/Project Team SOP 29-08-2025 (1).pdf`
- Original PSTC sample — `Downloads/PSTC sample.pdf`

---

*Maintained by COO office. Issues / requests → message Lychee.*
