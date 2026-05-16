# ⚛️ GARDIEN QUANTIQUE - Simulation d'authentification post-quantique

## 1. PRÉSENTATION

| Élément | Description |
|---------|-------------|
| Nom du projet | Gardien Quantique |
| Type | Simulation pédagogique |
| Domaine | Cryptographie post-quantique / Cybersécurité |
| Langage | Python 3 |
| Objectif principal | Démontrer les concepts d'intrication quantique appliqués à l'authentification |

---

## 2. TECHNOLOGIES UTILISÉES

| Technologie | Utilisation |
|-------------|-------------|
| Python 3 | Langage principal du projet |
| hashlib | SHA-3 pour le hachage sécurisé (standard NIST) |
| secrets | Génération cryptographique de nombres aléatoires |
| JSON | Sauvegarde des données utilisateur dans fingerprints.json |
| datetime | Horodatage des connexions et créations de comptes |

---

## 3. CONCEPTS QUANTIQUES SIMULÉS

| Concept quantique | Simulation dans le code | Explication |
|-------------------|------------------------|-------------|
| Superposition | Génération d'un état à partir de nombres aléatoires cryptographiques | Plusieurs états possibles avant mesure |
| Intrication | Lien entre l'utilisateur et son mot de passe via un identifiant unique | Deux particules liées quel que soit la distance |
| Principe d'incertitude | Détection des "espionnages" par vérification d'intégrité | L'observation modifie l'état mesuré |
| Non-clonage | Auto-destruction du mot de passe en cas d'intrusion | Impossible de copier un état quantique |

> ⚠️ Note importante : Ceci est une simulation pédagogique, pas un vrai système quantique.

---

## 4. MES 5 PROJETS SUR GITHUB

| N° | Projet | Description | Lien |
|----|--------|-------------|------|
| 1 | **Password Strength Checker** | Vérificateur de force de mot de passe (cybersécurité) | https://github.com/RVenoth91/password-checker |
| 2 | **Détecteur IA - Hasard vs Intelligence** | Classifieur IA qui devine si une phrase est humaine ou aléatoire | https://github.com/RVenoth91/detecteur-ia-hasard- |
| 3 | **Browser Fingerprinting** | Détecteur d'empreinte digitale de navigateur | https://github.com/RVenoth91/browser-fingerprinting- |
| 4 | **Détecteur d'Émotions par le Clavier** | Détecte les émotions (joie, tristesse, colère, stress) par la façon de taper | https://github.com/RVenoth91/detecteur-emotions-clavier- |
| 5 | **Gardien Quantique** | Simulation d'authentification post-quantique (projet actuel) | https://github.com/RVenoth91/gardien-quantique- |

---

## 5. FONCTIONNALITÉS DU MENU

| Option | Action | Description détaillée |
|--------|--------|----------------------|
| 1 | Créer un compte | Génère un état quantique unique et un mot de passe post-quantique |
| 2 | Se connecter | Vérifie l'identité par intrication quantique simulée |
| 3 | Niveau sécurité | Affiche le rapport de sécurité quantique complet |
| 4 | Infos projet | Présente les concepts et limites du projet |
| 5 | Quitter | Ferme l'application proprement |

---

## 6. INSTALLATION

| Étape | Action |
|-------|--------|
| 1 | Télécharger le fichier quantique.py |
| 2 | Ouvrir un terminal dans le dossier du fichier |
| 3 | Exécuter la commande : `python quantique.py` |
| 4 | Suivre les instructions du menu |

---

## 7. EXEMPLE D'EXÉCUTION

| Étape | Action | Résultat |
|-------|--------|----------|
| 1 | Lancer `python quantique.py` | Affichage du menu principal |
| 2 | Choisir option 1 | Demande du nom d'utilisateur |
| 3 | Entrer "Venoth" | Génération d'un mot de passe : a3f5c2e1b8d4f7h9 |
| 4 | Choisir option 2 | Demande du nom et mot de passe |
| 5 | Entrer "Venoth" et le mot de passe | Affichage : "✅ CONNEXION RÉUSSIE" |

