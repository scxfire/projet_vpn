# Questionnaire Candidat

## Bachelors 3 pour Système Réseaux et cybersécurité

Ce questionnaire contient 2 parties. Une première partie avec des questions sur vos connaissances générales en système, réseau et sécurité.  
La deuxième partie est un projet à réaliser.

---

## Système

### Question 1

Dans un terminal (BASH), vous tapez la commande:  

`ps -ef | grep ssh` pour:

Lister les processus actifs puis filtrer la recherche

Quelle autre commande pourriez-vous utiliser sous Debian/Ubuntu pour avoir plus d'informations?

`ps aux`

---

### Question 2

**Comment passer un ou plusieurs arguments à un script BASH?**  
Donnez des exemples de redirection des E/S standard pour passer un argument à un script.

Pour passer un  ou plusieurs arguments, il faut utilisé une de ces variables à la fin de la commande d'exécution du script 
`./mon_script.sh premier second` :

- $1
- $2
- $@

Exemple de redirection des E/S standard :

- Entrée : stdin  
- Sortie : stdout  
- Erreur : stderr

---

### Question 3

**Dans quel environnement est exécuté un script inscrit dans la crontab de l’utilisateur /home/debianUser ?**

 Le script est lancer dans l’environnement cron

---

### Question 4

**Citez et décrivez brièvement les 4 états des processus dans un environnement Unix/Linux.**

- R : Le processus est en cours d’exécution ou prêt à être exécuté par le processeur  
- S : Le processus attend un événement  
- T : Le processus est temporairement stoppé  
- Z : le processus est terminé mais reste dans la table des processus car son parent n’a pas encore récupéré son statut

---

## Réseau

### Question 1

**Sur un réseau Ethernet, que fera un host ou un équipement qui reçoit une trame contenant une adresse MAC unicast qui ne correspond pas à sa propre adresse MAC ?**

 Il rejette la trame, si ce n’est pas sa propre adresse mac.

---

### Question 2

**Sur quelle couche du modèle OSI va travailler :**

- Un commutateur (switch) : Data link layer  
- Un router : Network layer  
- Le protocole TCP : Transport layer  
- HTTP : Application

---

### Question 3

**On vous donne une trame réseau en hexadécimal. Quel outil/logiciel pouvez vous utiliser pour l'interpréter ?**

 Pour interpréter une trame réseau en hexadécimal, on peut utiliser **Wireshark**

---

### Question 4

**Quels champs appartiennent à un paquet TCP ? Sélectionnez tous les champs possibles.**
  
- Ack Number  
- Control Bits  
- Application Layer data

---

### Question 5

**Quel est le but d'une attaque d'ARP spoofing ?**

 Associer une adresse IP avec un adresse MAC erronée

---

## Sécurité

### Question 1

**Existe-t-il une norme pour la sécurité informatique ?**

 Oui, il existe une norme de sécurité qui se nomme ISO 27001 qui est pionnière dans le domaine de la sécurité informatique

---

### Question 2

**Concernant la sécurité, quelles institutions/agences pouvez-vous citer pour la France ? À l'international ?**

 ANSSI : Agence nationale de la sécurité des systèmes d'information

---

### Question 4

**Avec votre usage habituel du numérique (PC, tablette, téléphone), quels sont les moments où vous êtes vulnérables ?**

1. Télécharger une application ou un fichier inconnu  
2. Les faux mails que je reçois (Phishing)  
3. Les mises à jour de sécurité de mes appareils  
4. Utilisation de mots de passe répétitifs

**Quels pourraient en être les conséquences ?**

1. Infection de l’appareil par un malware ou virus qui peuvent avoir des conséquences désastreuses comme le vol de données, prise de contrôle à distance de l’appareil ou même la destruction de mes fichiers.  
2. Vol de mes identifiants (mails, comptes bancaires, réseaux sociaux), usurpation d’identité.  
3. Exposition à des failles.  
4. Si un mot de passe est connu, tous mes comptes qui ont le même mot de passe sont à risques.

**Qui d'autre pourrait être impacté d'une faille de sécurité chez vous (ou dans votre entreprise) ?**

 - Ma famille, ils peuvent profiter pour les contacter directement avec mon identité.  
 - Entreprise, Ils peuvent introduire un virus et qui aurait des conséquences désastreuses comme une fuite de données professionnelles ou un blocage des systèmes (ransomware).  
 - En conséquence de la fuite professionnelle, même les clients peuvent être affectés.
