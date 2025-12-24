# Web de Publicació - Seguretat de Dades en Recerca Biomèdica

Aquest directori conté l''estructura completa per publicar el contingut a GitHub Pages.

## 📂 Estructura

```
web-publicacio/
├── index.html                 # Pàgina principal
├── assets/
│   └── css/
│       └── style.css         # Estils generals
├── guia/
│   ├── inici/
│   │   └── accio-urgent.html # Acció urgent 30 min
│   ├── eines/
│   │   └── cursor-analisi.html # Anàlisi Cursor
│   ├── protocols/
│   │   ├── xifrat-drive.html
│   │   └── email-segur.html
│   ├── fonaments/
│   ├── casos-practics/
│   └── recursos/
```

## 🚀 Com Publicar

### 1. Crear Repositori GitHub

```bash
cd web-publicacio
git init
git add .
git commit -m "Initial commit - Seguretat recerca biomèdica"
```

### 2. Pujar a GitHub

```bash
git remote add origin https://github.com/TU-USUARIO/seguretat-recerca-biomedica.git
git branch -M main
git push -u origin main
```

### 3. Activar GitHub Pages

1. Ves al repositori a GitHub
2. Settings → Pages
3. Source: `main` branch, `/ (root)`
4. Save

### 4. Accedir al lloc

URL: `https://TU-USUARIO.github.io/seguretat-recerca-biomedica/`

## ✅ Navegació Funcional

El lloc ja té navegació completa:
- Breadcrumbs en cada pàgina
- Navegació principal (nav)
- Enllaços relacionats
- Navegació seqüencial (anterior/següent)

## 📝 Contingut Inclòs

- ✅ Index.html amb landing page
- ✅ Acció urgent (30 min)
- ✅ Anàlisi Cursor
- ✅ CSS complet i responsive
- ⏳ Resta d''articles (afegir més seguint plantilla)

## 🎨 Personalització

Per afegir més articles, segueix l''estructura dels existents:
- Usa el mateix header i nav
- Manté breadcrumbs
- Afegeix enllaços relacionats al final
- Segueix el mateix estil CSS

## 📊 Estat del Projecte

- [x] Estructura creada
- [x] CSS responsive
- [x] Navegació funcional
- [x] 3 articles principals
- [ ] Resta d''articles (es poden afegir progressivament)
- [ ] Imatges de diagrames (si necessari)
