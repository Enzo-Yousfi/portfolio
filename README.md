Template de portfolio pour le BUT MMI
===

Ce template permet de construire un portfolio statique pré-formatté à partir de données texte et images.
Il a été réalisé dans le cadre de la démarche portfolio des BUT MMI à l'IUT de Lannion.

Il utilise [Vite](https://vitejs.dev/), [React](https://fr.react.dev/) et [Tailwind.css](https://tailwindcss.com/)

Démo
---

[Voir la démo](https://mmi-lannion.github.io/template-portfolio-mmi/)

Prérequis
---

L'usage de ce template nécessite l'installation de [Node.js](https://nodejs.org/en), et un [compte GitHub](https://github.com/signup?ref_cta=Sign+up&ref_loc=header+logged+out&ref_page=%2F&source=header-home).

Dans le tutoriel d'installation, [GitHub Desktop](https://desktop.github.com/) et [Visual Studio Code](https://code.visualstudio.com/) sont également utilisés. Il est fortement recommandé de suivre ce tutoriel (et d'utiliser les mêmes outils), à moins de savoir ce que l'on fait ;)

Installation
---

1. Faire un fork du projet de template (depuis [cette page](https://github.com/MMI-Lannion/template-portfolio-mmi))

<img width="1138" alt="1" src="https://github.com/MMI-Lannion/template-portfolio-mmi/assets/80826481/e206e319-79f0-40a0-8da3-2494a11e2bb6">

<img width="790" alt="2" src="https://github.com/MMI-Lannion/template-portfolio-mmi/assets/80826481/3565966e-7e08-471d-898e-e47116ac457f">

2. Puis cloner le repository depuis GitHub Desktop

<img width="921" alt="3" src="https://github.com/MMI-Lannion/template-portfolio-mmi/assets/80826481/1dd75f45-9801-4da2-9c14-034d020c297e">

<img width="1014" alt="4" src="https://github.com/MMI-Lannion/template-portfolio-mmi/assets/80826481/b971ce2a-98b7-4d27-8a8e-0b621560bd27">


<img width="1023" alt="5" src="https://github.com/MMI-Lannion/template-portfolio-mmi/assets/80826481/7310e0b0-0e54-4804-8da0-b0176055ad65">

3. Ouvrir le repository dans Visual Studio Code
<img width="1024" alt="6" src="https://github.com/MMI-Lannion/template-portfolio-mmi/assets/80826481/2c174ed9-a300-4aa9-8980-a7131db319b4">

4. Ouvrir un nouveau terminal 
<img width="716" alt="8" src="https://github.com/MMI-Lannion/template-portfolio-mmi/assets/80826481/782f11b2-9cd7-4029-bd78-f6dce3984159">

5. Installer le projet avec la commande `npm install`

<img width="695" alt="9" src="https://github.com/MMI-Lannion/template-portfolio-mmi/assets/80826481/10218b24-2fd4-46ca-b1d3-4673d87ebebf">

6. Depuis le terminal la commande `npm run dev` lance un serveur local permettant de voir en direct les modifications apportées au template. Suivre le lien proposé pour ouvrir le site en local dans un navigateur.
<img width="638" alt="10" src="https://github.com/MMI-Lannion/template-portfolio-mmi/assets/80826481/6ae0bc5b-6173-4508-a79a-7a1cd31835e7">

7. Dans la suite, modifier le fichier `settings.json` pour y insérer vos informations. Les assets seront ajoutées dans le répertoire `assets`
   
<img width="1180" alt="7" src="https://github.com/MMI-Lannion/template-portfolio-mmi/assets/80826481/3e4f7880-6c1a-493c-9ecf-90101457025f">

Utilisation
---

### Fichiers à modifier 

Le contenu du site se modifie depuis le fichier `settings.json` dans le dossier `src/data`.

Toutes les images et icônes sont à placer dans le dossier `assets/media`.

Le CV téléchargeable est à placer dans le dossier `assets/download`

### Comment modifier le contenu ?

1. Nommer correctement vos fichiers images (vignettes de vos projets et votre photo de portrait) et copiez-les dans le répertoire `assets/media`.
   
2. Modifier le contenu du fichier `settings.json` avec vos informations. **Attention** à bien conserver le format et ne modifier que les valeurs à droite des clés (bien garder le nom des clés en bleu)

3. Il est possible d'ajouter autant de formations, de centres d'intérêts, de projets, de compétences et de contacts que l'on souhaite. Il suffit à chaque foit de copier-coller la structure. **Attention** également à bien respecter le format en exemple.
   
4. Pour modifier la liste de compétences mises en oeuvre dans un projet et profiter du code couleur dans les badges, les compétences doivent être choisies parmi :
   - "Anglais"
   - "Marketing"
   - "Comm"
   - "Écriture multimédia"
   - "Réseaux sociaux"
   - "3D"
   - "Graphisme"
   - "Audiovisuel"
   - "UI/UX"
   - "Dev Web"
   - "Entrepreneuriat"
   - "Gestion de projet"
  (Si la compétence ajoutée ne fait pas partie de cette liste, elle aparaîtra en gris)

5. Tous les noms de fichiers écrits dans le fichier `settings.json` doivent correspondre au nom des fichiers placés dans le répertoirte `assets`

### Enregistrement des modifications

Les modifications apportées au template doivent être régulièrement "enregistrées" (= _commitées_) en local puis _poussées_ sur le serveur depuis GitHub Desktop

1. A chaque modification des sources, GitHub Desktop propose de _commiter_ les modifications. Entrer un commentaire (significatif !) puis cliquer sur `Commit to main`
<img width="926" alt="11" src="https://github.com/MMI-Lannion/template-portfolio-mmi/assets/80826481/4852dbbf-b71c-468a-a3af-8508926470a2">

2. Après une série de modifications importantes, cliquer sur `Push origin` pour pousser sur le serveur distant les modifications.
<img width="1118" alt="12" src="https://github.com/MMI-Lannion/template-portfolio-mmi/assets/80826481/c66426a4-b423-49c8-b93d-39576d619739">

   
Déploiement
---

1. Vérifier que la version de développement (en local sur la machine) fonctionne bien, puis lancer la commande suivante dans un terminal :
   `npm run deploy`
   
2. Bravo ! Votre portfolio est déployé à l'adresse `_username_.github.io/portfolio` (où _username_ est votre identifiant GitHub)

3. À chaque modification du template, après avoir _pushé_ toutes les modifications, il faudra relancer la commande de déploiement pour voir appraître les modifications (léger délai possible)

