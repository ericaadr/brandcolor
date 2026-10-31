# erica.adr — Brand Colors

Warna dan font resmi brand **erica.adr**.

## Warna

| Peran | Nama | Hex |
|---|---|---|
| Utama | Red | `#980d11` |
| Utama | Cream | `#fff3ed` |
| Sekunder | Pink | `#ffbfb3` |
| Sekunder | Gold | `#d9b77c` |
| Tulisan | Black | `#000000` |
| Tulisan | Red | `#980d11` |
| Tulisan | Cream | `#fff3ed` |

Background default: `#fff3ed`.

## Font

| Peran | Font |
|---|---|
| Title | Montserrat |
| Subtitle 1 | Public Sans |
| Subtitle 2 | Soli Px (alternatif: Montserrat) |
| Body | Public Sans |
| Accent | Public Sans |

## File

- `tokens.json` — semua warna & font dalam format JSON
- `brand.css` — CSS variables (`var(--color-red)` dst.)
- `tailwind.config.js` — tema Tailwind (`bg-brand-red`, `font-title`, dst.)
- `index.html` — halaman preview palet
- `.claude/skills/erica-carousel/` — skill Claude untuk membuat carousel @erica.adr (+ contoh slide)
