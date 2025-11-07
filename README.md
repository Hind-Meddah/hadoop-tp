# TP Hadoop avec Docker

## Objectif
Mettre en place un cluster Hadoop avec Docker et manipuler HDFS.

## Structure du projet
- `docker-compose.yml` : Configuration des conteneurs (1 master, 2 slaves)  
- `shared_volume/` : Contient les fichiers `purchases.txt`, `alice.txt`, `achat.txt`  

## Instructions pour lancer le TP

1. Installer Docker et Docker Compose
2. Placer les fichiers dans `C:\hadoop_project\shared_volume`
3. Lancer les conteneurs :

```bash
docker compose up -d
