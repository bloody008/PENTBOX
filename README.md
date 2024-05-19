# La PENTBOX
## 🔍 À propos
Voici mon projet d'étude, une toolbox automatisée qui est conçue pour automatisée les tests d'intrusion. Développée en Python, elle permet de suivre la méthodologie des tests d'intrusion. La toolbox à été pensée de la manière suivante : 
Un pentesteur a toujours une distribution avec ses outils les plus utilisés, ou les plus populaires dans le domaine. Ce sont ces outils qui sont utilisés dans la toolbox pour chaque phase de test.

Bien qu'elle soit incomplète je compte bien l'améliorer dans le temps !

Bonne lecture.

![alt txt](https://gifdb.com/images/high/happy-jonah-hill-prw5obdo8pxp11p9.gif)

------------------

## 📋 Table des matières

- [🔍 À propos](#-à-propos)
- [📋 Prérequis](#-prérequis)
- [🚀 Installation](#-installation)
- [🛠️ Utilisation](#utilisation)
- [🏗️ Construit avec](#construit-avec)
- [📜 Licence](#licence)
------------------

## 📋 Prérequis
Pour faire fonctionner ce projet, vous aurez besoin des éléments suivants :

- Python 3.7+ 🐍 : Langage de programmation principal.
- pip : Gestionnaire de paquets pour Python.
- Git 🐙 : Logiciel de gestion de versions.
- Les outils mentionnés dans les fichiers de commande (PhasedeReconnaissance.txt), (ExploitPostExploit.txt), (PasswordAttack.txt) et (PasswordAnalysis.txt).
- Distribution Kali Linux  🐉 : Pour avoir la majorité des outils préinstallés (optionnel).

------------------

## 🚀 Installation
```bash
# Cloner le dépôt
git clone https://github.com/bloody008/PENTBOX

# Aller dans le répertoire du projet
cd PENTBOX
```

------------------

## 🛠️ Utilisation
Pour utiliser la toolbox, suivez ces étapes :

```bash
# Lancer l'outil
python3 toolexecute.py
```
La boîte de dialogue apparaît ensuite, avec des paramètres à entrée :

* l'adresse IP et l'url cible
* le nom d'user
* le mot de passe

L'user et mot de passe sont optionnels et utile pour la phase d'exploitation, par contre l'ip et l'URL fonctionne l'une avec l'autre. Utiliser qu'un paramètre ferait bug la boîte de dialogue.

------------------

## 🏗️ Construit avec
Langages & Frameworks
Python : Langage principal de développement. [Documentation 📃](https://www.python.org/doc/)

------------------

## Licence 📜
Voir le fichier [LICENSE](LICENSE) du dépôt.
