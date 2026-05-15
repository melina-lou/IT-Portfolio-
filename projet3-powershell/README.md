# Projet 3 – Script PowerShell (services arrêtés)

## Français

### Objectif
Écrire un script simple qui aide un technicien à voir rapidement quels services Windows sont arrêtés.

### Ce que j’ai fait
Le script fait une seule chose : il récupère la liste des services, filtre ceux qui sont à l’état `Stopped`, et exporte le résultat dans un fichier CSV (Excel).

```powershell
# Récupère tous les services, garde seulement ceux qui sont arrêtés
Get-Service | Where-Object { $_.Status -eq 'Stopped' } | 
Export-Csv -Path "C:\temp\services_stoppes.csv" -NoTypeInformation

J’ai ajouté des commentaires pour expliquer chaque ligne (même si c’est simple). Ensuite j’ai testé sur mon ordinateur.

Ce que j’ai appris
La différence entre Get-Service et Get-Process.

Comment utiliser Where-Object pour filtrer.

Exporter en CSV, ce qui permet d’ouvrir le résultat dans Excel.

Si j’avais plus de temps
Je ferais une version qui accepte un nom d’ordinateur en paramètre (-ComputerName) pour interroger une machine distante.

Compétences démontrées
PowerShell (bases)

Filtrage et export de données

Commenter du code

Preuves
Le script Get-ServicesStopped.ps1 dans ce dossier.

Capture d’écran du résultat (console + CSV).

English Summary
Goal: Write a PowerShell script to list stopped Windows services and export to CSV.

Code: Get-Service | Where-Object Status -eq 'Stopped' | Export-Csv ...

Learned: Filtering with Where-Object, exporting to CSV, commenting code.

Skills: PowerShell basics, automation, documentation.

Proofs: Script file, screenshot of output.
