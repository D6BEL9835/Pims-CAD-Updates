# Pim's-CAD BETA1.3.2

BETA1.3.2 reprend l'intégralité de la BETA1.3.1 et ajoute un patch ciblé sur la fiabilité des accrochages objet dans les commandes de placement.

## Patch BETA1.3.2

- conservation des accrochages objet 2D et 3D de l'utilisateur dans CoteAlt-Y, CoteAlt-Z, NUMBULLE et le carroyage ;
- conservation des repères visuels d'accrochage pendant la prise de points ;
- neutralisation temporaire limitée à la grille, à l'ortho, au suivi polaire et au SCU dynamique afin d'éviter les décalages de placement ;
- restauration automatique des réglages de saisie de l'utilisateur à la fin de chaque prise.

## Nouveautés

- ajout de la commande `PMSHAIE` dans le menu Habillage ;
- ajout de l'onglet Add-On dans le menu Application pour regrouper les extensions complémentaires validées ;
- ajout du journal interne « M.A.J. log » dans les préférences.

## Annotations et systèmes de coordonnées

- placement fidèle au clic en SCG, SCU Vue, tourné, déplacé ou incliné ;
- orientation à l'écran préservée pour CoteAlt-Y, CoteAlt-Z et NUMBULLE ;
- placement exact des points, bulles, textes et flèches ;
- annulation `Ctrl+Z` cote par cote sans quitter CoteAlt-Y ou CoteAlt-Z ;
- fond EtiquAlt-Y blanc RVB `255, 255, 255` par défaut et personnalisable.

## Carroyage

- orientation corrigée dans tous les systèmes de coordonnées ;
- conservation des accrochages aux objets pendant la sélection ;
- ordre de grandeur, nombre et taille des décimales configurables ;
- suppression automatique des croix qui recouvrent un texte.

## Interface et installation

- fenêtres de commande non bloquantes et réutilisées pour réduire leur temps d'ouverture ;
- retour automatique sur la dernière commande utilisée ;
- boutons de placement désactivés visuellement pendant une commande DWG ;
- nouvel installeur harmonisé avec la direction artistique Pim's-CAD.

## Installation

1. Enregistrez vos dessins et fermez complètement ZWCAD.
2. Lancez `Pims-CAD-BETA1.3.2-Setup.exe`.
3. Cliquez sur **Installer**, puis relancez ZWCAD 2026.

Compatible avec **Windows 11 64 bits** et **ZWCAD 2026 64 bits**.

> L'installateur n'est pas encore signé numériquement. Windows SmartScreen peut demander une confirmation lors du premier lancement.

## Contrôle de l'installateur

- taille : `12 981 760` octets ;
- SHA-256 : `48C1A84B8D614A6ECE74F4B740F5FFFFB0A7ABEA219E3AAAEA0E076EB42336FB`.
