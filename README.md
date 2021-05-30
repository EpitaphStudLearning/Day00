# Day00

Piscine Shell &amp; Python, It Akademy parcours Testeur Logiciel 2021
---

### Exercice 00

Cette archive contient des images de planètes réelles et fictives. Une fois que tu auras extrait ses fichiers, tu vas utiliser ton terminal pour remettre de l'ordre.
Voici le rendu attendu pour cet exercice : 

Créer trois répertoires dans le dossier planets : 
  * Real
  * Star Wars  
  * Star Trek
 
Créer deux sous répertoires pour le répertoire Real :
  * Telluriques 
  * Gazeuses

Avoir un fichier commands.txt se trouvant dans Day00/ex00/Planets contenant l'historique des commandes effectuées sous le terminal pour effectuer le rangement.

---

### Exercice 01 

Tu trouveras un fichier alumni.csv, ce fichier contient la liste des anciens élèves en fonction de leur ville, du pays, de l'année d'étude et du language de programmation.
  Créer les fichiers suivants :
   * php_france_2019.csv qui contiendra uniquement le nombre d'alumnis ayant fait du PHP en france, en 2019.
   * javascript_biarritz_toulouse.csv qui contiendra uniquement les alumnis ayant fait du JavaScript, sur les campus de Toulouse et Biarritz.
   * david.csv qui contiendra le nombre de toutes les personnes qui portent David en prénom ou en nom.

---

### Exercice 02

Créer un script qui salue un utilisateur, lui demande son prénom, et lui retourne une salutation en fonction de son prénom pris en paramètre. 

Le script devra avoir le nom suivant "bonjour.sh" .
Devra avoir le retour suivant : 

```
$ ./bonjour.sh 
Bonjour, quel est vôtre prénom ? 
{votre prénom}
Bonjour, {votre prénom} !
```

---

### Exercice 03

Placer dans un fichier  midLS la ligne de commande à taper pour lister les fichiers et les répertoires du répertoire courant, mais pas les fichiers cachés, ni '.' ni '..' (rien ne commençant par un point), séparés par des virgules, triés par date de création et de manière à ce que les répertoires soient suivis d'un caractère slash.

---

### Exercice 04

Créer un script shell nommé git_commit.sh qui renvoie les id des 5 derniers commit de votre dépot git.

le résultat devra être le suivant  : 

```bash
$ bash git_commit.sh | cat -e
490adecc778850161dae36d1b0b503abce83c171$
43ccb1031df2b92d557c3ab48a9a2f4ffff66690$
8cae02c5e98085b32c02303d4d7d90df9a1744fa$
225b0cfbc55030edda98e4134d9ed6683e31f16f$
2df0de72259517a23210a073814fab14a0265e32$

$
```


