# Crypto & Security Labs

🇫🇷 [Français](#-français) · 🇬🇧 [English](#-english)

---

## 🇫🇷 Français

Résumés de huit travaux pratiques de **cryptographie et sécurité de l’information** réalisés à VILNIUS TECH
(module *Kriptografija ir informacijos sauga*, 2026). Chaque laboratoire a été réalisé dans un
environnement de test personnel (machines virtuelles isolées), dans un but d’apprentissage **défensif**.

> Ce dépôt ne contient que des résumés et des enseignements. Les rapports d’origine comportent des
> captures d’écran, des identifiants de test et des empreintes : ils ne sont pas publiés ici.

| # | Sujet | Outils | Ce que j’en retiens |
|---|---|---|---|
| 1 | Chiffrement classique (César, Vigenère) | dcode.fr | combiner deux chiffrements, limites des chiffres par substitution, gestion des alphabets |
| 2 | Robustesse de l’authentification web | Apache2, environnement de test local | pourquoi un mot de passe faible tombe, et les contre-mesures : verrouillage de compte, limitation du débit, MFA |
| 3 | RSA : chiffrement et signature numérique | OpenSSL | paires de clés publique/privée, signature et vérification, pourquoi la taille de clé compte |
| 4 | Fonctions de hachage | OpenSSL (MD5, SHA-256, SHA-512) | effet d’avalanche, intégrité des fichiers, hachage de mots de passe avec sel et algorithmes dédiés |
| 5 | Stéganographie | Linux (`cat`, `unzip`) | différence entre cacher et chiffrer l’information, détection de données dissimulées |
| 6 | Standard d’exclusion des robots (`robots.txt`) | analyse de `robots.txt` publics | contrôle de l’accès des robots, blocage des robots d’IA, limites de ce standard (déclaratif, non contraignant) |
| 7 | Scanners de vulnérabilités web | Mozilla Observatory, Qualys SSL Labs, validateurs W3C | lecture d’un rapport de sécurité, en-têtes HTTP, configuration TLS, hiérarchie des correctifs |
| 8 | Vulnérabilités système | Tenable Nessus, Wireshark | scan d’hôtes et de services, classement des vulnérabilités par criticité, risque d’une authentification en clair (HTTP vs HTTPS) |

### Ce que ces TP démontrent

- compréhension des bases de la cryptographie (symétrique, asymétrique, hachage) ;
- lecture et interprétation de rapports de scanners de sécurité ;
- raisonnement **défensif** : chaque faiblesse observée est associée à sa contre-mesure ;
- usage d’outils standards (OpenSSL, Nessus, Wireshark) en environnement de test isolé.

### Lien avec mes autres projets

Le TP n° 2 (attaques par force brute) et le TP n° 7 (scan web) rejoignent mon analyseur de
journaux SSH : [ssh-log-analyzer](https://github.com/Sallislt/ssh-log-analyzer).

---

## 🇬🇧 English

Summaries of eight **cryptography and information security** lab sessions completed at VILNIUS TECH (2026),
all performed in a personal, isolated test environment for **defensive** learning.

> This repository only holds summaries and takeaways. The original reports contain screenshots, test
> credentials and hashes and are not published here.

| # | Topic | Tools | Key takeaway |
|---|---|---|---|
| 1 | Classical ciphers (Caesar, Vigenère) | dcode.fr | chaining ciphers, weakness of substitution, alphabet handling |
| 2 | Web authentication robustness | Apache2, local test lab | why weak passwords fall, and the defences: lockout, rate limiting, MFA |
| 3 | RSA encryption & digital signatures | OpenSSL | public/private key pairs, signing and verification, why key size matters |
| 4 | Hash functions | OpenSSL (MD5, SHA-256/512) | avalanche effect, file integrity, salted password hashing |
| 5 | Steganography | Linux (`cat`, `unzip`) | hiding vs. encrypting data, detecting hidden payloads |
| 6 | Robots Exclusion Standard | public `robots.txt` analysis | controlling crawler access, blocking AI bots, limits of a declarative standard |
| 7 | Web vulnerability scanners | Mozilla Observatory, Qualys SSL Labs, W3C validators | reading a security report, HTTP headers, TLS configuration |
| 8 | System vulnerabilities | Tenable Nessus, Wireshark | host/service scanning, ranking findings by severity, cleartext auth risk |

### What these labs show

Understanding of cryptography fundamentals, reading security-scanner reports, a defence-first mindset
(every weakness paired with its mitigation), and hands-on use of standard tools in an isolated lab.

---

Résumés rédigés avec l’aide d’un assistant IA à partir de mes propres rapports. · Licence MIT
