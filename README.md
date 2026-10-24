# salesView — téléchargements

La version stable actuelle est **[0.1.24 (25)](https://github.com/EROWINDJ/primes-objectifs-releases/releases/tag/v0.1.24)**.

- [Télécharger l’APK release signé](https://github.com/EROWINDJ/primes-objectifs-releases/releases/download/v0.1.24/primes-objectifs-0.1.24.apk)
- SHA-256 : `002d53edbd30e12694b1022e7010bde102866674f4b8c978dc2ca5bbd69600c0`
- Les notes, les métadonnées `update.json` et `SHA256SUMS` accompagnent l’APK dans la release.

**0.1.24 : Version de validation du parcours de mise à jour — aucun changement fonctionnel.** Depuis la release 0.1.23, l’application vérifie automatiquement les mises à jour à l’ouverture après chargement des données et éventuel déverrouillage. Une réponse réussie reste en cache six heures ; si elle mentionne encore 0.1.23, l’alerte apparaîtra lors d’une nouvelle ouverture après expiration du cache. Le bouton **Paramètres → À propos → Vérifier les mises à jour** force une vérification immédiate, mais ne constitue pas un test de l’alerte automatique. Le navigateur télécharge l’APK et Android confirme l’installation par-dessus la release 0.1.23.

Les installations debug utilisent un autre certificat : vérifiez une sauvegarde avant toute transition vers une release. Le code source et les données des utilisateurs ne sont pas hébergés dans ce dépôt public.
