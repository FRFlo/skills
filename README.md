# Skills

Collection de skills réutilisables pour les agents de développement. Chaque skill contient un fichier `SKILL.md` qui précise quand l'utiliser et les instructions à suivre ; certains comprennent aussi des références, recettes ou scripts.

## Index

### Animation et interactions

| Skill | Utilisation |
| --- | --- |
| [animate](skills/animate/SKILL.md) | Concevoir et implémenter une animation web ou une transition. |
| [animate-expo](skills/animate-expo/SKILL.md) | Créer des animations et interactions pour React Native et Expo. |
| [animation-performance](skills/animation-performance/SKILL.md) | Diagnostiquer et améliorer les performances des animations web. |
| [animation-vocabulary](skills/animation-vocabulary/SKILL.md) | Trouver le terme précis correspondant à un effet de mouvement. |
| [choreograph](skills/choreograph/SKILL.md) | Coordonner les animations de plusieurs éléments. |
| [find-animation-opportunities](skills/find-animation-opportunities/SKILL.md) | Repérer les endroits où une animation serait utile, sans modifier le code. |
| [gestures](skills/gestures/SKILL.md) | Construire des interactions tactiles : glisser, balayer, tiroirs et panneaux. |
| [improve-animations](skills/improve-animations/SKILL.md) | Auditer les animations d'un projet et préparer un plan d'amélioration. |
| [remove-animations](skills/remove-animations/SKILL.md) | Repérer et retirer les animations superflues. |
| [review-animations](skills/review-animations/SKILL.md) | Examiner la qualité d'une animation existante ; invocation explicite. |

### Interfaces et design

| Skill | Utilisation |
| --- | --- |
| [apple-design](skills/apple-design/SKILL.md) | Appliquer au web les principes d'interface et de mouvement inspirés d'Apple. |
| [ask-sonner](skills/ask-sonner/SKILL.md) | Installer, utiliser et dépanner les notifications Sonner pour React. |
| [break-ui](skills/break-ui/SKILL.md) | Tester une interface avec des données extrêmes et relever les problèmes. |
| [designing-data-visualizations](skills/designing-data-visualizations/SKILL.md) | Choisir, concevoir et améliorer des graphiques et visualisations de données. |
| [emil-design-eng](skills/emil-design-eng/SKILL.md) | Soigner les composants, animations et détails d'interface selon les principes d'Emil Kowalski. |
| [mobile-native](skills/mobile-native/SKILL.md) | Adapter une application web aux usages et aux interactions mobiles. |
| [pick-ui-library](skills/pick-ui-library/SKILL.md) | Choisir une bibliothèque frontend adaptée à un besoin ; invocation explicite. |
| [prototype](skills/prototype/SKILL.md) | Créer et comparer plusieurs variantes d'une interface ; invocation explicite. |
| [shadcn-svelte](skills/shadcn-svelte/SKILL.md) | Gérer les composants et projets shadcn-svelte. |
| [tailwind-4-docs](skills/tailwind-4-docs/SKILL.md) | Consulter la documentation et les usages de Tailwind CSS v4. |
| [unslop](skills/unslop/SKILL.md) | Revoir et améliorer une interface pour lui donner une identité visuelle propre. |

| [vocabulary](skills/vocabulary/SKILL.md) | Trouver le vocabulaire précis du design et des interfaces. |

### Développement et méthodes

| Skill | Utilisation |
| --- | --- |
| [babysit-pr](skills/babysit-pr/SKILL.md) | Suivre une pull request, ses vérifications et ses revues. |
| [karpathy-guidelines](skills/karpathy-guidelines/SKILL.md) | Guider l'écriture, la revue et la refactorisation de code avec des changements ciblés et vérifiables. |
| [leaving-pr-comments](skills/leaving-pr-comments/SKILL.md) | Rédiger des commentaires sur GitHub au nom de l’agent. |
| [modernize](skills/modernize/SKILL.md) | Mettre à jour une pull request ancienne, notamment par rebase. |
| [ponytail](skills/ponytail/SKILL.md) | Favoriser des solutions de code simples et ciblées. |
| [ponytail-audit](skills/ponytail-audit/SKILL.md) | Auditer la qualité et les risques d’un dépôt. |
| [ponytail-debt](skills/ponytail-debt/SKILL.md) | Recenser les raccourcis et la dette technique signalés. |
| [ponytail-gain](skills/ponytail-gain/SKILL.md) | Présenter les gains mesurés par Ponytail. |
| [ponytail-help](skills/ponytail-help/SKILL.md) | Consulter les commandes et niveaux de Ponytail. |
| [ponytail-review](skills/ponytail-review/SKILL.md) | Examiner la qualité et les risques d’un changement. |
| [security-audit](skills/security-audit/SKILL.md) | Auditer la sécurité du code et analyser les vulnérabilités. |
| [self-learning](skills/self-learning/SKILL.md) | Transformer une méthode ou une découverte issue d'une session en skill réutilisable. |
| [takeover](skills/takeover/SKILL.md) | Reprendre et mener à terme une pull request, une branche ou le travail d’un agent. |
| [write-swift](skills/write-swift/SKILL.md) | Écrire, relire ou moderniser du Swift, notamment sa concurrence. |

