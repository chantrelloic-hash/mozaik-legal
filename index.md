# Politique de confidentialité — Application Mozaïk

*Établie conformément au Règlement (UE) 2016/679 (RGPD) et à la loi n° 78‑17 du
6 janvier 1978 modifiée (Informatique et Libertés).*

**Dernière mise à jour : 23 septembre 2026 — Version 1.5** (adresse de contact
contact@mozaik973.fr et page de suppression hébergée sur mozaik973.fr ;
précédente version 1.4 du 22 septembre 2026 : fin de la mesure
d'audience Firebase Analytics aux §3, §5 et §10 ; purge à 90 jours des demandes
d'accès au back‑office au §7 ; suppression du compte depuis l'application au
§9 bis ; case « J'ai 15 ans ou plus » à la création de compte au §11 ;
précédente version 1.3 du même jour : connexion Google et
Apple, téléphone de réservation, demandes d'accès au back‑office et attestation
d'appareil ajoutés au §3 ; Apple et Brevo précisés au §5 ; retrait du WiFi Direct,
abandonné ; âge minimum reformulé au §11 ; précédente version 1.2 du 13 août 2026 :
ajout au §3 des captures
d'écran des signalements de bug et du bloc diagnostics, ajout de Brevo comme
sous‑traitant au §5 ; précédente version 1.1 du 14 juillet 2026 : §9 bis —
suppression de compte et de données, conforme à la politique Google Play sur
la suppression de compte)

## 1. Responsable du traitement

Le responsable du traitement des données personnelles est l'éditeur de Mozaïk :
Loïc Chantrel (particulier), Kourou, Guyane française, France. Conformément à la
faculté ouverte par l'article 6‑III‑2 de la LCEN aux personnes physiques agissant
à titre non professionnel, l'adresse complète n'est pas rendue publique ; elle
est transmise à l'hébergeur, qui la communique sur demande à l'autorité judiciaire.

