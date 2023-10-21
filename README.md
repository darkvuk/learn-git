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

Priprema fajlova za sljedeci commit (Staging)
> git add .

Commit (Kod je samo sacuvan lokalno)
> git commit -m "NASLOV" -m "OPIS"

Push
> git push origin main

Promijeni branch
> git checkout NAZIV
>
> git checkout main

Prikazi razliku izmedju brancheva (npr. na mainu)
>> git diff NAZIV_DRUGOG_BRANCHA