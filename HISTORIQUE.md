# Scalpel DJ — historique des versions

Toutes les versions publiées, la plus récente en haut. Le projet a commencé le 18 octobre 2026 avec la 0.1 ; il est sur
GitHub depuis le 4 novembre (0.87). Aujourd'hui : **49 versions publiées** en 17 jours, plus de 80 versions de
travail avant. Les versions qui manquent (0.88, 0.91, 0.97, 1.10, 1.20, 1.24 à 1.29, 1.31, 1.34 à 1.37, 1.40 à 1.42, 1.52) ne sont jamais sorties seules : leurs nouveautés sont
dans la version suivante.

**English:** every release, newest first; the English notes are under « In English ».

[⬇ Télécharger la dernière version](https://github.com/Djlistendat/scalpel-dj/releases/latest/download/Scalpel-DJ-Mac.zip)

## 1.55 BETA — 21 novembre 2026

**Version BETA**, comme la 1.54 : les versions d'avant restent téléchargeables.

- **Le micro de la REV5 marche dans tous les cas** : La REV5 peut se mettre à envoyer le micro sur ses deux paires
  d’entrées USB (par exemple après être passée par un autre logiciel), même quand son utilitaire dit le contraire :
  Scalpel DJ ne voyait alors plus ta voix. Il retire maintenant de l’entrée le son qu’il envoie lui-même à la table,
  et garde ta voix seule, quel que soit l’état de la REV5 (au premier allumage, la voix reste coupée quelques
  secondes, le temps de mesurer ce retour assez finement pour qu’il ne fasse jamais larsen ; il est ensuite retiré à
  plus de 70 dB). Et la liste ENTRÉE ne propose plus « Entrées 3-4 » ni « Entrées 1-2 » : sur une REV5, elles
  renvoyaient la voix dans la table, un larsen numérique (bruit atroce, barre toute rouge) ; un réglage d’avant sur
  l’une d’elles revient sur « Micro de la REV5 ».

<details><summary>In English (November 21, 2026)</summary>

- **The REV5 mic works in every case**: The REV5 can start sending the mic on both pairs of its USB inputs (for
  example after going through another app), even when its utility says otherwise: Scalpel DJ then no longer saw your
  voice. It now removes from the input the sound it sends to the deck itself and keeps your voice alone, whatever
  state the REV5 is in (the first time it is turned on, the voice stays muted for a few seconds while this return is
  measured precisely enough never to feed back; it is then removed by more than 70 dB). And the INPUT list no longer
  offers “Inputs 3-4” or “Inputs 1-2”: on a REV5 they sent the voice back into the deck, a digital feedback loop
  (awful noise, bar all red); a previous setting on one of them switches back to “REV5 mic”.

</details>

## 1.54 BETA — 21 novembre 2026

**Version BETA**, comme la 1.53 : les versions d'avant restent téléchargeables.

- **Colonne Débit** : Une nouvelle colonne (menu des colonnes de la liste) montre le débit de chaque fichier : « 320
  kb/s », « ≈245 kb/s » pour un MP3 à débit variable (sa moyenne exacte), le débit d’un WAV, AIFF, FLAC ou M4A. Un son
  compressé sous 192 kb/s s’affiche en ambre ; si la recherche de doublons a mesuré qu’il vient d’une source moins
  bonne que son débit ne l’annonce (un « 320 » tiré d’un 128), en rouge. Elle se trie comme les autres. La case sans
  nom du menu des colonnes s’appelle maintenant « Pochettes ».
- **Ranger ma bibliothèque** : Déplace des sons ou des vidéos d’un disque à l’autre en un geste : clic droit, « Ranger
  ailleurs… », ou Réglages → Bibliothèque (par exemple : toutes les vidéos du Mac vers ton disque externe,
  sous-dossiers gardés). Chaque fichier est copié, relu, puis retiré ; ses crates, cues, réglages, analyse et journal
  le suivent dans Scalpel DJ, et Serato est mis à jour (Serato fermé), ses fichiers sauvegardés avant. « Annuler »
  remet tout comme avant.
- **Une crate sur plusieurs disques : une seule, comme dans Serato** : Une crate rangée sur plusieurs disques (le Mac,
  des disques externes) pouvait sortir en plusieurs exemplaires dans la liste : celle de la base de Serato restait à
  part, et un nom avec des accents pouvait être écrit autrement d’un disque à l’autre. Elle n’en fait plus qu’une,
  avec tous ses sons, d’où qu’ils viennent. Les dates préparées, les dossiers liés et les rangements faits dans
  Scalpel la suivent.
- **Écran de démarrage plus sobre** : La carte « Reprendre là où tu en étais » n’a plus de cadre vert ni d’anneau
  blanc autour du bouton : une seule couleur, celle du bouton principal.

<details><summary>In English (November 21, 2026)</summary>

- **Bitrate column**: A new column (list columns menu) shows each file’s bitrate: “320 kb/s”, “≈245 kb/s” for a
  variable-bitrate MP3 (its exact average), the bitrate of a WAV, AIFF, FLAC or M4A. A compressed track under 192 kb/s
  shows in amber; if the duplicate search measured that it comes from a lower-quality source than its bitrate suggests
  (a “320” made from a 128), in red. It sorts like the others. The unnamed box in the columns menu is now called
  “Artwork”.
- **Organize my library**: Move tracks or videos from one drive to another in one go: right-click, “Move to…”, or
  Settings → Library (for example: all the Mac’s videos to your external drive, subfolders kept). Each file is copied,
  checked, then removed; its crates, cues, settings, analysis and history follow it in Scalpel DJ, and Serato is
  updated (with Serato closed), its files backed up first. “Undo” puts everything back.
- **A crate on several drives: just one, like in Serato**: A crate stored on several drives (the Mac, external drives)
  could show up several times in the list: the one from Serato’s database stayed separate, and a name with accents
  could be written differently from one drive to another. It is now a single crate with all its tracks, wherever they
  come from. Prepared dates, linked folders and arrangements made in Scalpel follow it.
- **Calmer start screen**: The “Pick up where you left off” card no longer has a green frame or a white ring around
  the button: a single colour, the main button’s.

</details>

## 1.53 BETA — 20 novembre 2026

**Version BETA**, comme la 1.51 : les versions d'avant restent téléchargeables. Cette version reprend la 1.52, jamais
sortie seule : le son part sur la platine dès qu'il est décodé, et la forme d'onde est retravaillée (couleurs, contour,
Stems EQ).

- **MID baissé : la forme d’onde suit, comme dans Serato** : En Stems EQ, baisser MID (la mélodie) ne changeait
  presque rien à la forme d’onde, et au premier cran une copie grise du morceau apparaissait autour. Maintenant c’est
  le morceau lui-même, et chaque stem y garde sa part : couper la mélodie retire sa part entière (mesuré sur un vrai
  son : la surface en couleur baisse de 10 %, contre 3 % avant), avec la silhouette grise autour. Là où la mélodie
  joue seule, tout passe au gris. Un stem laissé seul (une voix) est toujours agrandi, sans saut quand on baisse les
  autres.
- **Formes d’onde en tons profonds et saturés** : Les mêmes repères (grave rouge, médium vert, aigu bleu), en couleurs
  saturées et profondes : rouge velours, vermillon, ambre, or foncé, émeraude, saphir, indigo. Riches sans être fluo,
  ni pâles, ni ternes.
- **Finitions partout** : Numéros de mesure de la forme d’onde lisibles (une petite pastille sous leur trait, ils
  étaient à moitié cachés) ; interrupteurs arrêtés plus discrets (bouton gris) ; titre de la soirée en cours entier
  dans le Journal ; sous-crates en retrait sous leur crate dans Bookings (au lieu du nom du parent répété et du leur
  coupé) ; étoiles des favoris, croix et boutons de lecture dessinés comme le reste des icônes (c’étaient des
  caractères).
- **Boutons principaux plus sobres** : « Nouvelle date », « + Soirée », « Choisir un dossier », « Exporter », «
  Démarrer » : clairs et brillants, texte noir, ils faisaient « jouet » à côté du reste. Ils prennent maintenant un
  ton profond de la couleur de ton skin, texte clair. La vue d’ensemble des platines perd aussi son halo brun autour
  des crêtes.
- **Noms entiers dans la bande FX et le sampler** : Les effets s’affichaient coupés (« Écho de ... », « Délai pin...
  ») : leur nom tient maintenant en entier (case du numéro plus fine, flèche du menu au survol, texte un peu plus
  petit seulement s’il le faut). Dans le sampler, un nom trop long garde le titre du son entier plutôt que « titre ·
  artiste » coupé ; l’artiste reste dans la bulle.
- **Forme d’onde plus nette, au contour continu** : Chaque instant était un trait de sa propre longueur : bords en
  escalier, « poils », couleurs qui sautaient d’un trait à l’autre, la basse en rayures. Le contour est maintenant une
  courbe continue, lissée le long du temps (sans flou en travers) : les coups de grosse caisse restent francs et la
  basse dessine ses ondulations. Toujours presque rien pour la carte graphique.
- **Le téléphone aussi** : La télécommande et le Studio du téléphone reprennent la nouvelle forme d’onde (contour
  continu, couleurs profondes), les pads de stems sombres à barre de couleur comme sur le Mac, les touches allumées en
  tons profonds, les capuchons des faders au même métal brossé, et des icônes dessinées à la place des caractères.
- **La forme d’onde des samples, et leur point de départ** : Chaque case du sampler montre la forme d’onde de son son,
  comme dans Serato. Dans ses réglages (clic droit), un clic ou un glisser sur la grande forme d’onde place le point
  de départ ; « Au premier son » saute le silence du début.
- **Le son joue dès qu’il est chargé** : L’analyse (volume, tonalité, empreinte) passait avant que le son parte sur la
  platine : 0,3 à 0,9 s d’attente, plus quand le Mac travaillait. Un son qui a déjà sa grille (Serato 5, posée à la
  main, ou déjà analysé par Scalpel) part maintenant sur la platine dès qu’il est décodé, et l’analyse finit derrière,
  sans rien couper.

<details><summary>In English (November 20, 2026)</summary>

- **Lower MID: the waveform follows, like in Serato**: In Stems EQ, lowering MID (the melody) barely changed the
  waveform, and at the first notch a grey copy of the track appeared around it. Now it is the track itself, and each
  stem keeps its share of it: cutting the melody removes its whole share (measured on a real track: the coloured area
  drops by 10 %, against 3 % before), with the grey silhouette around it. Where the melody plays alone, everything
  turns grey. A stem left on its own (a vocal) is still enlarged, with no jump as you bring the others down.
- **Waveforms in deep, saturated tones**: The same cues (red lows, green mids, blue highs), in saturated, deep
  colours: velvet red, vermilion, amber, dark gold, emerald, sapphire, indigo. Rich without being neon, pale or dull.
- **Finishing touches everywhere**: Waveform bar numbers readable (a small badge under their line, they were half
  hidden); switches that are off are quieter (grey knob); full title of the current night in the Journal; sub-crates
  indented under their crate in Bookings (instead of the parent’s name repeated and theirs cut off); favourite stars,
  close and play buttons drawn like the rest of the icons (they were characters).
- **Calmer main buttons**: “Nouvelle date”, “+ Soirée”, “Choisir un dossier”, “Exporter”, “Démarrer”: light and glossy
  with black text, they looked like a toy next to the rest. They now take a deep tone of your skin’s colour, with
  light text. The decks’ overview also loses the brown halo around the peaks.
- **Full names in the FX strip and the sampler**: Effects were shown cut off (“Écho de ...”, “Délai pin...”): their
  name now fits in full (slimmer number box, menu arrow on hover, slightly smaller text only when needed). In the
  sampler, a name that is too long keeps the sound’s full title rather than a cut-off “title · artist”; the artist
  stays in the tooltip.
- **Sharper waveform, with a continuous outline**: Each instant was a line of its own length: stair-step edges,
  “hairs”, colours jumping from one line to the next, the bass in stripes. The outline is now a continuous curve,
  smoothed along time (no blur across): kick drums stay crisp and the bass draws its waves. Still almost nothing for
  the graphics card.
- **The phone too**: The remote and the phone Studio get the new waveform (continuous outline, deep colours), dark
  stems pads with a colour bar like on the Mac, lit buttons in deep tones, fader caps in the same brushed metal, and
  drawn icons instead of characters.
- **Sample waveforms, and their start point**: Each sampler slot shows its sound’s waveform, like in Serato. In its
  settings (right-click), a click or drag on the large waveform sets the start point; “At first sound” skips the
  silence at the start.
- **The track plays as soon as it’s loaded**: The analysis (volume, key, fingerprint) ran before the track reached the
  deck: 0.3 to 0.9 s of waiting, more when the Mac was busy. A track that already has its beatgrid (Serato 5, set by
  hand, or already analysed by Scalpel) now reaches the deck as soon as it’s decoded, and the analysis finishes
  behind, without cutting anything.

</details>

## 1.51 BETA — 20 novembre 2026

**Version BETA**, comme la 1.50 : les versions d'avant restent téléchargeables. Cette version corrige ce qu'un long set
rejoué a montré : au bout d'une vingtaine de minutes, le calcul des stems faisait chauffer le Mac et tout ralentissait.

- **Le Mac ne s’essouffle plus au fil du set** : Un long set rejoué (70 sons d’une vraie soirée, une fausse REV5 qui
  envoie les messages de la vraie) allait bien pendant 23 minutes ; puis les stems prenaient 2 à 3 fois plus de temps,
  les chargements passaient de 1 s à 3 à 5 s et les lumières de la table répondaient jusqu’à 0,8 s en retard : le
  calcul des stems tournait sans arrêt et le Mac chauffait. Maintenant, la platine qu’on vient d’arrêter ne calcule
  plus que ses 30 s devant (la suite vient quand elle repart), et quand macOS dit le Mac chaud, les stems ne se
  calculent que 90 s devant la tête de lecture.
- **Pas de stems pour un mix d’une heure** : Un mix enregistré (plus de 20 min) demandait ses stems en entier : plus
  de 2 Go de mémoire, la mémoire du Mac tombée à 16 %, un chargement de 22 s. Ses stems ne se calculent plus tout
  seuls, et la platine dit pourquoi.
- **Le son choisi reste au milieu de la liste** : En parcourant la liste avec la molette BROWSE ou les flèches, le son
  choisi reste au milieu : on voit ce qui vient après. Un clic ne fait pas bouger la liste. Réglages → Bibliothèque →
  « Choix au milieu de la liste ».

<details><summary>In English (November 20, 2026)</summary>

- **The Mac no longer runs out of breath during a set**: A long replayed set (70 tracks from a real gig, a fake REV5
  sending the real one’s messages) ran fine for 23 minutes; then stems took 2 to 3 times longer, loads went from 1 s
  to 3–5 s and the controller lights answered up to 0.8 s late: stems were computed non-stop and the Mac heated up.
  Now the deck you just stopped only computes its next 30 s (the rest comes when it plays again), and when macOS says
  the Mac is hot, stems are only computed 90 s ahead of the playhead.
- **No stems for a one-hour mix**: A recorded mix (over 20 min) asked for its full stems: over 2 GB of memory, the
  Mac’s free memory down to 16 %, a 22 s load. Its stems are no longer computed on their own, and the deck says why.
- **The selected track stays in the middle of the list**: When you browse the list with the BROWSE knob or the arrow
  keys, the selected track stays in the middle: you see what comes next. A click doesn’t move the list. Settings →
  Library → “Selection centered in the list”.

</details>

## 1.50 BETA — 20 novembre 2026

**Version BETA**, comme la 1.49 : les versions d'avant restent téléchargeables. Cette version corrige ce qu'une soirée
sur la REV5 a montré : la table qui se figeait pendant les chargements, PLAY qui tardait pendant le calcul des stems, le
bouton GLISSER disparu ; et elle ajoute un journal de soirée.

- **Ta table ne se fige plus pendant un chargement** : La page interrogeait le moteur en attendant sa réponse (liste
  des cartes son, pour le micro) plusieurs fois par seconde ; pendant un chargement, chaque question attendait : la
  REV5, ses lumières et ses boutons répondaient en retard. Mesuré sur des chargements depuis un disque externe : 4,9 s de page
  bloquée sur 75 avant, 3 ms après. Et la liste des versions à vérifier (toute la bibliothèque, 170 ms d’un bloc) ne
  se recalcule plus à chaque chargement.
- **PLAY part tout de suite, même pendant le calcul des stems** : Les ordres d’une platine (PLAY, pause, tempo, EQ…)
  attendaient derrière les morceaux de stems en route vers le moteur : le bouton s’allumait, le son partait une fois
  la file vidée. Ils ont maintenant leur propre file.
- **Bouton GLISSER de retour, avec son interrupteur** : La pastille GLISSER était cachée par l’affichage natif (on
  n’en voyait que la lueur), et ne venait qu’à partir de 4 BPM d’écart. Elle revient pour tout écart, et le
  glissement s’arrête ou se remet d’un clic sur son bouton, à côté de Q (aussi dans Réglages → Transitions).
- **Proposer de mémoriser une transition : à toi de voir** : Le message « Transition notée… Mémoriser » a un bouton «
  Ne plus proposer », et un interrupteur dans Réglages → Versions et liens.
- **La liste défile sans petits sauts** : Un cran sur deux, toutes les lignes visibles étaient refaites (même avec le
  bouton BROWSE de la table) : 1 143 lignes refaites pour un geste qui en demande 55.
- **Journal de soirée** : Un fichier par soirée (Réglages → À propos → Montrer dans le Finder) : chargements, PLAY qui
  tarde, page ou moteur figés, erreurs. Si quelque chose ne va pas en soirée, ce fichier dit ce qui s’est passé.

<details><summary>In English (November 20, 2026)</summary>

- **Your controller no longer freezes while a track loads**: The page asked the engine for things and waited for the
  answer (the sound card list, for the mic) several times a second; during a load each question waited, so the REV5,
  its lights and its buttons answered late. Measured on loads from an external disk: 4.9 s of blocked page out of 75 before, 3
  ms after. And the list of versions to check (the whole library, 170 ms in one go) is no longer recomputed on every
  load.
- **PLAY starts right away, even while stems are being computed**: A deck’s commands (PLAY, pause, tempo, EQ…) waited
  behind the stem chunks on their way to the engine: the button lit up, the sound started once the queue was empty.
  They now have their own queue.
- **GLIDE button is back, with its on/off switch**: The GLIDE pill was hidden by the native display (only its glow
  showed), and only came from a 4 BPM gap. It now comes back for any gap, and the glide turns off or on with one
  click on its button, next to Q (also in Settings → Transitions).
- **Offer to save a transition: your call**: The “Transition noted… Save” message has a “Don’t offer again” button,
  and a switch in Settings → Versions and links.
- **The list scrolls without little jumps**: Every other step, all visible rows were rebuilt (also with the BROWSE
  knob of your controller): 1,143 rows rebuilt for a gesture that needs 55.
- **Gig log**: One file per gig (Settings → About → Show in Finder): track loads, slow PLAY, frozen page or engine,
  errors. If something goes wrong during a gig, this file tells what happened.

</details>

## 1.49 BETA — 19 novembre 2026

**Version BETA**, comme la 1.48 : pas encore essayée en soirée ; les versions d'avant restent téléchargeables. Cette version
s'occupe des DJ qui n'ont ni REV5 ni Serato : autres tables, autres logiciels.

- **Le son sur ta table, quelle que soit sa marque** : La carte son de ta table s’ouvre toute seule dès qu’elle est
  reconnue (Hercules, Numark, Traktor, Reloop, Denon…), plus seulement chez Pioneer. Avant, le son restait sur les
  haut-parleurs du Mac.
- **Une table inconnue n’est plus prise pour une REV5** : Une table que Scalpel DJ ne connaît pas recevait le plan
  MIDI, les lumières et le jog de la REV5, et ses faders restaient fermés : aucun son. Elle garde maintenant son nom,
  rien n’est fermé, et un message propose le relevé guidé. Une table d’une autre marque passe aussi avant un clavier
  MIDI branché à côté.
- **Les tables qui mixent elles-mêmes** : Rane Seventy et Seventy-Two, DJM-S3, A9, 900NXS2, Xone:96, Numark Scratch,
  Reloop Elite, Denon X1850, Kontrol Z2 : chaque platine sur sa voie, comme les DJM-S. Avant, tout le mix arrivait sur
  une seule voie.
- **Jog d’une autre table : mesurer un tour** : Quand Scalpel DJ ne connaît pas les pas par tour du jog de ta table,
  Réglages → Contrôleur propose de mesurer un tour, gardé pour ce modèle. Avant, elle recevait la valeur de la REV5 et
  le scratch ne suivait pas la main.
- **Tes playlists de rekordbox, Traktor et VirtualDJ** : Réglages → Bibliothèque → Depuis un autre logiciel : les
  playlists de Traktor et les listes de VirtualDJ deviennent des crates, un export XML de rekordbox ou une playlist
  M3U aussi, avec les hot cues, les boucles et la grille de chaque son (rekordbox, Traktor). Ce que tu as posé à la
  main et ce qui vient de Serato passent toujours devant. Sur les MP3, rekordbox et Traktor ne comptent pas le début
  du fichier comme Scalpel DJ : les positions sont recalées d’après l’en-tête du fichier, puis vérifiées sur le son au
  premier chargement. Les dossiers des sons s’ouvrent s’il le faut. Au premier lancement sans Serato, Scalpel DJ le
  propose tout seul. Rien n’est écrit dans ces logiciels.
- **Aides de la REV5 seulement avec une REV5** : Les bulles et notes qui citaient les touches de la REV5 (« SHIFT +
  1/2X sur la REV5 ») ne s’affichent plus à ceux qui ont une autre table ; avec une REV5, rien ne change.
- **Table en USB seulement** : Une table qui ne parle qu’en USB (HID), pas en MIDI (Traktor Kontrol S4 MK3, X1…), est
  maintenant signalée : avant, rien ne disait qu’elle était vue.
- **Disque externe sans Serato** : Un disque branché sans bibliothèque Serato est maintenant proposé : un message
  demande quel dossier de musique y lire.
- **Autres tables : couleurs des pads, casque, DVS** : Les pads d’une table d’une autre marque s’allument sans
  couleurs au hasard ; l’aide « casque muet » et la proposition du DVS marchent aussi avec elle. « Valeurs par défaut
  » des couleurs remet la palette de ta table.
- **Sans Serato aussi** : Une bibliothèque vide dit maintenant comment ajouter ta musique, avec un bouton pour choisir
  un dossier, même si ton dossier Musique ne contient rien. L’écran de démarrage ne promet plus Serato à ceux qui ne
  l’ont pas.

<details><summary>In English (November 19, 2026)</summary>

- **Sound on your controller, whatever the brand**: Your controller’s sound card now opens on its own as soon as the
  controller is recognised (Hercules, Numark, Traktor, Reloop, Denon…), not only Pioneer gear. Before, the sound
  stayed on the Mac’s speakers.
- **An unknown controller is no longer treated as a REV5**: A controller Scalpel DJ didn’t know got the REV5’s MIDI
  map, lights and jog, and its faders stayed closed: no sound. It now keeps its own name, nothing is closed, and a
  message offers the guided learn. A controller from another brand is also chosen over a MIDI keyboard plugged in next
  to it.
- **Mixers that mix on their own**: Rane Seventy and Seventy-Two, DJM-S3, A9, 900NXS2, Xone:96, Numark Scratch, Reloop
  Elite, Denon X1850, Kontrol Z2: each deck on its own channel, like the DJM-S. Before, the whole mix arrived on a
  single channel.
- **Another controller’s jog: measure one turn**: When Scalpel DJ doesn’t know how many ticks per turn your
  controller’s jog sends, Settings → Controller offers to measure one turn, kept for that model. Before, it got the
  REV5’s value and scratching didn’t follow your hand.
- **Your rekordbox, Traktor and VirtualDJ playlists**: Settings → Library → From another DJ app: Traktor playlists and
  VirtualDJ lists become crates, and so do a rekordbox XML export or an M3U playlist, with each track’s hot cues,
  loops and beatgrid (rekordbox, Traktor). What you set by hand and what comes from Serato always come first. On MP3s,
  rekordbox and Traktor don’t count the start of the file the way Scalpel DJ does: positions are realigned from the
  file’s header, then checked against the audio on first load. The tracks’ folders open if needed. On first launch
  without Serato, Scalpel DJ offers it by itself. Nothing is written to those apps.
- **REV5 hints only with a REV5**: Tooltips and notes quoting REV5 buttons (“SHIFT + 1/2X on the REV5”) no longer show
  for people with another controller; with a REV5, nothing changes.
- **USB-only controller**: A controller that only talks USB (HID), not MIDI (Traktor Kontrol S4 MK3, X1…), is now
  reported: before, nothing said it was seen.
- **External disk without Serato**: A disk plugged in without a Serato library is now offered: a message asks which
  music folder to read on it.
- **Other controllers: pad colours, headphones, DVS**: Pads on another brand’s controller light up without random
  colours; the “silent headphones” help and the DVS offer work with it too. “Defaults” for colours restores your
  controller’s palette.
- **Without Serato too**: An empty library now tells you how to add your music, with a button to choose a folder, even
  when your Music folder is empty. The start screen no longer promises Serato to people who don’t have it.

</details>

## 1.48 BETA — 19 novembre 2026

**Version BETA**, comme la 1.47 : pas encore essayée en soirée ; les versions d'avant restent téléchargeables.

- **Moins éblouissant** : Plus aucun texte en blanc pur : le texte le plus clair est maintenant le gris clair de
  Serato. Les gros chiffres du disque, les titres des morceaux, les noms des pads et du sampler sont moins gras, et
  tout le reste est écrit un cran plus léger. Les capuchons de métal des faders et les potards ne sont plus presque
  blancs. Mesuré face à Serato DJ Pro sur le même écran : la bibliothèque était déjà à son niveau, c’est le haut de
  l’écran qui brillait trop.
- **Couleurs en tons profonds** : Les couleurs gardent leur teinte, leur richesse et leur rôle, mais dans des tons
  profonds au lieu de tons clairs qui éclatent aux yeux : un rouge sang, un or sombre, un bleu nuit, un violet
  profond. Cela vaut pour les onglets des pads, les pads de stems, le sampler, les anneaux des platines, les voyants
  et les alertes. Les pastilles de tonalité sont ton sur ton : fond profond, texte clair de la même teinte. Un petit
  texte en couleur garde une clarté lisible. L’onglet de pads choisi reste rempli de sa couleur, avec le texte clair ;
  un stem entendu garde sa barre de couleur et son nom s’écrit en clair, un stem coupé reste gris et barré.

<details><summary>In English (November 19, 2026)</summary>

- **Easier on the eyes**: No more pure white text: the brightest text is now Serato’s light grey. The big numbers on
  the platter, track titles, pad and sampler names are less bold, and everything else is written one step lighter. The
  metal fader caps and knobs are no longer almost white. Measured against Serato DJ Pro on the same screen: the
  library was already at its level, it was the top of the screen that was too bright.
- **Colours in deep tones**: Colours keep their hue, their richness and their role, but in deep tones instead of
  bright ones that glare: a blood red, a dark gold, a midnight blue, a deep purple. This goes for pad tabs, stem pads,
  the sampler, the platter rings, indicators and alerts. Key badges are tone on tone: deep background, light text of
  the same hue. Small coloured text keeps a readable lightness. The selected pad tab is still filled with its colour,
  with light text; a stem you hear keeps its colour bar and its name is written in light text, a muted stem stays grey
  and struck through.

</details>

## 1.47 BETA — 17 novembre 2026

**Version BETA**, comme la 1.46 : pas encore essayée en soirée ; les versions d'avant restent téléchargeables.

- **XDJ-RX3 : la molette BROWSE reste où tu as cliqué** : La molette de la table repartait dans les crates après un
  clic sur un morceau ou un chargement. Elle suit maintenant le volet cliqué en dernier (crates ou liste), comme dans
  Serato, et reste sur la liste après un chargement.
- **XDJ-RX3 : HOT CUE, LOOPS, SAMPLER, STEMS sur les boutons de mode** : Les quatre boutons de mode de la table
  donnent maintenant HOT CUE, LOOPS (BEAT LOOP), SAMPLER (SLIP LOOP) et STEMS (BEAT JUMP), les modes dont on se sert :
  Scalpel DJ n’a ni BEAT LOOP ni BEAT JUMP en pads. Avec SHIFT, EXTENSION1 donne ROLL et EXTENSION2 les sorties.
- **XDJ-RX3 : les SOUND COLOR FX** : Les six touches SOUND COLOR FX de la table choisissent l’effet du potard COLOR
  des deux voies : SPACE (réverbération), DUB ECHO (écho d’un demi-temps qui continue), SWEEP (passe-bande à droite,
  porte qui resserre le son à gauche), NOISE (bruit filtré), CRUSH (son écrasé), FILTER. Au milieu du potard, rien ;
  PARAMETER règle la nuance. La touche allumée, appuyée de nouveau, l’éteint : COLOR redevient le filtre.
- **XDJ-RX3 : sélecteur d’effet et MASTER CUE** : Le sélecteur BEAT FX de la table choisit maintenant l’effet de
  Scalpel DJ du même nom (DELAY, ECHO, PING PONG, SPIRAL, REVERB, TRANS, FILTER, FLANGER, PHASER, SLIP ROLL, ROLL,
  VINYL BRAKE ; PITCH et HELIX n’ont pas d’équivalent). MASTER CUE met le master au casque. Ces commandes venaient
  d’un relevé d’une vraie XDJ-RX3 et ne faisaient rien.
- **Casque débranché : le son revient sur le Mac** : Un casque (Bluetooth ou jack) débranché laissait Scalpel DJ muet
  : la sortie partie était réessayée en silence pendant 10 s, puis une « sortie de secours » ajoutée en 1.44 pouvait
  mettre les haut-parleurs du Mac de côté pour toujours et envoyer le son vers une carte virtuelle qui ne sonne nulle
  part. Ce mécanisme est retiré : le casque parti, le son repasse tout de suite sur la sortie du Mac, et revient sur
  le casque quand il est rebranché.
- **Choisir les haut-parleurs du Mac à la main** : Une carte que la liste interne ne voyait pas (les haut-parleurs du
  Mac, casque Bluetooth branché) était refusée : corrigé, et le faux message « ne répond pas, le Mac n’a pas d’autre
  sortie » ne paraît plus. L’app qui se fermait d’un coup en choisissant les haut-parleurs n’a pas pu être reproduite :
  si cela arrive encore, l’app en garde maintenant la cause.
- **Les préréglages d’Intro Lab gardent la mélodie** : Un préréglage enregistré garde maintenant aussi les variations
  de mélodie de chaque mesure, avec leur instrument et l’option « mélodie d’origine dessous ». Un préréglage d’avant
  ne change rien à la mélodie du son.

<details><summary>In English (November 17, 2026)</summary>

- **XDJ-RX3: the BROWSE knob stays where you clicked**: The deck’s browse knob jumped back to the crates after
  clicking a track or loading one. It now follows the panel you clicked last (crates or tracks), like Serato, and
  stays on the track list after a load.
- **XDJ-RX3: HOT CUE, LOOPS, SAMPLER, STEMS on the mode buttons**: The deck’s four mode buttons now give HOT CUE,
  LOOPS (BEAT LOOP), SAMPLER (SLIP LOOP) and STEMS (BEAT JUMP), the modes DJs actually use: Scalpel DJ has no BEAT
  LOOP or BEAT JUMP pad mode. With SHIFT, EXTENSION1 gives ROLL and EXTENSION2 the exits.
- **XDJ-RX3: SOUND COLOR FX**: The deck’s six SOUND COLOR FX buttons pick the effect of both channels’ COLOR knob:
  SPACE (reverb), DUB ECHO (a half-beat echo that keeps ringing), SWEEP (band-pass to the right, a gate that tightens
  the sound to the left), NOISE (filtered noise), CRUSH (crushed sound), FILTER. Nothing at the knob’s center;
  PARAMETER sets the shade. Pressing the lit button again turns it off: COLOR is the filter again.
- **XDJ-RX3: effect selector and MASTER CUE**: The deck’s BEAT FX selector now picks the Scalpel DJ effect of the same
  name (DELAY, ECHO, PING PONG, SPIRAL, REVERB, TRANS, FILTER, FLANGER, PHASER, SLIP ROLL, ROLL, VINYL BRAKE; PITCH
  and HELIX have no equivalent). MASTER CUE puts the master in the headphones. These controls came from a log of a
  real XDJ-RX3 and did nothing.
- **Headphones unplugged: sound comes back on the Mac**: Unplugging headphones (Bluetooth or jack) left Scalpel DJ
  silent: the missing output was retried silently for 10 s, then a 1.44 “fallback output” could set the Mac’s speakers
  aside for good and send sound to a virtual device that plays nowhere. That mechanism is gone: once the headphones
  leave, sound goes straight back to the Mac’s output, and back to the headphones when they are plugged in again.
- **Choosing the Mac’s speakers by hand**: A device the internal list missed (the Mac’s speakers with Bluetooth
  headphones connected) was refused: fixed, and the false “not responding, the Mac has no other output” message no
  longer appears. The app suddenly closing when choosing the speakers could not be reproduced: if it happens again,
  the app now keeps a record of the cause.
- **Intro Lab presets keep the melody**: A saved preset now also keeps each bar’s melody variation, with its
  instrument and the “keep the original melody underneath” option. An older preset leaves the track’s melody as it is.

</details>

## 1.46 BETA — 17 novembre 2026

**Version BETA**, comme la 1.45 : pas encore essayée en soirée ; les versions d'avant restent téléchargeables.

- **Moins de couleurs criardes** : Les pads de stems, les emplacements du sampler et l’onglet de pads choisi faisaient
  « jouet » : de gros aplats de couleurs vives côte à côte. Un stem entendu est maintenant un pad sombre, avec une
  barre et son nom dans sa couleur ; coupé, il est gris. Un emplacement du sampler est une plaque neutre avec une
  barre de couleur, et ne prend son cadre de couleur que pendant qu’il joue. L’onglet choisi reste rempli, en plus
  dense.
- **Menus déroulants aux couleurs de l’app** : Les listes déroulantes ouvraient le menu gris clair de macOS, qui
  jurait avec le reste. Elles ouvrent maintenant un menu sombre de l’app, avec des groupes titrés, la ligne choisie
  cochée, et le clavier (flèches, Entrée, Échap, première lettre).
- **Le même espace partout** : L’écart entre les platines, la table, les panneaux, la bibliothèque et les bords de la
  fenêtre est maintenant le même sur tous les onglets : 2 px, celui qu’il y avait déjà sous la barre du haut.
- **Curseur de tempo de la vue Extended** : En Extended, le curseur de tempo n’occupait que la moitié de sa rangée et
  n’avait qu’un trait au milieu. Il prend maintenant toute la rangée, avec les mêmes graduations et le même chapeau de
  métal que le curseur debout des autres vues.

<details><summary>In English (November 17, 2026)</summary>

- **Fewer garish colours**: The stem pads, the sampler slots and the selected pad tab looked like a toy: big blocks of
  bright colours side by side. A stem you hear is now a dark pad with a bar and its name in its colour; muted, it is
  grey. A sampler slot is a neutral plate with a colour bar, and only gets its coloured frame while it plays. The
  selected tab stays filled, in a denser shade.
- **Dropdown menus in the app’s colours**: Dropdown lists used to open the light grey macOS menu, which clashed with
  everything else. They now open a dark menu in the app’s style, with titled groups, a tick on the chosen line, and
  the keyboard (arrows, Enter, Escape, first letter).
- **The same spacing everywhere**: The gap between the decks, the mixer, the panels, the library and the window edges
  is now the same on every tab: 2 px, the one that was already under the top bar.
- **Tempo slider in the Extended view**: In Extended, the tempo slider only used half of its row and had a single mark
  in the middle. It now takes the whole row, with the same graduations and the same metal cap as the upright slider of
  the other views.

</details>

## 1.45 BETA — 17 novembre 2026

**Version BETA**, comme la 1.44 : pas encore essayée en soirée ; les versions d'avant restent téléchargeables.

- **Une grille de Serato fausse n’est plus suivie** : Quand l’ancienne grille de Serato d’un son ne tombe pas sur ses
  temps (un son à 125 BPM rangé à 93,75 dans Serato, par exemple), les traits glissaient entre les coups et le SYNC
  calait à côté. Scalpel DJ le voit maintenant au chargement, prend la grille qu’il a mesurée sur le son et te le dit,
  avec un bouton pour garder celle de Serato. Les sons dont la grille de Serato est juste ne changent pas.
- **Longue session : plus de craquements** : Dans une longue session, le son craquait par moments quand on chargeait
  un morceau pendant que les stems d’un autre se calculaient. Cause trouvée : le fil qui fabrique le son attendait que
  macOS lui rende un bout de mémoire qu’il venait de lui reprendre. Toute la mémoire dont le son a besoin est
  maintenant gardée en mémoire vive, pas seulement les morceaux. Mesuré sur la même session de 6 minutes : 22 à 39
  retards du son avant, aucun après.
- **L’écran ne se fige plus toutes les une à deux minutes** : Pendant le calcul des stems, le point de l’onglet STEMS
  qui pulse remplissait peu à peu la réserve d’images de l’écran ; une fois pleine, tout l’écran était repeint d’un
  coup : un quart de seconde figé, toutes les une à deux minutes. Ce point ne prend plus de place, et une réserve
  pleine se renouvelle maintenant sans rien figer. La mise en cache des stems d’un morceau (quatre blocages d’un quart
  de seconde) est aussi découpée en petits morceaux.
- **Chargement d’un morceau deux fois plus rapide** : Un morceau qui a la grille de Serato, ou que Scalpel DJ a déjà
  analysé, ne refait plus le calcul de sa grille à chaque chargement. Mesuré : de 1,2 à 1,4 s avant, 0,3 à 0,8 s
  maintenant, avec la même grille, le même tempo et la même tonalité.
- **Changer de langue deux fois de suite** : Passer en anglais puis revenir au français (ou l’inverse) ramenait
  l’écran de démarrage, platines vides. Les platines reviennent maintenant à chaque fois.
- **Une date ouverte dans la bibliothèque se voit** : « Voir dans la bibliothèque », dans Bookings, changeait la liste
  sans rien dire. La date a maintenant sa section en haut des crates, avec son jour, son nom, sa préparation et ses
  crates, et une flèche pour revenir à Bookings.

<details><summary>In English (November 17, 2026)</summary>

- **A wrong Serato beatgrid is no longer followed**: When a track’s old Serato beatgrid does not land on its beats (a
  125 BPM track stored as 93.75 in Serato, for instance), the grid lines drifted between the hits and SYNC locked off
  the beat. Scalpel DJ now sees it when the track loads, uses the grid it measured on the sound and tells you, with a
  button to keep Serato’s. Tracks whose Serato grid is right do not change.
- **Long sessions: no more crackles**: In a long session, the sound crackled now and then when you loaded a track
  while another track’s stems were still being computed. Cause found: the thread that makes the sound was waiting for
  macOS to give back a piece of memory it had just taken away. All the memory the sound needs is now kept in RAM, not
  only the tracks. Measured on the same 6-minute session: 22 to 39 late audio callbacks before, none after.
- **The screen no longer freezes every minute or two**: While stems were being computed, the pulsing dot on the STEMS
  tab slowly filled the screen’s image store; once full, the whole screen was repainted at once: a quarter of a second
  frozen, every minute or two. That dot no longer takes any room, and a full store now renews itself without freezing
  anything. Saving a track’s stems to the cache (four quarter-second stalls) is also split into small pieces.
- **Loading a track is twice as fast**: A track that has Serato’s beatgrid, or that Scalpel DJ has already analysed,
  no longer recomputes its grid on every load. Measured: 1.2 to 1.4 s before, 0.3 to 0.8 s now, with the same grid,
  tempo and key.
- **Changing language twice in a row**: Switching to English and then back to French (or the other way round) brought
  back the start screen with empty decks. The decks now come back every time.
- **A date opened in the library now shows**: “Show in the library”, in Bookings, changed the list without saying so.
  The date now has its own section above the crates, with its day, name, set preparation and crates, and an arrow back
  to Bookings.

</details>

## 1.44 BETA — 17 novembre 2026

**Version BETA**, comme la 1.43 : pas encore essayée en soirée ; les versions d'avant restent téléchargeables.

- **Casques et enceintes Bluetooth** : Un casque Bluetooth qui a aussi un micro était refusé comme sortie : pour
  macOS, c’est deux cartes son du même nom, son micro puis sa sortie, et Scalpel DJ prenait la première. Il prend
  maintenant celle qui a des sorties. Le son y part à la fréquence du casque, et les formes d’onde tiennent compte de
  son retard (environ 190 ms : bien pour écouter ou préparer, trop pour scratcher). Tu peux aussi prendre son micro
  pour la voix : le casque passe alors en mode téléphone (une voie à 16 kHz, c’est le Bluetooth qui l’impose) et
  Scalpel DJ le suit, quand le micro s’ouvre comme quand il se ferme, avec un quart de seconde de silence au passage.
  Le panneau Micro ouvert ne fait plus passer le casque en mode téléphone : son micro ne s’ouvre que quand la voix est
  allumée. Et les haut-parleurs du Mac restent dans la liste des sorties quand un casque Bluetooth est branché : tu
  peux parler dans le micro du casque et sortir sur le Mac.
- **Une sortie qui ne répond pas ne bloque plus tout** : Un casque Bluetooth ou une carte son peut rester dans la
  liste du Mac sans plus recevoir aucun son. Scalpel DJ restait alors muet et figé, sans rien dire, et un chargement
  restait bloqué à « analyse ». Maintenant il s’en aperçoit en une seconde et demie, rouvre la sortie une fois, puis
  passe sur celle du Mac et te le dit, avec un bouton Réessayer. La sortie mise de côté est marquée dans Réglages →
  Sortie audio et dans la check-list ; elle est reprise toute seule si tu la rebranches.
- **Vertical : platines complètes et table dès le premier lancement** : En Vertical, sur un écran de MacBook, un
  nouvel utilisateur avait des platines repliées, sans disque, la table effacée et un vide sous les pads. Maintenant
  la bibliothèque garde au moins la moitié de la hauteur et, dans cette limite, tout se montre : platines complètes et
  table. Quand la place manque, la table s’efface d’abord et les platines gardent leur disque ; elles ne se replient
  qu’ensuite. Une hauteur de bibliothèque choisie à la poignée reste respectée.
- **Rolls courts sur un casque Bluetooth** : Sur une sortie qui a beaucoup de retard (casque Bluetooth, haut-parleurs
  du Mac), les rolls de 1/16, 1/8 et 1/4 de temps ne faisaient rien : le moteur avait déjà dépassé la fin de la boucle
  au moment où elle était posée. La boucle est maintenant reprise au même endroit de son motif, pour les rolls et les
  boucles automatiques.
- **Micro sur une autre carte que la sortie : moins de retard** : Quand le micro et la sortie ne sont pas la même
  carte son (micro du Mac ou d’un casque, sortie ailleurs), la voix attendait dans une file plus longue que
  nécessaire. Elle y passe maintenant environ 2 ms de moins. Le micro d’une table (même carte que la sortie) n’est pas
  concerné : il n’a pas de file.
- **Le téléphone au dessin de l’app** : La télécommande et le Studio du téléphone reprennent le dessin de l’app du Mac
  : mêmes coins, mêmes pads, même logo, crossfader plus gros et strié. Les formes d’onde du téléphone sont celles du
  Mac : l’onde réelle, aux couleurs de Serato.
- **Potards, faders et crossfader en métal** : Les potards ont un chapeau en métal à bord moleté, les faders et le
  crossfader un capuchon strié sur un rail creusé, le crossfader est plus gros. Sur les platines, les petits boutons
  sont réunis en plaques, SYNC, CUE et PLAY ont du relief, le disque et le transport forment un bloc, et le nom d’un
  pad s’écrit en entier au lieu d’être coupé. Rien de plus à calculer pendant la lecture.
- **Image écrasée après un changement de taille de la fenêtre** : En sortant du plein écran ou en changeant la taille
  de la fenêtre, les platines pouvaient s’afficher écrasées, textes élargis. La surface de dessin prend maintenant sa
  nouvelle taille tout de suite.

<details><summary>In English (November 17, 2026)</summary>

**BETA version**, like 1.43: not yet tried at a gig; earlier versions can still be downloaded.

- **Bluetooth headphones and speakers**: A Bluetooth headset that also has a mic was refused as an output: for macOS
  it is two sound cards with the same name, its mic then its output, and Scalpel DJ picked the first one. It now picks
  the one that has outputs. Sound goes out at the headset’s own sample rate, and the waveforms account for its delay
  (about 190 ms: fine for listening or prepping, too much for scratching). You can also use its mic for the voice: the
  headset then switches to phone mode (one channel at 16 kHz, which Bluetooth imposes) and Scalpel DJ follows it, when
  the mic opens and when it closes, with a quarter of a second of silence at the switch. Opening the Mic panel no
  longer switches the headset to phone mode: its mic only opens when the voice is on. And the Mac’s speakers stay in
  the output list while a Bluetooth headset is connected: you can talk into the headset’s mic and play through the
  Mac.
- **An output that stops responding no longer blocks everything**: Bluetooth headphones or a sound card can stay in
  the Mac’s list while no longer receiving any sound. Scalpel DJ then stayed silent and frozen, saying nothing, and a
  load stayed stuck on “analysis”. It now notices within a second and a half, reopens the output once, then moves to
  the Mac’s own output and tells you, with a Try again button. The output set aside is marked in Settings → Audio
  output and in the checklist; it is taken again by itself if you plug it back in.
- **Vertical: full decks and mixer from the first launch**: In Vertical, on a MacBook screen, a new user got folded
  decks with no platter, the mixer hidden and a gap under the pads. Now the library keeps at least half the height
  and, within that limit, everything is shown: full decks and the mixer. When space runs short, the mixer hides first
  and the decks keep their platter; they only fold after that. A library height set with the handle is still
  respected.
- **Short rolls on Bluetooth headphones**: On an output with a lot of delay (Bluetooth headphones, the Mac’s
  speakers), 1/16, 1/8 and 1/4 beat rolls did nothing: the engine was already past the end of the loop when it was
  set. The loop is now caught at the same place in its pattern, for rolls and auto loops.
- **Mic on a different card than the output: less delay**: When the mic and the output are not the same sound card
  (the Mac’s or a headset’s mic, output elsewhere), the voice waited in a longer queue than needed. It now spends
  about 2 ms less there. A mixer’s mic (same card as the output) is not affected: it has no queue.
- **The phone gets the app’s look**: The phone remote and Studio now use the Mac app’s design: same corners, same
  pads, same logo, a bigger ridged crossfader. The phone’s waveforms are the Mac’s: the real wave, in Serato’s
  colours.
- **Metal knobs, faders and crossfader**: Knobs have a metal cap with a knurled edge, faders and the crossfader a
  ridged cap on a recessed rail, and the crossfader is bigger. On the decks, small buttons are grouped into plates,
  SYNC, CUE and PLAY have relief, the platter and transport form one block, and a pad’s name is written in full
  instead of being cut. Nothing more to compute during playback.
- **Squashed image after resizing the window**: When leaving full screen or resizing the window, the decks could be
  drawn squashed, with widened text. The drawing surface now takes its new size right away.

</details>

## 1.43 BETA — 16 novembre 2026

**Version BETA**, comme les 1.38 et 1.39 : pas encore essayée en soirée, et le matériel repris de Mixxx n'a pas encore
été essayé sur les vraies tables ; les versions d'avant restent téléchargeables.

- **Le son continue si l’écran plante** : Le moteur audio ne vit plus dans le même processus que l’écran. Si l’écran
  plante, sature ou se recharge, le son ne s’arrête plus : les platines continuent de jouer, le scratch au jog aussi.
  L’écran revient tout seul (de quelques secondes à une vingtaine avec une grosse bibliothèque) et reprend tes
  platines là où elles en sont, sans un clic et sans rien couper. Essai : écran tué en pleine lecture, aucun
  échantillon perdu ni décalé.
- **L’enregistrement du mix continue aussi** : L’enregistrement est maintenant écrit par le moteur, plus par l’écran.
  Si l’écran plante pendant REC, les morceaux continuent de s’écrire sur le disque et l’écran revenu retrouve
  l’enregistrement en cours. Essai : écran tué pendant l’enregistrement, fichier final sans trou ni saut.
- **SYNC et glissement de tempo tenus par le moteur** : Le suivi du SYNC et le glissement de tempo sont calculés dans
  le moteur, à chaque tour du son. Avant, l’écran corrigeait 10 fois par seconde : s’il se figeait, la correction
  s’arrêtait. Essai : écran figé 3 s après un décalage de 19 ms entre les platines, écart déjà corrigé au réveil (19
  ms restants avant).
- **Un filet sous le fil audio** : Une erreur interne dans le calcul du son fermait toute l’app d’un coup. Elle est
  maintenant rattrapée : un instant de silence au pire, puis le son reprend.
- **Au retour de l’écran, rien ne bouge dans le son** : Quand l’écran revient après un plantage, il reprend aussi ce
  qui sonnait : un stem coupé reste coupé (les stems ne sont pas renvoyés au moteur), un effet allumé reste allumé, le
  micro reste ouvert. Et si c’est le moteur audio lui-même qui tombe, Scalpel DJ le relance et reprend ton set tout
  seul, sans fenêtre à cliquer. Essais : écran tué avec les quatre stems coupés, un effet et le micro allumés ; moteur
  tué en pleine lecture.
- **La table et les boutons des platines ne se redessinent plus** : Les potards de la table gardent leur mode (Stems
  ou EQ) d’un morceau à l’autre : avant, chaque chargement les remettait en EQ, puis les repassait en Stems avec leurs
  couleurs quelques secondes plus tard. Les boutons des platines restent dessinés tant que leur nouvelle image n’est
  pas à l’écran (ils pouvaient manquer un instant), et l’écran de démarrage n’est plus recouvert par l’image d’avant.
- **Traktor Kontrol S2 MK2 et S4 MK2 en USB** : Ces deux tables ne parlent pas en MIDI : Scalpel DJ lit maintenant
  leurs messages USB directement, d’après le mapping libre de Mixxx (octets et bits relus dans son texte, sans faire
  tourner ses scripts). PLAY, CUE, SYNC, SHIFT, jog (1 024 pas par tour), fader de tempo, faders, EQ, filtre et appui
  de la molette sur la S4, crossfader, molette de navigation, LOAD, quatre hot cues par platine, boucle IN et OUT,
  SLIP, CUE du casque. Branchée seule, elle devient ta table ; à côté d’une autre, elle sert d’appoint. Ses voyants
  restent éteints : Scalpel DJ ne lui envoie rien pour l’instant. Les autres tables USB hors MIDI de Mixxx ne sont pas
  reprises : chaque Traktor a sa propre forme de messages (S2 MK3, S3, Z1, F1, MX2 : lus, pas branchés), et les
  anciennes Hercules et la S4 MK3 ne sont pas lisibles sans faire tourner leurs scripts. Jamais essayé sur une vraie
  table.
- **Fader de tempo : le sens de chaque table, d’après Mixxx** : Le fader de tempo n’envoie pas ses valeurs dans le
  même sens d’une marque à l’autre. Pour chaque table reprise de Mixxx, Scalpel DJ suit ce que dit son mapping : la
  valeur telle quelle pour celles qui envoient comme une Pioneer, inversée pour les autres. Si le fader d’une table va
  quand même à l’envers : Réglages → Contrôleur → Sens du fader de tempo. Rien de tout cela n’a été essayé sur les
  vraies tables.
- **Lecteurs seuls, tables de mixage et appareils d’appoint repris de Mixxx** : Six lecteurs seuls (Pioneer CDJ-350,
  Gemini CDMP-7000, American Audio Radius 2000, Denon DN-HS5500 et DN-SC2000, DJ-Tech CDJ-101) pilotent chacun une
  platine, comme les CDJ. Quatre tables de mixage seules (DJ-Tech DJM-101 et Mixer One, Behringer CMD MM-1, Numark
  Scratch). Et 25 appareils d’appoint (Korg nanoKONTROL et nanoPAD2, Akai LPD8 et MPD24, Novation Dicer, MIDI Fighter
  Twister et Spectra, Arturia KeyLab, QuNeo…) : branché à côté de ta table, un appareil d’appoint ajoute ses commandes
  aux siennes ; un message le dit, avec un bouton pour ne pas l’utiliser. Un clavier MIDI ordinaire n’est jamais pris
  tout seul : il se choisit dans Réglages → Contrôleur. Rien de tout cela n’a été essayé sur le vrai matériel.
- **Plus de 100 appareils repris de Mixxx** : Les DJ qui se servent de Mixxx, le logiciel libre, ont écrit pour leur
  matériel quel message MIDI envoie chaque bouton. Scalpel DJ reprend ces adresses (pas leur code, et sans jamais
  faire tourner leurs scripts : leur texte est seulement lu) pour 120 appareils, dont 85 tables à deux platines de
  Hercules, Numark, Denon, Reloop, Pioneer DJ, Vestax, Behringer, MixVibes, Stanton, Roland, Korg, Ion et d’autres :
  PLAY, CUE, SYNC, jog et son nombre de pas par tour, pitch, table, crossfader, navigation, LOAD, pads de hot cues,
  boucles. Ils sont reconnus au nom de leur port ; sinon, Réglages → Contrôleur → Ta table permet de choisir, et donne
  la liste de tout le matériel connu avec ce qui manque encore à chacun. Dix-sept mappings de Mixxx ne sont pas repris
  : leurs commandes ne sont écrites que dans des scripts qu’il faudrait faire tourner (Novation Launchpad, Allen &
  Heath Xone K2, Behringer BCR2000 et DDM4000, Stanton SCS…). Aucun de ces appareils n’a encore été essayé en vrai
  dans Scalpel DJ.

<details><summary>In English (November 16, 2026)</summary>

**BETA version**, like 1.38 and 1.39: not tried at a gig yet, and the hardware taken from Mixxx hasn't been tried on
the real controllers yet; earlier versions are still available.

- **The sound keeps going if the screen crashes**: The audio engine no longer lives in the same process as the screen.
  If the screen crashes, runs out of memory or reloads, the sound no longer stops: the decks keep playing, and so does
  jog scratching. The screen comes back by itself (from a few seconds to about twenty with a large library) and picks
  up your decks where they are, with no click and no cut. Test: screen killed during playback, not one sample lost or
  shifted.
- **The mix recording keeps going too**: The recording is now written by the engine, not by the screen. If the screen
  crashes while REC is on, the chunks keep being written to disk and the screen finds the running recording when it
  comes back. Test: screen killed during a recording, final file with no gap and no jump.
- **SYNC and tempo glide held by the engine**: SYNC tracking and the tempo glide are computed inside the engine, on
  every audio cycle. Before, the screen corrected 10 times a second: if it froze, the correction stopped. Test: screen
  frozen for 3 s after a 19 ms offset between the decks, offset already corrected on wake-up (19 ms left before).
- **A safety net under the audio thread**: An internal error in the sound computation used to close the whole app at
  once. It is now caught: a moment of silence at worst, then the sound resumes.
- **When the screen comes back, nothing changes in the sound**: When the screen comes back after a crash, it also
  picks up what was sounding: a muted stem stays muted (stems are not sent to the engine again), an effect that was on
  stays on, the mic stays open. And if the audio engine itself goes down, Scalpel DJ restarts it and resumes your set
  on its own, with no dialog to click. Tests: screen killed with all four stems muted, an effect and the mic on;
  engine killed during playback.
- **The mixer and the deck buttons are no longer redrawn**: The mixer knobs keep their mode (Stems or EQ) from one
  track to the next: before, every load put them back to EQ, then switched them to Stems with their colours a few
  seconds later. Deck buttons stay drawn until their new image is on screen (they could be missing for a moment), and
  the start screen is no longer covered by the previous image.
- **Traktor Kontrol S2 MK2 and S4 MK2 over USB**: These two controllers do not speak MIDI: Scalpel DJ now reads their
  USB messages directly, from the open Mixxx mapping (bytes and bits read in its text, without running its scripts).
  PLAY, CUE, SYNC, SHIFT, jog (1,024 steps per turn), tempo fader, faders, EQ, filter and encoder press on the S4,
  crossfader, browse encoder, LOAD, four hot cues per deck, loop IN and OUT, SLIP, headphone CUE. Plugged in alone, it
  becomes your controller; next to another one, it works as an add-on. Its lights stay off: Scalpel DJ sends it
  nothing for now. The other non-MIDI USB controllers from Mixxx are not taken: each Traktor has its own message
  layout (S2 MK3, S3, Z1, F1, MX2: read, not wired in), and the older Hercules and the S4 MK3 cannot be read without
  running their scripts. Never tried on a real controller.
- **Tempo fader: each controller’s direction, from Mixxx**: A tempo fader does not send its values the same way round
  from one brand to another. For each controller taken from Mixxx, Scalpel DJ follows what its mapping says: the value
  as it is for those that send like a Pioneer, inverted for the others. If a controller’s fader still runs backwards:
  Settings → Controller → Tempo fader direction. None of this has been tried on the real controllers.
- **Standalone players, mixers and add-on devices taken from Mixxx**: Six standalone players (Pioneer CDJ-350, Gemini
  CDMP-7000, American Audio Radius 2000, Denon DN-HS5500 and DN-SC2000, DJ-Tech CDJ-101) each drive one deck, like the
  CDJs. Four standalone mixers (DJ-Tech DJM-101 and Mixer One, Behringer CMD MM-1, Numark Scratch). And 25 add-on
  devices (Korg nanoKONTROL and nanoPAD2, Akai LPD8 and MPD24, Novation Dicer, MIDI Fighter Twister and Spectra,
  Arturia KeyLab, QuNeo…): plugged in next to your controller, an add-on device adds its controls to it; a message
  says so, with a button not to use it. An ordinary MIDI keyboard is never picked up on its own: choose it in Settings
  → Controller. None of this has been tried on the real hardware.
- **More than 100 devices taken from Mixxx**: DJs who use Mixxx, the open-source software, have written down which
  MIDI message each button of their gear sends. Scalpel DJ takes those addresses (not their code, and without ever
  running their scripts: their text is only read) for 120 devices, including 85 two-deck controllers from Hercules,
  Numark, Denon, Reloop, Pioneer DJ, Vestax, Behringer, MixVibes, Stanton, Roland, Korg, Ion and others: PLAY, CUE,
  SYNC, jog and its steps per turn, pitch, mixer, crossfader, browsing, LOAD, hot cue pads, loops. They are recognised
  by their port name; otherwise, Settings → Controller → Your controller lets you choose, and lists all known hardware
  with what each still lacks. Seventeen Mixxx mappings are not taken: their controls are only written in scripts that
  would have to be run (Novation Launchpad, Allen & Heath Xone K2, Behringer BCR2000 and DDM4000, Stanton SCS…). None
  of these devices has been tried for real in Scalpel DJ yet.

</details>

## 1.39 BETA — 16 novembre 2026

**Version BETA**, comme la 1.38 : pas encore essayée en soirée ; la 1.33 reste téléchargeable.

- **Clic droit sur plusieurs sons, comme Serato 5** : Le clic droit sur une sélection ouvre le menu de Serato 5, dans
  son ordre, pour tous les sons choisis : Ajouter à, Analyser, Grille, Changer le BPM, Note en émoji, Couleur du son,
  Montrer dans les crates (un son à la fois, comme dans Serato), Verrouiller et Déverrouiller la grille, Relire les
  infos du fichier, Retrouver, Montrer dans le Finder (tous sélectionnés), Supprimer. Puis « Modifier… » (tags,
  langue, riddim, énergie, ce qu’ouvrait le clic droit avant) et la marque « joué ce soir ». Les grilles verrouillées
  ne changent pas. « Retrouver » (Relocate) est aussi dans le menu d’un son.
- **Plus de fenêtre cachée sous les platines** : Les platines, la table et les formes d’onde sont dessinées par une
  surface posée par-dessus la page. Si elle ne recevait plus les images de la page, elle gardait sa dernière image, et
  une fenêtre ouverte (comme « Modifier » sur plusieurs sons) passait dessous. Maintenant, une image qu’elle n’a pas
  pu montrer est refaite à l’image suivante ; si l’écran ne donne plus de rafraîchissement, elle est montrée quand
  même ; une erreur pendant le dessin refait la surface au lieu de la figer ; et à chaque fenêtre ou menu ouvert,
  Scalpel vérifie qu’elle l’a bien montré, sinon il la cache tant que la fenêtre reste ouverte.

<details><summary>In English (November 16, 2026)</summary>

**BETA version**, like 1.38: not tried at a gig yet; 1.33 is still available.

- **Right-click on several tracks, like Serato 5**: Right-clicking a selection opens Serato 5’s menu, in its order,
  for all selected tracks: Add to, Analyze, Beatgrid, Change BPM, Rating emoji, Track colour, Show in crates (one
  track at a time, as in Serato), Lock and Unlock beatgrid, Re-scan file info, Relocate, Show in Finder (all
  selected), Delete. Then “Edit…” (tags, language, riddim, energy, what right-click opened before) and the “played
  tonight” mark. Locked beatgrids don’t change. “Relocate” is also in a single track’s menu.
- **No more window hidden under the decks**: The decks, the mixer and the waveforms are drawn by a surface placed over
  the page. If it stopped receiving the page’s images, it kept its last image, and an open window (like “Edit” on
  several tracks) went underneath. Now an image it could not show is redrawn at the next frame; if the screen stops
  refreshing, it is shown anyway; an error while drawing rebuilds the surface instead of freezing it; and for each
  window or menu that opens, Scalpel checks the surface showed it, otherwise it hides the surface while the window
  stays open.

</details>

## 1.38 BETA — 15 novembre 2026

**Version BETA** : ses nouveautés n'ont pas encore été essayées en soirée ; la 1.33 reste téléchargeable.

- **Intro Lab : plus de trous dans l’intro** : Une zone de 16 mesures pour une intro de 8 en donnait les 8 dernières,
  que le bloc vert ne distinguait pas : sur un son, c’était la fin du morceau, sans batterie ni basse. L’intro prend
  maintenant la zone depuis son début, et la zone ne peut plus être plus longue que l’intro (ou la sortie). La zone
  proposée d’office évite les mesures où le beat s’arrête dans le morceau (un break, la fin) : parmi les passages du
  refrain, le premier où la grosse caisse et la basse jouent du début à la fin. Si ta zone en contient quand même,
  chacune prend le beat de la mesure de la zone qui a la même harmonie, et la voix garde ses mesures. Ces mesures sont
  hachurées sur la forme d’onde du haut et soulignées dans l’arrangement ; « Avancé ▾ » permet de les garder telles
  quelles.
- **Logo plus grand dans le Dock** : Le disque du logo remplit maintenant toute l’icône (avant, 80 % de sa largeur,
  comme la grille d’Apple ; celui de Serato en remplit 88 %). Posé par-dessus, le logo de Serato laisse voir un anneau
  de celui de Scalpel DJ tout autour.
- **Nouveau logo** : Le disque vinyle et le bistouri : dans la barre du haut, sur l’écran de démarrage, dans l’onglet,
  dans le Dock pendant que l’app tourne et sur la page du téléphone.
- **Mesures et sorties calées sur le vrai 1** : Sur une partie des sons (175 des 750 analysés par Serato 5, et des
  sons analysés par Scalpel), le 1 de la mesure ne tombe pas sur un multiple de 4 depuis le début de la grille. Le
  compte à rebours de phrase le savait, mais pas le reste : les sorties propres (écho, filtre, basses, roll, backspin)
  pouvaient partir un à trois temps à côté du 1, et les traits épais des mesures, leurs numéros et la règle des
  phrases étaient décalés d’autant, sur l’écran comme sur le téléphone. Tout se compte maintenant depuis le vrai 1,
  comme le compte à rebours.
- **Anti-larsen : un interrupteur, et rien sans micro** : L’anti-larsen ne tourne plus quand le micro est coupé
  (avant, il écoutait la salle pendant tout le set dès que le micro l’entendait). Un interrupteur ANTI-LARSEN, en haut
  de sa bulle (bouton à côté de l’état du micro) et dans l’onglet Micro du téléphone, l’arrête en entier : filtres de
  la salle, direct, retour retiré du micro, porte, retenue. Arrêté, son bouton est barré.
- **Platines et formes d’onde dessinées par Scalpel DJ, comme Serato** : Le haut de l’écran Mix (formes d’onde, vues
  d’ensemble, disques, vu-mètres) ne passe plus par Chromium : Scalpel DJ le dessine lui-même avec la carte graphique
  (Metal), à chaque rafraîchissement de l’écran, et le fait avancer d’après la position et la vitesse de chaque
  platine. Quand la page est occupée (un son qui se charge), l’écran continue d’avancer au lieu de geler. Filmé de
  l’écran sur batterie, la page bloquée 150 ms quatre fois de suite pendant la lecture : avant, l’écran gelait à
  chaque fois (8 à 11 trous par film) ; maintenant, 0 à 1. Même image au pixel près. Réglages → Affichage → Dessin
  natif pour revenir à l’ancien dessin.
- **Lecture : moins d’images sautées au démarrage** : Filmé de l’écran (le même test sur Serato) : sur batterie,
  l’écran ratait 4 à 6 images dans la seconde qui suit l’appui sur lecture. Deux causes, réglées : le canevas des
  formes d’onde ne se redessinait plus à l’arrêt, et l’affichage mettait du temps à repartir (il se redessine
  maintenant dans les 10 secondes qui suivent un geste à la souris, au clavier ou sur la table, sans rien coûter au
  repos) ; et les fondus de la platine à l’antenne obligeaient à repeindre une partie de l’écran à leur fin. Mesuré :
  1 à 2 images au lieu de 4 à 6.
- **Chargement : le son décodé reste dans le moteur** : Quand tu chargeais un morceau, son décodé passait par l’écran
  (la page) avant de revenir au moteur, puis une seconde fois pour le calcul des stems : plus de 250 Mo de tableaux
  par morceau, qui faisaient sauter des images à la platine qui jouait. Le son décodé reste maintenant dans le moteur
  : la platine le prend sur place, l’analyse le lit sur place, et le calcul des stems lit le fichier lui-même. Mêmes
  analyses et même son, au bit près.

<details><summary>In English (November 15, 2026)</summary>

**BETA version**: not tried at a gig yet; 1.33 is still available.

- **Intro Lab: no more gaps in the intro**: A 16-bar zone for an 8-bar intro used its last 8 bars, which the green
  block didn’t single out: on one track, that was the end of the song, with no drums or bass. The intro now takes the
  zone from its start, and the zone can no longer be longer than the intro (or the outro). The zone suggested by
  default avoids bars where the beat stops in the track (a break, the ending): among the chorus passages, the first
  one where the kick and the bass play from start to end. If your zone still has some, each one takes the beat of the
  zone bar with the same harmony, and the vocals keep their own bars. These bars are hatched on the top waveform and
  underlined in the arrangement; “Advanced ▾” lets you keep them as they are.
- **Bigger logo in the Dock**: The logo’s record now fills the whole icon (before, 80% of its width, like Apple’s
  grid; Serato’s fills 88%). Placed on top, Serato’s logo leaves a ring of the Scalpel DJ logo showing all around.
- **New logo**: The vinyl record and scalpel: in the top bar, on the start screen, in the tab, in the Dock while the
  app runs, and on the phone page.
- **Bars and exits locked to the real downbeat**: On some tracks (175 of the 750 analyzed by Serato 5, plus tracks
  analyzed by Scalpel), the 1 of the bar is not a multiple of 4 from the start of the grid. The phrase countdown knew
  it, but nothing else did: clean exits (echo, filter, bass, roll, backspin) could start one to three beats off the 1,
  and the bold bar lines, their numbers and the phrase ruler were off by the same amount, on screen and on the phone.
  Everything now counts from the real 1, like the countdown.
- **Anti-feedback: an on/off switch, and nothing without the mic**: Anti-feedback no longer runs while the mic is off
  (before, it listened to the room for the whole set as soon as the mic heard it). An ANTI-FEEDBACK switch, at the top
  of its bubble (the button next to the mic status) and in the phone’s Mic tab, turns it off entirely: room filters,
  live, music removed from the mic, gate, per-band limiter. When off, its button is struck through.
- **Decks and waveforms drawn by Scalpel DJ itself, like Serato**: The top of the Mix screen (waveforms, overviews,
  platters, meters) no longer goes through Chromium: Scalpel DJ draws it itself with the graphics card (Metal), at
  every screen refresh, and moves it on from each deck’s position and speed. When the page is busy (a track loading),
  the screen keeps moving instead of freezing. Filmed from the screen on battery, with the page blocked for 150 ms
  four times in a row during playback: before, the screen froze every time (8 to 11 gaps per film); now, 0 to 1. Same
  image to the pixel. Settings → Display → Native drawing to go back to the old drawing.
- **Playback: fewer skipped frames when starting**: Filmed from the screen (same test run on Serato): on battery, the
  screen skipped 4 to 6 frames in the second after pressing play. Two causes, fixed: the waveform canvas stopped
  redrawing while stopped and the display took time to restart (it now keeps redrawing for 10 seconds after a mouse,
  keyboard or controller gesture, at no cost when idle); and the on-air deck fades forced part of the screen to be
  repainted when they ended. Measured: 1 to 2 frames instead of 4 to 6.
- **Loading: decoded audio stays in the engine**: When you loaded a track, its decoded audio went through the screen
  (the page) before coming back to the engine, then a second time for the stems: over 250 MB of arrays per track,
  which made the playing deck skip frames. Decoded audio now stays in the engine: the deck takes it in place, the
  analysis reads it in place, and the stems process reads the file itself. Same analyses and same sound, bit for bit.

</details>

## 1.33 — 14 novembre 2026

- **Charger un son sans faire sauter l’autre platine** : Quand un son finissait de se charger pendant que l’autre
  platine jouait, sa forme d’onde, sa vue d’ensemble, la liste de la bibliothèque et les suggestions se recalculaient
  toutes dans la même image : la forme d’onde qui jouait sautait quelques images. Ce travail est maintenant étalé sur
  plusieurs images, et la vue d’ensemble n’est plus calculée deux fois de suite.

<details><summary>In English (November 14, 2026)</summary>

- **Loading a track no longer makes the other deck skip**: When a track finished loading while the other deck was
  playing, its waveform, its overview, the library list and the suggestions were all recomputed within the same frame,
  and the playing waveform skipped a few frames. This work is now spread over several frames, and the overview is no
  longer computed twice in a row.

</details>

## 1.32 — 14 novembre 2026

- **Potard MASTER dans la barre du haut** : Le volume du master se règle maintenant à l’écran, comme dans Serato : un
  potard en haut à droite, à côté de la sortie audio. Glisse-le, ou utilise la molette ; double-clic : niveau normal.
  Le réglage est gardé d’un lancement à l’autre.
- **Forme d’onde et disque : un défilement régulier** : Les images sortaient bien à 60 par seconde, mais la position
  dessinée tremblait d’une image à l’autre (jusqu’à plusieurs points) : la forme d’onde et le disque avançaient par
  petits à-coups. Le dessin avance maintenant exactement du temps écoulé, et ne se recale sur le son que tout
  doucement. Rien ne change pour le son, les calages ni les sauts.
- **Forme d’onde nette en mouvement** : En défilant, les pics fins de l’onde réelle changeaient de hauteur à chaque
  image, ce qui la faisait grésiller. Chaque colonne prend maintenant le creux et la crête de tout ce qu’elle couvre :
  un pic garde sa hauteur où qu’il passe.
- **Lecture fluide juste après un chargement** : Dans les secondes qui suivent le chargement d’un morceau dont les
  stems sont déjà gardés, l’écran se figeait plusieurs fois un quart de seconde (forme d’onde et disque saccadés) : le
  dessin des stems recalculait tout le morceau chaque fois qu’un stem finissait d’arriver. Chaque stem n’est plus
  recalculé que là où il a changé.
- **Table en bande : les potards tiennent dans l’écran** : Sur un écran de 1280 points de large, le potard TRIM de
  gauche sortait de l’écran dès qu’un morceau avait ses stems (l’étiquette STEMS EQ élargit la voie). Les potards se
  resserrent maintenant pour tenir, à la même distance du bord des deux côtés.

<details><summary>In English (November 14, 2026)</summary>

- **MASTER knob in the top bar**: Master volume can now be set on screen, as in Serato: a knob at the top right, next
  to the audio output. Drag it or scroll; double-click: normal level. The setting is kept from one launch to the next.
- **Waveform and platter: steady scrolling**: Frames did come out at 60 per second, but the drawn position jittered
  from one frame to the next (by up to several points): the waveform and the platter moved in small jerks. The drawing
  now advances by exactly the elapsed time, and only realigns with the sound very gently. Nothing changes for the
  sound, syncing or jumps.
- **Clean waveform in motion**: While scrolling, the thin peaks of the real waveform changed height on every frame,
  which made it sizzle. Each column now takes the trough and crest of everything it covers: a peak keeps its height
  wherever it passes.
- **Smooth playback right after a load**: In the seconds after loading a track whose stems are already cached, the
  screen froze several times for a quarter of a second (jerky waveform and platter): the stems drawing recomputed the
  whole track each time a stem finished arriving. Each stem is now recomputed only where it changed.
- **Mixer strip: the knobs fit on screen**: On a 1280-point-wide screen, the left TRIM knob went off screen as soon as
  a track had its stems (the STEMS EQ label widens the channel). The knobs now tighten to fit, at the same distance
  from the edge on both sides.

</details>

## 1.30 — 13 novembre 2026

- **Formes d’onde : l’onde réelle, une seule couche** : La forme d’onde des platines dessine maintenant le son
  lui-même, creux et crêtes, au lieu d’une enveloppe lissée : au zoom, on voit les alternances d’une basse ou d’une
  grosse caisse, comme dans un éditeur audio. La seconde couche plus large et plus pâle (le contour de crête)
  disparaît : une seule forme, nette, aux couleurs de Serato. Les EQ, le filtre et les stems coupés la font toujours
  fondre en direct. Dans le menu des formes d’onde, « Forme » : onde réelle, onde symétrique (repliée des deux côtés,
  comme Serato) ou l’enveloppe d’avant.
- **L’écran Mix demande deux fois moins à la carte graphique** : Formes d’onde, vues d’ensemble et textes des platines
  sont dessinés autrement, pour la même image : ce qui ne dépend que de la ligne de temps est calculé une fois par
  ligne au lieu d’une fois par point, et les textes ne sont redessinés que lorsqu’ils changent. Mesuré en lecture sur
  un Mac M1, deux platines : 3 ms par image au lieu de 5 à 6, toujours à 60 images par seconde.
- **Tonalité calculée : elle ne disparaît plus** : Un son sans grille perdait sa tonalité calculée un chargement sur
  deux (« — » à la place de la tonalité). Elle reste maintenant affichée.
- **Un son glissé du Finder revient à la reprise** : Un fichier glissé du Finder sur une platine revient lui aussi
  avec « Démarrer et reprendre », au même endroit, après une relance ou un plantage. Avant, sa platine revenait vide.
- **Glisser un son d’une platine vers l’autre** : Comme dans Serato : attrape le titre (ou la pochette, ou le numéro)
  d’une platine et lâche-le sur l’autre platine ou sur sa forme d’onde : le son s’y charge. Avec « Instant Doubles »
  (allumé d’office), il arrive au même endroit, au même tempo, et repart calé si l’autre joue. Une platine qui passe à
  l’antenne reste protégée, comme pour tout chargement.
- **Onglet des pads allumé en couleur, boucle et pads resserrés, coins moins arrondis** : L’onglet des pads choisi
  (HOT CUE, STEMS, FLIP, LOOPS, ROLL, SAMPLER, SORTIES) se remplit de sa couleur : on le voit d’un coup d’œil, la
  nuit, en plein set ; les autres gardent leur trait de couleur. Sur la platine, les boutons de boucle sont serrés
  entre eux et mieux séparés des huit pads, eux aussi un peu plus serrés. Partout dans l’app, les coins arrondis sont
  réduits de moitié (boutons, plaques, champs, menus, fenêtres) ; ce qui est rond le reste (disques, potards,
  voyants). Aussi : les champs du Journal sont alignés et leurs textes d’aide entiers, les curseurs de l’Égaliseur et
  du Micro sont dessinés, et les dernières flèches écrites en caractères (mois, Intro Lab, Mélodie, sous-menus) sont
  de vraies icônes.
- **Barre de la liste, onglets et boucle : la même finition partout** : Dans la barre de la liste, plus rien ne se
  coupe : le champ de recherche garde son texte entier, « Compatibles » devient une icône quand la place manque (au
  lieu de « C… »), et la taille du texte, les pochettes et le menu Analyser ont de vraies icônes. La barre du bas
  affiche toujours ce que fait chaque bouton (Charger, Deck 1, Deck 2, Pré-écoute, Rechercher) ; sur un écran étroit,
  elle ne montrait que des touches. Dans toutes les dispositions : les onglets des pads en mots entiers quand ils
  tiennent, la boucle en 1/2X et 2X avec un reloop dessiné, GRILLE et la plage du tempo en vrais boutons. Au survol
  d’une ligne, le bouton de pré-écoute ne coupe plus la pastille des versions en deux.
- **La platine : un disque bien rond, des commandes mieux dessinées** : Le disque a maintenant une jante : la pochette
  tourne à l’intérieur et le bord du disque reste le même tout autour. Avant, la pochette allait jusqu’au bord : il
  prenait sa couleur à cet endroit, claire ici, sombre là, et semblait se déformer en tournant ; un liseré en
  pointillé courait aussi le long du bord. En Vertical et en Horizontal, Key lock, Slip, Reverse et Éjecter mordaient
  dans le disque : ce sont maintenant de petites icônes dans ses coins, hors du cercle. Les onglets des pads
  s’écrivent en entier (SAMPLER, SORTIES au lieu de SMPL, SORT.) ; chacun garde sa couleur, par un trait fin du côté
  de ses pads. Les flèches, le reloop, − et + sont dessinés au lieu d’être des caractères, et les boutons d’une même
  platine ont la même forme. La boucle se divise et se double avec 1/2X et 2X, comme sur la table.
- **La platine range ses boutons comme Serato** : Dans les dispositions Vertical et Horizontal, la platine reprend la
  place des boutons de Serato DJ Pro. Le pitch est au bord extérieur, avec − + (coup de vitesse) et RANGE dessous. Les
  onglets des pads sont en colonne, dans l’ordre de Serato : HOT CUE, STEMS, FLIP, LOOPS, puis ROLL, SAMPLER et
  SORTIES. Sous les pads : IN, OUT, LOOP, reloop, 1/2X et 2X, puis les boucles automatiques par taille (de 1/8 à 16
  temps, les flèches pour aller de 1/32 à 32). Autour du disque : SYNC en haut à gauche, CUE et lecture en haut à
  droite ; dans ses coins, en icônes : Key lock et Slip en haut, Reverse en bas à gauche, Éjecter en bas à droite ; le
  vumètre au bord. Dans la tête, sous le micro (Acapella) et la tonalité : Instrumental (la voix coupée) et Key Sync
  entre ses deux flèches. Un hot cue vide montre une croix. Le disque est plus grand quand la place le permet. Les
  platines repliées, l’Extended et la Classique gardent leur rangement.

<details><summary>In English (November 13, 2026)</summary>

- **Waveforms: the real wave, a single layer**: The deck waveform now draws the sound itself, troughs and peaks,
  instead of a smoothed envelope: zoomed in, you see the cycles of a bass or a kick, as in an audio editor. The
  second, wider and paler layer (the peak outline) is gone: one crisp shape, in Serato’s colours. EQs, the filter and
  muted stems still make it shrink live. In the waveform menu, “Shape”: real wave, mirrored wave (folded on both
  sides, like Serato) or the previous envelope.
- **The Mix screen asks half as much of the graphics card**: Waveforms, overviews and deck texts are drawn
  differently, for the same picture: what only depends on the time line is computed once per line instead of once per
  pixel, and texts are only redrawn when they change. Measured while playing on an M1 Mac, two decks: 3 ms per frame
  instead of 5 to 6, still at 60 frames per second.
- **Computed key: it no longer disappears**: A track without a beatgrid lost its computed key every other load (“—”
  instead of the key). It now stays displayed.
- **A track dragged from the Finder comes back on resume**: A file dragged from the Finder onto a deck now also comes
  back with “Start and resume”, at the same position, after a relaunch or a crash. Before, its deck came back empty.
- **Drag a track from one deck to the other**: As in Serato: grab the title (or the cover, or the deck number) of a
  deck and drop it on the other deck or on its waveform: the track loads there. With Instant Doubles (on by default),
  it lands at the same position and tempo, and starts in time if the other deck is playing. A deck that is live stays
  protected, as for any load.
- **Selected pad tab lit in its colour, tighter loop and pads, less rounded corners**: The selected pad tab (HOT CUE,
  STEMS, FLIP, LOOPS, ROLL, SAMPLER, EXITS) now fills with its colour: you see it at a glance, at night, mid-set; the
  others keep their colour strip. On the deck, the loop buttons sit closer together and are better separated from the
  eight pads, which are a little tighter too. Everywhere in the app, rounded corners are halved (buttons, panels,
  fields, menus, windows); what is round stays round (platters, knobs, lights). Also: the Journal fields are aligned
  and their hints are no longer cut, the Equalizer and Mic sliders are drawn, and the last arrows written as
  characters (months, Intro Lab, Melody, submenus) are real icons.
- **List toolbar, tabs and loop: the same finish everywhere**: In the list toolbar, nothing is cut off any more: the
  search field keeps its full text, “Compatible” becomes an icon when space is short (instead of “C…”), and text size,
  cover art and the Analyze menu have proper icons. The bottom bar always says what each button does (Load, Deck 1,
  Deck 2, Preview, Search); on a narrow screen it only showed keys. In every layout: pad tabs in full words when they
  fit, the loop as 1/2X and 2X with a drawn reloop, GRID and the tempo range as real buttons. When you hover a row,
  the preview button no longer cuts the versions badge in half.
- **The deck: a truly round platter, better-drawn controls**: The platter now has a rim: the cover art spins inside it
  and the edge of the platter stays the same all the way round. Before, the art went right to the edge, which took its
  colour at that spot, light here, dark there, and seemed to change shape as it turned; a dotted line also ran along
  the edge. In Vertical and Horizontal, Key lock, Slip, Reverse and Eject were biting into the platter: they are now
  small icons in its corners, outside the circle. The pad tabs are written in full (SAMPLER, EXITS instead of SMPL,
  EXIT); each keeps its colour, as a thin line on the side of its pads. Arrows, reloop, − and + are drawn instead of
  being typed characters, and the buttons of a deck share the same shape. The loop is halved and doubled with 1/2X and
  2X, as on the controller.
- **The deck puts its buttons where Serato has them**: In the Vertical and Horizontal layouts, the deck now puts its
  buttons where Serato DJ Pro has them. Pitch sits on the outer edge, with − + (nudge) and RANGE below it. The pad
  tabs are in a column, in Serato’s order: HOT CUE, STEMS, FLIP, LOOPS, then ROLL, SAMPLER and EXITS. Under the pads:
  IN, OUT, LOOP, reloop, 1/2X and 2X, then auto loops by size (1/8 to 16 beats, arrows to reach 1/32 to 32). Around
  the platter: SYNC top left, CUE and play top right; in its corners, as icons: Key lock and Slip at the top, Reverse
  bottom left, Eject bottom right; the meter on the edge. In the header, under the mic (Acapella) and the key:
  Instrumental (vocals muted) and Key Sync between its two arrows. An empty hot cue shows a cross. The platter gets
  bigger when there is room. Folded decks, Extended and Classic keep their arrangement.

</details>

## 1.23 — 13 novembre 2026

- **Intro Lab : un instrument par bloc de mélodie** : Jusqu’à la 1.22, l’instrument d’une variation valait pour tout
  le morceau : mettre le piano sur une mesure le mettait partout. Chaque bloc (une mesure de la ligne Mélodie qui joue
  une variation) a maintenant le sien : piano électrique sur l’un, lead, nappe, pluck ou basse 808 sur un autre, et de
  même « Garder la mélodie d’origine dessous ». Clic droit sur le bloc, puis Instrument. Le nom de l’instrument est
  écrit sur le bloc. Un edit déjà fait garde son réglage.
- **Intro Lab : glisser un bloc pour le copier** : Un bloc qui te plaît se glisse vers une autre mesure, à gauche ou
  à droite : il y est copié tel quel (variation, instrument, mélodie dessous), sans rien régler de nouveau. Avec ⇧
  tenu, il est posé sur toutes les mesures traversées. Lâché hors de la ligne, ou Échap : rien ne change. La copie ne
  demande aucun calcul (c’est le même son) et reste indépendante : on peut ensuite lui donner un autre instrument.
- **Plus de place à l’écran : marges resserrées partout, barre du haut plus fine** : Les marges ont été réduites un
  peu partout pour gagner de la place. Barre du haut : 34 px au lieu de 40, le logo intact. Platines : bords de 6 px
  au lieu de 12, la place va au disque et aux pads (dans une fenêtre de 1280 × 800, en Vertical, le disque passe de
  129 à 149 px). Intro Lab, Journal, Bookings et Réglages ont maintenant les mêmes marges fines que l’écran Mix. Dans
  Intro Lab, chaque préréglage tient sur une ligne ; dans Réglages, toutes les sections se voient sans défiler.
  L’icône du téléphone (télécommande) est redessinée : un téléphone qui émet, plus facile à reconnaître.
- **Une nouvelle version ? Scalpel DJ te prévient** : Quand une version plus récente est sortie, Scalpel DJ le dit :
  une pastille sur l’écran de démarrage, un message une fois, un point sur l’onglet Réglages, et dans Réglages → À
  propos ce qu’elle change et le bouton pour la télécharger. La question est posée à GitHub au lancement, puis deux
  fois par jour, hors de l’écran et du son, et jamais pendant qu’une platine joue ou que REC enregistre. Sans
  Internet, rien ne s’affiche et rien n’attend. Rien de ton Mac n’est envoyé, rien n’est téléchargé ni installé tout
  seul. L’annonce se coupe dans Réglages → À propos.

<details><summary>In English (November 13, 2026)</summary>

- **Intro Lab: one instrument per melody block**: Up to 1.22, a variation’s instrument applied to the whole track:
  putting the piano on one bar put it everywhere. Each block (a bar of the Melody row that plays a variation) now has
  its own: electric piano on one, lead, pad, pluck or 808 bass on another, and likewise “Keep the original melody
  underneath”. Right-click the block, then Instrument. The instrument’s name is written on the block. An edit you
  already made keeps its setting.
- **Intro Lab: drag a block to copy it**: A block you like can be dragged to another bar, left or right: it is
  copied there as is (variation, instrument, melody underneath), with nothing to set up again. Hold ⇧ to drop it on
  every bar crossed. Released outside the row, or Esc: nothing changes. The copy needs no computation (it is the same
  sound) and stays independent: you can then give it another instrument.
- **More room on screen: tighter margins everywhere, thinner top bar**: Margins have been trimmed all over to save
  room. Top bar: 34 px instead of 40, the logo untouched. Decks: 6 px edges instead of 12, the room goes to the
  platter and the pads (in a 1280 × 800 window, in Vertical, the platter grows from 129 to 149 px). Intro Lab,
  Journal, Bookings and Settings now have the same thin margins as the Mix screen. In Intro Lab, each preset fits on
  one line; in Settings, every section shows without scrolling. The phone icon (remote) is redrawn: a phone that
  transmits, easier to recognise.
- **A new version? Scalpel DJ tells you**: When a newer version is out, Scalpel DJ says so: a pill on the start
  screen, a message once, a dot on the Settings tab, and in Settings → About what it changes and the button to
  download it. The question is asked to GitHub at launch, then twice a day, off the screen and off the audio, and
  never while a deck is playing or REC is recording. With no Internet, nothing shows and nothing waits. Nothing from
  your Mac is sent, nothing is downloaded or installed by itself. The notice can be turned off in Settings → About.

</details>

## 1.22 — 13 novembre 2026

- **Intro Lab : les variations de mélodie refaites pour sonner juste (à tester)** : Les variations de la 1.21
  sonnaient faux. Mesuré sur huit stems : quatre « notes » sur cinq d’un stem de mélodie sont en fait des accords, et
  la 1.21 ré-accordait ces morceaux d’accords comme une seule note. Maintenant, les variations intelligentes (harmonie
  à la tierce ou à la sixte, arpèges des accords, arpège sur la mélodie, question-réponse, ornements, nouveau rythme,
  miroir, épurée, accords, ligne de basse, et treize phrases façon Nora : arpège montant, pluck afro 3-3-2, stabs
  dancehall à contretemps, rolls trap, reggaeton 3+3+2…) sont fabriquées d’après l’harmonie mesurée dans le morceau :
  la gamme et l’accord de chaque mesure, d’après ce qui sonne dans le stem et la basse, même quand le tag de tonalité
  se trompe. Elles sont jouées par un instrument au choix, accordé comme le morceau (pluck, piano électrique, nappe,
  lead ou basse 808), par-dessus la mélodie d’origine ou à sa place. S’y ajoutent les variations du stem lui-même,
  cloné d’un bloc : octaves, réponse à l’octave, octaves alternées, à l’envers, demi-tempo. Clic droit sur une case de
  la ligne Mélodie. Vérifié par la mesure, pas encore jugé à l’oreille.

<details><summary>In English (November 13, 2026)</summary>

- **Intro Lab: melody variations rebuilt to sound in tune (to be tested)**: The variations of 1.21 sounded out of
  tune. Measured on eight stems: four out of five « notes » in a melody stem are in fact chords, and 1.21 retuned
  those chunks of chords as if they were one note. Now the smart variations (harmony a third or a sixth away, chord
  arpeggios, arpeggio on the melody, call and response, ornaments, new rhythm, mirror, pared down, chords, bass line,
  and thirteen Nora-style phrases: rising arpeggio, afro 3-3-2 pluck, offbeat dancehall stabs, trap rolls, reggaeton
  3+3+2…) are built from the harmony measured in the track: the scale and the chord of each bar, from what actually
  sounds in the stem and the bass, even when the key tag is wrong. They are played by an instrument of your choice,
  tuned like the track (pluck, electric piano, pad, lead or 808 bass), over the original melody or in its place. Added
  to them are the variations of the stem itself, cloned in one block: octaves, answer at the octave, alternating
  octaves, backwards, half-time. Right-click a cell of the Melody row. Checked by measurement, not yet judged by ear.

</details>

## 1.21 — 13 novembre 2026

- **Intro Lab : variations de mélodie au clic droit (à tester)** : Clic droit sur une case de la ligne Mélodie : un
  menu déroulant de 37 variations de la mélodie de cette mesure, en 12 familles (harmonie, octaves, arpèges, miroir, à
  l’envers, nouveau rythme, ornements, épurée, question-réponse, accords, ligne de basse). La variation est rejouée
  avec le son du stem lui-même, au même niveau, et ne remplace que la mélodie de cette mesure ; « Mélodie d’origine »
  la rend. L’edit est refait en 1 à 3 secondes, la case porte une note (♪). C’était l’idée de départ du moteur Mélodie
  : son onglet à part quitte la barre du haut. Pas encore jugé à l’oreille : les notes relevées sur un stem séparé
  sont approximatives.
- **Les hot cues se déplacent à la souris** : Pris par le haut de son pad (la ligne du numéro), un hot cue se glisse
  sur un autre pad : les deux échangent leurs places ; sur un pad vide, il y va. Comme dans Serato, où un cue se prend
  par son heure. Le reste du pad déclenche le cue comme avant. Sans effet quand les cues sont rangés dans l’ordre du
  morceau (réglage).
- **Mode incognito : deux appuis sur Fn (à tester)** : Deux appuis brefs sur la touche Fn (🌐), la même sur tous les
  claviers de Mac, masquent ou remontrent titres, artistes et pochettes (le « Hide Track/Artist » de Serato, déjà sur
  ⌥ /). À couper dans Réglages → Bibliothèque si macOS se sert déjà de ce double appui (dictée). Vérifié avec de faux
  appuis envoyés au système, pas encore sur un vrai clavier.
- **Intro Lab : la forme d’onde du morceau est revenue** : Depuis la 1.18, la forme d’onde du morceau ouvert dans
  Intro Lab ne montrait plus que son début (un cinquième à un tiers du morceau) : le son partait au calcul avant que
  la forme d’onde ait fini de le lire. Elle couvre de nouveau tout le morceau, et un contrôle automatique le vérifie
  maintenant à chaque version.
- **Intro Lab : le nombre de mesures et la sortie se choisissent de nouveau** : Depuis la 1.13, « Intro, en mesures »
  (8, 16, 32) et « Sortie » étaient écrasés à 2 pixels de haut dès que la colonne de gauche débordait (écran de 13
  pouces, ou un préréglage personnel gardé) : on ne pouvait plus les choisir. Ils ont retrouvé leur hauteur et sont
  passés en tête de colonne, toujours visibles sans défiler. La ligne d’infos sous l’edit n’est plus coupée quand les
  reprises proposées tiennent sur deux rangées.

<details><summary>In English (November 13, 2026)</summary>

- **Intro Lab: melody variations on right-click (to be tested)**: Right-click a cell of the Melody row: a drop-down
  list of 37 variations of that bar’s melody, in 12 families (harmony, octaves, arpeggios, mirror, backwards, new
  rhythm, ornaments, stripped down, call and response, chords, bass line). The variation is replayed with the sound of
  the stem itself, at the same level, and only replaces the melody of that bar; “Original melody” brings it back. The
  edit is rebuilt in 1 to 3 seconds, and the cell carries a note (♪). This was the original idea behind the Melody
  engine: its separate tab leaves the top bar. Not judged by ear yet: the notes read from a separated stem are
  approximate.
- **Hot cues can be moved with the mouse**: Grabbed by the top of its pad (the number line), a hot cue can be dragged
  onto another pad: the two swap places; on an empty pad, it moves there. Like in Serato, where a cue is grabbed by
  its time. The rest of the pad triggers the cue as before. No effect when cues are sorted in track order (setting).
- **Incognito mode: press Fn twice (to be tested)**: Two quick presses on the Fn (🌐) key, the same on every Mac
  keyboard, hide or show titles, artists and artwork (Serato’s “Hide Track/Artist”, already on ⌥ /). Switch it off in
  Settings → Library if macOS already uses that double press (dictation). Checked with simulated presses sent to the
  system, not on a real keyboard yet.
- **Intro Lab: the track waveform is back**: Since 1.18, the waveform of the track opened in Intro Lab only showed its
  beginning (a fifth to a third of the track): the audio left for processing before the waveform had finished reading
  it. It covers the whole track again, and an automatic check now verifies it for every version.
- **Intro Lab: the number of bars and the outro can be chosen again**: Since 1.13, “Intro, in bars” (8, 16, 32) and
  “Outro” were squashed to 2 pixels high as soon as the left column overflowed (13-inch screen, or a saved personal
  preset): they could no longer be chosen. They have their height back and moved to the top of the column, always
  visible without scrolling. The info line under the edit is no longer cut off when the suggested comebacks take two
  rows.

</details>

## 1.19 — 12 novembre 2026

- **Plus d’image sautée au lancement d’un morceau quand les stems démarrent** : Suite de la 1.18. Dans la seconde qui
  suit le lancement, l’éclairage d’ambiance (la lumière bleue ou orange qui s’allume derrière la platine à l’antenne)
  faisait redessiner toute la fenêtre à chaque image, pile au moment où le calcul des stems prend la carte graphique :
  une image sautée dans un départ sur deux, et de temps en temps un blocage de 85 à 270 ms. Les deux lumières ne
  couvrent plus que la zone où elles se voient : même image (1 niveau sur 255 d’écart au plus), même fondu de 0,8 s,
  et les stems arrivent aussi vite qu’avant. Les formes d’onde des stems, encore vides au chargement, ne sont plus
  calculées ni envoyées à la carte graphique pour rien. Mesuré sur un MacBook Air M1 en économie d’énergie, 12 départs
  : 10 sans aucune image lente pendant les 4 premières secondes, 2 avec une seule image de 33 ms à l’instant même du
  lancement ; avant, 2 à 5 départs sur 8 étaient touchés entre 0,6 et 0,9 s.

<details><summary>In English (November 12, 2026)</summary>

- **No more skipped frame when a track starts while the stems are starting**: Follow-up to 1.18. In the second after a
  track starts, the ambient lighting (the blue or orange glow that lights up behind the deck on air) made the whole
  window redraw on every frame, right when the stems computation takes the graphics chip: one skipped frame in every
  other start, and now and then a 85 to 270 ms stall. The two glows now only cover the area where they can be seen:
  same picture (1 level out of 255 at most), same 0.8 s fade, and the stems arrive as fast as before. The stem
  waveforms, still empty at load, are no longer computed and sent to the graphics chip for nothing. Measured on an M1
  MacBook Air in Low Power Mode, 12 starts: 10 with no slow frame at all in the first 4 seconds, 2 with a single 33 ms
  frame at the very instant of the start; before, 2 to 5 starts out of 8 were hit between 0.6 and 0.9 s.

</details>

## 1.18 — 12 novembre 2026

- **La forme d’onde ne se fige plus au départ d’un morceau** : Signalé par Dj Adrian Reid : un morceau lancé dès qu’il
  est chargé, et pendant deux secondes la forme d’onde avançait par à-coups (le son, lui, ne bougeait pas). Le morceau
  partait vers le calcul des stems en gros paquets, coup sur coup, sur le fil qui dessine l’écran ; il part maintenant
  en petits paquets, autant qu’il en tient dans une image, et les stems ne démarrent pas plus tard (envoi en 0,1 s).
  Mesuré sur un MacBook Air M1 : 13 images figées (67 à 134 ms) à chaque départ avant ; après, 7 départs sur 8 sans
  aucune, et sinon une ou deux, au moment où le calcul des stems démarre sur la carte graphique.
- **Charger un morceau ne fige plus l’écran** : Pendant qu’une platine joue, charger l’autre figeait l’image quatre à
  cinq fois, de 100 à 230 ms à chaque fois : la liste et les suggestions de la bibliothèque étaient refaites en entier
  à chaque étape du chargement, le son était mélangé d’un bloc, le fichier relu quatre fois. Les suggestions ne sont
  plus refaites que si elles changent, et par petites tranches ; le reste aussi. Mesuré sur 8 chargements : 515 ms
  d’écran figé par chargement avant, 100 à 160 ms après ; la pire image, 232 ms avant, 85 à 134 ms après.
- **Un écran fluide juste après « Démarrer »** : Les couleurs de Serato étaient relues d’un bloc sur le fil qui
  dessine l’écran, et le tempo des samples y était calculé, avec leur tonalité et une grille dont ils n’ont pas
  besoin. Les deux se font maintenant à part. Mesuré : 30 blocages (3,4 s en tout) après « Démarrer » avant, un seul
  de 54 ms après.

<details><summary>In English (November 12, 2026)</summary>

- **The waveform no longer freezes when a track starts**: Reported by Dj Adrian Reid: a track started as soon as it
  was loaded, and for two seconds the waveform moved in jerks (the sound itself was fine). The track was sent to the
  stems computation in big packets, back to back, on the thread that draws the screen; it now goes in small packets,
  as many as fit in one frame, and the stems start no later (sent in 0.1 s). Measured on an M1 MacBook Air: 13 frozen
  frames (67 to 134 ms) at every start before; after, 7 starts out of 8 with none, and otherwise one or two, at the
  moment the stems computation starts on the graphics chip.
- **Loading a track no longer freezes the screen**: While one deck was playing, loading the other froze the picture
  four to five times, 100 to 230 ms each time: the library list and suggestions were rebuilt entirely at each step of
  the load, the audio was mixed down in one block, the file read four times. Suggestions are now rebuilt only when
  they change, and in small slices; so is the rest. Measured over 8 loads: 515 ms of frozen screen per load before,
  100 to 160 ms after; the worst frame, 232 ms before, 85 to 134 ms after.
- **A smooth screen right after “Start”**: Serato’s colours were read in one block on the thread that draws the
  screen, and the tempo of the samples was computed there, with their key and a grid they do not need. Both are now
  done elsewhere. Measured: 30 stalls (3.4 s in all) after “Start” before, a single one of 54 ms after.

</details>

## 1.17 — 12 novembre 2026

- **XDJ-RX3 : le son sort du master (à tester)** : Signalé par Dj Adrian Reid : avec la 1.16, toutes les commandes de
  la XDJ-RX3 répondaient mais rien ne sortait du master. La carte son de la RX3 ne tourne qu’à 44,1 kHz ; Scalpel, qui
  travaille à 48 kHz, la refusait et envoyait le son sur la sortie du Mac. Scalpel ouvre maintenant une telle carte à sa
  fréquence et y convertit son moteur (niveau exact, 0,7 ms de plus). Vaut pour toute table à 44,1 kHz seulement.
  Vérifié sur une carte virtuelle à 44,1 kHz, pas encore sur une vraie RX3.
- **Grille flexible : Scalpel la calcule** : Clic droit sur un son → Grille → Grille flexible : pour un son que Serato
  5 n’a pas analysé, Scalpel calcule une grille dont le tempo suit le morceau (batteur, vieux disques, live) et la garde
  ; « Grille fixe » revient à un seul tempo ; pareil pour toute une crate. À l’analyse, elle n’est prise d’office que si
  elle colle nettement mieux que la grille fixe. Mesuré contre les grilles de Serato 5 sur 155 sons dont le tempo change
  : 72 % des temps trouvés à 20 ms près, contre 61 % avec la grille fixe. Réglages → Platines → « Changements de tempo
  de la grille » : à la mesure ou au temps, comme dans Serato.
- **Clic droit d’un morceau et d’une crate, comme dans Serato 5** : Morceau : Ajouter à (Préparation, crate Stems),
  Analyser, Grille (flexible / fixe), Changer le BPM (÷ 2, × 2, d’origine), Note en émoji, Couleur du son (les 20
  couleurs de Serato), Montrer dans les crates, Marquer comme joué ou non joué, Verrouiller la grille, Relire les infos
  du fichier, Supprimer (de la crate, de la bibliothèque avec retour possible, corbeille du Mac). Sons introuvables :
  Chercher partout ou Choisir l’emplacement. Crate : émoji, couleur, Ajouter à, Analyser, grille pour toute la crate,
  Relire les infos, Crate favorite (en tête de liste), Renommer, Supprimer ou Masquer. Rien n’est écrit dans Serato.
- **Sur la platine : Acapella, Repeat, FLIP, saut de temps, Autoplay** : Un bouton micro dans la tête de platine joue
  la voix seule, puis le morceau entier. « Repeat » rejoue le morceau à la fin. Nouvel onglet FLIP sur les pads :
  enregistrer et rejouer une suite de hot cues (pads 1 à 6 rejouent, 7 enregistre, 8 boucle, Maj efface). Boutons ◀ N ▶
  pour sauter d’un nombre de temps (Réglages → Platines → Boutons de saut). Autoplay, en bas de la bibliothèque : charge
  et lance le morceau suivant de la liste à la fin du morceau.
- **Les réglages de Serato 5, vérifiés dans Serato** : Chaque réglage a été comparé à Serato DJ Pro 5 ouvert (bulles
  d’aide, essais sur ses platines). Mode de SYNC : Smart (tempo et temps gardés calés), Simple (calés une fois à
  l’appui), Coupée ; Garder la SYNC au chargement ; Caler les points sur la grille ; Pas du Quantize (1/16 à 4 temps) ;
  Poser un hot cue d’une touche (1 à 0 sans ⌘) ; Cue Loops (pendant une boucle, 1 à 0 la rangent dans un hot cue qui la
  rallume ; ceux écrits par Serato sont lus) ; Ranger les cues dans l’ordre ; Retour du SLIP (1/2 à 8 temps) ; Démarrage
  et Arrêt freinés, avec le même bouton que Serato (rampe mesurée, jusqu’à 24,6 s) ; Aiguille bloquée pendant la lecture
  (Maj passe) ; Éteindre les effets au chargement ; BPM à 1 ou 2 décimales ; tempo écrit sur la forme d’onde là où il
  change.
- **Tonalité calculée comme Serato, et menu Analyser** : Pour un son sans tonalité, Scalpel la calcule avec la méthode
  de Serato 5 : 89 % identiques à Serato et 97 % compatibles en Camelot sur 596 sons, en 0,4 s par son. Notation au
  choix : Camelot, Open Key ou classique. Bouton « Analyser ▾ » dans la bibliothèque : la liste ouverte, toute la
  bibliothèque, arrêter ; les sons ajoutés peuvent être analysés d’office.
- **Bibliothèque : pochettes, colonnes par crate, Day Mode** : Vue avec les pochettes (▦) ; colonnes propres à une
  crate ; colonne « Joué » avec le nombre de lectures ; Day Mode (☀) pour le plein soleil ; titres et artistes masqués
  pour un écran filmé (⌥ /) ; morceaux déjà joués estompés, en couleur ou sans marque, remis à zéro au lancement si tu
  veux ; bibliothèque protégée en soirée (rien ne s’efface par erreur) ; le morceau choisi peut rester au milieu de la
  liste ; les sons chargés peuvent rester dans Préparation. Les playlists de l’app Musique en crates, avec leurs étoiles
  (à tester).
- **Journal : non joués, exports, Live Playlist** : Dans le Journal : démarrer et terminer une soirée, insérer un
  morceau joué ailleurs, voir les sons chargés mais pas joués, remettre les joués à zéro, exporter la setlist en texte,
  CSV, M3U ou en crate. Live Playlist : la setlist en direct sur une page du Wi-Fi du lieu, avec un QR code.
- **Table, affichage, son vers une autre app, aide** : Table : hausse de l’EQ (+12, +6, +3 ou 0 dB), côté du
  crossfader par platine (A, THRU, B), fondu Power ou Linéaire. Affichage : formes d’onde sans couleurs d’EQ, images par
  seconde, haute résolution, liste des cues avec leurs temps. Audio : le master copié vers une autre sortie (BlackHole,
  Loopback… pour OBS ou un live) et le morceau en cours écrit dans un fichier texte (à tester). Aide : bulles d’aide
  coupables, touches du clavier affichées sur les platines, touches de jeu coupables.
- **Vinyles et CDJ timecode : les réglages de Serato (à tester)** : Anti-Drift, pose d’aiguille en relatif (à
  l’endroit lu sur le disque, ou sur un hot cue), Sticker Lock (au plus près, en avant, en arrière), boucles réglées au
  disque. Jamais essayés sur un vrai disque timecode.
- **Effets : 66 au lieu de 20, dont 15 calés sur Serato par la mesure** : 46 effets de plus, avec les noms de Serato
  5, une recherche par nom et des favoris (étoile ; le sélecteur de la table ne tourne alors que sur eux). 15 sont calés
  sur ceux de Serato 5, mesurés un par un dans Serato (signal d’essai enregistré, puis comparaison) : Delay, Low Cut
  Echo, Multi Tap Delay, Version Echo, Drive Filter, Wah Filter, Tremolo, Pansformer, Distortion, Lo-Fi Warmth, Bright
  Reverb, Empty Mall Verb, Epic Reverb, Next Door Verb, Vast Reverb. Les 31 autres nouveaux sont faits d’après leur nom
  et pas encore mesurés (à tester) : ils peuvent sonner autrement que dans Serato. Braker et Roll Out manquent encore.
- **Corrigé : la recherche écrasée sur un écran de 13 pouces** : Sur un écran de 1 440 points de large, le champ de
  recherche de la bibliothèque n’affichait plus que « C… » ; il a retrouvé sa largeur. À 1 100 points, le bouton plein
  écran ne sort plus de la fenêtre.

<details><summary>In English (November 12, 2026)</summary>

- **XDJ-RX3: sound now comes out of the master (to be tested)**: Reported by Dj Adrian Reid: with 1.16, every control
  of the XDJ-RX3 responded but nothing came out of the master. The RX3 sound card only runs at 44.1 kHz; Scalpel, which
  works at 48 kHz, refused it and sent the sound to the Mac output. Scalpel now opens such a card at its own rate and
  converts its engine to it (exact level, 0.7 ms more). This applies to any 44.1 kHz-only controller. Checked on a
  virtual 44.1 kHz card, not yet on a real RX3.
- **Flexible beatgrid: Scalpel computes it**: Right-click a track → Beatgrid → Flexible beatgrid: for a track Serato 5
  has not analysed, Scalpel computes a grid whose tempo follows the track (live drummer, old records) and keeps it;
  “Fixed beatgrid” goes back to one tempo; same for a whole crate. During analysis it is only chosen by itself when it
  clearly fits better than the fixed grid. Measured against Serato 5 grids on 155 tracks whose tempo changes: 72 % of
  beats found within 20 ms, against 61 % with the fixed grid. Settings → Decks → “Beatgrid tempo changes”: on bars or on
  beats, like Serato.
- **Track and crate right-click menus, like Serato 5**: Track: Add to (Prepare, Stems crate), Analyze, Beatgrid
  (flexible / fixed), Change BPM (÷ 2, × 2, original), Rating emoji, Track colour (Serato’s 20 colours), Show in crates,
  Mark as played or unplayed, Lock beatgrid, Re-scan file info, Delete (from the crate, from the library with a way
  back, Mac trash). Missing tracks: Search everywhere or Choose location. Crate: emoji, colour, Add to, Analyze,
  beatgrid for the whole crate, Re-scan info, Favourite crate (top of the list), Rename, Delete or Hide. Nothing is
  written to Serato.
- **On the deck: Acapella, Repeat, FLIP, beat jump, Autoplay**: A mic button in the deck header plays the vocal alone,
  then the full track. “Repeat” plays the track again at the end. New FLIP tab on the pads: record and replay a sequence
  of hot cues (pads 1 to 6 replay, 7 records, 8 loops, Shift erases). ◀ N ▶ buttons jump a number of beats (Settings →
  Decks → Beat jump buttons). Autoplay, at the bottom of the library: loads and starts the next track of the list when
  the track ends.
- **Serato 5 settings, checked in Serato**: Each setting was compared with Serato DJ Pro 5 open (tooltips, trials on
  its decks). Sync mode: Smart (tempo and beats kept matched), Simple (matched once on the press), Off; Maintain sync on
  track load; Snap to beatgrid; Quantize step (1/16 to 4 beats); Set a hot cue with one key (1 to 0 without ⌘); Cue
  Loops (during a loop, 1 to 0 store it in a hot cue that turns it back on; those written by Serato are read); Sort cues
  chronologically; SLIP release (1/2 to 8 beats); braked Start and Stop, with the same knob as Serato (measured ramp, up
  to 24.6 s); Needle locked during playback (Shift passes); Turn off FX on load; BPM with 1 or 2 decimals; tempo written
  on the waveform where it changes.
- **Key detected like Serato, and the Analyze menu**: For a track with no key, Scalpel computes it with Serato 5’s
  method: 89 % identical to Serato and 97 % Camelot-compatible on 596 tracks, in 0.4 s per track. Notation of your
  choice: Camelot, Open Key or classical. “Analyze ▾” button in the library: the open list, the whole library, stop;
  added tracks can be analysed automatically.
- **Library: artwork, per-crate columns, Day Mode**: Artwork view (▦); columns of their own for a crate; “Played”
  column with the play count; Day Mode (☀) for bright sunlight; titles and artists hidden for a filmed screen (⌥ /);
  played tracks dimmed, coloured or unmarked, reset at launch if you like; library protected during a gig (nothing gets
  erased by mistake); the selected track can stay in the middle of the list; loaded tracks can stay in Prepare. Music
  app playlists as crates, with their stars (to be tested).
- **Journal: unplayed tracks, exports, Live Playlist**: In the Journal: start and end a gig, insert a track played
  elsewhere, see tracks loaded but not played, reset played tracks, export the setlist as text, CSV, M3U or a crate.
  Live Playlist: the setlist live on a page of the venue’s Wi-Fi, with a QR code.
- **Mixer, display, sound to another app, help**: Mixer: EQ boost (+12, +6, +3 or 0 dB), crossfader side per deck (A,
  THRU, B), Power or Linear fade. Display: waveforms without EQ colours, frames per second, high resolution, cue list
  with times. Audio: the master copied to another output (BlackHole, Loopback… for OBS or a livestream) and the current
  track written to a text file (to be tested). Help: tooltips can be turned off, keyboard keys shown on the decks, play
  keys can be turned off.
- **Timecode vinyl and CDJs: Serato’s settings (to be tested)**: Anti-Drift, needle dropping in relative mode (to the
  position read on the record, or to a hot cue), Sticker Lock (nearest, forwards, backwards), loops adjusted with the
  vinyl. Never tried on a real timecode record.
- **Effects: 66 instead of 20, 15 of them matched to Serato by measurement**: 46 more effects, with Serato 5’s names,
  a search by name and favourites (star; the controller’s selector then only cycles through them). 15 are matched to
  Serato 5’s, measured one by one in Serato (test signal recorded, then compared): Delay, Low Cut Echo, Multi Tap Delay,
  Version Echo, Drive Filter, Wah Filter, Tremolo, Pansformer, Distortion, Lo-Fi Warmth, Bright Reverb, Empty Mall Verb,
  Epic Reverb, Next Door Verb, Vast Reverb. The other 31 new ones are built from their names and not measured yet (to be
  tested): they may sound different from Serato. Braker and Roll Out are still missing.
- **Fixed: the search box squeezed on a 13-inch screen**: On a 1,440-point-wide screen, the library search box only
  showed “C…”; it has its width back. At 1,100 points, the full-screen button no longer leaves the window.

</details>

## 1.16 — 11 novembre 2026

- **La Pioneer DJ XDJ-RX3 (à tester)**, demandée par **Dj Adrian Reid** sur Instagram : merci ! Elle est reconnue
  d'après la liste officielle de ses messages MIDI (AlphaTheta) : les deux platines (lecture, CUE, boucles, hot cues,
  SEARCH, sync, MASTER TEMPO, REVERSE, jog), la table (faders, TRIM, EQ, COLOR, crossfader, casque), les pads en couleur
  (HOT CUE, SLIP LOOP, et SAVED LOOP, SAMPLER, STEMS dans les modes EXTENSION), les effets, l'écran des jogs et les
  VU-mètres. Scalpel met la table en MIXER MODE « MIDI CONTROL » et mixe lui-même. Jamais essayée sur une vraie table :
  le tour du jog se mesure une fois dans Réglages ; BEAT LOOP, BEAT JUMP et le sélecteur d'effet ne font rien encore.

