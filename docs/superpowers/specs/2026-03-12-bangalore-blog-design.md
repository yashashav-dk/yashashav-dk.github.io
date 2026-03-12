# Bangalore Blog — GitHub Pages Site Design

## Overview
A personal blog on GitHub Pages (`yashashav-dk.github.io`) with a South Indian / Karnataka-inflected visual design. Pure HTML + CSS, no build tools. Blog structure with index page + individual post pages.

## First Post
"Stop Feeling Guilty About Progress" — a love letter to Bengaluru exploring EA, technology, automation, and what Bangalore teaches about progress.

## Color Palette
| Token | Hex | Name |
|---|---|---|
| Background | `#FEFDF5` | Jasmine White |
| Text | `#2C2420` | Warm Brown |
| Headings | `#9A031E` | Deep Carmine |
| Links | `#C83A00` | Temple Red |
| Accent border | `#D4A843` | Zari Gold |
| Accent highlight | `#FEC016` | Turmeric |
| Footer bg | `#8B3A2A` | Red Oxide |
| Date/tags | `#2E7F25` | Banana Leaf Green |
| Card bg | `#F5F0E8` | Ivory |
| Subtle text | `#8C8279` | Temple Stone |

## Typography
- Headings: Cormorant Garamond (600-700)
- Body: Alegreya (400, italic 400)
- Kannada: Noto Serif Kannada (400, 700)
- Base: 18px, line-height 1.75
- Max-width: ~720px centered

## Layout

### Index Page (`index.html`)
- Site title at top
- List of posts: title (linked), date, one-line excerpt
- Simple, no cards or grids
- Red oxide footer

### Post Page (`posts/*.html`)
- Hero image (full content-width)
- Post title + date
- Flowing prose with images at contextual breakpoints
- Kolam-inspired dot dividers between major sections (CSS-generated)
- Zari gold left-border on blockquotes
- Red oxide footer with attribution

## Images (freely licensed)
1. Koramangala Junction — opening section (Public Domain, Wikimedia)
2. Lalbagh Glass House — Lalbagh mention (CC BY-SA 3.0)
3. Cubbon Park canopy — morning walks (CC BY-SA 4.0)
4. Filter coffee in dabara — darshini section (CC BY-SA 3.0)
5. Bangalore auto-rickshaw — "baralla" mention (GFDL 1.2)
6. Church Street at night — Church Street mention (CC BY-SA 4.0)
7. Bangalore skyline from Lalbagh — tech/growth section (CC BY-SA 3.0)
8. Masala dosa — VV Puram mention (CC BY-SA 4.0)

## File Structure
```
/
├── index.html
├── posts/
│   └── stop-feeling-guilty-about-progress.html
├── css/
│   └── style.css
└── images/
    └── (downloaded image files)
```

## Design Details
- Subtle handloom-weave CSS texture on cards/sections
- Kolam dot-pattern section dividers (pure CSS)
- Responsive: works on mobile
- No JavaScript required
- All image attributions in footer or alt text
