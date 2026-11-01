---
title: Politique de confidentialité de Quit Vaping
lang: fr
---

# Politique de confidentialité de Vape Tracker: Quit Vaping

*Ceci est une traduction. En cas de divergence avec la [version anglaise](../privacy), la version anglaise prévaut.*

Date d’entrée en vigueur : 2026-10-31

Cette politique explique comment Vape Tracker: Quit Vaping (affichée « Arrêt Tabac » sur votre écran d’accueil, l’« App »), créée par Stanislau Malchanau (« nous »), traite vos informations. En bref : **nous ne collectons, ne vendons ni ne partageons vos données personnelles. Votre parcours d’arrêt reste sur votre appareil et dans votre propre compte iCloud.**

## 1. Données enregistrées par l’App

L’App enregistre sur votre appareil : ce que vous arrêtez (le type de produit, la quantité consommée par jour et son prix), votre date d’arrêt et vos tentatives précédentes, les écarts que vous notez, les envies que vous surmontez avec l’App (quand, à quelle intensité, ce qui les a déclenchées et combien de temps vous avez respiré), les prises que vous comptez dans le plan progressif, vos objectifs d’épargne, l’état de votre vallée et vos réglages. Votre Apple Watch conserve une copie de ces mêmes données pour afficher votre temps sans nicotine et vous aider à traverser une envie.

Comme ces données concernent votre consommation de nicotine, certaines lois les considèrent comme des informations liées à la santé. Elles ne quittent jamais votre appareil ni votre compte iCloud (section 2), sauf de la manière décrite aux sections 5 et 8, qui ne les incluent jamais. Nous n’exploitons aucun serveur qui reçoit ces données et nous n’y avons pas accès.

## 2. Synchronisation iCloud

