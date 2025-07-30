# Mini-Projet pour la Plateforme – OpenVPN sur Debian

Ce projet met en œuvre un serveur OpenVPN sécurisé sur un système Debian virtualisé.  
Il comprend la configuration complète du serveur, la création d'utilisateurs, la sécurité réseau et la gestion via Git.

---

## Suivi des étapes du projet :

- Installation d’OpenVPN et Easy-RSA
- Génération des clés serveur
- Génération des utilisateurs `alice` et `bob`
- Configuration de `/etc/openvpn/server.conf`
- Activation du routage IP (`/etc/sysctl.conf`)
- Pare-feu UFW configuré
- Authentification à deux facteurs (2FA)| (Le plugin est directement dans le fichier sever.conf)
- Dépôt GitHub

---

## Contenu du dépôt :

- `server.conf` – Configuration du serveur OpenVPN
- `vars` – Paramètres Easy-RSA
- `ta.key` – Clé TLS d’authentification
- `alice.ovpn.example` – Exemple de fichier de configuration client VPN
- `README.md` – Ce fichier de documentation

### Lancer le serveur OpenVPN avec bash :

```
sudo systemctl start openvpn@server
sudo systemctl enable openvpn@server
