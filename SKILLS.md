# NAPO GROUP — Skill d'interface et d'animation

## Skill de référence d'Emil Kowalski

- Page officielle : https://emilkowal.ski/skill
- Dépôt officiel : https://github.com/emilkowalski/skills
- Commande officielle d'installation dans un environnement compatible :

```bash
npx skills@latest add emilkowalski/skills
```

Déposer ce fichier dans GitHub documente les consignes, mais ne lance pas la commande et n'installe pas automatiquement le skill dans un agent de développement.

## Objectif pour NAPO GROUP

Créer des interfaces professionnelles, rapides, accessibles et soignées, en préservant l'identité rouge et blanche de NAPO GROUP. Les animations doivent aider les utilisateurs à comprendre les actions, pas les distraire.

## Règles de conception

1. **Comprendre avant d'animer.** Définir ce qui change, pourquoi le mouvement est utile et comment il peut être interrompu.
2. **Rester sobre.** Utiliser des transitions courtes et cohérentes pour les menus, boutons, panneaux et notifications. Éviter les mouvements décoratifs répétitifs.
3. **Choisir une courbe adaptée.** Les éléments qui apparaissent ralentissent en arrivant; les éléments qui disparaissent peuvent accélérer en sortant. Éviter une même courbe mécanique pour tous les mouvements.
4. **Préserver les performances.** Préférer `transform` et `opacity`; éviter les animations fréquentes qui provoquent des recalculs de mise en page.
5. **Penser mobile d'abord.** Les boutons doivent être faciles à toucher. Aucun élément essentiel ne doit dépendre du survol (`hover`).
6. **Respecter l'accessibilité.** Prendre en charge `prefers-reduced-motion`, conserver un focus clavier visible et ne jamais communiquer une information uniquement par le mouvement ou la couleur.
7. **Respecter la marque.** Garder la palette rouge/blanche NAPO GROUP, un contraste lisible, une typographie claire et des ombres/bordures discrètes.
8. **Éviter les dépendances inutiles.** Examiner les fichiers et bibliothèques existants avant d'ajouter une bibliothèque d'animation ou de composants.
9. **Protéger les fonctions existantes.** Préserver les chemins de fichiers et tester les liens, boutons et formulaires après chaque modification.
10. **Ne jamais bloquer l'utilisateur.** Une animation ne doit pas retarder une action importante ou empêcher la navigation.

## Procédure obligatoire pour l'agent

Avant de modifier l'interface :
- examiner la structure et les fichiers existants;
- identifier les problèmes visuels réels;
- prioriser les améliorations selon leur impact pour l'utilisateur.

Après modification :
- vérifier l'affichage sur mobile et ordinateur;
- vérifier le clavier, le focus et la réduction des animations;
- vérifier que les contenus et commandes restent visibles;
- indiquer les fichiers modifiés et les tests réellement effectués;
- signaler honnêtement tout test impossible à exécuter.

## Prompt prêt à l'emploi

> Pour le projet NAPO GROUP, utilise le skill `emil-design-eng` d'Emil Kowalski s'il est installé. Examine d'abord l'interface existante, puis améliore avec retenue les animations, transitions et détails d'interaction. Conserve l'identité rouge et blanche, privilégie l'expérience mobile, respecte `prefers-reduced-motion`, évite les dépendances inutiles et teste les fonctions existantes. Ne prétends pas que le skill est installé si tu ne peux pas le vérifier.