Si vous êtes connecté à iCloud, l’App synchronise vos données via CloudKit d’Apple, dans la base de données privée de votre propre compte iCloud, afin que votre iPhone et votre Apple Watch affichent le même parcours. Ces données sont stockées et protégées par Apple conformément à sa Politique de confidentialité (https://www.apple.com/legal/privacy/). Nous ne pouvons ni les voir, ni les lire, ni les exporter. Vous pouvez désactiver la synchronisation dans Réglages iOS > [votre nom] > iCloud.

## 3. Informations de santé et Apple Santé

L’App ne lit aucune donnée d’Apple Santé et n’y écrit rien. Les étapes de récupération qu’elle affiche (par exemple 20 minutes, 3 jours, 2 semaines, 3 mois) sont des informations générales issues de sources de santé publique comme l’OMS, le NHS et les CDC ; elles ne constituent ni un diagnostic ni un avis médical (voir les Conditions d’utilisation).

## 4. Mouvements des écouteurs et son spatial

Avec des AirPods ou d’autres écouteurs compatibles, l’App peut utiliser les mouvements de votre tête pour garder les sons de la vallée à leur place quand vous tournez la tête. Ces données de mouvement sont traitées en temps réel sur votre appareil, ne sont jamais enregistrées et ne quittent jamais votre appareil.

## 5. Notifications, Activité en direct et widgets

Les notifications sont créées sur votre appareil. Les widgets et les complications de l’Apple Watch lisent vos données sur votre appareil.

L’App peut afficher une Activité en direct pour vos 72 premières heures sur l’écran verrouillé et dans la Dynamic Island. iOS ne laisse une Activité en direct fonctionner que quelques heures ; pour la maintenir pendant que l’App est en veille, l’App envoie à notre petit serveur relais les jetons push qu’Apple lui fournit pour les Activités en direct, ainsi que le calendrier : les moments où la démarrer ou la mettre à jour et ce qu’elle affiche à chacun d’eux (le temps écoulé depuis votre date d’arrêt et la prochaine étape). Aucun produit, aucune quantité, aucun montant, aucune envie, aucun écart, aucun texte saisi, aucun nom, aucune adresse e-mail, aucun compte ni aucun identifiant d’appareil n’est envoyé. À chaque moment du calendrier, le serveur demande au service push d’Apple de démarrer ou de mettre à jour l’Activité en direct, et il supprime ce qu’il détient dès que la notification prévue est envoyée ou que l’Activité en direct se termine. Le serveur fonctionne sur Cloudflare Workers ; comme pour tout service internet, Cloudflare voit l’adresse IP de la requête lors de son acheminement, et nous ne la conservons pas. Si vous désactivez les Activités en direct pour l’App dans les Réglages iOS, rien n’est envoyé.

## 6. Game Center

Si vous êtes connecté à Game Center, vos succès sont transmis à Game Center d’Apple et traités conformément à la Politique de confidentialité d’Apple. Nous ne recevons pas votre identité Game Center.

## 7. Achats

Les abonnements sont vendus et traités par Apple via l’App Store. Nous ne recevons pas vos informations de paiement. Apple indique à l’App si votre abonnement est actif et quelle formule vous avez choisie, avec son prix ; la section 8 précise ce qui en est transmis à nos statistiques d’utilisation.

## 8. Statistiques d’utilisation et rapports de plantage

Pour savoir quelles fonctions aident et où l’App gêne, l’App envoie des signaux d’utilisation anonymes à TelemetryDeck, un service d’analyse de TelemetryDeck GmbH (Augsbourg, Allemagne) dont les serveurs sont situés dans l’UE. Un signal désigne une action dans l’App : par exemple qu’une étape du premier lancement a été terminée, qu’une envie a été surmontée en respirant, que l’écran d’abonnement a été affiché ou qu’un abonnement a commencé, ou que l’App a demandé une note. Il est accompagné d’un horodatage arrondi à l’heure et de détails techniques généraux : les versions de l’App et d’iOS, le modèle de l’appareil, la langue, la région et le fuseau horaire, ainsi que des réglages d’affichage et d’accessibilité comme le mode sombre ou la taille du texte. Lorsqu’un abonnement commence, son signal indique aussi la formule, son prix converti en dollars américains, la devise et le pays de votre App Store, afin que nous puissions voir quelles formules sont choisies.

Un signal ne contient jamais ce que vous arrêtez, ce que vous consommiez ou dépensiez, votre date d’arrêt, vos envies, vos écarts ou leurs causes, un texte que vous saisissez, votre nom, votre adresse e-mail, votre compte Apple ni votre position. Votre installation n’est identifiée que par un identifiant aléatoire que l’App sale et hache avant l’envoi, de sorte que les signaux ne peuvent pas être reliés à vous ni suivis d’une app à l’autre. TelemetryDeck ne stocke aucune adresse IP et n’utilise aucun cookie. Nous n’examinons ces signaux que sous forme de statistiques pour améliorer l’App ; nous ne les vendons pas, ne les partageons pas avec des annonceurs et ne les utilisons pas pour vous suivre. L’App ne contient aucun code publicitaire ni de suivi et ne vous suit pas à travers d’autres apps ou sites web.

Par ailleurs, si vous choisissez de partager des analyses avec les développeurs d’apps dans Réglages iOS > Confidentialité et sécurité > Analyses et améliorations, Apple peut nous fournir des statistiques d’utilisation et des rapports de plantage agrégés et anonymes. Ils ne permettent pas de vous identifier.

## 9. Ce que l’App n’utilise pas

L’App ne demande pas votre position, vos contacts, vos photos, votre appareil photo, votre micro ni vos données Apple Santé, et elle n’a ni compte, ni connexion, ni messagerie, ni fil social.

## 10. Enfants

L’App ne s’adresse pas aux enfants et ne collecte sciemment aucune information personnelle auprès de quiconque, y compris des enfants de moins de 13 ans (ou de l’âge équivalent dans votre pays).

## 11. Conservation et suppression des données

Les données restent tant que vous les conservez. Vous pouvez supprimer un écart ou un objectif d’épargne dans l’App à tout moment, ou tout supprimer en supprimant l’App et, pour les données synchronisées, dans Réglages iOS > [votre nom] > iCloud > Gérer le stockage du compte > Quit Vaping. Comme nous n’en détenons aucune copie, il n’y a rien d’autre à supprimer de notre côté. Le serveur relais ne conserve les jetons et le calendrier d’une Activité en direct que jusqu’à l’envoi de la notification prévue ou la fin de cette Activité en direct. Les signaux d’utilisation sont anonymes et ne peuvent pas vous être associés ; il n’existe donc aucun enregistrement personnel à consulter ou à supprimer.

## 12. Vos droits

Selon votre lieu de résidence (par exemple en vertu du RGPD dans l’UE, du UK GDPR, du CCPA/CPRA en Californie, de l’APPI au Japon, de la PIPA en Corée ou de la LGPD au Brésil), vous pouvez avoir le droit d’accéder à vos données personnelles, de les rectifier, de les supprimer ou de les transférer, et de vous opposer à leur traitement ou de le limiter. Comme nous ne détenons pas vos données, vous pouvez exercer ces droits directement sur votre appareil et dans iCloud, comme décrit ci-dessus. Vous pouvez aussi nous contacter pour toute demande ou question, et vous pouvez déposer une plainte auprès de votre autorité locale de protection des données.

Nous ne vendons ni ne partageons d’informations personnelles au sens du CCPA/CPRA.

## 13. Modifications

Si cette politique change, nous mettrons à jour la date d’entrée en vigueur ci-dessus et, pour les changements importants, nous vous en informerons dans l’App.

## 14. Contact

Stanislau Malchanau, Bélarus
E-mail : 7tam.official@gmail.com