---

## 8. NIVEAU DE SÉCURITÉ SIMULÉ

| Critère | Statut | Explication |
|---------|--------|-------------|
| Cryptographie post-quantique | ✅ ACTIVE | Utilisation de SHA-3 (standard NIST validé) |
| Intrication quantique | ✅ SIMULÉE | Identifiant unique lié à l'utilisateur |
| Principe d'incertitude | ✅ APPLIQUÉ | Détection des modifications d'état |
| Résistance aux ordinateurs quantiques | ✅ THÉORIQUE | Simulation des principes de résistance |
| Auto-destruction | ✅ PRÊTE | Destruction du mot de passe en cas d'intrusion |

---

## 9. COMPÉTENCES DÉMONTRÉES

| Compétence | Niveau | Justification |
|------------|--------|---------------|
| Compréhension des concepts quantiques | ⭐⭐⭐ | Vulgarisation de l'intrication et superposition |
| Algorithmes cryptographiques | ⭐⭐⭐ | Utilisation de SHA-3 et de la génération sécurisée |
| Programmation Python | ⭐⭐⭐ | Code structuré, documenté et modulaire |
| Innovation et créativité | ⭐⭐⭐⭐ | Concept original d'authentification quantique simulée |
| Vulgarisation scientifique | ⭐⭐⭐⭐ | Explication claire de concepts complexes |

---

## 10. ARCHITECTURE DU PROJET

| Fichier | Rôle | Généré automatiquement ? |
|---------|------|--------------------------|
| quantique.py | Programme principal | Non (fichier source) |
| fingerprints.json | Base de données des utilisateurs | Oui (à la première exécution) |
| .gitignore | Fichiers ignorés par Git | Non (à créer manuellement) |

---

## 11. LIMITES DU PROJET

| Limite | Explication |
|--------|-------------|
| Pas un vrai système quantique | Les ordinateurs quantiques n'existent pas encore à cette échelle industrielle |
| Simulation classique | La simulation utilise des algorithmes classiques, pas des qubits réels |
| Usage pédagogique | Projet à but éducatif et démonstratif uniquement |
| Non utilisable en production | Ne pas utiliser pour de vraies données sensibles |

---

## 12. AMÉLIORATIONS POSSIBLES

| Amélioration | Difficulté | Priorité |
|--------------|------------|----------|
| Ajouter une bibliothèque de cryptographie post-quantique réelle (liboqs) | Moyenne | Haute |
| Créer une interface web avec Flask | Moyenne | Moyenne |
| Ajouter une base de données chiffrée (SQLite + AES) | Facile | Moyenne |
| Implémenter une authentification à deux facteurs | Moyenne | Haute |
| Ajouter des tests unitaires avec pytest | Facile | Basse |
| Déployer sur Azure avec Docker | Difficile | Basse |

---

## 13. LIENS UTILES POUR COMPRENDRE

| Sujet | Lien | Description |
|-------|------|-------------|
| Cryptographie post-quantique (ANSSI) | https://www.ssi.gouv.fr/guide/post-quantique/ | Guide officiel de l'agence française de cybersécurité |
| Prix Nobel physique 2022 | https://www.nobelprize.org/prizes/physics/2022/summary/ | Découverte de l'intrication quantique |
| Standards NIST | https://csrc.nist.gov/projects/post-quantum-cryptography | Standards américains post-quantiques |

---

## 14. INFORMATIONS AUTEUR ET LIENS

