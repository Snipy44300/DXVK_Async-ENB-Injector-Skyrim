Source : DXVK Async 1.10.3 Github


Anglais :

Bonjour!

Voici un mod qui vous permet d'utiliser DXVK-Async et votre ENB ensemble, sans conflits !
❓ À quoi ça sert ?

DXVK Async est un outil qui améliore les anciens jeux PC conçus pour DirectX (comme Skyrim, Fallout, etc.) en les convertissant pour utiliser Vulkan, une API graphique beaucoup plus moderne et efficace.

Voici ce que cela peut vous apporter :

🌟 Moins de bégaiements, grâce à la compilation des shaders d'arrière-plan.
💾 Meilleure gestion de la VRAM : fuites de mémoire réduites, meilleure utilisation des ressources – particulièrement utile avec de nombreux mods.
💥 Moins de crashs et une stabilité accrue lors de longues sessions de jeu.
🚀 Gains de FPS / meilleurs 1% de baisses dans de nombreuses situations (zones complexes, combats, etc.).
🔥 Une expérience de jeu globalement plus fluide, plus propre et plus agréable.

En bref : DXVK Async donne une seconde vie à votre jeu, améliorant les performances sans rien sacrifier.
🔧 Installation :

Étape 1 :
Téléchargez mes archives, accédez à votre dossier de jeu et déposez les fichiers dans le répertoire racine.
Si vous n’utilisez pas ENB, vous pouvez ignorer l’étape 2.

Étape 2 :
Ouvrez votre fichier enblocal.ini et tout en haut sous [PROXY], définissez-le comme ceci :

[PROXY]
EnableProxyLibrary=true
InitProxyFunctions=false
ProxyLibrary=d3d11_dxvkasync1_10_3.dll

Étape 3 :
Et voilà ! C'est super simple. Tout est maintenant installé et fonctionnel !
ℹ️ Informations complémentaires :

J'utilise intentionnellement DXVK Async 1.10.3, car les versions plus récentes peuvent provoquer des problèmes ou une instabilité avec certaines configurations modifiées.
J'ai testé les dernières versions de DXVK-GPLAsync, mais aucune ne semble fonctionner correctement pour le moment. Je surveillerai les prochaines mises à jour et fournirai une mise à niveau stable si nécessaire.

PS : Pour ceux qui connaissent bien DXVK et ses variantes, je n'utilise intentionnellement pas dxgi.dll, car dans certains cas, cela casse complètement le jeu.
Par exemple, NVIDIA Smooth Motion ne fonctionne pas avec lui et provoque des plantages instantanés.

------------

Français : 

Bonjour,  
Voici un mod qui vous permettra d'utiliser DXVK-Async avec votre ENB, sans aucun conflit !

---

À quoi ça sert ?  
DXVK Async, c’est un outil qui améliore les jeux PC conçus pour DirectX (comme Skyrim, Fallout, etc.) en les faisant passer sur une technologie plus moderne appelée Vulkan, bien plus rapide et fluide.

Voici globalement ce que cela peut apporter :

🌟 Moins de stutters (saccades), grâce au chargement des shaders en arrière-plan.  
💾 Meilleure gestion de la VRAM: moins de fuites mémoire, meilleure utilisation des ressources particulièrement utile avec beaucoup de mods.  
💥 Moins de crashs et plus de stabilité sur les longues sessions de jeu.  
🚀 Gains de FPS / meilleures 1% low FPS dans de nombreuses situations (zones complexes, combats, etc.).  
🔥 Une expérience de jeu plus fluide, plus propre et plus agréable.

En résumé : DXVK Async, c’est comme offrir une seconde jeunesse à votre jeu PC, en boostant ses performances sans rien sacrifier.

---

🔧 Installation :

Étape 1 :  
Récupérez mon archive, rendez-vous dans le dossier de votre jeu, et placez les fichiers à la racine.  

Étape 2 :  
Ouvrez votre fichier enblocal.ini (qui ce trouve à la racine de votre jeu), et tout en haut, dans la section [PROXY], modifiez comme ceci :

[PROCURATION]
EnableProxyLibrary=true
InitProxyFunctions=false
ProxyLibrary=d3d11_dxvkasync1_10_3.dll

Étape 3 :  
Et voilà, c’était simple ! Tout est bien installé.

---

ℹ️ Informations complémentaires :  
J’utilise volontairement la version DXVK Async 1.10.3.  
Les versions plus récentes peuvent poser des problèmes ou entraîner des instabilités avec certains modpacks.  
J’ai testé les dernières versions de DXVK-GPLAsync, mais aucune ne semble fonctionner correctement pour le moment.  
Je garde toutefois un œil sur les prochaines mises à jour afin de vous proposer une version stable si nécessaire.

PS : Pour ceux qui connaissent bien DXVK et ses variantes :  
Je n’utilise pas dxgi.dll volontairement, car dans certains cas, cela rend le jeu inutilisable.  
Par exemple, Smooth Motion de NVIDIA ne le supporte pas actuellement, et provoque un crash instantané du jeu. 
