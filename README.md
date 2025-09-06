# Rainmeter OpenAPI Actions

Spécifications OpenAPI pour actions utiles à la création de skins Rainmeter.
# Rainmeter OpenAPI Actions

Ce dépôt contient une spécification **OpenAPI 3.1** unique (`rainmeter_actions.yaml`) qui regroupe trois actions pour un assistant GPT spécialisé dans **Rainmeter**.

## Actions disponibles

- **runCode** → Exécuter un snippet court (Python, PowerShell, Batch) et récupérer `stdout`, `stderr`, `exitCode`.  
- **fileGen** → Générer/écrire un fichier texte (.ini, .lua, .txt, etc.) et obtenir son `sha256`.  
- **searchDocs** → Rechercher dans la documentation Rainmeter (sitemaps docs/forum) et renvoyer une liste d’URLs.

## URL RAW à importer dans GPT

```text
https://raw.githubusercontent.com/eLnoVateur/rainmeter-openapi-actions/main/rainmeter_actions.yaml
