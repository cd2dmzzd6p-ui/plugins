☣️ARTI☣️-C
Conserver. Vérifier. Protéger. Transmettre avec preuve.
📥 Originaux
🛠️ Travail
🗑️ Corbeille
💾 Sauvegarde
📥 Importer dans Originaux
Photos, vidéos, documents, audios et fichiers.

☣️ ARTI-C — Protection complète
0. 📋 Référence du projet
RéférenceRTC
Application☣️ARTI☣️-C
Les paramètres non sensibles sont préremplis. Les clés cryptographiques, mots de passe, signatures et identifiants personnels restent volontairement à renseigner localement.
Architecture locale autonome : identité cryptographique, contrôle d’intégrité, droits d’utilisation, messages chiffrés, mots-clés, coffre, compteur anti-rejeu, journal d’audit, visibilité et présence. Aucun serveur ni appel réseau n’est ajouté par cette couche.
1. 🧬 Identité de l’appareil
ECDSA P-256 pour les signatures. Les clés ECDH utilisées pour les messages sont générées séparément ; les clés privées restent dans le stockage local de l’application.
Créer mon identité
Afficher ma clé publique
Identité non créée.
2. ✍️ Droits, signature et intégrité
AUTORISATION D’UTILISATION — ARTI-C
Référence : RTC

Titulaire : RTC
Destinataire : ☣️ARTI☣️-C
Objet / périmètre : Projet ARTI-C — conservation, vérification, protection, transmission avec preuve.

Le destinataire peut consulter et utiliser les éléments qui lui sont remis dans le cadre défini ci-dessus.

Sauf accord exprès du titulaire, cette autorisation n’inclut pas le droit de modifier, altérer, supprimer ou créer une version dérivée des éléments.

Toute modification doit faire l’objet d’une autorisation distincte et explicite.

Date : 11/09/2026
Signature : RTC RTC J’accepte le texte ci-dessus.
Signer le document
Vérifier la signature
Aucune signature.
3. 🔎 Moteur de mots-clés
Classement local et détection de termes. Aucun mot-clé n’est envoyé automatiquement.
confidentiel, ARTI-C, RTC, sécurité, intégrité, preuve, audit ARTI-C — conserver, vérifier, protéger, transmettre avec preuve. Référence RTC. Analyser
Aucune analyse.
4. 🔐 Message protégé
Le paquet utilise AES-256-GCM pour le contenu, ECDH P-256 pour la clé de session et une signature ECDSA P-256. Le destinataire doit disposer de la clé privée ECDH correspondante pour déchiffrer.
Clé publique JWK du destinataire RTC
Chiffrer + signer
Déchiffrer + vérifier
Aucun paquet.
5. 🔑 Coffre local
PBKDF2-SHA-256 dérive une clé AES-256-GCM. La phrase secrète n’est jamais enregistrée. Le coffre peut contenir du texte ou des données de configuration.
Configuration locale ARTI-C — Référence : RTC
Chiffrer le coffre
Déverrouiller un coffre
Coffre non chargé.
6. 🔢 Compteur anti-rejeu
Chaque message sortant reçoit un compteur local croissant. Lors d’une réception, un compteur déjà accepté pour le même expéditeur est refusé.
RTC

Contrôler le compteur
Aucun contrôle.
7. 👁️ Protection de visibilité
Lorsque l’onglet perd la visibilité ou le focus, les zones sensibles sont masquées. Cela ne peut pas empêcher matériellement les captures d’écran du système.
Activer la protection de visibilité
Protection inactive.
8. 📷 Présence locale
La caméra n’est ouverte qu’après action explicite. Cette page ne fait aucune reconnaissance faciale et ne prétend pas identifier une personne.
Demander l’accès caméra
Arrêter
Caméra inactive.
9. 📜 Journal d’audit
Le journal enregistre les actions et résultats, mais pas les phrases secrètes ni les clés privées.
Exporter le journal Effacer le journal local
10. 🛡️ Diagnostic
Lancer le diagnostic
Diagnostic non lancé.
À renseigner manuellement uniquement : identité/clé du destinataire, phrase secrète du coffre, contenu sensible, compteur reçu et signature réelle.
