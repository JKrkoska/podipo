# PODIPO – PWA brána do Spreamu

## Rýchly návod
1) Doplň v `index.html` tvoje hlboké linky (BLOGY/VIDEÁ/KURZY/MENTORING): hľadaj `__BLOGS_URL__` atď.
2) Nahraj celý priečinok na GitHub Pages (napr. `jkrkoska.github.io/podipo/`) alebo do tvojho hostingu.
3) Otvor na mobile → Pridať na plochu → spustíš ako appku. Prihlásenie do Spreamu sa zachová.
4) Notifikácie: nastavíme cez OneSignal (potrebné APP ID + doména).

## Súbory
- `index.html` – UI, odkazy, inštalácia PWA
- `manifest.json` – názov, ikony, farby
- `sw.js` – jednoduchý service worker (cache shell)
- `icons/*` – placeholder ikony (nahraď vlastným logom 1024×1024, ostatné vygeneruj)
