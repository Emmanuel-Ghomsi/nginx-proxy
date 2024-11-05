# Nginx Reverse Proxy avec SSL Automatisé

Ce projet configure un reverse proxy Nginx pour héberger plusieurs applications sur un VPS avec des certificats SSL gratuits et renouvelables de Let's Encrypt. Ce n’est pas un projet de développement, mais une configuration utilisée en production.

## Fonctionnalités
- Proxy inverse pour gérer le trafic vers plusieurs applications.
- Certificats SSL automatiques via Let's Encrypt et renouvellement automatique.
- Gestion simplifiée de plusieurs domaines avec Nginx-proxy et acme-companion.

## Prérequis
- Docker et Docker Compose installés.
- Un domaine avec les sous-domaines configurés pour pointer vers le serveur.

## Notes
- Nginx-proxy : Gère le routage du trafic.
- Docker-gen : Met à jour dynamiquement les configurations Nginx.
- Let’s Encrypt Companion : Crée et renouvelle les certificats SSL automatiquement.