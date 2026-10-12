# GlassGaze support

English first, français plus bas.

GlassGaze is a Fabric mod for Minecraft servers. Mobs see players through glass, panes, bars, ice, leaves, slime and honey, walk up to the pane and follow along it. By default they cannot hit through it, and one setting lets them if you want a harsher server. The rule runs on the server alone, so players install nothing to join.

This repository holds no code. It is the place to report a problem or ask a question about the mod, and nothing else.

## Reporting a bug

Open an issue and pick the bug form. It asks for the game and loader versions, the mod version, what you expected, what happened, the steps to reproduce it and the lines of `latest.log` around it. A report with those lines gets answered much faster than one without them.

Before you write, check that the mob is not excluded: the `excludedMobs` setting and the tag `glassgaze:blind_to_glass` make a mob keep the base game sight on purpose. Settings live in OasCore, under the Sight category, and in `config/oas/glassgaze/glassgaze.json`.

## What is not a bug

A mob that stands at the pane and does not hurt you is the default behaviour. A mob that sees nothing through a door, a trapdoor, packed ice or blue ice is also expected, these stay opaque. An enderman and a creaking keep the base game rules for the player who looks at them.

## Français

GlassGaze est un mod Fabric pour serveurs Minecraft. Les monstres voient les joueurs à travers le verre, les vitres, les barreaux, la glace, les feuilles, le slime et le miel, viennent jusqu'à la vitre et la longent en les suivant. Par défaut ils ne peuvent pas frapper à travers, et un réglage le permet pour un serveur plus dur. La règle tourne côté serveur seulement, donc les joueurs n'installent rien pour se connecter.

Ce dépôt ne contient aucun code. On y signale un problème ou on y pose une question sur le mod, rien d'autre.

### Signaler un bug

Ouvrez un ticket et choisissez le formulaire de bug. Il demande les versions du jeu et du chargeur, la version du mod, ce que vous attendiez, ce qui s'est passé, les étapes pour le reproduire et les lignes de `latest.log` autour du problème. Un signalement avec ces lignes reçoit une réponse bien plus vite.

Avant d'écrire, vérifiez que le monstre n'est pas exclu : le réglage `excludedMobs` et l'étiquette `glassgaze:blind_to_glass` lui laissent exprès la vue du jeu de base. Les réglages sont dans OasCore, catégorie Sight, et dans `config/oas/glassgaze/glassgaze.json`.

### Ce qui n'est pas un bug

Un monstre qui reste contre la vitre sans vous blesser, c'est le comportement par défaut. Un monstre qui ne voit rien à travers une porte, une trappe, la glace compacte ou la glace bleue est aussi normal, ces blocs restent opaques. L'enderman et le creaking gardent les règles du jeu de base pour le joueur qui les regarde.