- **Contact « données personnelles » / référent** : contact@mozaik973.fr (point de contact dédié ; pas de DPO désigné,
  non requis au sens de l'art. 37 RGPD pour ce traitement).

## 2. Rôles : responsable de traitement et sous‑traitant

- Pour les données des **utilisateurs** de l'application (invités et membres),
  Mozaïk est **responsable de traitement**.
- Pour les données que chaque **structure partenaire** (association, professionnel)
  gère depuis sa tuile au sujet de ses propres adhérents/clients (réservations,
  inscriptions, etc.), la structure est **responsable de traitement** et Mozaïk
  agit comme **sous‑traitant** (art. 28 RGPD — voir l'accord de sous‑traitance
  annexé à la convention de partenariat).

## 3. Données collectées, finalités, bases légales

| Catégorie de données | Finalité | Base légale (art. 6 RGPD) |
|---|---|---|
| Identifiant anonyme (auth. anonyme) | Lecture publique de l'agenda et des contenus sans compte | Intérêt légitime (fournir le service) |
| Email, mot de passe (chiffré), identifiants HelloAsso ; nom et adresse email transmis par Google ou Apple en cas de connexion avec ces comptes | Création et sécurisation du compte, connexion | Exécution du contrat (CGU) / mesures précontractuelles |
| Nom, téléphone, préférences (thème, taille texte) | Profil membre, personnalisation, contact pour réservations | Exécution du contrat |
| Numéro de téléphone saisi lors d'une réservation auprès d'une structure (obligatoire pour réserver) | Permettre à la structure de joindre la personne qui réserve ; lisible par le responsable de cette structure seulement | Exécution du contrat |
| Adhésions (via HelloAsso) | Affichage du statut d'adhérent, accès aux espaces réservés | Exécution du contrat / intérêt légitime |
| Rapports de plantage (Crashlytics) : type d'appareil, version du système et de l'application, trace technique de l'erreur | Stabilité de l'application | Intérêt légitime (corriger les pannes) |
| Position géographique (Tribu, mode festival, covoiturage) | Carte de présence, retrouvailles entre amis, covoiturage | **Consentement explicite** (activation volontaire) |
| Messages (chat : Bluetooth maillé / cloud) | Messagerie entre membres | Exécution du contrat |
| Jeton de notification (FCM) | Envoi de notifications push | **Consentement** |
| Identifiants techniques d'appareil (identifiant d'installation Firebase, identifiant Crashlytics) | Rattachement technique des rapports de plantage à un même appareil, sans lien avec l'identité civile | Intérêt légitime (corriger les pannes) |
| Demande d'accès au back‑office (identifiant, nom et adresse email du compte, date) | Examen de la demande par l'éditeur, prévenu par email | Intérêt légitime |
| Déclaration « J'ai 15 ans ou plus » cochée à la création du compte (date de la déclaration) | Respect de l'âge minimum (§11) | Obligation légale (art. 8 RGPD, art. 45 loi Informatique et Libertés) |
| Attestation d'intégrité de l'appareil et de l'application (Google Play Integrity, Apple App Attest, reCAPTCHA Enterprise pour le back‑office) — un jeton technique, sans donnée d'identité | Protéger le service contre les appels frauduleux | Intérêt légitime (sécurité) |
| Signalements, blocages, rapports de modération | Sécurité, modération, respect de la charte | Intérêt légitime + obligation légale (LCEN/DSA) |
| Horodatage de connexion (date/heure), pour les membres identifiés uniquement | Sécurité, vision d'activité réservée au super-admin (back-office) | Intérêt légitime |
| Captures d'écran des signalements de bug (**facultatif** — fournies volontairement par l'invité avec son rapport) | Diagnostic des incidents signalés ; lisibles par le **super‑admin seul**, conservées **30 jours** puis supprimées automatiquement | **Consentement** (pièce jointe volontaire) |
| Bloc diagnostics joint aux signalements (depuis la version 1.0.31) : rôle, adhésion, méthode de connexion, autorisations système accordées, état de l'application, réglages d'affichage | Diagnostic des incidents signalés ; lisible par le **super‑admin seul** ; **aucune** position, **aucun** contenu de message, **aucun** jeton n'y figure | Intérêt légitime (résolution d'incidents) |

> **Aucune décision entièrement automatisée** produisant des effets juridiques
> (art. 22 RGPD) n'est mise en œuvre. Aucune donnée n'est vendue à des tiers.

> **Aucune donnée financière** (numéro de carte bancaire, IBAN) n'est collectée
> ni stockée par Mozaïk : les paiements d'adhésion sont traités exclusivement
> par **HelloAsso**, qui agit comme prestataire de paiement indépendant et
> applique sa propre politique de confidentialité. Mozaïk ne reçoit que le
> statut de l'adhésion (payée / en attente) et les informations d'identité
> nécessaires pour la rattacher à un membre.

> **L'application ne diffuse aucune publicité**, ne mesure pas l'audience et
> ne recourt à aucun SDK publicitaire ou de traçage à des fins de ciblage
> marketing.

## 4. Géolocalisation, réseau « Tribu » et mode festival

- Le partage de position est **désactivé par défaut** et requiert une activation
  volontaire et un **consentement explicite**, révocable à tout moment.
- En **mode festival**, la position est partagée de manière **éphémère** (durée
  maximale **8 heures**) puis supprimée (purge à l'expiration ou à la
  désactivation).
- **Aucun historique GPS** n'est conservé : la position transite par la Realtime
  Database et est effacée dès la désactivation ou à expiration.
- La position d'un membre **n'est pas accessible** aux planificateurs,
  responsables ou administrateurs des structures. Seul le **super‑administrateur**
  de la plateforme (droit technique `isMosaikAdmin`) peut, à des fins
  d'exploitation et de sécurité, visualiser la carte d'ensemble. Cet accès est
  strictement limité à l'éditeur, utilisé aux seules fins de support et de
  sécurité, et journalisé par l'infrastructure Firebase.

## 5. Destinataires et sous‑traitants

