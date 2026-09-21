# CV
## CV en HTML CSS JS
* 1. Masquer la flèche par défaut sous WebKit/Chromium */
summary::-webkit-details-marker {
  display: none;
}

    * Masquer aussi le marqueur standard si nécessaire */
summary::marker {
  display: none;
}

* 2. Ajouter votre propre logo/icône via un pseudo-élément */
summary::before {
  content: "";
  display: inline-block;
  width: 16px;
  height: 16px;
  background-image: url('chemin-vers-votre-logo.svg');
  background-size: cover;
  margin-right: 8px;
  transition: transform 0.2s ease;
}

* 3. Faire pivoter ou changer l'icône quand le details est ouvert */
details[open] summary::before {
  transform: rotate(90deg); /* Rotation de l'icône */
}
## soft skills
### initiateur 1
* Pédagogie et communication (expliquer des consignes simples et complexes).
* Gestion de groupe et leadership (fédérer un collectif autour d'un objectif).
* Organisation et rigueur (gestion du matériel, respect des horaires et de la sécurité).
