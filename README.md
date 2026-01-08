# LM-Tools
Outils informatiques et documentations diverses

## Structure du Répertoire

Ce répertoire est organisé par plateforme cible afin d'offrir une navigation plus claire et intuitive.

### Outils pour Linux (`/linux`)

Outils et scripts conçus pour les systèmes Linux :

- **`linux/scripts_shell/`** - Scripts Shell (bash, sh, etc.)
- **`linux/python/`** - Scripts Python et outils pour Linux

### Outils pour Windows (`/windows`)

Outils et scripts conçus pour les systèmes Windows :

- **`windows/fichiers_batch/`** - Fichiers Batch (.bat, .cmd)
- **`windows/scripts_powershell/`** - Scripts PowerShell (.ps1)
- **`windows/python/`** - Scripts Python et outils pour Windows

## 🛠️ Outils Disponibles

### Script de Maintenance Windows 10/11

Un script PowerShell sécurisé pour effectuer des opérations de maintenance système sur Windows 10 et Windows 11.

**Fichiers :**
- `Windows-Maintenance.ps1` - Script PowerShell principal
- `Lancer-Maintenance.bat` - Lanceur simple pour faciliter l'exécution
- `README-Windows-Maintenance.md` - Documentation complète

**Fonctionnalités :**
- ✅ Nettoyage des fichiers temporaires
- ✅ Nettoyage de disque Windows
- ✅ Vérification des fichiers système (SFC)
- ✅ Réparation de l'image système (DISM)
- ✅ Vérification de Windows Update
- ✅ Journalisation complète de toutes les opérations
- ✅ Menu interactif avec plusieurs modes de fonctionnement

**Utilisation Rapide :**
1. Téléchargez les fichiers
2. Double-cliquez sur `Lancer-Maintenance.bat` OU
3. Exécutez `Windows-Maintenance.ps1` dans PowerShell en tant qu'administrateur

📖 **[Voir la documentation complète](README-Windows-Maintenance.md)**

## Guide de Migration

### Pour de Nouvelles Contributions

Lorsque vous ajoutez de nouveaux outils ou scripts, placez-les dans le bon répertoire selon :
1. **Plateforme cible** : Choisissez `/linux` ou `/windows`
2. **Type de script** : Choisissez le sous-répertoire correspondant selon le langage de script/technologie

### Transition depuis une Structure Précédente

Si vous travaillez avec une version antérieure de ce répertoire ayant une structure différente, voici le mappage des anciens répertoires vers les nouveaux :
- `windows/Batch/` → `windows/fichiers_batch/`
- `windows/PowerShell/` → `windows/scripts_powershell/`

#### Étapes de Migration :
1. Déplacez vos scripts batch de `windows/Batch/` vers `windows/fichiers_batch/`
2. Déplacez vos scripts PowerShell de `windows/PowerShell/` vers `windows/scripts_powershell/`
3. Placez les scripts Python dans le répertoire approprié à la plateforme :
   - Scripts Python pour Linux → `linux/python/`
   - Scripts Python pour Windows → `windows/python/`
4. Mettez à jour toute documentation ou référence pointant vers les anciens chemins.

## Contributions

Lorsque vous contribuez à ce répertoire :
1. Placez vos scripts dans le bon répertoire lié à la plateforme et à la technologie.
2. Ajoutez une brève description ou commentaire expliquant à quoi sert votre script.
3. Suivez les conventions de nommage utilisées dans chaque répertoire.
4. Mettez à jour les fichiers README pertinents si vous ajoutez des fonctionnalités importantes.

## Utilisation

Chaque répertoire contient son propre README avec des informations spécifiques sur les outils qui s'y trouvent. Veuillez vous référer à ces fichiers README pour des instructions détaillées sur l'utilisation.

## 📋 À Propos

Ce dépôt contient divers outils informatiques et documentations développés par LM-Tools pour faciliter la maintenance et la gestion des systèmes.
