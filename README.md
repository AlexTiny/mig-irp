# MIG IRP V6 — reconstrucție de la zero

Site static, fără framework și fără proces de build. GitHub Pages poate servi direct fișierele din rădăcina ramurii `main`.

## Publicare
1. Salvează/descărcă ZIP-ul și dezarhivează.
2. În repository `AlexTiny/mig-irp`, înlocuiește fișierele existente cu **conținutul** arhivei V6, păstrând structura folderelor (`assets/`, `servicii/`, `resurse/`, `legal/`). Nu încărca ZIP-ul ca atare.
3. GitHub → Settings → Pages → Deploy from a branch → `main` → `/ (root)`.
4. Verifică `https://alextiny.github.io/mig-irp/` după publicare.

## Notă importantă
Logo-ul `assets/img/brand-concept.svg` este un **concept**, nu un logo oficial confirmat. Înlocuiește-l cu identitatea originală când este disponibilă. Fotografia principală este generată original. Imaginea de referință aprobată este păstrată numai în `docs/` pentru comparație, nu folosită ca pagină statică.

## Conținut
- 3 categorii principale: SSM (7 servicii), SU (4), RSVTI (3)
- 14 pagini individuale de servicii, 3 articole resurse, pagini Despre, Contact și legale
- HTML semantic, CSS responsive, JS minimal; fără dependențe npm, fără bază de date
- Formularul **deschide aplicația de e-mail**, nu trimite automat

## Verificări înainte de lansare
- Confirmă documentele de autorizare și domeniul exact al serviciilor.
- Confirmă identitatea vizuală oficială și eventualele drepturi asupra logo-ului.
- Revizuiește juridic politicile de confidențialitate și actualitatea legislației.
- Nu interpreta exemplele editoriale ca studii de caz reale.
