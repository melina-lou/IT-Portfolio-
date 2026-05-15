# Projet 5 – VPN WireGuard (télétravail)

## Français

### Objectif
Configurer un tunnel VPN sécurisé entre deux machines pour simuler le télétravail.

### Ce que j’ai fait (à compléter quand tu l’auras fait)
- Installé WireGuard sur mon Mac et sur deux VMs (Ubuntu Server et Windows 10).
- Généré les clés privées/publiques.
- Créé les fichiers de configuration (`wg0.conf`) pour le serveur et le client.
- Établi la connexion et vérifié le ping à travers le tunnel.

### Difficultés (exemples)
- Le routage ne fonctionnait pas au début : j’avais oublié d’activer le `ip forwarding` sur le serveur.
- J’ai dû ouvrir le port UDP 51820 dans le pare-feu Windows.

### Compétences démontrées
- VPN (WireGuard)
- Configuration réseau (routage, pare-feu)
- Virtualisation

### Preuves
- Fichiers de configuration (clés masquées)
- Captures d’écran des pings réussis

---

## English Summary

**Goal:** Set up a secure VPN tunnel between two machines to simulate remote work.

**What I did:** Installed WireGuard, generated keys, configured server/client, tested connectivity.

**Issues:** Forgot to enable IP forwarding, opened UDP port in firewall.

**Skills:** VPN, networking, firewall, virtualization.

**Proofs:** Config files (keys redacted), ping screenshots.
