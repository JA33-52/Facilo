# Facilo

https://img.shields.io/badge/@disocrd/discord.gg/5gfpZ2452q

Devis, factures et relances en 2 minutes, pensés pour les micro-entrepreneurs et indépendants français.

Facilo tient dans **un seul fichier HTML**, sans compte, sans serveur et sans installation. Vos données restent sur votre appareil.

<!-- Ajoutez ici une capture d'écran : ![Facilo](docs/capture.png) -->

## Fonctionnalités

- **Devis et factures** avec aperçu en direct pendant la saisie
- **Numérotation automatique** par année (`F2026-001`, `D2026-001`)
- **Mentions légales françaises** : franchise de TVA (art. 293 B du CGI), pénalités de retard, indemnité forfaitaire de recouvrement de 40 €
- **TVA au choix** : non applicable, 20 %, 10 % ou 5,5 %
- **Devis → facture** en un clic
- **Suivi des paiements** : brouillon, envoyée, payée, avec les montants à encaisser, en retard et encaissés ce mois-ci
- **Messages de relance** générés automatiquement, courtois puis plus fermes selon le retard
- **Export PDF** via l'impression du navigateur
- **Thème clair et sombre** selon les réglages de l'appareil

## Utilisation

1. Ouvrez `index.html` dans votre navigateur (double-clic, aucun serveur nécessaire).
2. Renseignez vos informations dans « Mes informations » : elles sont mémorisées.
3. Créez un document, cliquez sur **Enregistrer**, puis sur **Enregistrer et imprimer / PDF** pour obtenir le PDF.
4. Retrouvez vos documents et leurs statuts dans l'onglet « Mes documents ».

## Données et confidentialité

Toutes les données (vos informations, vos clients, vos documents) sont enregistrées dans le `localStorage` de votre navigateur. Rien n'est envoyé sur un serveur.

Conséquences à connaître :

- vider les données du navigateur efface vos documents ;
- les données ne sont pas synchronisées entre vos appareils ;
- pensez à exporter vos factures en PDF pour les conserver (obligation de conservation de 10 ans).

## Publier sur GitHub Pages

1. Renommez `facilo.html` en `index.html` à la racine du dépôt.
2. Dans **Settings → Pages**, choisissez la branche `main` et le dossier `/ (root)`.
3. Votre application est en ligne à l'adresse `https://<votre-pseudo>.github.io/<nom-du-depot>/`.

## Avertissement

Facilo est fourni tel quel, sans garantie. Les mentions légales intégrées sont des modèles courants : **vérifiez-les selon votre situation** (régime de TVA, statut, activité réglementée) auprès de votre expert-comptable ou de votre CFE avant tout usage professionnel. Ce projet ne constitue pas un conseil juridique ou fiscal.

## Pistes d'évolution

- [ ] Export et import des données (sauvegarde JSON)
- [ ] Carnet de clients réutilisables
- [ ] Logo et couleurs personnalisables
- [ ] Envoi des documents par e-mail
- [ ] Synchronisation entre appareils
- [ ] Facturation électronique (Factur-X)

## Contribuer

Les suggestions et corrections sont les bienvenues : ouvrez une *issue* pour proposer une idée ou signaler un problème, ou une *pull request* pour une modification. Le code est volontairement simple (HTML, CSS et JavaScript sans dépendance) pour rester facile à relire.

## Licence

Distribué sous licence MIT. Voir le fichier [`LICENSE`](LICENSE).