## Installation avec Skills CLI

Depuis un projet, listez les skills disponibles puis choisissez ceux à installer :

```bash
npx skills add FRFlo/skills --list
npx skills add FRFlo/skills --skill animate
```

Pour choisir parmi tous les skills, lancez `npx skills add FRFlo/skills`. Ajoutez `-g` pour une installation globale. Le CLI installe les copies présentes dans ce dépôt. Pour actualiser une installation existante, relancez la commande d’installation.

## Sources

- [emilkowalski/skills](https://github.com/emilkowalski/skills) : animate, animate-expo, animation-performance, animation-vocabulary, apple-design, ask-sonner, break-ui, choreograph, emil-design-eng, find-animation-opportunities, gestures, improve-animations, mobile-native, pick-ui-library, prototype, remove-animations, review-animations et write-swift.
- [multica-ai/andrej-karpathy-skills](https://github.com/multica-ai/andrej-karpathy-skills) : karpathy-guidelines.
- [kulaxyz/self-learning-skills](https://github.com/kulaxyz/self-learning-skills) : self-learning.
- [ali-kassir-phd/designing-data-visualizations](https://github.com/ali-kassir-phd/designing-data-visualizations) : designing-data-visualizations.
- [index-how/vocabulary](https://github.com/index-how/vocabulary) : vocabulary.
- [cloudflare/security-audit-skill](https://github.com/cloudflare/security-audit-skill) : security-audit.
- [DietrichGebert/ponytail](https://github.com/DietrichGebert/ponytail) : les six skills Ponytail, sans doublons OpenClaw.
- [Tsuzat/Edra](https://github.com/Tsuzat/Edra/tree/next/.agents/skills) : shadcn-svelte et tailwind-4-docs, branche `next`.
- [t3dotgg/tstack](https://github.com/t3dotgg/tstack) : babysit-pr, leaving-pr-comments, modernize et takeover.
- [heydamir/unslop](https://github.com/heydamir/unslop) : unslop, créé par [Damir Sokolovsky](https://github.com/heydamir), sous licence [CC BY 4.0](skills/unslop/LICENSE).

Les révisions importées sont consignées dans [skills-sources.lock.json](skills-sources.lock.json). Le workflow [Actualiser les skills](.github/workflows/update-skills.yml) vérifie les sources chaque lundi à 6 h UTC et ouvre ou actualise une pull request si nécessaire. Il peut aussi être lancé manuellement depuis GitHub Actions. L’ouverture de pull requests par GitHub Actions doit être autorisée dans les paramètres du dépôt. Les chemins des skills et les licences à copier sont définis dans ce fichier JSON.

La synchronisation remplace entièrement les dossiers des skills suivis par leur contenu amont ; les modifications locales dans ces dossiers doivent donc être proposées aux dépôts d'origine.

## Utilisation

Consultez le `SKILL.md` du skill adapté à votre tâche et ses éventuels fichiers complémentaires. Selon l'agent utilisé, vous pouvez aussi invoquer un skill disponible par son nom, par exemple `$animate`. Les skills marqués « invocation explicite » doivent être demandés directement.

Cette collection exclut les skills métier ainsi que les skills intégrés à Codex/OpenAI (`openai-docs`, `skill-creator` et `skill-installer`). Les conditions de licence propres à chaque skill restent applicables ; voir notamment les licences de [designing-data-visualizations](skills/designing-data-visualizations/README.md).

