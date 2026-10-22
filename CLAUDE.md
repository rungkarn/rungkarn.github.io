# rungkarn.github.io

GitHub Pages repo สำหรับเว็บส่วนตัว — เผยแพร่ผ่าน branch `main`

## Deploy หน้าใหม่

1. สร้าง `<name>/index.html` เป็น **standalone HTML** (ต้องมี `<!doctype>`, `<html>`, `<head>`, `<body>` ครบ — ไม่ใช่ artifact fragment)
2. เพิ่ม `<li><a class="card">` block ใน root `index.html` ตามรูปแบบที่มีอยู่ (h2 title, p description, span.url)
3. `git add` → `git commit` → `git push`

## Style

- Landing page: Anuphan (display) + IBM Plex Sans Thai (body) + IBM Plex Mono
- Dark mode: `@media (prefers-color-scheme: dark)` บน `:root`
- แต่ละ subdirectory เป็น self-contained — ใช้ font/style ของตัวเองได้

## หน้าที่มีอยู่

- `claude-code-guide/` — คู่มือ Claude Code ภาษาไทย
- `stock-dashboard/` — Stock Trend Board
- `worm-docs/` — Worm Docs Navigator (FoodSERP)
