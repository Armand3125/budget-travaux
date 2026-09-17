# Budget travaux

Application statique de suivi du budget de rénovation, prévue pour GitHub Pages.

## Fichiers

- `index.html` : application complète, sans dépendance externe.
- `budget-travaux.json` : données initiales et données synchronisées.

## Sauvegarde GitHub depuis l’application

1. Créer un jeton GitHub finement ciblé sur ce dépôt.
2. Lui attribuer uniquement la permission **Contents: Read and write**.
3. Dans l’application, cliquer sur **GitHub**, renseigner le compte, le dépôt et le jeton, puis cliquer sur **Connecter et charger**.

Le jeton reste dans le stockage du navigateur choisi et n’est jamais écrit dans le dépôt. Chaque modification met à jour la copie locale immédiatement, puis `budget-travaux.json` sur GitHub après un court délai.

## Confidentialité

Un site GitHub Pages classique est public. Ne pas placer de données confidentielles dans `budget-travaux.json` si le dépôt ou le site est public.
