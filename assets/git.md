# Grundlagen Git 

## Grundlagenkapitel im Web

<https://git-scm.com/book/de/v2/Los-geht%E2%80%99s-Git-Grundlagen>

## Globale Variablen definieren
```bash
git config --global user.name "Stephan Waldtmann"
git config --global user.email "stephan@waldtmann.de"
```

## Neues Repo anlegen
```bash
git clone <gitlab repo url>
cd <reponame>
touch README.md
git add README.md
git commit -m "add README"
git push -u origin master
```

## Bestehenen Ordner nutzen

```bash
cd existing_folder
git init
git remote add origin <gitlab repo url>
git add .
git commit -m "Initial commit"
git push -u origin master
```

## Bestehendes Git Repo nutzen

```bash
cd existing_repo
git remote rename origin old-origin
git remote add origin <gitlab repo url>
git push -u origin --all
git push -u origin --tags
```

## An einem gemeinsam genutzen Repo arbeiten
```bash
git pull
<Dateien ändern>
git add .
git commit -m "<Beschreibung der Änderungen>"
git push -u origin master
```


