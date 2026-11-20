# Marchés Connectés

**Plateforme numérique de gestion et d'encaissement des marchés municipaux**
Département de Pikine, Sénégal · 12 communes · 39 marchés

> Plateforme en ligne. Code source privé. Démonstration complète sur demande.

![Page d'accueil](captures/accueil-ordinateur.png)

---

## Le projet

Dans les marchés de la banlieue dakaroise, le ticket journalier des commerçants se paie encore en espèces, contre un ticket papier. Les recettes sont difficiles à suivre, les tickets ne prouvent rien et les impayés passent inaperçus.

**Marchés Connectés** remplace ce système par une plateforme simple :

- le commerçant paie son ticket depuis son téléphone, en quelques secondes ;
- chaque paiement est enregistré et ne peut être ni modifié ni effacé ;
- chaque responsable suit, en temps réel, ce qui le concerne, et seulement cela ;
- les recettes vont directement à la collectivité.

## Fonctionnalités principales

- **Site public** : présentation des communes et des marchés, carte des arrondissements, actualités.
- **Espace vendeur** : connexion simple pensée pour tous les commerçants, paiement du ticket, historique et reçus.
- **Espaces de pilotage** : un espace propre à chaque rôle (administration, maires, superviseurs de marché, contrôle), avec des droits réglables.
- **Paiement mobile** : Wave et Orange Money.
- **Application installable** sur téléphone et ordinateur, depuis le navigateur.
- **Tableaux de bord et rapports** : recettes par marché et par commune, impayés, exports.
- **Sécurité** : connexions surveillées, actions tracées, suppressions archivées.

![Page des marchés](captures/marches-ordinateur.png)

## Technologies

| Partie | Technologies |
|---|---|
| Interface | React 18, Tailwind CSS, application web installable (PWA) |
| Serveur | Laravel 12 (PHP 8.2), API REST |
| Base de données | MongoDB |
| Temps réel | Node.js, Socket.IO |
| Cartes et graphiques | Leaflet, Recharts |
| Paiements | Wave, Orange Money |
| Hébergement | Vercel, Render, MongoDB Atlas |

## Mon rôle

**Ibrahima Thiam** — fondateur du collectif **T-Tech** (jeunes développeurs et ingénieurs du numérique, Pikine).

Conception et développement de bout en bout : analyse du terrain, interface, serveur, base de données, paiements, sécurité, mise en ligne et suivi.

## Statut

Plateforme en ligne et opérationnelle. Présentation en cours auprès des collectivités du Département de Pikine.

---

*Le code source de ce projet est privé. Pour une démonstration, merci de me contacter via les coordonnées indiquées dans mon CV.*
