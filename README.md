# Support IndéFiscal

Page de support professionnelle pour l'application IndéFiscal.

## 🚀 Déploiement sur GitHub Pages

### Étape 1 : Créer un nouveau dépôt GitHub

1. Va sur [github.com](https://github.com) et connecte-toi
2. Clique sur **"New repository"** (ou "+" → "New repository")
3. Configure :
   - **Repository name** : `indefiscal-support`
   - **Description** : `Page de support pour l'application IndéFiscal`
   - **Public** ✅ (obligatoire pour GitHub Pages gratuit)
   - ❌ Ne coche PAS "Add a README file"
4. Clique sur **"Create repository"**

### Étape 2 : Uploader les fichiers

1. Sur la page du dépôt, clique sur **"uploading an existing file"**
2. Drag & drop les fichiers :
   - `index.html`
   - `README.md`
3. Clique sur **"Commit changes"**

### Étape 3 : Activer GitHub Pages

1. Dans ton dépôt `indefiscal-support`, clique sur **Settings** (⚙️)
2. Dans le menu de gauche, clique sur **Pages**
3. Dans **Source** :
   - **Branch** : `main`
   - **Folder** : `/ (root)`
4. Clique sur **Save**
5. ⏱️ Attends 1-2 minutes

### Étape 4 : Récupérer l'URL

Tu verras apparaître :
```
Your site is live at https://TON_USERNAME.github.io/indefiscal-support/
```

**C'est cette URL que tu vas mettre dans App Store Connect comme Support URL !**

### Étape 5 : Personnaliser le contenu

**IMPORTANT** : Avant de publier, modifie les éléments suivants dans `index.html` :

#### 1. Email de contact (2 endroits à modifier)

**Ligne 148** - Dans la boîte de contact :
```html
<p><strong>Email :</strong> <a href="mailto:contact@indefiscal.app">contact@indefiscal.app</a></p>
```
Remplace par ton vrai email :
```html
<p><strong>Email :</strong> <a href="mailto:ton.email@exemple.com">ton.email@exemple.com</a></p>
```

**Ligne 210, 285, 313** - Dans le texte :
```html
contact@indefiscal.app
```
Remplace par ton email.

#### 2. Liens vers la politique de confidentialité (2 endroits)

**Ligne 192** - Dans la FAQ :
```html
<a href="https://TON_USERNAME.github.io/indefiscal-privacy/" style="color: #007AFF;">politique de confidentialité</a>
```

**Ligne 310** - Dans les ressources :
```html
<a href="https://TON_USERNAME.github.io/indefiscal-privacy/" class="button">Lire la politique</a>
```

Remplace `TON_USERNAME` par ton nom d'utilisateur GitHub.

### Étape 6 : Ajouter l'URL dans App Store Connect

1. Va sur [App Store Connect](https://appstoreconnect.apple.com)
2. **Mes Apps** → **IndéFiscal** → **App Information**
3. Dans le champ **"Support URL"** :
   ```
   https://TON_USERNAME.github.io/indefiscal-support/
   ```
4. Clique sur **Save**

---

## 📝 Contenu de la page

La page de support inclut :

✅ **Contact direct** - Email mis en avant  
✅ **FAQ complète** - 8 questions fréquentes couvrant :
- Essai gratuit et abonnement
- Résiliation
- Sécurité et confidentialité des données
- Synchronisation bancaire (non requise)
- Seuils fiscaux 2025
- Export de données
- Fonctionnement hors ligne
- Dépassement de seuils

✅ **Signalement de bugs** - Instructions claires  
✅ **Suggestions d'amélioration** - Encouragement aux retours  
✅ **Ressources utiles** - Liens vers politique de confidentialité  
✅ **Délais de réponse** - Engagement transparent  
✅ **Design professionnel** - Responsive et aux couleurs d'IndéFiscal

---

## 🎨 Personnalisation avancée (optionnel)

### Modifier les couleurs

Le bleu principal (#007AFF) est utilisé partout. Pour le changer :

Recherche dans le fichier `#007AFF` et remplace par ta couleur :
- `#007AFF` → Couleur principale
- `#0051D5` → Couleur hover (plus foncée)

### Ajouter une section

Tu peux ajouter de nouvelles sections avant le `<footer>` :

```html
<h2>🆕 Titre de ta section</h2>
<p>Contenu de ta section</p>
```

### Modifier les délais de réponse

**Ligne 339-342** - Modifie selon tes capacités réelles :
```html
<li><strong>Questions générales :</strong> Réponse sous 48 heures ouvrées</li>
<li><strong>Bugs critiques :</strong> Prise en charge prioritaire sous 24 heures</li>
```

---

## 🔄 Mettre à jour la page plus tard

1. Modifie le fichier `index.html` localement
2. Va sur ton dépôt GitHub
3. Clique sur `index.html`
4. Clique sur l'icône crayon (Edit)
5. Copie-colle ton nouveau contenu
6. Clique sur **Commit changes**
7. La page se met à jour automatiquement en 1-2 minutes

---

## ✅ Checklist finale

- [ ] Dépôt GitHub `indefiscal-support` créé et public
- [ ] Fichiers uploadés
- [ ] GitHub Pages activé
- [ ] Email de contact personnalisé dans `index.html` (tous les endroits)
- [ ] Liens vers politique de confidentialité corrigés (TON_USERNAME)
- [ ] URL testée dans le navigateur
- [ ] URL ajoutée dans App Store Connect → App Information → Support URL
- [ ] Sauvegardé dans App Store Connect

---

## ❓ Questions fréquentes

**Puis-je utiliser un nom de domaine personnalisé ?**  
Oui ! GitHub Pages supporte les domaines personnalisés. Configure-le dans Settings → Pages → Custom domain.

**Dois-je créer une adresse email contact@indefiscal.app ?**  
Non, tu peux utiliser n'importe quelle adresse email (Gmail, Outlook, etc.). L'important est qu'elle soit professionnelle et que tu la consultes régulièrement.

**Puis-je modifier la page après avoir soumis l'app ?**  
Oui ! Tu peux modifier le contenu de ta page de support à tout moment sans avoir à resoumettre ton app à Apple.

---

**Support** : Si tu as des questions sur le déploiement de cette page, crée une issue sur le dépôt.

**Licence** : Ce document est fourni pour l'application IndéFiscal. Libre à toi de le modifier selon tes besoins.
