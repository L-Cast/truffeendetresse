# 🌟 Truffe en Détresse - Site officiel

Bienvenue sur le dépôt du site officiel **Truffe en Détresse**, un jeu de société engagé en faveur des associations animalières 🐾  
Ce site présente notre histoire, le jeu, nos associations partenaires et permet aux visiteurs de s’inscrire à notre newsletter.

---

## 🚀 Mise en ligne avec GitHub Pages

Ce projet est hébergé gratuitement via **GitHub Pages**.

🔗 Site en ligne : [https://TON_PSEUDO.github.io/truffeendetresse/](https://TON_PSEUDO.github.io/truffeendetresse/)

---

## 🛠️ Structure

- `index.html` : page d’accueil complète (statique)
- Intégration de Tailwind CSS via CDN
- Formulaire d'inscription fonctionnel (à connecter à Formspree ou Getform)

---

## 🧪 Pour mettre à jour le site

1. Modifie le fichier `index.html` localement
2. Fais un `commit` puis un `push` sur la branche `main`
3. GitHub Pages déploie automatiquement les changements (pas besoin de build)

---

## 📬 Formulaire de contact

🔒 Pour respecter le RGPD, n'oublie pas :
- Ajouter une case à cocher de consentement
- Utiliser un service externe comme [Formspree](https://formspree.io) ou [Getform](https://getform.io)

📦 Exemple de code Formspree :
```html
<form action="https://formspree.io/f/tonID" method="POST">
  <input type="text" name="prenom" required>
  <input type="email" name="email" required>
  <label><input type="checkbox" required> J’accepte de recevoir des emails</label>
  <button type="submit">S’inscrire</button>
</form>
