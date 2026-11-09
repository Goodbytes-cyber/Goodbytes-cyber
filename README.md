# GoodBytes — SOC open source pour PME

**Détection d'intrusions et surveillance de sécurité 24/7, construites sur des briques open source, pour les PME françaises et belges.**

GoodBytes conçoit, déploie et exploite un SOC (Security Operations Center) managé à partir d'outils reconnus et auditables, sans boîte noire ni licence propriétaire.

## Ce que nous faisons

- **SOC-as-a-Service** : collecte des journaux, détection et alertes email avec suivi, de 20 à 200 postes
- **Réponse active** sur les alertes critiques (selon l'offre et les modalités prévues au contrat)
- **Scan de vulnérabilités** de sites web (Nuclei + Nmap, contrôle préalable de la propriété du domaine)
- **Accompagnement NIS2**, y compris pour les sous-traitants de la chaîne d'approvisionnement

## Stack

![Wazuh](https://img.shields.io/badge/Wazuh-SIEM%20%2F%20XDR-0A4C6A) ![Suricata](https://img.shields.io/badge/Suricata-IDS-EF6C00) ![Grafana](https://img.shields.io/badge/Grafana-Dashboards-F46800) ![Prometheus](https://img.shields.io/badge/Prometheus-Monitoring-E6522C) ![Ansible](https://img.shields.io/badge/Ansible-IaC-1A1918)

## Threat intelligence

Nous exploitons des honeypots et des leurres ransomware, et partageons ce que nous observons :

- 📊 [**honeypot-observatory**](https://github.com/Goodbytes-cyber/honeypot-observatory) : agrégats hebdomadaires d'un honeypot Cowrie SSH/Telnet et règles Wazuh
- 🛡️ Contributeur [AbuseIPDB](https://www.abuseipdb.com/) : plusieurs milliers d'IP malveillantes signalées

## Contact

🌐 [goodbytes.fr](https://goodbytes.fr) · ✉️ contact@goodbytes.fr
