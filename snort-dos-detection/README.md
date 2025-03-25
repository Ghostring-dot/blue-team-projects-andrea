![visitors](https://visitor-badge.laobi.icu/badge?page_id=Ghostring-dot.snort-dos-detection)
![repo](https://img.shields.io/badge/Projet-Snort_DoS_Detection-orange)
![last-commit](https://img.shields.io/github/last-commit/Ghostring-dot/snort-dos-detection)
![language](https://img.shields.io/github/languages/top/Ghostring-dot/snort-dos-detection)


# 🌐 Projet SOC Blue Team – Détection d’une attaque DoS avec Snort  


📄 **Ref:GH-A4 — Projet réalisé par Andrea Zhao — Usage personnel uniquement**

---

## 🔎 Objectif du projet

Détecter une attaque par déni de service (TCP SYN Flood) en configurant et testant des règles personnalisées dans **Snort IDS/IPS**.  
Le projet inclut la simulation de l’attaque, l’écriture de règles, l’activation en mode **inline IPS**, et la validation du blocage réseau.

---

## 📄 Rapport

📝 Rapport technique → [`rapport_investigation.pdf`](./rapport_investigation.pdf)

---

## 🛠️ Outils utilisés

- Snort v3 (mode NIDS et IPS)  
- hping3 (génération du flood TCP)  
- NFQUEUE (redirection du trafic)  
- Wireshark (vérification du blocage)  
- Linux iptables + journalctl

---

## 👤 Auteur

Andrea Zhao  
Alternant cybersécurité – Blue Team / SOC  
📎 [Retour au portfolio principal](https://github.com/Ghostring-dot/blue-team-projects-andrea)
