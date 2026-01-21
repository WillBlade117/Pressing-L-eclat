<div align="center">

  <img src="https://astro.build/assets/press/astro-icon-dark.svg" width="100" alt="Logo Astro" />
  <br/>

  # 🧺 Pressing L'Éclat
  
  **Site vitrine ultra-rapide pour un commerce local Premium**
  
  [![Statut](https://img.shields.io/badge/Statut-En_Ligne-success?style=for-the-badge&logo=check)](https://demo.votre-domaine.com)
  [![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)](LICENSE)

  <p>
    <a href="https://l-eclat.william-sart.fr"><strong>Voir le site en direct »</strong></a>
    <br/>
    <br/>
    <a href="#-stack-technique">Stack Technique</a> •
    <a href="#-fonctionnalités">Fonctionnalités</a> •
    <a href="#-installation">Installation</a>
  </p>

</div>

---

## 📝 À propos du projet

**L'Éclat** est un projet de démonstration simulant la présence numérique d'un pressing écologique haut de gamme. L'objectif était de concevoir un site **statique et performant**, capable d'obtenir un score de 100/100 sur Google Lighthouse.

Le design s'éloigne des standards "cliniques" pour adopter une identité visuelle **"Stone & Amber"** (Pierre et Or), évoquant l'artisanat et le luxe.

## 🛠 Stack Technique

Ce projet utilise une architecture moderne **Jamstack** pour garantir sécurité et rapidité.

| Technologie | Usage | Badge |
| :--- | :--- | :--- |
| **Astro** | Framework Web | ![Astro](https://img.shields.io/badge/astro-%232C2052.svg?style=for-the-badge&logo=astro&logoColor=white) |
| **Tailwind CSS** | Styling & Design System | ![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white) |
| **JavaScript** | Logique (Menu, Animations) | ![JS](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E) |
| **o2switch** | Hébergement (cPanel) | ![o2switch](https://img.shields.io/badge/Host-o2switch-blue?style=for-the-badge&logo=server) |

## ✨ Fonctionnalités Clés

* 🚀 **Performance Extrême :** Génération de site statique (SSG). Aucun JavaScript inutile n'est chargé.
* 📱 **100% Responsive :** Menu mobile fluide, grilles adaptatives (Flexbox/Grid).
* 🎨 **Design System :** Palette de couleurs personnalisée (`stone` & `amber`) et typographie soignée (`Playfair Display`).
* 🔍 **SEO Ready :** Balises Méta dynamiques, Sitemap XML généré automatiquement, Données structurées (JSON-LD) pour le référencement local.
* ✨ **Micro-Interactions :** Animations au scroll (Reveal on scroll) et effets de survol.
* 🔒 **Sécurité :** Certificat SSL (Let's Encrypt).

## 📂 Structure du Projet

```bash
/
├── public/          # Fichiers statiques (Images, robots.txt)
├── src/
│   ├── components/  # Composants réutilisables (Header, Footer)
│   ├── layouts/     # Mise en page globale (SEO, Styles globaux)
│   └── pages/       # Pages du site (index, tarifs, services...)
├── astro.config.mjs # Configuration du framework
└── tailwind.config.mjs # Configuration du design