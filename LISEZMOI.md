# Classement Weekly Shorts : versions Android et iOS

## Android (APK)
Workflow **Build APK** : se lance à chaque envoi sur GitHub. Télécharger l'artefact `classement-weekly-shorts-apk`.

## iOS, option 1 (recommandée) : installer comme appli via Safari
1. Dépôt GitHub > Settings > Pages > Source : **GitHub Actions**.
2. Envoyer le projet sur la branche `main` (ou lancer à la main le workflow « Publier la version web »).
3. Ouvrir l'adresse `https://<ton-pseudo>.github.io/<nom-du-depot>/` dans **Safari** sur l'iPhone.
4. Bouton Partager > **Sur l'écran d'accueil**.
L'appli s'ouvre alors en plein écran, avec son icône, et fonctionne hors connexion après la première ouverture.
Remarque : les données (localStorage) restent propres à cette appli installée.

## iOS, option 2 : fichier IPA
Workflow **Build iOS (IPA non signé)** (à lancer à la main via « Run workflow »).
L'IPA obtenu n'est PAS signé : il ne s'installe pas tel quel. Il faut le signer avec un identifiant Apple :
- gratuit : AltStore ou Sideloadly (l'appli expire au bout de 7 jours, à renouveler) ;
- 99 €/an : compte Apple Developer, pour TestFlight / App Store (nécessite de configurer la signature).
