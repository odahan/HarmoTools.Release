# HarmoTools

**L'harmonie pratique pour les musiciens** — un espace de travail pour les gammes, les accords, les relations tonales et l'exploration assistée par MIDI.

> 🇬🇧 English speakers: read the [English version](README.md).

HarmoTools est une application de bureau destinée aux musiciens, compositeurs, arrangeurs et enseignants qui ont besoin d'outils pratiques pour travailler l'harmonie musicale.

Le projet vise à offrir une interface claire pour explorer, comprendre et utiliser les concepts courants de la théorie musicale :

- accords et extensions ;
- gammes et modes ;
- relations entre notes, degrés et tonalités ;
- le cycle des quintes ;
- la visualisation du clavier ;
- l'exploration assistée par MIDI ;
- des outils d'aide à l'analyse et à la composition harmoniques.

## Fonctionnalités

- **Accueil** — gammes favorites, mémorisations d'accords et lecteur de séquences d'accords.
- **Gammes & Accords** — construire une gamme à partir d'une note de départ et d'une définition ; en examiner les notes et les accords (triades ou accords de septième).
- **Recherche de gamme** — identifier les gammes candidates à partir d'un ensemble de notes, avec un catalogue de reconnaissance de 48 définitions.
- **Catalogue de gammes** — 52 définitions distinctes : modes majeurs, modes des mineurs harmonique et mélodique, pentatoniques et collections exotiques (ton entier, octatonique, blues, bebop, napolitain, japonaises…).
- **Séquenceur aléatoire** — générer, éditer, jouer, mémoriser et exporter en MIDI des mélodies monophoniques.
- **Accords** — reconnaître les accords candidats à partir des notes du clavier ou du MIDI ; **Nom d'accord** analyse les symboles d'accords dans l'autre sens.
- **Cycle des quintes** — armures, tonalités relatives, fenêtre de degrés déplaçable et mémorisations d'accords par tonalité.
- **Fréquences** — fréquences exactes des notes et comparaison des registres d'instruments.
- **Prévisualisation audio** — lecture des notes et accords via les SoundFonts intégrées, ou votre propre fichier `.sf2`.
- **Entrée MIDI** — jouer des accords en direct depuis un clavier MIDI.
- **Export MIDI** — progressions et séquences en fichiers MIDI standard (type 0), directement exploitables dans votre DAW.

## Téléchargement

Récupérez le dernier binaire sur la page **[Releases](https://github.com/odahan/HarmoTools.Release/releases)**.

- Téléchargez `HarmoTools-<version>-win-x64.zip`
- Extrayez l'archive où vous voulez
- Lancez `HarmoTools.exe`

Aucune installation nécessaire — l'application est portable.

## Configuration requise

- Windows 10 version 2004 (build 19041) ou ultérieur, 64 bits
- Aucun droit administrateur requis

## Pour commencer

- **Prévisualisation audio** : HarmoTools joue les aperçus internes via une SoundFont (`.sf2`). Ouvrez `Paramètres`, choisissez un préréglage intégré (par exemple *Preview Piano*, ou l'ensemble complet *GeneralUser GS*) ou sélectionnez votre propre SoundFont, choisissez un périphérique de sortie et testez.
- **Entrée MIDI** : dans `Paramètres`, sélectionnez votre périphérique d'entrée MIDI et le canal d'écoute. Si votre DAW utilise le même clavier, laissez-le non sélectionné dans HarmoTools pour que les deux applications puissent fonctionner ensemble.
- **Raccourcis de démarrage** :
  - maintenez `Shift` au lancement pour centrer la fenêtre principale à l'écran ;
  - maintenez `Alt+Shift` pour réinitialiser tous les paramètres après confirmation, y compris la position enregistrée de la fenêtre.

Le manuel d'utilisation complet est intégré à l'application (`Aide > Manuel d'utilisation`, disponible en anglais et en français).

## Licence

HarmoTools est un **Donationware** propriétaire. Il est distribué gratuitement pour un usage personnel non commercial ; la redistribution et l'usage commercial requièrent l'autorisation écrite préalable d'Olivier Dahan. Les licences complètes sont disponibles en anglais et en français dans l'application.

Les dons, d'un montant libre, sont facultatifs et peuvent être faits sur [buymeacoffee.com/knhsynths](https://buymeacoffee.com/knhsynths). Aucun compte ni adresse e-mail n'est requis. Seuls les donateurs sont éligibles au support et aux notifications de mise à jour.

La bibliothèque sous-jacente [Enaxos.MusicHarmony](https://github.com/odahan/MusicHarmony) est open source sous sa propre licence. HarmoTools, lui, n'est pas open source.
