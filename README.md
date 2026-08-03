# WebCraft — Site Agence Web

## 🚀 Déploiement rapide sur Vercel

### Étape 1 : Créer un compte GitHub
1. Va sur **github.com** et crée un compte (gratuit)
2. Clique sur **"New repository"**
3. Nom : `webcraft-site`
4. Laisse en **Public**, clique **Create**

### Étape 2 : Uploader le projet
1. Sur la page du repo, clique **"uploading an existing file"**
2. Glisse TOUT le contenu de ce dossier (pas le dossier lui-même, les fichiers dedans)
3. Clique **"Commit changes"**

### Étape 3 : Déployer sur Vercel
1. Va sur **vercel.com** et connecte-toi avec GitHub
2. Clique **"Add New → Project"**
3. Sélectionne ton repo **webcraft-site**
4. Framework : **Vite** (détecté automatiquement)
5. Clique **"Deploy"**
6. ✅ Ton site est en ligne en 1 minute !

### Étape 4 : Ajouter ton domaine
1. Achète un domaine sur **namecheap.com** ou **ovh.com** (~10€/an)
2. Dans Vercel → Settings → Domains → ajoute ton domaine
3. Suis les instructions DNS (2 min)

## 🛠 Développement local

```bash
npm install
npm run dev
```

Le site sera accessible sur `http://localhost:5173`

## 📁 Structure
- `src/App.jsx` — Le site complet
- `src/main.jsx` — Point d'entrée React
- `index.html` — HTML de base + SEO
- `public/` — Favicon et assets statiques

## 🔐 Admin
Accède au dashboard admin via `tonsite.com/#admin`
Mot de passe : `WebCraft2026!` (à changer dans src/App.jsx ligne ADMIN_PASS)
