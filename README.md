# Čebelice

## [Koncept pdf](https://github.com/borbregant/cebelice/issues/1)

## TODO

- [ ] vlaga_temperatura not working properly

## Repo structure

- [X] Data collection
  - [X] [Beehive data (weight and diary)](https://zenodo.org/record/4953762)
  - [X] [Weather data](http://rp5.am/Weather_archive_in_Flakkebjerg)

***uvoz.ipynb*** uvozi zgornje datasete in jih spravi v pickle format

- [X] Data cleaning (folder *ciscenje*)

Skripte sprejmejo delno očiščene podatke in jih spet spravijo v format pickle

- ***cebelarski_dnevnik.ipynb***
  Sprejme dataset s težo panja in čebelarski dnevnik ter prilagodi težo glede na spremembe
- ***outlier_removal.ipynb***
  Sprejme dataset s podatki o teži panja in odstrani osamelce (napaka v meritvi, hitra zunanja sprememba, ...)
- ***padavine_sneg.ipynb***
  Work in progress
- ***vlaga_temperatura.ipynb***
  Sprejme dataset s težo panja in notranjo vlago in temperaturo in izračuno suho težo panja. Podatki so slabi (drugi viri ne iz panja ali pa je koda slaba)