<details><summary>In English (November 11, 2026)</summary>

- **The Pioneer DJ XDJ-RX3 (to be tested)**, requested by **Dj Adrian Reid** on Instagram: thank you! It is recognized
  from AlphaTheta's official list of its MIDI messages: both decks (play, CUE, loops, hot cues, SEARCH, sync, MASTER
  TEMPO, REVERSE, jog), the mixer (faders, TRIM, EQ, COLOR, crossfader, headphones), the color pads (HOT CUE, SLIP LOOP,
  plus SAVED LOOP, SAMPLER and STEMS in the EXTENSION modes), the effects, the jog displays and the level meters. Scalpel
  sets the mixer to MIXER MODE “MIDI CONTROL” and does the mixing itself. Never tried on a real unit yet: measure the jog
  turn once in Settings; BEAT LOOP, BEAT JUMP and the effect selector do nothing yet.

</details>

## 1.15 — 10 novembre 2026

- **Tous les raccourcis clavier de Serato DJ Pro 5, aux mêmes touches** : E / R et D / F font glisser le tempo tant qu'on
  les tient, comme dans Serato (doucement d'abord, puis plus vite) ; ⌘ ⇧ → / ← doublent dans le même sens que Serato ;
  ⌘ ⇧ R montre le morceau dans ses crates ; ⌘ ⇧ ⌫ le met à la corbeille du Mac (après confirmation) ; Échap quitte la
  recherche, puis l'app (après confirmation). Les touches propres à Scalpel passent avec Maj : ⇧ E sortie, ⇧ R glissement,
  ⇧ D caler, ⇧ F plein écran. Flip (\) n'est pas encore dans Scalpel.
- **Le pitch dessiné comme celui de Serato** : un rail fin, des graduations, un capuchon noir barré de blanc.
- **Plus de place sur l'écran Mix** : bords et écarts réduits à 4 px, moins de vide autour des platines.

<details><summary>In English (November 10, 2026)</summary>

- **All the Serato DJ Pro 5 keyboard shortcuts, on the same keys**: E / R and D / F slide the tempo while held, like
  Serato (slowly at first, then faster); ⌘ ⇧ → / ← double in the same direction as Serato; ⌘ ⇧ R shows the track in its
  crates; ⌘ ⇧ ⌫ moves it to the Mac's Trash (after confirming); Esc exits the search, then the app (after confirming).
  Scalpel's own keys now use Shift: ⇧ E exit, ⇧ R glide, ⇧ D snap, ⇧ F full screen. Flip (\) isn't in Scalpel yet.
- **The pitch drawn like Serato's**: a thin rail, tick marks, a black cap with a white line.
- **More room on the Mix screen**: edges and gaps down to 4 px, less empty space around the decks.

</details>

## 1.14 — 10 novembre 2026

- **Un curseur de pitch sur chaque platine, à la souris** : quand les platines sont repliées (Mac de 13 pouces,
  bibliothèque agrandie), un curseur de pitch apparaît au bord de chaque platine ; avant, il n'y en avait aucun en
  Vertical, Horizontal et Classique à 1280 × 800. Molette ou trackpad dessus pour le réglage fin (Maj : plus vite),
  double-clic : 0 %.
- **Plus de textes qui se chevauchent** : les tuiles du sampler tiennent sur deux lignes ; le titre du son passe avant
  les gros chiffres sur une platine étroite ; les deux temps du plateau ne se touchent plus.
- **Disposition Classique, table cachée** : les deux platines se partagent la largeur (la platine 2 était écrasée).
- **Finitions** : plus de « null » dans le résumé d'une soirée (Journal), plus de coins blancs aux barres de
  défilement, plus de barre de couleur à gauche des titres de la bibliothèque ; recherche, colonnes et champs du
  Journal ne sont plus coupés ; « Nouvelle date » n'apparaît plus trois fois dans un agenda vide.

<details><summary>In English (November 10, 2026)</summary>

- **A pitch slider on each deck, with the mouse**: when the decks are folded (13-inch Mac, enlarged library), a pitch
  slider appears on the edge of each deck; before, there was none in Vertical, Horizontal and Classic at 1280 × 800.
  Mouse wheel or trackpad over it for fine tuning (Shift: faster), double-click: 0 %.
- **No more overlapping text**: sampler tiles fit on two lines; the track title comes before the big numbers on a
  narrow deck; the platter's two times no longer touch.
- **Classic layout, mixer hidden**: the two decks share the width (deck 2 was squeezed).
- **Finishing touches**: no more "null" in a night's summary (Journal), no more white scrollbar corners, no more colour
  bar on the left of library headings; search, columns and Journal fields are no longer cut off; "New date" no longer
  appears three times in an empty agenda.

</details>

## 1.13 — 10 novembre 2026

- **Sampler : le son part de son cue, comme dans Serato** : un son posé sur le sampler part de son premier cue (sinon du
  début), comme « Play From » dans Serato. Clic droit sur un emplacement, « Départ » : le début, un de ses cues ou une de
  ses boucles. Les réglages « Play From » de Serato sont repris avec tes samples.
- **Numark NS7II et NS7III (à tester)** : platines, pads, table et navigation reconnus ; les plateaux motorisés suivent
  la musique quand la platine joue, une main qui tient ou pousse le plateau fait un scratch. Numark ne publie pas leurs
  messages MIDI : la définition suit des relevés publiés par des utilisateurs, jamais essayée ici sur une vraie table.
- **Relevé guidé pour les tables inconnues (à tester)** : Réglages → Contrôleur → « Commencer le relevé… ». Pour une table
  que Scalpel ne connaît pas (Rane Performer, Rane One, Twelve…), Scalpel te demande de toucher chaque commande, une par
  une, et note ce qu'elle envoie. Rien ne joue pendant le relevé. La table marche tout de suite, et le fichier enregistré
  s'envoie à Dj ListenDat pour qu'elle soit reconnue par tous. Essayé avec une fausse table, jamais avec une vraie.

<details><summary>In English (November 10, 2026)</summary>

- **Sampler: the sample starts from its cue, like in Serato**: a sample starts from its first cue (or from the start),
  like Serato's "Play From". Right-click a slot, "Start": the beginning, one of its cues or one of its loops. Serato's
  "Play From" settings come with your samples.
- **Numark NS7II and NS7III (to be tested)**: decks, pads, mixer and browsing recognized; the motorized platters follow
  the music while the deck plays, a hand holding or pushing the platter scratches. Numark does not publish their MIDI
  messages: the definition follows maps published by users, never tried here on a real controller.
- **Guided capture for unknown controllers (to be tested)**: Settings → Controller → "Start the capture…". For a
  controller Scalpel doesn't know (Rane Performer, Rane One, Twelve…), Scalpel asks you to touch each control, one by
  one, and notes what it sends. Nothing plays during the capture. The controller works right away, and the saved file
  goes to Dj ListenDat so it is recognized for everyone. Tried with a simulated controller, never with a real one.

</details>

## 1.12 — 10 novembre 2026

- **Anti-larsen, coupé avant qu'il s'entende (à tester)** : quand la boucle monte (micro approché d'un retour, retours
  montés), Scalpel le voit sur la musique en moins d'une seconde, même pendant que tu parles, et baisse la voix dans
  cette bande seulement. Mesuré au banc (6 salles simulées, 18 cas ; jamais essayé en vraie salle) : larsen audible
  0,05 s en médiane au lieu de 0,45 s, 0,5 s au pire au lieu de 1,0 s ; avec la voix robot 0,4 s au pire au lieu de
  2,4 s. Aucun cas moins bon que la 1.11.
- **Anti-larsen, ta voix et la musique ne sont plus prises pour un larsen (à tester)** : 2 fausses alertes en 10 minutes
  au lieu de 18 (parole, chant, morceaux joués dans le micro).
- **Anti-larsen, la musique retirée du micro, ta voix intacte (à tester)** : 20 dB de musique des retours retirés
  pendant que tu parles, 26 à 31 dB dans les pauses ; ta voix change de 0,4 dB au plus.
- **« Mesurer sur la musique » (à tester)** : dans « Régler… » (Mac et Studio du téléphone), laisse jouer un son 20 à
  30 s : Scalpel dit à combien de dB tu es du larsen et pose les filtres utiles, sans rien faire siffler.
- **Moins de processeur** : micro ouvert voix éteinte, l'annulation coûte 1,3 % au lieu de 6,6 % ; le son de deux
  platines passe de 14 % à 6-7 % d'un cœur.
- **Son Scalpel, le punch** (Moyen et Fort) : chaque coup de grosse caisse et de caisse claire frappe plus fort
  (+1,7 dB en Moyen, +3,1 dB en Fort), au même volume perçu.
- **Grilles du bouyon** : quand la grosse caisse frappe au double du tempo, la grille se pose sur la caisse claire,
  comme dans Serato 5 (14 grilles justes sur 16 au lieu de 7).
- **Chercher dans toute la bibliothèque, comme dans Serato** : ⌘ F cherche partout, Échap ramène à la crate, bouton
  « Tout » ; les sons d'un disque débranché sont trouvés aussi.
- **Boucles enregistrées, comme dans Serato** : l'onglet LOOPS montre les 8 boucles du son, celles de Serato comprises.
- **Mélodie** : une note allongée garde une attaque nette ; les curseurs d'une note répondent au clic.

<details><summary>In English (November 10, 2026)</summary>

- **Anti-feedback, cut before you hear it (to be tested)**: when the loop rises (mic brought near a monitor, monitors
  turned up), Scalpel sees it on the music in under a second, even while you talk, and lowers the voice in that band
  only. On the bench (6 simulated rooms, 18 cases; never tried in a real room): audible feedback 0.05 s median instead
  of 0.45 s, 0.5 s at worst instead of 1.0 s; with the robot voice 0.4 s at worst instead of 2.4 s. No case worse than 1.11.
- **Anti-feedback, your voice and the music are no longer taken for feedback (to be tested)**: 2 false alarms in
  10 minutes instead of 18.
- **Anti-feedback, music removed from the mic, your voice untouched (to be tested)**: 20 dB of monitor music removed
  while you talk, 26 to 31 dB in pauses; your voice changes by 0.4 dB at most.
- **"Measure on the music" (to be tested)**: in "Set up…" (Mac and phone Studio), let a track play for 20 to 30 s:
  Scalpel tells you how far you are from feedback and sets the useful filters, without any howl.
- **Less processor**: mic open with the voice off, cancellation costs 1.3 % instead of 6.6 %; two decks' audio goes from
  14 % to 6-7 % of a core.
- **Scalpel Sound punch** (Medium and Strong): every kick and snare hits harder (+1.7 dB Medium, +3.1 dB Strong), at
  the same perceived loudness.
- **Bouyon beat grids**: when the kick hits at twice the tempo, the grid lands on the snare, like Serato 5 (14 right
  grids out of 16 instead of 7).
- **Search the whole library, like Serato**: ⌘ F searches everywhere, Esc goes back to the crate, "All" button; tracks on
  an unplugged drive are found too.
- **Saved loops, like Serato**: the LOOPS tab shows the track's 8 loops, Serato's included.
- **Melody**: a lengthened note keeps a sharp attack; a note's sliders respond to a click.

</details>

## 1.11 — 9 novembre 2026

- **Mélodie, un éditeur façon Melodyne** (nouvel onglet, à côté d'Intro Lab) : la mélodie, la voix ou la basse d'un son
  devient des notes. Chaque note montre sa courbe de hauteur ; déplace-la, allonge-la, coupe-la, avec l'aimant au temps
  et à la gamme. Réglages de chaque note comme dans Melodyne : justesse, dérive, vibrato, formants, volume, cents.
- **Le son du stem, rejoué note par note** : chaque note est ré-accordée sans changer de timbre et posée à sa place
  (mesuré sur une voix : à 4 cents près, de −12 à +12 demi-tons). Sur une ligne mélodique, une note non touchée garde
  le son d'origine ; quand plusieurs notes sonnent ensemble, déplacer l'une déplace aussi ce qui sonne avec elle.
- **Façon Nora** : des phrases sur l'accord, la mélodie ou la gamme (jusqu'à 4 pistes, 64 pas, 13 préréglages, hasard,
  mutations), jouées avec un synthé ou des chops du stem, puis posées en boucle dans un pad du sampler.
- **Intro Lab complet sur le Mac** : bloc vert de 1 à 16 mesures, voix d'un autre passage, ligne « Tout le son », clic
  droit sur une case (niveau, fondu, filtre), réglages de chaque effet, début de la sortie, plafond du limiteur.
- **Anti-larsen refait (à tester)** : l'annulation du retour apprend pendant la musique, une porte baisse le micro
  quand tu ne parles pas, le larsen est coupé dans sa bande, l'analyseur et « Filtrer » sur le pic (téléphone et Mac).
  Mesuré seulement au banc, jamais dans une vraie salle : +14 dB de marge avant larsen à 10 s et +20 dB à 30 s (1.10 :
  +3 et +10), un larsen qui écrête dans 1 cas sur 18 au lieu de 5, mais le sifflement dure encore 2 s en médiane. Deux
  cas font moins bien que la 1.10 : avec la voix robot, micro tourné vers un retour à 30 cm, 11,7 s au lieu de 8 ; et,
  micro ouvert voix éteinte, le calcul prend ≈ 10 % d'un cœur (1.10 : 1 %).
- **Key lock juste** : changer la tonalité d'une platine la décalait jusqu'à 33 cents ; maintenant 0 à 3,5 cents.
- **Plus de trou après un hot cue en key lock** : le son était coupé 5 à 20 ms à chaque hot cue, cue, roll ou boucle ;
  il est là dès le départ. (Mesuré hors ligne.)
- **Aussi dans cette version (la 1.10 n'est pas sortie seule)** : le **Studio du téléphone** (bouton Studio de la
  télécommande) : bibliothèque et set du soir, Intro Lab, Mélodie, Micro ; et l'**accès de loin** par Tailscale ou un
  tunnel Cloudflare (**à tester**).

<details><summary>In English (November 9, 2026)</summary>

- **Melody, a Melodyne-style editor** (new tab, next to Intro Lab): the melody, vocals or bass of a track become notes.
  Each note shows its pitch curve; move, lengthen or split it, snapped to the beat and the scale. Per-note settings as
  in Melodyne: pitch center, drift, vibrato, formants, volume, cents.
- **The stem's own sound, replayed note by note**: each note is retuned without changing its tone and put in its place
  (measured on a vocal: within 4 cents, from −12 to +12 semitones). On a melodic line, an untouched note keeps the
  original sound; when several notes sound together, moving one also moves what sounds with it.
- **Nora-style**: phrases on the chord, the melody or the scale (up to 4 tracks, 64 steps, 13 presets, random,
  mutations), played with a synth or stem chops, then looped in a sampler pad.
- **Full Intro Lab on the Mac**: green block of 1 to 16 bars, vocals from another passage, « Full track » row,
  right-click a cell (level, fade, filter), settings for each effect, outro start, limiter ceiling.
- **Anti-feedback rebuilt (to be tested)**: the canceller learns during the music, a gate lowers the mic when you don't
  talk, feedback is cut in its own band, the analyzer and « Notch it » on the peak (phone and Mac). Measured only on the
  bench, never in a real room: +14 dB of margin before feedback at 10 s and +20 dB at 30 s (1.10: +3 and +10), clipping
  feedback in 1 case out of 18 instead of 5, but the howl still lasts 2 s in median. Two cases are worse than 1.10: with
  the robot voice, mic facing a monitor at 30 cm, 11.7 s instead of 8; and, mic open with the voice off, it takes about
  10 % of a core (1.10: 1 %).
- **Key lock in tune**: changing a deck's key put it up to 33 cents off; now 0 to 3.5 cents.
- **No more gap after a hot cue with key lock**: the sound was cut 5 to 20 ms on every hot cue, cue, roll or loop; it
  is there from the start. (Measured offline.)
- **Also in this version (1.10 was never released on its own)**: the **phone Studio** (Studio button of the remote):
  library and tonight's set, Intro Lab, Melody, Mic; and **remote access** through Tailscale or a Cloudflare tunnel
  (**to be tested**).

</details>

[Notes et téléchargement de la 1.11](https://github.com/Djlistendat/scalpel-dj/releases/tag/v1.11)

## 1.09 — 9 novembre 2026

- **Son Scalpel, une clarté propre** (Réglages → Sortie audio → Son Scalpel, Moyen ou Fort) : la clarté est refaite.
  Elle ajoute maintenant l'octave exacte de l'aigu de la musique, et rien d'autre : l'ancienne fabriquait aussi des sons
  qui ne sont pas dans la musique (un aigu plus dur, « métallique ») et pouvait monter à plus de trois fois l'aigu
  d'où elle venait. La nouvelle ne le dépasse jamais, même pendant un scratch ou une coupe au crossfader. Même air
  qu'avant, même volume.
- **Le choix Coupé / Moyen / Fort agit dès le clic** : avant, il ne prenait effet qu'au redémarrage de l'app.
- Rappel : 1.08 Intro Lab plus simple, ton agencement gardé, 8 mesures d'office.

<details><summary>In English (November 9, 2026)</summary>

- **Scalpel Sound, clean clarity** (Settings → Audio Output → Scalpel Sound, Medium or Strong): the clarity stage has
  been rebuilt. It now adds the exact octave of the music's treble, and nothing else: the old one also made sounds that
  aren't in the music (a harsher, « metallic » treble) and could reach more than three times the treble it came from.
  The new one never exceeds it, even while scratching or cutting with the crossfader. Same air as before, same volume.
- **The Off / Medium / Strong choice takes effect on the click**: before, it only applied after restarting the app.
- From earlier: 1.08 simpler Intro Lab, your arrangement kept, 8 bars by default.

</details>

[Notes et téléchargement de la 1.09](https://github.com/Djlistendat/scalpel-dj/releases/tag/v1.09)

## 1.08 — 8 novembre 2026

- **Intro Lab, un écran plus simple** : sur la forme d'onde, deux choses à tirer avec leur nom écrit dessus : le bloc
  vert « Beat de l'intro » (la partie du morceau qui sert de beat, calée sur les phrases) et le drapeau rouge « Le
  morceau reprend » (là où la voix arrive). Les reprises proposées sont des boutons nommés ; le réglage fin (premier
  temps de la grille, raccord au temps près) est dans « Avancé ». L'edit dit ce qu'il contient.
- **Intro Lab garde ton agencement** : un nouveau son reprend ton dernier agencement (préréglage, cases, effets,
  longueur), et l'intro fait 8 mesures d'office, comme presque toutes les versions intro des record pools.
- **Pré-écoute de l'edit avec sa forme d'onde.**
- Rappel : 1.07 plus de craquements au scratch avec le Son Scalpel ; plus de mot coupé aux raccords d'Intro Lab.

<details><summary>In English (November 8, 2026)</summary>

- **Intro Lab, a simpler screen**: on the waveform, two things to drag, each with its name on it: the green « Intro
  beat » block (the part of the track used as the beat, snapped to phrases) and the red « Track comes back in » flag
  (where the vocals arrive). Suggested comebacks are named buttons; fine tuning (grid downbeat, join to the beat) is
  under « Advanced ». The edit says what it contains.
- **Intro Lab keeps your arrangement**: a new track takes your last arrangement (preset, cells, effects, length), and
  the intro is 8 bars by default, like almost every record-pool intro version.
- **Edit pre-listen with its waveform.**
- From earlier: 1.07 no more crackles when scratching with Son Scalpel; no more cut-off words at Intro Lab joins.

</details>

[Notes et téléchargement de la 1.08](https://github.com/Djlistendat/scalpel-dj/releases/tag/v1.08)

## 1.07 — 8 novembre 2026

- **Plus de craquements au scratch avec le Son Scalpel** : sur un coup de scratch (un aigu qui arrive après un silence),
  la clarté du Son Scalpel faisait un pic qui craquait. Elle reste maintenant au niveau d'un son tenu.
- **Intro Lab : plus de mot coupé aux raccords** : quand le chanteur attaque juste avant le premier temps, sa phrase est
  gardée en entier (avant le drop, et à chaque tour de la boucle) ; un mot qui passe la fin d'un bloc est fini ; les
  coupes de la voix tombent dans un silence.
- **Intro Lab : la voix d'un autre passage** : clic sur « Voix ▾ » dans l'arrangement, « D'un autre passage » : la voix
  d'autres mesures du morceau posée sur la boucle, comme une a cappella, sur la même grille.

<details><summary>In English (November 8, 2026)</summary>

- **No more crackles when scratching with Son Scalpel**: on a scratch stroke (highs arriving after a silence), Son
  Scalpel's clarity spiked and crackled. It now stays at the level of a held sound.
- **Intro Lab: no more cut-off words at the joins**: when the singer comes in just before beat one, the whole phrase is
  kept (before the drop, and on every pass of the loop); a word running past the end of a block is finished; vocal cuts
  land in a silence.
- **Intro Lab: vocals from another passage**: click « Vocals ▾ » in the arrangement, « From another passage »: the
  vocals of other bars of the track laid over the loop, like an a cappella, on the same grid.

</details>

[Notes et téléchargement de la 1.07](https://github.com/Djlistendat/scalpel-dj/releases/tag/v1.07)

## 1.06 — 6 novembre 2026

- **Les pads de ta table aux couleurs de l'écran** : sur toutes les tables Pioneer à pads (DDJ-REV5, REV7, FLX, SB3,
  SR2, 1000SRT, DJM-S9, S11, S7), chaque pad s'allume de la couleur qu'il a à l'écran : hot cues (couleurs de Serato
  comprises), sampler, boucles, stems, sorties. Avant, la plupart des couleurs étaient fausses (le rouge s'allumait en
  bleu, le cyan en jaune…).
- Rappel : 1.05 scratch de la REV5 au bon déplacement ; 1.04 démarrage figé avec une grosse bibliothèque corrigé.

<details><summary>In English (November 6, 2026)</summary>

- **Your controller's pads in the screen's colors**: on every Pioneer controller with pads (DDJ-REV5, REV7, FLX, SB3, SR2,
  1000SRT, DJM-S9, S11, S7), each pad lights in the color it has on screen: hot cues (Serato colors included), sampler,
  loops, stems, exits. Before, most colors were wrong (red lit up blue, cyan yellow…).
- From earlier: 1.05 REV5 scratch with the right travel; 1.04 startup freeze with a big library fixed.

</details>

[Notes et téléchargement de la 1.06](https://github.com/Djlistendat/scalpel-dj/releases/tag/v1.06)

## 1.05 — 6 novembre 2026

- **Scratch sur la DDJ-REV5 au bon déplacement, comme dans Serato** : le dessus du jog compte toujours ses 13 222 pas
  par tour. Une ancienne mesure faussée pouvait faire avancer le son trop loin à chaque cran (petit geste, grand
  déplacement, son métallique).
- Rappel de la 1.04 : démarrage figé avec une grosse bibliothèque Serato corrigé, et un message clair si le démarrage
  bloque.

<details><summary>In English (November 6, 2026)</summary>

- **Scratch on the DDJ-REV5 with the right travel, like in Serato**: the jog top always counts its 13,222 steps per turn.
  An old mis-measured setting could move the sound too far on each step (small gesture, big travel, metallic sound).
- From 1.04: startup freeze with a big Serato library fixed, and a clear message if startup gets stuck.

</details>

[Notes et téléchargement de la 1.05](https://github.com/Djlistendat/scalpel-dj/releases/tag/v1.05)

## 1.04 — 6 novembre 2026

- **Démarrage figé avec une grosse bibliothèque Serato, corrigé** : avec beaucoup de crates, l'app se figeait à la fin
  de la lecture de la bibliothèque, puis le bouton « Démarrer » ne répondait plus à chaque lancement. Le rapprochement
  des crates avec les sons était refait son par son pour chaque crate : 500 crates sur 60 000 sons prenaient 8 s, à
  chaque passage. Maintenant 0,1 s.
- **Un démarrage bloqué n'est plus muet** : si le bouton « Démarrer » n'est pas prêt au bout de 15 s, l'écran dit
  quelle étape ne répond pas et propose de relancer.

<details><summary>In English (November 6, 2026)</summary>

- **Startup freeze with a big Serato library, fixed**: with many crates, the app froze at the end of reading the
  library, then the « Start » button stopped responding at every launch. Matching crates to tracks was redone track by
  track for every crate: 500 crates over 60,000 tracks took 8 s, every time. Now 0.1 s.
- **A stuck startup is no longer silent**: if the « Start » button is not ready after 15 s, the screen says which step is
  not responding and offers to relaunch.

</details>

[Notes et téléchargement de la 1.04](https://github.com/Djlistendat/scalpel-dj/releases/tag/v1.04)

## 1.03 — 6 novembre 2026

- **Chronos, BPM et pitch** dessinés à partir de caractères préparés une seule fois, au lieu d'être redessinés à chaque
  dixième de seconde.
- **Moins de calques à recomposer** à chaque image : la bibliothèque et les platines ne sont plus recomposées pendant
  que les formes d'onde défilent.
- **Times, BPM and pitch** drawn from characters prepared once, instead of being redrawn every tenth of a second.
- **Fewer layers to recomposite** on every frame: the library and the decks are no longer recomposited while the
  waveforms scroll.

[Notes et téléchargement de la 1.03](https://github.com/Djlistendat/scalpel-dj/releases/tag/v1.03)

## 1.02 — 6 novembre 2026

- **L'écran Mix dessiné par la carte graphique** : les formes d'onde, les vues d'ensemble, les plateaux, les vu-mètres et
  les chronos sont maintenant dessinés ensemble par la carte graphique, en une seule image, comme le fait Serato. Mesuré
  sur un Mac M1, deux platines en lecture, plein écran : processeur 60 % → 53 %, affichage de macOS 32 % → 24 %. Rien ne
  change à l'écran.

<details><summary>In English (November 6, 2026)</summary>

- **The Mix screen drawn by the graphics card**: waveforms, overviews, platters, level meters and times are now drawn
  together by the graphics card, in a single image, the way Serato does it. Measured on an M1 Mac, two decks playing,
  full screen: CPU 60% → 53%, macOS display 32% → 24%. Nothing changes on screen.

</details>

[Notes et téléchargement de la 1.02](https://github.com/Djlistendat/scalpel-dj/releases/tag/v1.02)

## 1.01 — 6 novembre 2026

- **Ranger les sons d'une crate, comme dans Serato** : nouvelle colonne « # » (la place du son dans la crate). Triée par
  « # », glisse un son ou une sélection à l'endroit voulu ; un trait montre où il tombe. Les crates de Serato ne sont pas
  modifiées : l'ordre reste dans Scalpel DJ.
- **Les couleurs de Serato** : chaque son garde la couleur donnée dans Serato, affichée comme dans Serato, lue dans la
  base de Serato 4 à chaque lancement (même une couleur que Serato n'a pas réécrite dans le fichier).
- **Modifier le titre d'un son** : clic droit → « Modifier le titre », pour ajouter une 🔥 à tes bangers (⌃⌘ Espace). Gardé
  dans Scalpel DJ : ni le fichier ni Serato ne changent.
- **L'écran ne s'éteint plus pendant un set** : les gestes sur la table (MIDI) ne comptent pas pour macOS, et l'écran
  pouvait se mettre en veille en plein mix.
- **Moins de processeur** : au repos, sur une nouvelle installation, 50 % → 20 % (les empreintes des versions se calculent
  maintenant doucement en tâche de fond) ; en lecture avec deux platines, 69 % → 64 %.

<details><summary>In English (November 6, 2026)</summary>

- **Reorder a crate's tracks, like in Serato**: new « # » column (the track's place in the crate). Sorted by « # », drag a
  track or a selection where you want it; a line shows where it lands. Serato crates are not modified: the order stays in
  Scalpel DJ.
- **Serato colors**: each track keeps the color you gave it in Serato, shown like in Serato, read from the Serato 4
  database at each launch (even a color Serato did not rewrite into the file).
- **Edit a track's title**: right-click → « Edit title », to add a 🔥 to your bangers (⌃⌘ Space). Kept in Scalpel DJ:
  neither the file nor Serato change.
- **The screen no longer sleeps during a set**: moves on the controller (MIDI) don't count for macOS, and the screen could
  go to sleep mid-mix.
- **Less CPU**: idle on a new install, 50% → 20% (version fingerprints now run gently in the background); playing two
  decks, 69% → 64%.

</details>

[Notes et téléchargement de la 1.01](https://github.com/Djlistendat/scalpel-dj/releases/tag/v1.01)

## 1.00 — 5 novembre 2026

- **Clic droit sur un son, comme dans Serato** : Ajouter à Préparation (⌘ P), Préparer les stems, Analyser, BPM ÷ 2 /
  × 2 (140 → 70 en un clic), BPM d'origine, Montrer dans les crates, Montrer dans le Finder, Retirer de la crate, puis la
  fiche du son. Scalpel ne supprime jamais un fichier.
- **Glissement de tempo fluide** : avec deux sons tout juste chargés, les formes d'onde sautaient pendant le glissement ;
  la liste et les suggestions ne se refont plus à chaque image (images en retard : 14 % → 2 %).

<details><summary>In English (November 5, 2026)</summary>

- **Right-click a track, like in Serato**: Add to Prepare (⌘ P), Prepare stems, Analyze, BPM ÷ 2 / × 2 (140 → 70 in one
  click), original BPM, Show in crates, Show in Finder, Remove from crate, then the track sheet. Scalpel never deletes a
  file.
- **Smooth tempo glide**: with two freshly loaded tracks, the waveforms stuttered during the glide; the list and
  suggestions are no longer redone every frame (late frames: 14% → 2%).

</details>

[Notes et téléchargement de la 1.00](https://github.com/Djlistendat/scalpel-dj/releases/tag/v1.00)

## 0.99 — 5 novembre 2026

- **Ranger les crates à la souris**, comme dans Serato DJ Pro : glisse une crate sur le haut ou le bas d'une autre (avant,
  après) ou au milieu (sous-crate). Les crates de Serato arrivent aussi dans l'ordre de Serato. Serato n'est pas modifié ;
  clic droit sur « Crates Serato » pour revenir à son ordre.
- **Colonnes de la bibliothèque** : tire le bord d'un titre pour la largeur, glisse un titre pour déplacer la colonne.
- **FX1 et FX2 sur la platine de ton choix** (boutons 1 / 2) : le tempo des effets suit cette platine, sans TAP.
- **CDJ en USB** : au branchement, Scalpel demande « sur quelle platine ? » (1 ou 2) ; le choix est gardé.
- **Hot cues tapés vite** : plus de retard. Q (calage) est coupé d'origine, comme dans Serato ; allumé, un hot cue part
  tout de suite en gardant sa place dans le temps, comme sur un CDJ.
- **Boucle auto** : elle part là où tu l'entends, comme dans Serato.
- **Tables DJM-S (S7, S9, S11)** : Scalpel propose d'allumer le DVS pour les vinyles timecode ou Phase (Phase en mode DVS,
  sur les entrées LINE, « Control Tone LINE » dans l'utilitaire de la table) ; si les entrées restent muettes, il dit quoi
  régler.
- Textes anglais corrigés.

<details><summary>In English (November 5, 2026)</summary>

- **Arrange crates with the mouse**, like in Serato DJ Pro: drag a crate onto the top or bottom of another (before, after)
  or onto its middle (subcrate). Serato crates also show up in Serato's order. Serato isn't changed; right-click
  “Serato crates” to go back to its order.
- **Library columns**: drag a header's edge for its width, drag a header to move the column.
- **FX1 and FX2 on the deck you choose** (1 / 2 buttons): the effects' tempo follows that deck, no TAP needed.
- **CDJs over USB**: when one is plugged in, Scalpel asks “which deck?” (1 or 2); the choice is kept.
- **Fast hot cue taps**: no more lag. Q (beat snapping) is off by default, like in Serato; when on, a hot cue starts right
  away keeping its place in the beat, like on a CDJ.
- **Auto loop**: it starts where you hear it, like in Serato.
- **DJM-S mixers (S7, S9, S11)**: Scalpel offers to turn on DVS for timecode vinyl or Phase (Phase in DVS mode, on the LINE
  inputs, “Control Tone LINE” in the mixer utility); if the inputs stay silent, it tells you what to set.
- English text fixed.

</details>

[Notes et téléchargement de la 0.99](https://github.com/Djlistendat/scalpel-dj/releases/tag/v0.99)

## 0.98 — 5 novembre 2026

- **Crates à sous-crates : l'arbre reste en place.** Sur la 0.96, un clic sur une crate qui a des sous-crates faisait
  remonter l'arbre tout en haut : la crate s'ouvrait, mais hors de vue. Maintenant la flèche la déplie (ou la replie) et
  la crate reste sous la souris ; la position de l'arbre est de nouveau gardée d'un lancement à l'autre.
- **Un cadenas sur l'arbre des crates**, à côté de sa loupe : il le fixe à sa taille, l'arbre ne s'agrandit plus au
  survol. Un autre clic le libère.
- **L'arbre des crates s'élargit** : tire la poignée entre l'arbre et la liste des morceaux (double-clic : largeur
  d'origine). La largeur est gardée, cadenas ouvert ou fermé.

<details><summary>In English (November 5, 2026)</summary>

- **Crates with sub-crates: the tree stays put.** In 0.96, clicking a crate that has sub-crates sent the tree back to
  the top: the crate opened, but out of view. Now its arrow opens (or closes) it and the crate stays under the mouse;
  the tree's position is kept between launches again.
- **A lock on the crate tree**, next to its magnifier: it keeps the tree at its size, so it no longer grows on hover.
  Click again to free it.
- **The crate tree widens**: drag the handle between the tree and the track list (double-click: original width). The
  width is kept, with the lock open or closed.

</details>

[Notes et téléchargement de la 0.98](https://github.com/Djlistendat/scalpel-dj/releases/tag/v0.98)

## 0.96 — 5 novembre 2026

- **MoodyScratch 3D**, l'effet des scratcheurs (FX → Échos et réverb ; sur la table : SHIFT + FX pour le choisir, le
  levier pour le faire sonner). Le son tourne autour de toi au tempo (à ½ : gauche sur un temps, droite sur le suivant,
  un peu plus sombre en passant derrière) et ses échos ping-pong répondent du côté opposé, puis s'éloignent. Les échos se
  baissent sous tes coupes et remontent dans les trous et quand tu lâches le disque : rien de baveux, jamais plus fort que
  le son. Pendant que ta main tient le disque, le tour continue au tempo de la musique. BEAT ◀ ▶ règle le temps de l'écho
  et la vitesse du tour (1/8 à 8 temps) ; LEVEL/DEPTH, la largeur, le niveau des échos et leur nombre.
- Textes anglais corrigés : des mots restaient en français ou collés (Bookings, Doublons, égaliseur, « played02:23 »,
  « in 1 beats »).

<details><summary>In English (November 5, 2026)</summary>

- **MoodyScratch 3D**, an effect made for scratch DJs (FX → Echoes and reverb; on the mixer: SHIFT + FX to pick it, the
  lever to make it sound). The sound circles around you in time (at ½: left on one beat, right on the next, a little
  darker as it passes behind) and its ping-pong echoes answer from the opposite side, then fade into the distance. The
  echoes drop under your cuts and come back in the gaps and when you let go of the record: nothing smeared, never louder
  than the sound itself. While your hand holds the record, the turn keeps going in time with the music. BEAT ◀ ▶ sets the
  echo time and the speed of the turn (1/8 to 8 beats); LEVEL/DEPTH sets the width, the echo level and the repeats.
- English text fixed: some words stayed in French or ran together (Bookings, Duplicates, equalizer, “played02:23”,
  “in 1 beats”).

</details>

[Notes et téléchargement de la 0.96](https://github.com/Djlistendat/scalpel-dj/releases/tag/v0.96)

## 0.95 — 5 novembre 2026

- Potard LOW : un clic droit sur le potard LOW de la table choisit ce qu'il coupe en Stems EQ (basse et batterie
  entière, ou basse et kick avec les charleys et percus gardés), sans passer par Réglages.

<details><summary>In English (November 5, 2026)</summary>

Right-clicking the mixer's LOW knob now picks what it cuts in Stems EQ: bass and the whole drums, or bass
and kick (hi-hats and percussion kept), without going to Settings.

</details>

[Notes et téléchargement de la 0.95](https://github.com/Djlistendat/scalpel-dj/releases/tag/v0.95)

## 0.94 — 5 novembre 2026

- Le raccord au temps près : le trait rouge se tire à la souris, collé au temps. Posé sur le premier coup de basse, la
  grille s'y cale, et la zone et le trait restent alignés.
- L'entrée du beat n'est plus proposée une mesure trop tard (une entrée sur la 4e mesure d'un groupe de 4 était poussée
  à la mesure suivante).
- La zone et la reprise avancent d'une mesure (⇧ : 4), la barre d'espace lance et met en pause l'edit, et un nouveau
  son garde la longueur d'intro choisie.
- Réglages → À propos : « Fait par un DJ, pour les DJ », avec un lien pour m'offrir un café.

<details><summary>In English (November 5, 2026)</summary>

Intro Lab's join is now set to the beat: drag the red line onto the first bass hit and the grid locks onto
it, with the zone and line aligned. The beat entry is no longer proposed one bar too late. The zone and resume move one
bar at a time (⇧: 4), the space bar plays and pauses the edit, and a new track keeps the chosen intro length.
Settings → About now says "Made by a DJ, for DJs", with a link to buy me a coffee.

</details>

[Notes et téléchargement de la 0.94](https://github.com/Djlistendat/scalpel-dj/releases/tag/v0.94)

## 0.93 — 5 novembre 2026

- Les effets au choix : un clic sur une mesure de la ligne Effets ouvre ses effets à cocher (écho de la voix ou de la
  mélodie, réverb sur la voix ou la mélodie, roll de batterie, filtre qui monte, silence avant le drop).
- L'écho se règle : retard (1/4, 1/2, 3/4 ou 1 temps), temps repris, durée reprise, répétitions, et stéréo ping-pong
  (chaque répétition passe d'un côté à l'autre). Nouveau préréglage « Montée stéréo ».
- Mes préréglages : garde sous un nom l'agencement que tu as cliqué (cases, effets, longueur, sortie), pose-le sur un son
  ou sur tous les « À faire » (chacun garde sa zone), puis « Tout exporter » les fait en lot dans le même style.
- Pendant l'écoute, une barre avance sur l'arrangement et la mesure jouée s'allume : tu vois où cocher.

<details><summary>In English (November 5, 2026)</summary>

Intro Lab effects are now yours to choose: click a bar in the Effects row to tick its effects (vocal or
melody echo, reverb, drum roll, rising filter, silence before the drop). The echo can be set (delay, beat taken, length,
repeats) and switched to stereo ping-pong, with a new "Stereo build-up" preset. "My presets" saves the arrangement you
clicked and applies it to one track or to all "To do" tracks for a batch export in the same style. While listening, a bar
moves along the arrangement.

</details>

[Notes et téléchargement de la 0.93](https://github.com/Djlistendat/scalpel-dj/releases/tag/v0.93)

## 0.92 — 5 novembre 2026

- Le micro sans table : sans REV5, la liste ENTRÉE du panneau Micro propose les micros du Mac (le micro intégré, un
  micro USB, une carte son, entrée par entrée). D'office, le micro par défaut du Mac ; la REV5 reprend la main dès
  qu'elle est branchée. Le micro s'ouvre à part : la musique ne coupe pas quand on l'allume, ni quand on débranche un
  micro USB. Micro et haut-parleurs du Mac ensemble : Scalpel prévient que ça va siffler.
- SYNC comme dans Serato : SYNC allume les deux platines. Calées au-delà de leur plage (70 sur 80 BPM à ±8 %), les
  curseurs restent où ils sont et la platine affiche REL (ici −12,5 %). Bouger un curseur en SYNC change le tempo des
  deux platines de l'écart, sans jamais pousser l'autre curseur en butée. SYNC coupé ramène la platine à son curseur.
  Au téléphone, le fader de tempo marche aussi en SYNC.
- Curseur de tempo : après un double-clic (retour à 0 %), son bouton revient au milieu.
- « À propos de Scalpel DJ » affiche la bonne version (elle disait 1.0), et la barre du haut dit « Recherche… » pendant
  qu'elle cherche ta table.
- Intro Lab : « Écouter », « Raccord » et « Exporter » marchent tout de suite : ils lancent les stems de la zone s'il le
  faut, puis jouent ou exportent. L'écran affiche l'avancement, ne montre plus l'edit d'avant pendant un nouveau rendu,
  et remettre le premier temps ne refait plus le calcul des stems.
- Le panneau Browse ne recouvre plus la liste des morceaux.
- Les onglets des pads ne sont plus coupés en mode SAMPLER : la banque se lit sur les pads (A1 à A8), et un clic sur
  l'onglet SAMPLER déjà choisi passe à la suivante. Le panneau Sampler nomme les sons comme les pads.

<details><summary>In English (November 5, 2026)</summary>

The mic now works without a controller: the Mic panel's INPUT list offers the Mac's microphones
(built-in, USB mic, sound card, input by input), the Mac's default mic is picked automatically and the REV5 takes over
when plugged in; the mic opens on its own, so the music never cuts when you turn it on or unplug a USB mic, and Scalpel
warns when the Mac's mic and speakers are used together. SYNC works like Serato: both decks light up, synced decks
beyond their range keep their sliders in place and show REL, moving a slider in SYNC shifts both decks by the
difference without pushing the other slider to its end, and SYNC off returns a deck to its slider (the phone's tempo
fader works in SYNC too). A double-click on the tempo slider now centres its knob, "About Scalpel DJ" shows the right
version, and the top bar says "Searching…" while it looks for your controller. Also since 0.90: Intro Lab "Listen",
"Join" and "Export" work right away, the Browse panel no longer covers the track list, and the pad tabs are no longer
cut in SAMPLER mode.

</details>

[Notes et téléchargement de la 0.92](https://github.com/Djlistendat/scalpel-dj/releases/tag/v0.92)

## 0.90 — 4 novembre 2026

- Les cases de l'arrangement marchent : un clic allume ou coupe un élément (batterie, basse, voix…) à cette mesure,
  à l'écran comme dans le son. Dans la 0.89, le clic restait sans effet.
- La zone d'abord, les stems ensuite : ouvrir un son ou déplacer la zone ne lance plus de calcul. Choisis ta zone sur
  la forme d'onde, puis clique « Lancer les stems ». Changer de préréglage, de longueur ou de cases dans la même zone
  ne redemande rien.
- L'edit est toujours rangé à côté du son d'origine : le choix d'un dossier, qui prêtait à confusion, est retiré.
- Le double-clic sur un son marche à tous les coups : sur un son juste ajouté, il ne faisait parfois rien (ni ouverture
  dans Intro Lab, ni chargement sur une platine).

<details><summary>In English (November 4, 2026)</summary>

Intro Lab fixed: the arrangement cells now turn an element on or off (they did nothing in 0.89), the
stems are computed only when you click "Separate stems" after picking your zone, and the edit is always saved next to
the original track. Double-clicking a track that was just added now always opens or loads it.

</details>

[Notes et téléchargement de la 0.90](https://github.com/Djlistendat/scalpel-dj/releases/tag/v0.90)

## 0.89 — 4 novembre 2026

- Scalpel DJ en anglais : Réglages → Affichage → Langue. Toute l'app passe en anglais, la télécommande du téléphone
  aussi. Une nouvelle installation prend la langue du Mac ; une app déjà installée reste en français.
- Sans table branchée, « Écouter » (Intro Lab, bibliothèque) sort sur les haut-parleurs ou le casque du Mac. Avec une
  table, la pré-écoute reste au casque et ne part jamais dans la sono.
- Les formes d'onde d'Intro Lab ont le même rendu que celles de l'écran Mix.
- Le jog d'une platine à l'arrêt fait bouger la tête de lecture, même pendant le calcul des stems.
- Moins d'à-coups après un chargement : l'écran ne se fige plus au départ du calcul des stems, ni pendant le calage
  d'un son sur ses autres versions, et un nouveau son passe avant les stems du son d'avant.
- Réglages → Sortie audio → Carte son propose maintenant toutes les cartes son.
- Les samples enregistrés à 22 kHz gardent tout leur aigu.
- Petites corrections : « Démarrer » répond au premier clic ; « Table » revient au premier clic ; le sampler prévient
  quand son volume est à zéro ; la recherche reste lisible dans une petite fenêtre ; les pads restent alignés quand les
  platines sont repliées.

<details><summary>In English (November 4, 2026)</summary>

Scalpel DJ now speaks English: Settings → Display → Language. A new install follows your Mac's
language. This version also plays "Listen" (preview) on the Mac's own output when no controller is plugged in, keeps
the jog working while stems are computed, and removes the screen freezes right after loading a track.

</details>

[Notes et téléchargement de la 0.89](https://github.com/Djlistendat/scalpel-dj/releases/tag/v0.89)

## 0.87 — 4 novembre 2026

- Les cues, boucles et grilles que Serato a mis dans tes fichiers M4A tombent au même endroit que dans Serato DJ Pro 5.
- La vue Vertical comme celle de Serato : les deux platines en miroir, et un grand disque qui montre le BPM, le pitch
  et les temps.
- La barre du haut est recentrée.
- Un anti-larsen pour le micro : un réglage avant le set, gardé salle par salle, et une protection pendant le set.
  C'est tout nouveau : dis-nous comment il se comporte chez toi.
- Le même son chargé sur les deux platines n'est calculé qu'une fois.

[Notes et téléchargement de la 0.87](https://github.com/Djlistendat/scalpel-dj/releases/tag/v0.87)