Les données sont accessibles à l'éditeur et à ses sous‑traitants techniques :

- **Google Ireland Ltd** (Firebase : Auth, Firestore, Realtime Database, Storage,
  FCM, Crashlytics, App Check) — hébergement et infrastructure ;
- **HelloAsso** — adhésions et paiements associatifs ;
- **Apple Distribution International Ltd** (Cork, Irlande) — distribution de
  l'application iOS, connexion « Se connecter avec Apple » et attestation
  d'appareil (App Attest) ;
- **Brevo** (SAS, Sendinblue) — sous‑traitant pour les envois transactionnels
  (réinitialisation de mot de passe, avis de demande d'accès au back‑office), traitement **en France / Union
  européenne** ;
- les **structures partenaires**, uniquement pour les données les concernant
  (p. ex. l'identité d'un membre qui réserve chez elles) ;
- les **autorités** légalement habilitées, sur réquisition.

## 6. Transferts hors Union européenne

Le recours à Firebase (Google) peut impliquer des transferts de données **hors
UE**. Ces transferts sont encadrés par les garanties appropriées prévues au
chapitre V du RGPD : **clauses contractuelles types** de la Commission
européenne et/ou adhésion au **EU‑US Data Privacy Framework**. Google LLC est certifié au titre du EU‑US Data Privacy Framework et s'appuie
sur les clauses contractuelles types pour les transferts non couverts par
cette certification.

## 7. Durées de conservation

| Donnée | Durée |
|---|---|
| Compte membre et profil | Le temps de l'utilisation, puis suppression / anonymisation 3 ans après la dernière activité |
| Position « mode festival » | 8 heures maximum, purge automatique |
| Messages de chat | Le temps de l'utilisation ; suppression possible par l'utilisateur (groupes, blocage) ; les copies cloud sont purgées lors de la suppression du compte (délai maximal 30 jours) |
| Rapports de plantage (Crashlytics) | 90 jours (durée de conservation de Crashlytics) |
| Demandes d'accès au back‑office | 90 jours, puis suppression automatique |
| Signalements / modération | Durée de traitement du signalement, puis archivage 12 mois (préservation des preuves en cas de contentieux) |
| Captures d'écran des signalements de bug | 30 jours (suppression automatique) |
| Journal de connexion (membres identifiés) | 45 jours maximum (purge automatique) ; l'heure précise n'est visible côté back-office que 15 jours, seule la date reste ensuite |
| Données comptables (factures partenaires) | 10 ans (obligation légale comptable) |

## 8. Sécurité

L'éditeur met en œuvre des mesures techniques et organisationnelles appropriées :
authentification, règles d'accès Firestore/Storage/RTDB cloisonnant les données
par structure et par rôle, custom claims, immuabilité des messages, chiffrement
en transit. Les administrateurs de structure n'accèdent pas aux données des
autres univers.

## 9. Vos droits

Conformément aux articles 15 à 22 RGPD, vous disposez des droits d'**accès**, de
**rectification**, d'**effacement**, de **limitation**, d'**opposition**, de
**portabilité**, du droit de **retirer votre consentement** à tout moment, et du
droit de définir des **directives post‑mortem**.

- **Exercice** : par courriel à contact@mozaik973.fr, en justifiant de votre
  identité. Réponse dans un délai d'**un mois** (art. 12 RGPD).
- **Réclamation** : vous pouvez saisir la **CNIL** — 3 place de Fontenoy, TSA
  80715, 75334 Paris Cedex 07 — ou via [cnil.fr](https://www.cnil.fr).

## 9 bis. Suppression du compte et de vos données

- **Depuis l'application** : « Mon compte » → « Supprimer mon compte ». Après
  confirmation et une nouvelle connexion (mot de passe, Google ou Apple), le
  compte et les données ci‑dessous sont supprimés **immédiatement**. Pour un
  compte « Se connecter avec Apple », l'autorisation donnée à Mozaïk est aussi
  révoquée auprès d'Apple.
- **Sans l'application** : tout membre peut aussi demander la suppression de son
  compte et de ses données, sans avoir besoin de réinstaller ou d'ouvrir
  l'application, par courriel à contact@mozaik973.fr (objet « Suppression de
  compte »), ou via la page web dédiée :
  https://mozaik973.fr/supprimer-mon-compte.html. La demande peut être faite par toute
  personne disposant d'un compte, y compris si l'application a été
  désinstallée.
- **Délai de traitement** : une demande par courriel ou par la page web est
  traitée dans un délai maximal de **30 jours**. Le compte Firebase Auth, le profil membre (Firestore), les
  préférences, le jeton de notification et la position partagée sont supprimés
  ou anonymisés.
- **Ce qui est supprimé** : compte de connexion, profil membre, préférences,
  jeton de notification, position partagée (« Tribu »/festival), liste d'amis
  et demandes d'amitié (y compris chez les autres membres), inscriptions
  bénévoles, commentaires, votes, étoiles, covoiturages, réservations auprès des
  structures, idées déposées, messages de contact, signalements de bug et leurs
  captures, journal de connexion, demandes d'accès au back‑office, droits
  d'administration de structure. L'application ne conserve pas de photo de
  profil.
- **Ce qui peut être conservé temporairement, pour une durée limitée et un
  motif précis** :
  - les messages déjà transmis à d'autres membres (le retrait d'un message
    d'une conversation collective n'est techniquement possible que pour son
    propre appareil et le nœud cloud dont le membre est responsable — voir
    §3 « Messages ») ;
  - la fiche d'adhérent tenue par l'association (import HelloAsso) : elle
    relève de l'association, responsable de ce traitement (§2) ;
  - les données nécessaires au respect d'une obligation légale (données
    comptables des adhésions, durée 10 ans — §7) ;
  - les signalements de modération vous concernant, pour la durée strictement
    nécessaire au traitement du signalement et au délai légal de prescription.
