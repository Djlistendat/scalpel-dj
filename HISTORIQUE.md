# Scalpel DJ — historique des versions

Toutes les versions publiées, la plus récente en haut. Le projet a commencé le 18 octobre 2026 avec la 0.1 ; il est sur
GitHub depuis le 4 novembre (0.87). Aujourd'hui : **23 versions publiées** en 7 jours, plus de 80 versions de
travail avant. Les versions qui manquent (0.88, 0.91, 0.97, 1.10) ne sont jamais sorties seules : leurs nouveautés sont
dans la version suivante.

**English:** every release, newest first; the English notes are under « In English ».

[⬇ Télécharger la dernière version](https://github.com/Djlistendat/scalpel-dj/releases/latest/download/Scalpel-DJ-Mac.zip)

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
