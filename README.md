<h1 align="center" text-center>Projet-infra-b2</h1>

Ici vous retrouverez le déroulement du projet Infra dans ses moindres détails.
De l'analyse des besoins du client à la validation du projet.

Pour le projet, Nous sommes **L'équipe**, l'intervenant et le **Client**.

## Analyse client

- Besoin d'infrastructure pour l'entreprise
- Besoin de 4 postes clients (commercial, administratif, assistant et chef)
- Besoin de droit pour l'écriture/Lecture des dossiers par rôle
- Besoin d'un firewall pour la protection des données

## Planification

- **Jalon 1** : Création d'un serveur AD/DHCP (4 comptes à créer : commercial, administratif, assistant et chef) avec les 4 postes Windows 10 ou 11 comme clients

- **Jalon 2** : Création d'un serveur de fichier (arborescence avec 4 dossiers : Direction, commerce, commande et vie d’entreprise)


- **Jalon 3** : Création d'un firewall pour la gestion de la sécurité réseau (VLAN, ouverture de flux)

- **Jalon 4** : Création des régles d'accès au dossiers par rôle dans l'entreprise

- **Jalon 5** : Création d'un serveur dit « applicatif » accès https pour le chef et le commercial

- **Jalon 6** : Création d'un Readme, mise à jour réguliére pour l'avancement du projet 

## Trello

Vous retrouverez ici, notre lien vers notre planning des tâches à effectuer pour le projet :
[Juste ici](https://trello.com/b/FjyDZ8vH)

## Client + Mot de passe

> Vous retrouverez ici, les noms des clients ainsi que leur mot de passe pour avoir accès au poste.

| Nom des pc | Mot de passe |
| :-----:| :-----------: |
| winserver | administratorw |
| commercial | commercialw |
| administratif | administratifw |
| assistant | assistantw |
| chef | chefw |
| firewall | firewallw |

## VM

> Concernant nos VMs, voici leur informations dans notre infrastructure.

Adresses IP pour les VMs :
```
    Serveur AD (Contrôleur de domaine, DHCP, DNS) :
        Adresse IP : 192.168.1.101
        Masque de sous-réseau : 255.255.255.0
        Passerelle par défaut : 192.168.1.1
        DNS : 192.168.1.101
```
```
    PC1 (Commercial) :
        Adresse IP : 192.168.1.102
        Masque de sous-réseau : 255.255.255.0
        Passerelle par défaut : 192.168.1.1
        DNS : 192.168.1.101
```
```
    PC2 (Administratif) :
        Adresse IP : 192.168.1.103
        Masque de sous-réseau : 255.255.255.0
        Passerelle par défaut : 192.168.1.1
        DNS : 192.168.1.101
```
```
    PC3 (Assistant) :
        Adresse IP : 192.168.1.104
        Masque de sous-réseau : 255.255.255.0
        Passerelle par défaut : 192.168.1.1
        DNS : 192.168.1.101
```
```
    PC4 (Chef) :
        Adresse IP : 192.168.1.105
        Masque de sous-réseau : 255.255.255.0
        Passerelle par défaut : 192.168.1.1
        DNS : 192.168.1.101
```

## RACI

> Vous retrouverez ici, notre tableau de ***RACI*** avec les rôles pour chaque étape.

[Voici notre Tableau RACI](https://miro.com/welcomeonboard/NjRUTWp1YVEwQjN3emlXM09KRHE2cEtaMjNyTGFaMEVncWwzRnRlbFJDbWdvNWprY1ZVd0ZxTFlzRFRHaVJTWnwzNDU4NzY0NTkwMTE1NTIxNzAxfDI=?share_link_id=761897958977)

## Réalisation

- Création du Readme (Mise à jour régulière)
- Mise en place des serveurs Windows (serveur par serveur)
- Réalisation des postes
- Mise en place du firewall
- Création du serveur de fichier
- Test de fonctionnement

## Validation

- Revue et acceptation par le client

### Réalisation de tests finaux