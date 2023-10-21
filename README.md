# Tutorial

## Pocetak
- Kreiraj repozitorijum na Githubu
- Kreiraj README.md fajl

# Dio 1
Preuzima sadrzaj iz zeljenog repozitorijuma
> git clone https://github.com/darkvuk/learn-git.git

Udji u direktorijum
> cd learn-git

Prikazuje fajlove koji su izmijenjeni, kreirani ili obrisani
> git status

Priprema fajlova za sljedeci commit (Staging) - SAMO AKO FAJL NE POSTOJI
> git add .

Opozovi staging
> git reset
> git reset IME_FAJLA
> git reset HEAD~1

Commit (Kod je samo sacuvan lokalno) 
> git commit -m "NASLOV" -m "OPIS"
> git commit -am "NASLOV" -m "OPIS"

Push
> git push origin main

Pogledaj aktuelne brancheve
> git branch

Promijeni branch
> git checkout NAZIV
>
> git checkout main

Prikazi razliku izmedju brancheva (npr. na mainu)
> git diff NAZIV_DRUGOG_BRANCHA

Push branch na Github
> git push --set-upstream origin feature1

* Na Githubu odraditi merge na master

Updatuj kod na najnovije stanje
> git pull

Obrisi branch
> git branch -d NAZIV

Opozovi commit
> git reset HASHCODE
> git reset --hard HASHCODE