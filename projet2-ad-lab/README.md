# Projet 2 – Laboratoire Active Directory

## Français

### Objectif
Démontrer que je sais installer et configurer un contrôleur de domaine (AD DS) et gérer des utilisateurs, groupes et permissions.

### Ce que j’ai fait
- Téléchargé VirtualBox et une ISO d’évaluation de Windows Server 2022.
- Créé une VM (2 Go RAM, 20 Go disque) et installé Windows Server.
- Ajouté le rôle Active Directory Domain Services (AD DS).
- Élevé le serveur en contrôleur de domaine (domaine `mel.local`).
- Créé 3 utilisateurs : Jean, Marie, Paul.
- Créé 2 groupes : Commercial, Technique.
- Sur un dossier partagé, donné accès en lecture seule au groupe Commercial.

### Difficultés rencontrées
- Le service DNS ne démarr pas du premier coup. J’ai dû redémarrer la VM et vérifier la configuration des cartes réseau.
- J’ai oublié de cocher « Promote this server to a domain controller » après avoir ajouté le rôle. Ça a pris 10 minutes avant de comprendre.

### Compétences démontrées
- Installation et configuration d’AD DS
- Gestion des utilisateurs et groupes
- Permissions NTFS sur dossiers
- VirtualBox

### Preuves
- Captures d’écran dans `captures/` (console AD, dossier partagé, permissions)
- Fichier `README.md` (celui-ci)

---

## English Summary

**Goal:** Set up a domain controller and manage users/groups/permissions.

**What I did:** Installed Windows Server on VirtualBox, added AD DS role, created domain `mel.local`, created 3 users, 2 groups, set folder permissions.

**Issues:** DNS didn't start at first – rebooted VM and checked network config. Forgot to promote server – wasted 10 min.

**Skills:** AD DS setup, user/group management, NTFS permissions, VirtualBox.

**Proofs:** Screenshots in `captures/` folder.
