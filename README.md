# Skills

Copie des skills d'Emil Kowalski pour le design d'interface et l'animation, prêts à l'emploi dans Claude Code.

- Source : https://github.com/emilkowalski/skills (commit `64eb3de`)
- Licence : MIT, © 2026 Emil Kowalski (voir `LICENSE`)

## Contenu

Ce dépôt est un plugin Claude Code (`emil-skills`) et sa marketplace (`msdg-skills`). Les 20 skills sont dans `skills/`.

| Skill | Rôle |
|---|---|
| `emil-design-eng` | Skill principal : animation et conseils de design |
| `animate` | Créer une animation (courbe, durée, propriétés) |
| `animate-expo` | Animations React Native / Expo |
| `choreograph` | Coordonner plusieurs éléments animés |
| `gestures` | Glisser, swipe, panneaux |
| `animation-performance` | Corriger les animations qui saccadent |
| `animation-vocabulary` | Le bon vocabulaire pour décrire une animation |
| `review-animations` | Revue stricte des animations |
| `improve-animations` | Audit complet + plans de correction |
| `find-animation-opportunities` | Où une animation apporterait quelque chose |
| `remove-animations` | Retirer les animations inutiles |
| `break-ui` | Tester l'interface avec des données extrêmes |
| `apple-design` | Principes d'interface d'Apple pour le web |
| `mobile-native` | Ressenti natif d'une web app sur mobile |
| `prototype` | Plusieurs variantes d'un élément avec sélecteur |
| `pick-ui-library` | Choisir une bibliothèque UI fiable |
| `write-swift` | Écrire du Swift |
| `learn-taste` | Transformer vos corrections en règles dans `DESIGN.md` |
| `ask-emil` | Orienter vers le bon skill |
| `ask-sonner` | Guide de la bibliothèque Sonner |

## Utiliser ces skills dans un projet

Ajoutez ceci au fichier `.claude/settings.json` du projet (cloud, ordinateur et application) :

```json
{
  "extraKnownMarketplaces": {
    "msdg-skills": {
      "source": { "source": "github", "repo": "msoareschristeyns-hue/skills" }
    }
  },
  "enabledPlugins": {
    "emil-skills@msdg-skills": true
  }
}
```

Ou installez-le une fois pour toutes sur votre ordinateur :

```
/plugin install emil-skills --marketplace msoareschristeyns-hue/skills
```

## Mettre à jour depuis le dépôt d'Emil

Recopiez le dossier `skills/` de https://github.com/emilkowalski/skills, puis augmentez `version` dans `.claude-plugin/plugin.json`.
