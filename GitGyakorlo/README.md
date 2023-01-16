# Verziókezelés alapjai

## 1. Git letöltése

- [git for windows](https://gitforwindows.org/)
- [git scm](https://gitscm.com/)
  ## 2. Konfig parancsok
  - git config --global user.name prumullertamas
  - git config --global user.email
  - git config --global credential.helper wincred

## 3. Repo létrehozása

- git init

## 4. Állomány hozzáadása a stage-hez (staging area)
>A stagen lévő állományokról tudunk állapotfelvételt (commit) készíteni.
>Üres mappa nem kerül a stage-re
- git add állomány_neve
- git add . (összes állomány és mappa hozzáadása)
## 5. Állapotfelvétel (commit) készítése
- git  commit -m "commit message"
## 6. Git állapot és log lekérdezése
- git status
- git log
## 7. Lokális változások feltöltése a távoli repoba
- git push
## 8. Távoli repo másolása (klómozása) a lokális repoba
- git clone "távoli repo URL címe"
## 9. Ágak (branches) kezelése
> Lokális ágak listázása
- git branch
> Lokális és távoli ágak listázása
- git branch -av
> Ág létrehozása (-b és váltása)
- git branch újágneve
> Váltás egy másik ágra
- git checkout másikágneve
> Ág törlése
- git branch -d törlendőágneve (aktuális ágat nem lehet)
> Változások átvezetése (merge)
- git checkout
- git merge
## 10. Távoli repo változásainakk letöltése a lokális gépre
- git fetch origin
- 