# <img src="https://play-lh.googleusercontent.com/rAgy3Oj1Iv_NAxTqlJTKpmwl9n862gyc-vcWda3ekS2_G8YtCm2D9csGwWgHFchsRu0" alt="" width="40"> &nbsp;&nbsp; **Filtrer les spams téléphoniques**

Les appels de démarchages et d’escroquerie (ils se confondent) se sont multipliés. La cause est que vos données personnelles ont été volées et vendues aux escrocs en tout genre.

[![BUY ME A COFFEE](https://img.shields.io/badge/BUY%20ME%20A%20COFFEE-ffffff?logo=buymeacoffee&style=for-the-badge&color=710067&logoColor=ffe071)](https://github.com/sponsors/Fred-Vatin)

<details>
<summary><b>Sommaire</b></summary>

1. [Les vols de données](#les-vols-de-donn%C3%A9es)
   1. [La revente de "fadettes" et géolocalisations par des agents d'opérateurs](#1-la-revente-de-fadettes-et-g%C3%A9olocalisations-par-des-agents-dop%C3%A9rateurs)
   2. [La fraude à la carte SIM ("SIM Swapping") avec complicité interne](#2-la-fraude-%C3%A0-la-carte-sim-sim-swapping-avec-complicit%C3%A9-interne)
   3. [Les vols de fichiers pour concurrence ou revente directe](#3-les-vols-de-fichiers-pour-concurrence-ou-revente-directe)
3. [Documentaires](#documentaires)
4. [Législation](#l%C3%A9gislation)
5. [Solution de blocage automatisé](#solution-de-blocage-automatis%C3%A9)
   1. [Installation](#installation)
6. [Configuration](#configuration)

</details>

> [!TIP]
> Pour toutes questions ou suggestions, RDV dans la section [Discussions](https://github.com/Fred-Vatin/Android-Call-Filter-Tutorial/discussions)

---

## Les vols de données

Généralement, les escrocs-démarcheurs ont au moins votre numéro. C’est suffisant pour démarrer une arnaque. Sauf qu’ils ont souvent bien plus que ça car des millions de données personnelles ont été dérobées ces dernières années. Des pirates ont pu hacker divers serveurs.
- Bouygues en 2025
- Free en 2024
- Viamedis et Almerys en 2024 (pros de la Santé)
- France Travail

Outre les pirates, il y a aussi des menaces internes. C'est un phénomène redouté par les experts en cybersécurité, car aucune barrière informatique ou pare-feu ne peut bloquer un employé qui possède des accès légitimes au système et décide de trahir son entreprise et ses clients.

En France et en Europe, plusieurs affaires marquantes ont illustré ce type de complicité ou de corruption. Mais énormément de fuites ont lieu chaque année en toute discretion dans les entreprises et les administrations où pullulent les employés peu scrupuleux qui arrondissent leurs fins de mois en vendant des données ciblées à leurs connaissances criminelles.

### 1. La revente de "fadettes" et géolocalisations par des agents d'opérateurs
C'est le cas le plus fréquent et le plus documenté. Des employés de niveau intermédiaire chez des opérateurs télécoms (Orange, SFR, Bouygues) sont régulièrement approchés par des criminels ou des détectives privés véreux.

- **Le mode opératoire** : L'employé utilise ses accès pour extraire des fiches clients, des listings d'appels (les "fadettes") ou des données de géolocalisation en temps réel.
- **L'objectif des criminels** : Ces fiches servent souvent au grand banditisme (pour surveiller des rivaux, préparer un règlement de comptes ou un cambriolage ciblé).
- **Exemple marquant** : Un réseau majeur a été démantelé en Suisse et en zone frontalière française, où des cadres moyens des trois principaux opérateurs du pays fournissaient, contre des centaines de milliers d'euros, des listings complets à des officines de renseignement privées liées à la criminalité.

### 2. La fraude à la carte SIM ("SIM Swapping") avec complicité interne
Pour pirater les comptes bancaires ou les comptes de cryptomonnaies de cibles précises, les cybercriminels ont besoin d’intercepter les SMS de double authentification.
- Des employés travaillant dans des boutiques de téléphonie ou des centres d'appels ont été condamnés pour avoir accepté des pots-de-vin (parfois quelques centaines d'euros par carte) afin de transférer le numéro de téléphone d'une victime sur une carte SIM vierge détenue par les criminels. En un instant, le criminel reçoit tous les SMS de la victime et peut vider ses comptes.

### 3. Les vols de fichiers pour concurrence ou revente directe
Parfois, la motivation est purement financière ou liée à une vengeance lors d'un départ de l'entreprise.
- **L'affaire T-Mobile** : Un employé de l'opérateur a extrait à lui seul les données personnelles de 1,5 million de clients dans le but explicite de les vendre sur le marché noir à des structures criminelles de phishing. Il a été arrêté avant que la base ne soit massivement diffusée.
- **En France** : La jurisprudence s'est durcie. Des salariés spécialisés ont déjà été condamnés à de la prison avec sursis et de lourdes amendes pour avoir copié l'intégralité du fichier client de leur employeur sur une clé USB juste avant une rupture conventionnelle ou un licenciement.

---

L'accumulation de ces fichiers volés permet aujourd'hui aux cybercriminels de croiser les bases de données. Un pirate peut utiliser votre numéro Free, votre numéro de sécurité sociale issu de France Travail et votre IBAN Bouygues pour monter une escroquerie parfaitement crédible.

Les données compromises sont beaucoup plus précises et peuvent inclure tout ou partie de:
- Identité (noms, prénoms, dates de naissance)
- Coordonnées (adresses postales, emails, numéros de téléphone)
- Informations contractuelles (offres souscrites) des organismes piratés et identifiant utilisé dans le contrat ou compte
- IBAN (relevés d'identité bancaire)
- Numéro de sécu
- Nom de l’assureur santé et garanties du contrat
- Historique et identifiant France Travail

Partez toujours du principe que toutes ces données sont dans la nature et que les criminels les possèdent.

## Documentaires

Pour comprendre l’ampleur du problème et l’impunité dont bénéficient les escrocs, regardez:

| Titre | Vidéo |
| :---:   | :---:   |
| ***[J’ai infiltré le réseau d’escrocs qui vous harcèlent au téléphone](https://www.youtube.com/watch?v=1HoU17dIEos)*** | <a href="https://www.youtube.com/watch?v=1HoU17dIEos" target="_blank"><img src="https://img.youtube.com/vi/1HoU17dIEos/maxresdefault.jpg" alt="Regarder la vidéo sur YouTube" width="200"></a> |
| ***[J’ai infiltré un réseau réseau d’arnaqueurs au SMS](https://www.youtube.com/watch?v=6Jv0EzXdQbk)*** | <a href="https://www.youtube.com/watch?v=6Jv0EzXdQbk" target="_blank"><img src="https://img.youtube.com/vi/6Jv0EzXdQbk/maxresdefault.jpg" alt="Regarder la vidéo sur YouTube" width="200"></a> |
| ***[Reportage JT France 2](https://www.youtube.com/watch?v=mK6BSudDc8k)*** | <a href="https://www.youtube.com/watch?v=mK6BSudDc8k" target="_blank"><img src="https://img.youtube.com/vi/mK6BSudDc8k/maxresdefault.jpg" alt="Regarder la vidéo sur YouTube" width="200"></a> |

## Législation

Une chance dans notre malheur qu’est l’impuissane et le laxisme de la justice française est que les numéros de démarchage sont encadrés par l’ARCEP. Ce type d’escrocs doit utiliser certains préfixes définis [ici](https://www.arcep.fr/la-regulation/grands-dossiers-thematiques-transverses/la-numerotation.html#c8961). Ils sont labellisés tels que : ***Numéros polyvalents vérifiés (pouvant être utilisés comme numéro d’appelant par des systèmes automatisés d’appels et d’envoi de messages)***. Ainsi, ces numéros sont facilement identifiables. Et cela va bien nous arranger pour tous les bloquer. De mon expérience, le blocage de ces seuls numéros élimine 99% des appels non sollicités.

Pour bloquer d’autres types de spams, qui sont tous des arnaques criminelles, il faudra utiliser d’autres méthodes que nous verrons.

## Solution de blocage automatisé

Pour les smartphones Android, bien qu’il existe quelques apps dans le play store qui font en partie le job, j’utilise une solution gratuite, sans pub, open source et bien plus complète.

On va pouvoir filtrer des plages de numéros, interroger automatiquement des annuaires anti-spams, filtrer les spoofers (ceux qui vous appellent avec le vrai numéro de votre banque) si l’infrastruture le permet.

### Installation

De même que votre PC utilise des `.exe` pour installer un logiciel, votre smartphone utilise des `.apk` pour installer des apps. Et ceci est relativement facile même pour l’utilisateur lambda. Malheureusement, progressivement à partir de la rentrée 2026, Google (propriétaire et fabriquant du système) va considérablement compliquer la procédure. Du moins pour Android 16 et supérieur. Je mettrai à jour le tutoriel à ce moment-là.

L’application se nomme [SpamBlocker](https://github.com/aj3423/SpamBlocker) et j’ai contribué à créer ou mettre à jour les filtres pour la France.

Pour la télécharger cliquez [ici](https://github.com/aj3423/SpamBlocker/releases/latest/download/app-release.apk) ou scannez ce QRCode avec l’appareil photo de votre smartphone ou l’application [Lens](https://play.google.com/store/apps/details?id=com.google.ar.lens):

<img width="100" alt="image" src="https://github.com/user-attachments/assets/1c3c5f16-d813-48be-ad30-724c5dabd336" />

Vous allez aussi avoir besoin de mon fichier de configuration. Téléchargez-le en cliquant [ici](https://github.com/Fred-Vatin/Android-Call-Filter-Tutorial/releases/latest/download/SpamBlocker-settings.gz) :

Dans votre smartphone, RDV dans vos fichiers téléchargés et cliquer sur `app-release.apk` pour l’installer. Une fois installé, lancez l’application **SpamBlocker**. Ça ressemble à ça.

<img width="150" alt="Screenshot_20260526-232549 - Copy" src="https://github.com/user-attachments/assets/8683d845-9471-4381-84f6-9de80e438398" />

Pour l’instant, rien de fou. C’est le journal d’appels et il est vide. De plus, l’application n’est pas active. Allez dans les **paramètres**.

<img width="150" alt="image" src="https://github.com/user-attachments/assets/39eb8a6c-7b4b-4dc0-aab5-75426fce58ef" />

Tout en bas, cliquez sur **Importer**.

<img width="300" alt="image" src="https://github.com/user-attachments/assets/41a24bcd-084b-4de5-aef4-d32231ad2536" />

Et sélectionner le fichier `SpamBlocker-settings.gz ` téléchargé plus tôt. **À ce moment-là il peut vous être demandé d’autoriser certaines choses afin que l’app puisse fonctionner. Acceptez tout.**

Désormais vos prochains appels seront filtrés silencieusement.

Quand ce sera le cas, il y aura une notification pour vous indiquer qu’un appel a été bloqué. Elle indique le numéro bloqué et par quelle règle.

<img width="300" alt="image" src="https://github.com/user-attachments/assets/bbb09b54-283a-4800-a81b-c6b99614e04e" />

Et pour voir le journal des appels, ouvrez l’app et cliquez sur l’icône en bas à gauche.

<img width="300" alt="Screenshot_20260526-232549" src="https://github.com/user-attachments/assets/84865206-6951-4f5b-aee2-98ad8a20601f" />

Les numéros en rouge ont été bloqués. Les numéros en vert ont été autorisés (aucun sur la capture d’écran). On y voit le pays émetteur et le nom du filtre appliqué.

Notez que cette configuration ne filtre que les appels et non les SMS. Lisez la suite si vous avez besoin d’activer le filtre SMS.

## Configuration

J’explique ici le détail de la configuration pour ceux que ça intéresse et qui voudraient aller plus loin. Allez dans les **paramètres** de l’app pour voir les correspondances aux références suivantes.

> [!TIP]
> Chaque paramètre possède une aide intégrée en appuyant sur les ❔

### Filtrage

C’est la partie où on active ou désactive le filtrage global. Ici, on active le filtre des appels uniquement car filtrer les SMS ici est techniquement difficile et peut briser une fonctionnalité ou un comportement ([détails](https://github.com/aj3423/SpamBlocker#how-it-works)).

<img width="300" alt="config - Copy" src="https://github.com/user-attachments/assets/1d01ee1a-051a-437b-ae00-deb6bfe05add" />

#### SMS

Chaque marque de smartphone Android a tendance à préinstaller ses apps propriétaires pour les appels et les SMS. Si vous recevez des SMS frauduleux un peu trop souvent, la première chose que vous pouvez faire est d’installer l’application SMS officielle de Google via le playstore [ici](https://play.google.com/store/apps/details?id=com.google.android.apps.messaging).

Une fois que vous l’avez définie comme app SMS par défaut, allez dans les paramètres pour vous assurer que le filtre antispam est actif.

<img width="300" alt="image" src="https://github.com/user-attachments/assets/27406a5d-b640-4141-8735-2e0f7b6e212c" /><img width="300" alt="image" src="https://github.com/user-attachments/assets/6223b015-eaae-4b95-9a2a-e3f3049f4b96" />

Si vous recevez un SMS qui vous semble suspect, faites une capture d’écran et envoyez-la à Gemini en lui demandant s’il pense que ce SMS est suspect. Si oui, signalez-le comme spam.

<img width="300" alt="google message" src="https://github.com/user-attachments/assets/34b0fc51-5f0f-4929-b6e5-14cf8b8fe164" />

> [!TIP]
> Apprenez à vous servir de Gemini sur votre smartphone. Il est un assistant fort utile pour répondre aux questions techniques.
> Demandez-lui par exemple comment faire une capture d’écran sur votre smartphone en lui indiquant la marque et le modèle.

Personnellement, ça fait longtemps que je n’ai pas reçu de SMS frauduleux en utilisant cette méthode. Google et les opérateurs ont progressé afin de filtrer ces messages en amont.

### Paramètres rapides

*Vous ne devriez pas avoir besoin de toucher cette section.*

<img width="300" alt="config - Copy" src="https://github.com/user-attachments/assets/39150528-b101-4888-a730-dd42079b99b0" />

Voici la configuration :
- Tous les numéros faisant partie de vos contacts seront toujours autorisés
- STIR: permet de bloquer les appels qui usurpent des numéros valides (banques, contacts, etc.). Le succès va dépendre de la modernité du réseau et de votre appareil. En France, les opérateurs sont censés de toute façon bloquer en amont les numéros dont le certificat est invalide mais des limitations techniques existent encore. ([détails](https://github.com/Fred-Vatin/Android-Call-Filter-Tutorial/wiki/STIR-SHAKEN-en-France-:-Obligation-et-Limites))
   - Par défaut, l’option `inclure non vérifié` est désactivée. À l’heure actuelle, l’activer pourrait bloquer des appels fiables bien qu’il soit probable que les opérateurs bloquent d’eux-mêmes les numéros français qui ne parviennent pas à s’authentifier. Pour les numéros étranger c’est une autre histoire mais vous n’avez de toute façon aucune raison de faire confiance à un numéro hors France.

---

[![BUY ME A COFFEE](https://img.shields.io/badge/BUY%20ME%20A%20COFFEE-ffffff?logo=buymeacoffee&style=for-the-badge&color=710067&logoColor=ffe071)](https://github.com/sponsors/Fred-Vatin)