- **Suppression partielle** : un membre peut aussi demander la suppression
  d'une seule catégorie de données (p. ex. seulement la position, ou
  seulement l'historique de chat) sans supprimer le compte entier, via le
  même contact.
- **Mode invité (auth. anonyme)** : les invités n'ayant pas créé de compte ne
  détiennent pas de données personnelles identifiées côté serveur au-delà de
  l'identifiant anonyme technique ; celui-ci est supprimable sur simple
  demande ou expire avec la session de l'application.

## 10. Cookies et traceurs

L'application et le back‑office n'utilisent que des traceurs **strictement
nécessaires** (exemptés de consentement) : session de connexion, attestation
d'appareil (App Check) et identifiant technique des rapports de plantage
(Crashlytics). **Aucune mesure d'audience** n'est réalisée : Firebase Analytics
a été retiré de l'application. Ces données ne servent ni à la publicité ni au
profilage. Vous pouvez vous opposer aux rapports de plantage par courriel au
contact indiqué au §1.

## 11. Mineurs

L'application n'est pas destinée aux enfants de moins de **15 ans** sans
autorisation. Conformément à l'article 8 RGPD et à l'article 45 de la loi
Informatique et Libertés, lorsque le traitement repose sur le consentement, le
consentement d'un titulaire de l'autorité parentale est requis en‑dessous de
15 ans. La création d'un compte (par e‑mail, Google ou Apple) exige de
cocher la case **« J'ai 15 ans ou plus »** ; la date de cette déclaration est
conservée avec le profil. Il s'agit d'une déclaration : aucun justificatif
n'est demandé. Tout compte signalé comme appartenant à un mineur de moins de
15 ans sans consentement parental est supprimé sur demande du titulaire de
l'autorité parentale (contact ci-dessus).

## 12. Modifications

La présente politique peut être mise à jour. Toute modification substantielle
sera portée à la connaissance des utilisateurs par un moyen approprié (notice
in‑app). La date de dernière mise à jour figure en tête de document.

---
*Mozaïk — Kourou, Guyane — mozaik973.fr · Projet de document à valider par un professionnel du droit.*

