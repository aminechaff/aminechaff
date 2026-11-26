# aminechaff 👋

**Administration systèmes & réseaux · Cybersécurité · Développement d’outils**

Je travaille sur des infrastructures Windows/Linux et je développe des outils autour du réseau, de l’automatisation et de l’analyse de données.

J’aime autant monter un environnement que comprendre ce qui se passe à l’intérieur : suivre un échange réseau, chercher l’origine d’un incident ou écrire un script pour simplifier une tâche.

Ce profil rassemble des travaux en équipe, des laboratoires et des projets personnels. Chaque dépôt précise son contexte et son état d’avancement.

## Infrastructure & sécurité

### [NovaTech — Infrastructure multi-sites](https://github.com/aminechaff/infrastructure-lab-novatech)
Un projet collectif qui relie architecture, gestion des identités, stockage et sauvegardes. Le dépôt rassemble les configurations, les choix techniques et la documentation de l’infrastructure.

`Proxmox` · `FreeIPA` · `Terraform` · `Ansible` · `Restic`

### [CodeMax — Audit en laboratoire](https://github.com/aminechaff/security-audit-lab-codemax)
Étude d’une application volontairement vulnérable dans un environnement Docker. Analyse des échanges réseau, relevé d’indicateurs et recommandations à partir des observations du laboratoire.

`DVWA` · `Docker` · `TShark` · `Analyse réseau`

### [Protocol Analysis Lab — Réseau & identité applicative](https://github.com/aminechaff/protocol-analysis-lab)
Comment reconstruire des messages à partir d’un flux TCP ? Que représente l’identifiant machine vu par une application ?

Une étude anonymisée qui explique la démarche, avec deux démonstrations synthétiques exécutables et leurs limites.

`TCP` · `Formats binaires` · `Identité applicative` · `Node.js`

### [Try_Tools — Contrôles et rapports](https://github.com/aminechaff/try-tools)
Un prototype pour réunir plusieurs contrôles derrière une même interface : définir le périmètre, exécuter les plugins et regrouper leurs observations dans un rapport.

`Python` · `Plugins` · `Tests` · `Markdown / JSON`

## Applications personnelles

### [SRM Lab — Télémétrie iRacing](https://github.com/aminechaff/SRM_Lab)
Le sim racing m’a donné un autre terrain d’expérimentation : récupérer la télémétrie, l’afficher en direct et composer des tableaux de bord dans un overlay Windows.

Le dépôt public présente l’application ; les sources restent privées.

`Python` · `Electron` · `SDK iRacing` · `Widgets`

### [Voice Master — Transcription locale](https://github.com/aminechaff/voice-master)
Une application Windows pour transformer le son du microphone et du PC en texte. Elle associe capture audio, transcription locale et présentation chronologique des interventions.

`Python` · `Faster-Whisper` · `Audio Windows`

## Mes outils

| Domaine | Environnements et outils utilisés |
| --- | --- |
| Systèmes & identités | Windows Server, Linux, Active Directory, FreeIPA |
| Virtualisation & services | Proxmox, VMware, Docker |
| Réseau | VLAN, DNS, DHCP, pfSense, OPNsense, VPN |
| Automatisation | PowerShell, Bash, Python, Ansible, Terraform |
| Sauvegarde & supervision | Restic, Zabbix, Grafana |
| Analyse | TShark, captures PCAP, analyse de protocoles |

## En cours

J’approfondis l’analyse d’incidents et l’automatisation des infrastructures. Sur mes projets, je travaille aussi à rendre les tests plus reproductibles et la documentation plus utile : pouvoir reprendre un environnement, comprendre un choix et vérifier un résultat.
