# **szia uram verziókezelés**
- helyi repo inicializálása
	> git init
- megadjuk a github felhasználó nevünket és email címünket
	> git config user.name

	> git config user.email
- ellenőrzés (van-e különbség a repo és a munkakönyvtár közt)
	> git status
- előkészítjük a helyi repoba való eltárolásra a fájlokat commit-olásra (a verzió beindexelése megtörténik)
	> git add .
- ellenőrzés
	> git status
- commit lmao
	> git commit -m "desc"
- ellenőrzés már megint
	> git status
- összes verzió megjelenítése
	> git log
- távoli repo létrehozása (Github)

- helyi repo és távoli repo összekapcsolása
	> git remote add origin https://token@github.com/username/reponame.git
- **első** push alkalmával meg kell adni melyik ágba (branch) kerüljön
	> git push -u origin main
- token bemásolása
- ezutáni módosításoknál
	> git push