# 🚗 Express VTC 66 — Site Web Professionnel

Un site VTC professionnel inspiré du style **OUASS VTC** et des couleurs **Bolt**.  
Créé pour **Express VTC 66**, chauffeur VTC à Perpignan et toutes distances.  
Le site inclut un **formulaire de réservation** avec **estimation automatique du tarif**.

---

## 🌐 Fonctionnalités

- Design moderne vert foncé / vert Bolt (#05E279)
- Réservation express via **WhatsApp**
- Estimation automatique du prix :
  - 20 € pour 0 à 7 km
  - + 1,60 € par kilomètre au-delà
- Responsive (mobile & desktop)
- Sections : Services, Tarifs, Zone, Avis, Contact
- Logo intégré (base64)
- Bouton WhatsApp flottant

---

## 💰 Calcul du tarif

```
Si distance ≤ 7 km → 20 €
Sinon → 20 € + (distance - 7) × 1,60 €
```

### Exemples
| Distance | Prix estimé |
|-----------|-------------|
| 5 km      | 20 €        |
| 10 km     | 24,80 €     |
| 20 km     | 40 €        |

---

## 📦 Structure du projet

```
express-vtc-66-site.zip
└── index.html   ← page complète (HTML, CSS, JS inclus)
```

---

## 🚀 Mise en ligne

Tu peux déposer le fichier **index.html** :
- Sur [Netlify](https://www.netlify.com/) (glisser-déposer)
- Sur [GitHub Pages](https://pages.github.com/)
- Sur ton hébergement OVH (dans le dossier `/www`)

---

## 👨‍💼 Infos

- **Nom :** Express VTC 66  
- **SIREN :** 925 008 690  
- **Téléphone :** 06 85 61 89 83  
- **Email :** expressvtc66@gmail.com  
- **Zone :** Perpignan et toutes distances  
- **Créateur du site :** [Naudin Sylvain](mailto:expressvtc66@gmail.com)

---

🟢 *Projet web moderne réalisé avec soin et élégance façon Bolt.*
