- Klonen: **git clone** <URL>
- Branch wechseln: **git checkout** <branch>
- Alle geänderten, gelöschten oder hinzugefügten Dateien stagen: **git add --all**
- Commit (lokal): **git commit -m** <msg>
- Änderungen vom Server holen: **git fetch -p**
- Abgefragte Änderungen vom Server mergen: **git merge --ff-only**
  - Bei Fehlschlag (Fast-Forward nicht möglich): **git rebase**
  - Bei Merge-Konflikten: **git mergetool**
- Zum Server pushen: **git push**

