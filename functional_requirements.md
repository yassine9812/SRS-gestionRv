# Exigences fonctionnelles

## FR-01 : Créer un compte patient
- **Description** : Le système doit permettre à un patient de créer un compte en renseignant son nom, prénom, téléphone et adresse e-mail.
- **Raison** : Identifier le patient et permettre le suivi de ses rendez-vous.
- **Source** : Patient / Clinique
- **Priorité** : Haute
- **Critère d’acceptation** : Un patient peut créer un compte et reçoit un message de confirmation.

## FR-02 : Authentification des utilisateurs
- **Description** : Le système doit permettre aux utilisateurs (patient, médecin, secrétariat, administrateur) de s’authentifier.
- **Raison** : Sécuriser l’accès au système et différencier les rôles.
- **Source** : Clinique
- **Priorité** : Haute
- **Critère d’acceptation** : Un utilisateur avec des identifiants valides accède à son espace personnel.

## FR-03 : Consulter les médecins
- **Description** : Le système doit permettre au patient de consulter la liste des médecins disponibles.
- **Raison** : Aider le patient à choisir un professionnel de santé.
- **Source** : Patient
- **Priorité** : Moyenne
- **Critère d’acceptation** : La liste des médecins s’affiche avec leur spécialité.

## FR-04 : Consulter les disponibilités
- **Description** : Le système doit afficher les créneaux disponibles d’un médecin sélectionné.
- **Raison** : Permettre la prise de rendez-vous.
- **Source** : Patient / Médecin
- **Priorité** : Haute
- **Critère d’acceptation** : Seuls les créneaux libres sont affichés.

## FR-05 : Prendre un rendez-vous
- **Description** : Le système doit permettre à un patient authentifié de réserver un créneau disponible.
- **Raison** : Fonction principale du système.
- **Source** : Patient
- **Priorité** : Haute
- **Critère d’acceptation** : Le rendez-vous apparaît dans l’espace patient et dans le planning du médecin.

## FR-06 : Annuler un rendez-vous
- **Description** : Le système doit permettre au patient d’annuler un rendez-vous.
- **Raison** : Gérer les imprévus et réduire les rendez-vous non honorés.
- **Source** : Patient / Clinique
- **Priorité** : Haute
- **Critère d’acceptation** : Le créneau annulé redevient disponible.

## FR-07 : Gérer les disponibilités médecin
- **Description** : Le système doit permettre au médecin de définir et modifier ses créneaux de disponibilité.
- **Raison** : Maintenir un planning à jour.
- **Source** : Médecin
- **Priorité** : Haute
- **Critère d’acceptation** : Les créneaux définis sont visibles côté patient.
## FR-08 : Consulter l’historique des rendez-vous d’un patient
- **Description** : Le système doit permettre au médecin et au secrétariat de consulter l’historique des rendez-vous d’un patient.
- **Raison** : Améliorer le suivi médical et la continuité des soins.
- **Source** : Médecin / Clinique
- **Priorité** : Moyenne
- **Critère d’acceptation** : L’historique affiche la date, le médecin et le statut du rendez-vous (réalisé, annulé, no-show).
