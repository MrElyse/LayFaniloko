# 'Lay faniloko

> « 'Lay faniloko ho an'ny tongotro ny teninao, sady fanazavana ho amin'ny lalako. » — Salamo 119:105

Application Android pour l'église **Fiangonan'i Jesosy Mamonjy** : la Baiboly, le Fihirana et
l'enseignement, dans un seul téléphone. Gratuite, sans publicité, et sans internet pour lire.

## Télécharger

**→ [Page de téléchargement](https://mrelyse.github.io/LayFaniloko/)**

Ou directement le fichier : [dernière version](https://github.com/MrElyse/LayFaniloko/releases/latest/download/LayFaniloko.apk).

Ouvrez le fichier descendu, acceptez l'installation depuis cette source — c'est normal pour une
application qui ne vient pas encore du Play Store — et c'est tout. La Bible et les cantiques sont
déjà dedans.

## Ce qu'elle contient

- **La Baiboly en quatre versions**, avec la comparaison de deux versions côte à côte
- **Recherche** rapide par référence, et par les mots dont on se souvient quand la référence échappe
- **Fihirana** Jesosy Mamonjy, FFPM, Tononkira, Noely 2024 · 2025 · 2026
- **Vos mp3 sur les cantiques** : l'application range et renomme le fichier elle-même, l'enregistrement se lance avec les paroles
- **Pour les musiciens** : grille d'accords, transposition, métronome, accompagnement au piano
- **Partage entre téléphones** : passer ses enregistrements par wifi, sans internet, d'un téléphone
  à l'autre
- **Suivi de lecture** : versets enregistrés, notes, plan de lecture, série de jours
- **Assistance par IA**, facultative, avec sa propre clé

## Ce dépôt

Il ne contient pas le code de l'application, seulement ce qui doit être public :

| Fichier | À quoi il sert |
| --- | --- |
| `index.html` | la page de téléchargement, publiée par GitHub Pages |
| `confidentialite.html` | la politique de confidentialité |
| `conditions.html` | les conditions d'utilisation |
| `version.json` | ce que l'application lit pour savoir qu'une version plus récente existe |

## Publier une nouvelle version

L'application regarde `version.json` une fois par demi-journée, seulement si le téléphone est déjà
en ligne, et affiche une ligne discrète quand le `code` publié dépasse celui de la version
installée. C'est le **`code`** qui décide, jamais le nom.

1. augmenter `versionCode` et `versionName` dans l'application, puis construire l'APK signé ;
2. créer la *release* ici et y joindre l'APK ;
3. mettre `version.json` à jour :

```json
{
  "code": 2,
  "nom": "1.1",
  "notes": "Ce qui a changé, en une phrase.",
  "lien": "https://github.com/MrElyse/LayFaniloko/releases/latest"
}
```

Les téléphones s'en aperçoivent dans les douze heures.

## Vie privée

L'application **ne collecte rien** : pas de compte, pas de serveur, pas de mesure d'audience, pas de
publicité. Tout reste sur le téléphone. Voir la
[politique de confidentialité](https://mrelyse.github.io/LayFaniloko/confidentialite.html).

## Les textes et les chants

Les textes bibliques, les recueils de cantiques et les enseignements appartiennent à ceux qui les
ont écrits, traduits ou publiés. Ils sont réunis ici pour l'usage personnel et pour le culte, sans
but lucratif. Ayant droit d'un contenu présent dans l'application et vous ne souhaitez pas l'y voir
figurer ? Écrivez-nous : il sera retiré de la mise à jour suivante.

## Signaler un problème

Dites ce que vous faisiez au moment du souci : [yasharelyse@gmail.com](mailto:yasharelyse@gmail.com)
ou une [issue](https://github.com/MrElyse/LayFaniloko/issues).
