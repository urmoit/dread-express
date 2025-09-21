# Dread Express – Public Road-map

Legend  
🚂 = code   🎨 = art   🎧 = audio   📊 = design   🧪 = qa   📦 = build

## 0.1  ✅  (vertical slice – done)
- 5-min win/lose loop
- 1 train, 5 cars, 10 passengers, 1 monster
- Light-based terror meter
- Fuel/Doors/AC resource panic

## 0.2  🚧  (polish & first wishlist trailer)
Target date: 4 weeks from repo creation  
Goal: Steam page draft + 60-second trailer + public wishlist button

| Task | Owner | Tag | Notes |
|------|-------|-----|-------|
| Replace mannequins with stylised passenger meshes | @art | 🎨 | 3 variants, 2K tris max |
| Monster IK skin & 8 k → 2 K normals | @art | 🎨 | |
| Substance pass: car interior PBR kit | @art | 🎨 | tile-wall, grubby seats, metal floor |
| Niagara blood spurt on kill | @code | 🚂 | GPU 200 particles |
| Footstep & ambient sound mix | @audio | 🎧 | 3-layer mix, master EQ |
| Jumpscare sting (0.2 s silence → stab) | @audio | 🎧 | |
| Steam SDK integration + leaderboard stub | @code | 🚂 | BestTime, BestSave% |
| Capsule art 616×353 | @art | 🎨 | key art: train window + monster silhouette |
| Hero art 1920×620 | @art | 🎨 | |
| 5 screenshots (1920×1080) | @art | 📦 | no UI, 16:9 |
| 60-second trailer cut | @video | 📦 | 0-3 s hook, 3-45 s gameplay, 45-60 s CTA |
| Steam page draft (english) | @marketing | 📊 | short ≤ 300 char, long ≤ 1 000 char |
| Store build uploaded (private) | @build | 📦 | Shipping Win64, no dev symbols |
| Public wishlist button live | @marketing | 📦 | |
| Tag repo `v0.2-trailer` | @lead | 📦 | |

## 0.3  (content expansion)
- 3 monster types (crawler, leaper, shade)
- Night-/day cycle via exterior skylight
- 2 alternate train car layouts
- Random event cards (power outage, brake fire)
- Speed-run timer + replay exporter

## 0.4  (console ports & localisation)
- Xbox Series S GDK port
- PS5 (dev-kit) port
- JP / CN / ES localisation
- Achievements 1 000 G / Platinum

## 0.5  (1.0 ship)
- Final balance pass
- Release-day trailer
- Press kit
- Launch
