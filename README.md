\# Izihash<span>.</span>



<p align="center">

&#x20; <img src="favicon.png" alt="Izihash Logo" width="100"/>

</p>



> \*\*Vérificateur d'intégrité cryptographique 100% Local.\*\*



Izihash est un utilitaire web ultra-léger conçu pour vérifier l'intégrité de vos fichiers et textes sans jamais compromettre votre vie privée.



\*\*Le problème :\*\* Pour vérifier qu'un fichier téléchargé n'est pas corrompu ou vérolé, il faut calculer son empreinte (hash). La plupart des outils en ligne exigent d'uploader votre fichier sur leurs serveurs, ce qui pose un énorme problème de confidentialité pour les documents sensibles.



\*\*La solution Izihash :\*\* Le calcul de l'empreinte se fait directement dans la mémoire vive (RAM) de votre navigateur. Le fichier ne quitte JAMAIS votre ordinateur.



<p align="center">

&#x20; <a href="#"><strong> Essayer Izihash</strong></a>

</p>



\---



\## Sécurité \& Confidentialité par Design



Izihash démontre la puissance des capacités cryptographiques natives des navigateurs modernes (approche "Client-Side" pure).



&#x20;  \*\*Aucun upload serveur :\*\* Les données restent strictement sur votre machine.

&#x20;  \*\*Traitement en RAM :\*\* Le fichier est lu en mémoire tampon (`ArrayBuffer`), haché, puis la mémoire est libérée.

&#x20;  \*\*Fonctionne hors ligne :\*\* Une fois l'application chargée, vous pouvez couper votre connexion internet et hacher vos fichiers en toute sécurité.



\## Fonctionnalités



&#x20;  \*\*Hachage de fichiers :\*\* Supporte n'importe quel type de fichier, quelle que soit sa taille (limité uniquement par la RAM de votre appareil).

&#x20;  \*\*Hachage de texte :\*\* Pour la vérification de clés, mots de passe ou messages courts.

&#x20;  \*\*Algorithmes supportés :\*\* SHA-256 (standard de l'industrie), SHA-384, SHA-512.

&#x20;  \*\*Comparaison automatique :\*\* Collez le hash attendu, l'outil vous indique instantanément si les empreintes correspondent.

&#x20;  \*\*Multilingue :\*\* Français 🇫🇷, Anglais 🇺🇸, Allemand 🇩🇪.

&#x20;  \*\*Théming :\*\* Mode Clair et Mode Sombre.



\## Stack Technique



Fidèle à la philosophie de la suite Izi, ce projet est un modèle de minimalisme technique. Il tient dans \*\*un seul fichier\*\* HTML/CSS/JS et n'utilise aucune dépendance externe :



&#x20;  \*\*HTML5 / CSS3\*\* (Design responsive, Variables CSS, SVG natifs).

&#x20;  \*\*JavaScript Vanilla\*\*.

&#x20;  \*\*Web Crypto API\*\* (`crypto.subtle.digest`) : Utilise le moteur cryptographique du système d'exploitation sous-jacent pour des performances optimales.

&#x20;  \*\*File API\*\* (`FileReader` / `ArrayBuffer`) : Pour la lecture des fichiers en local.



\## Installation \& Déploiement



Le projet étant une Single Page Application (SPA) contenue dans un fichier unique, l'hébergement est d'une simplicité absolue.



1\.  Téléchargez le dépôt.

2\.  Ouvrez `index.html` dans votre navigateur pour une utilisation locale immédiate.

3\.  Pour un accès en ligne, uploadez le dossier sur \*\*Cloudflare Pages\*\*, GitHub Pages, ou tout serveur web basique (Nginx/Apache via Docker).



\## Licence



Ce projet est sous licence MIT. Voir le fichier \[LICENSE] pour plus de détails.

