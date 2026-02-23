# Cloud Portfolio – Alain Appart

> Junior Cloud / Systems Engineer | AWS | Linux | Tanger, Maroc

Site en ligne : http://15.236.40.11

---

## Architecture du projet
---

## Services AWS utilisés

| Service | Rôle |
|---|---|
| EC2 (Amazon Linux 2023) | VM Linux dans le cloud, héberge le site via Apache |
| Apache (httpd) | Serveur web qui sert les fichiers HTML |
| AWS Lambda (Python 3.12) | Fonction serverless – incrémente le compteur de visites |
| DynamoDB | Base de données NoSQL – stocke le compteur |
| Function URL | URL HTTPS publique exposant la Lambda |
| IAM | Gestion des permissions Lambda → DynamoDB |
| Security Groups | Contrôle des accès réseau (ports SSH/HTTP) |

---

## Ce que j'ai fait

- Déploiement d'une instance EC2 Amazon Linux 2023 sur AWS (région eu-west-3 Paris)
- Configuration d'un Security Group (ports 22 et 80)
- Connexion SSH depuis Windows 11 (PowerShell + clé .pem)
- Installation et configuration d'un serveur web Apache
- Création d'une table DynamoDB `portfolio-visits`
- Développement d'une fonction Lambda Python avec gestion CORS
- Exposition de la Lambda via une Function URL HTTPS
- Intégration du compteur de visites en JavaScript (fetch API)
- Configuration d'une alerte de facturation AWS à 1$

---

## Compétences démontrées

- Administration Linux (Amazon Linux 2023)
- Gestion des services systemd (Apache)
- Architecture serverless AWS (Lambda + DynamoDB + Function URL)
- Débogage CORS (headers HTTP, conflits multi-sources)
- Sécurité AWS (IAM roles, Security Groups, permissions)
- HTML/CSS/JavaScript (fetch API, DOM manipulation)

---

## Roadmap

- [ ] Nom de domaine + HTTPS (Let's Encrypt / ACM)
- [ ] Infrastructure as Code (Terraform)
- [ ] CI/CD pipeline (GitHub Actions)
- [ ] Certifications AWS (Cloud Practitioner → Solutions Architect)

---

*Projet réalisé en autonomie avec assistance IA pour accélérer l'apprentissage des services AWS.*
