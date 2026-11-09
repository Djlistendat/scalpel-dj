# Scalpel DJ

Logiciel DJ gratuit pour Mac avec puce Apple, en français ou en anglais. Il retrouve tout seul ta bibliothèque Serato DJ Pro (sons, crates,
cues, boucles, grilles, pads du sampler), sans la copier ni la modifier, et il marche sans Internet.

## Télécharger

**[⬇ Scalpel DJ pour Mac (1,2 Go)](https://github.com/Djlistendat/scalpel-dj/releases/latest/download/Scalpel-DJ-Mac.zip)**

Ce lien donne toujours la dernière version. Les anciennes sont dans [Versions](https://github.com/Djlistendat/scalpel-dj/releases), et ce que chacune apporte dans l'[historique](HISTORIQUE.md).

## Historique des versions

**21 versions publiées depuis le 4 novembre 2026** (le projet a commencé le 18 octobre avec la 0.1). Les dernières :

- **[1.11](https://github.com/Djlistendat/scalpel-dj/releases/tag/v1.11)** (9 novembre 2026) : Mélodie, un éditeur façon Melodyne · Le son du stem, rejoué note par note · Façon Nora · Intro Lab complet sur le Mac · Anti-larsen refait (à tester) · Key lock juste
- **[1.09](https://github.com/Djlistendat/scalpel-dj/releases/tag/v1.09)** (9 novembre 2026) : Son Scalpel, une clarté propre · Le choix Coupé / Moyen / Fort agit dès le clic
- **[1.08](https://github.com/Djlistendat/scalpel-dj/releases/tag/v1.08)** (8 novembre 2026) : Intro Lab, un écran plus simple · Intro Lab garde ton agencement · Pré-écoute de l'edit avec sa forme d'onde
- **[1.07](https://github.com/Djlistendat/scalpel-dj/releases/tag/v1.07)** (8 novembre 2026) : Plus de craquements au scratch avec le Son Scalpel · Intro Lab : plus de mot coupé aux raccords · Intro Lab : la voix d'un autre passage

**[Tout l'historique, version par version →](HISTORIQUE.md)** (*English: [full version history](HISTORIQUE.md), English notes under each version.*)

## Moins de processeur que Serato DJ Pro

L'écran Mix (formes d'onde, plateaux, vu-mètres, chronos) est dessiné en entier par la carte graphique, en une seule
image. Mesuré sur un MacBook Air M1 (8 Go), plein écran, Pioneer DDJ-REV5 branchée, deux platines en lecture :

| | Scalpel DJ 1.03 | Serato DJ Pro 4 |
|---|---|---|
| Processeur de l'app | 50 % | 46 % |
| Affichage de macOS (WindowServer) | 22 % | 35 % |
| **Total** | **72 %** | **81 %** |

Le détail est dans les [notes de la 1.03](https://github.com/Djlistendat/scalpel-dj/releases/tag/v1.03).

## Ce qu'il faut

- Un Mac avec une puce Apple (M1 ou plus récent). Testé sur macOS 14 (Sonoma).
- Ta musique, rangée ou non avec Serato DJ Pro.
- Une table DJ si tu en as une. La Pioneer DJ DDJ-REV5 et la DJM-S9 sont essayées en vrai. D'autres sont prévues
  (la liste est dans « À lire.txt », dans le zip) : dis-nous si la tienne marche.

## Installer

1. Ouvre le zip, puis glisse « Scalpel DJ » dans le dossier Applications.
2. Ouvre Scalpel DJ. macOS dit qu'il ne peut pas vérifier l'app, parce qu'elle n'est pas passée par Apple :
   clique sur « Terminé ».
3. Va dans Réglages Système → Confidentialité et sécurité. Plus bas, macOS dit que Scalpel DJ a été bloqué :
   clique sur « Ouvrir quand même », puis confirme.
4. Au premier lancement, l'app demande l'accès à tes dossiers de musique, et au micro seulement si tu allumes
   l'autotune.

## Bon à savoir

- C'est gratuit. Rien ne passe par Internet : tout marche sans Wi-Fi en club.
- Scalpel DJ n'écrit jamais dans les fichiers de Serato ni dans tes sons. Rouvre Serato quand tu veux : tout y est
  comme avant.
- C'est une version en cours : garde Serato à côté le temps de t'y faire.
- Un bug, une table qui ne marche pas ? Dis-le à Dj ListenDat sur Instagram.
- Les licences des pièces écrites par d'autres sont dans l'app : clic droit sur Scalpel DJ → Afficher le contenu du
  paquet → Contents → Resources → Licences.

---

**In English.** Scalpel DJ is a free DJ app for Apple Silicon Macs (M1 or later). On first launch it finds your Serato
DJ Pro library by itself (tracks, crates, cues, loops, grids, sampler pads), without copying or changing it, and it
works offline. [Download the latest version](https://github.com/Djlistendat/scalpel-dj/releases/latest/download/Scalpel-DJ-Mac.zip).
With two decks playing on an M1 MacBook Air, it uses less CPU in total than Serato DJ Pro (72 % vs 81 %,
app + macOS display). To open it the first time: open it once, then System Settings → Privacy & Security → "Open Anyway".
The app speaks English too: Settings → Display → Language (a new install follows your Mac's language).

## Droits

**© 2026 Dj ListenDat. Tous droits réservés.** Scalpel DJ est gratuit à utiliser. Ce dépôt ne contient pas son code
source, et l'app n'est pas un logiciel libre : il est interdit de la copier, la décompiler, la désassembler, la
modifier, d'en reprendre le code, de la redistribuer ou de la revendre, en tout ou en partie, sans l'accord écrit de
Dj ListenDat. Pour la partager, envoie le lien de cette page.

**© 2026 Dj ListenDat. All rights reserved.** Scalpel DJ is free to use. This repository does not contain its source
code, and the app is not open source: you may not copy, decompile, disassemble, modify, reuse its code, redistribute or
resell it, in whole or in part, without Dj ListenDat's written permission. To share it, send the link to this page.

Scalpel DJ est fait par Dj ListenDat. Serato, Pioneer DJ et AlphaTheta sont des marques de leurs propriétaires.
Scalpel DJ n'est lié à aucune de ces sociétés.
