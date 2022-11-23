# Reddit Video Maker Bot 🎥

Branche du projet de Lewis Menelaws : 

Ce projet à permis la naissance de la chaine youtube 

Patch : 
-  L'utilisateur peut modifier le thread reddit à scrape 
-  Le bot évite les thread NSFW qui seront systématiquement bloqués par Youtube short

Amélioration future : 
-  Le contenu généré à été flagué par l'algorithme de Tik tok qui à banni le compte. Expérimenter les limites de l'algorithme. 
Rendre le contenu "Tik tok approuved". 
-  Ajouter une fonctionnalité de choix de langue pour cibler le contenu en français pour viser la niche de la communauté française.

https://user-images.githubusercontent.com/6053155/170525726-2db23ae0-97b8-4bd1-8c95-00da60ce099f.mp4

All done WITHOUT video editing or asset compiling. Just pure ✨programming magic✨.

Created by Lewis Menelaws & [TMRRW](https://tmrrwinc.ca)

<a target="_blank" href="https://tmrrwinc.ca">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://user-images.githubusercontent.com/6053155/170528535-e274dc0b-7972-4b27-af22-637f8c370133.png">
  <source media="(prefers-color-scheme: light)" srcset="https://user-images.githubusercontent.com/6053155/170528582-cb6671e7-5a2f-4bd4-a048-0e6cfa54f0f7.png">
  <img src="https://user-images.githubusercontent.com/6053155/170528582-cb6671e7-5a2f-4bd4-a048-0e6cfa54f0f7.png" width="350">
</picture>

</a>

## Motivation 🤔

These videos on TikTok, YouTube and Instagram get MILLIONS of views across all platforms and require very little effort. The only original thing being done is the editing and gathering of all materials...

... but what if we can automate that process? 🤔

## Disclaimers 🚨

-   This is purely for fun purposes.
-   **At the moment**, this repository won't attempt to upload this content through this bot. It will give you a file that you will then have to upload manually. This is for the sake of avoiding any sort of community guideline issues.

## Requirements

-   Python 3.6+
-   Playwright (this should install automatically during installation)

## Installation 👩‍💻

1. Clone this repository

2. Run `pip3 install -r requirements.txt`
3. Run `playwright install` and `playwright install-deps`.
4. 
	4a **Automatic Install**: Run `python3 main.py` and type 'yes' to activate the setup assistant.

	4b **Manual Install**: Rename `.env.template` to `.env` and replace all values with the appropriate fields. To get Reddit keys (**required**), visit [the Reddit Apps page.](https://www.reddit.com/prefs/apps) TL;DR set up an app that is a "script". Copy your keys into the `.env` file, along with whether your account uses two-factor authentication.

5. Run `python3 main.py` (unless you chose automatic install, then the installer will automatically run main.py)
7. Enjoy 😎