| Information | Détail |
|-------------|--------|
| Nom complet | Venoth RAJASEKARAN |
| Pseudo GitHub | RVenoth91 |
| Lien GitHub | https://github.com/RVenoth91 |
| Lien Portfolio | https://portfoliovenothrajasekaran.lovable.app/ |
| Lien LinkedIn | https://www.linkedin.com/in/venoth-rajasekaran-684b60291/ |
| Adresse email | venothrajasekaran13@gmail.com |
| Formation | BTS SIO Option SISR obtenu en 2025 (diplômé depuis 1 an) |
| Formation recherchée | Alternance Bac+3 Cybersécurité / Bachelor Cybersécurité |
| Durée souhaitée | 12 mois (possible 2 ans) |
| Disponibilité | Rentrée Septembre 2026 |
| Objectif professionnel | Devenir Ingénieur en Cybersécurité (Master) |

---

## 15. PARCOURS ET MOTIVATION

| Point | Détail |
|-------|--------|
| Situation actuelle | BTS SIO SISR obtenu en 2025, recherche d'alternance depuis 1 an |
| Problème rencontré | Je n'ai pas encore trouvé d'alternance malgré ma motivation |
| Ce que je recherche | Une alternance pour une 3ème année de Bachelor en Cybersécurité |
| Durée d'alternance | 12 mois (ou 2 ans si possible, cela me va parfaitement) |
| Objectif à long terme | Poursuivre en Master pour devenir Ingénieur en Cybersécurité |
| Postes acceptés | Cybersécurité (priorité), Administration Système & Réseaux, Support Informatique |
| Engagement | Tout poste en informatique pour valider mon Bachelor et continuer à apprendre |

---

## 16. RÉSUMÉ FINAL

| Point | Récapitulatif |
|-------|---------------|
| Ce que fait le projet | Simule une authentification post-quantique |
| Ce qu'il utilise | Python, SHA-3, JSON, secrets |
| Ce qu'il démontre | Concepts quantiques, algorithmes cryptographiques, innovation |
| Ce qu'il n'est pas | Un vrai système quantique (simulation pédagogique) |
| Public cible | Recruteurs en cybersécurité, passionnés de technologies |

---

*Projet créé dans le cadre d'une recherche d'alternance en Cybersécurité par Venoth RAJASEKARAN (RVenoth91)*

---

## 📞 CONTACT POUR LES RECRUTEURS

| Information | Détail |
|-------------|--------|
| Nom | Venoth RAJASEKARAN |
| Email | venothrajasekaran13@gmail.com |
| GitHub | https://github.com/RVenoth91 |
| Portfolio | https://portfoliovenothrajasekaran.lovable.app/ |
| LinkedIn | https://www.linkedin.com/in/venoth-rajasekaran-684b60291/ |
| Formation | BTS SIO SISR (2025) |
| Recherche | Alternance Bac+3 Cybersécurité - Septembre 2026 |
| Mobilité | France |

**Je suis très motivé et prêt à m'investir pleinement dans votre entreprise pour apprendre et contribuer à vos projets Cybersécurité.**

**🔗 Retrouvez tous mes projets sur mon portfolio : https://portfoliovenothrajasekaran.lovable.app/**

---

## 📁 MES 5 PROJETS SUR GITHUB (récapitulatif)

| N° | Projet | Description | Lien |
|----|--------|-------------|------|
| 1 | Password Strength Checker | Vérificateur de force de mot de passe | https://github.com/RVenoth91/password-checker |
| 2 | Détecteur IA - Hasard vs Intelligence | Classifieur IA texte humain vs aléatoire | https://github.com/RVenoth91/detecteur-ia-hasard- |
| 3 | Browser Fingerprinting | Détecteur d'empreinte digitale de navigateur | https://github.com/RVenoth91/browser-fingerprinting- |
| 4 | Détecteur d'Émotions par le Clavier | Détecte les émotions par la frappe clavier | https://github.com/RVenoth91/detecteur-emotions-clavier- |
| 5 | Gardien Quantique | Simulation d'authentification post-quantique | https://github.com/RVenoth91/gardien-quantique- | 
