# git_voor_jonge_tieners

Branch|[![Travis CI logo](pics/TravisCI.png)](https://travis-ci.org)
---|---
`master`|[![Build Status](https://travis-ci.org/richelbilderbeek/git_voor_jonge_tieners.svg?branch=master)](https://travis-ci.org/richelbilderbeek/git_voor_jonge_tieners)

Lesmateriaal om git te leren, geschreven voor jonge tieners

## Video's

Onderwerp|YouTube   |Download
---------|----------|--------
git basis|[hier](https://youtu.be/lzIYHH5JbmM)|[hier](http://richelbilderbeek.nl/git_voor_jonge_tieners.ogv)
Een nieuwe branch maken|[hier](https://youtu.be/XXQQjDQS0p4)|[hier](http://richelbilderbeek.nl/git_voor_jonge_tieners_branch_maken.ogv)
git merge|[hier](https://youtu.be/hXiwmCwcwko)|[hier](http://richelbilderbeek.nl/git_merge.ogv)
Processing game op GitHub zetten|[hier](https://youtu.be/tNtuRKjH2Fc)|[hier](http://richelbilderbeek.nl/git_voor_jonge_tieners_processing_game_op_github_zetten.ogv)
Qt Creator game op GitHub zetten|[hier](https://youtu.be/QkNzsjmoV_U)|[hier](http://richelbilderbeek.nl/git_voor_jonge_tieners_cpp_game_op_github_zetten.ogv)

## Wat is `git`?

`git` is een versiebeheersysteem.

## Wat is versiebeheersysteem?

Een versiebeheersysteem houdt de geschiedenis bij van alle veranderingen.
Iedere keer als iemand wat verandert, houdt `git` dat bij.
Hierdoor kun je altijd terug gaan naar eerdere versies.

## Werkwijze `git`

Hier een overzichtje:

 * `0.` instellen wie je bent (een keer per computer)
 * `1.` `git clone`: klonen van de repo
 * `2.` `git add` en `git commit`: jouw veranderingen opslaan
 * `3.` `git push`: jouw code delen met de rest
 * `4.` `git pull`: jouw code updaten met het werk van de rest
 * `5.` `git status`: kijken op welke branch je zit
 * `6.` `git checkout richel`: ga naar jouw branch
 * `7.` `git merge develop`: merge develop naar jouw branch

Hieronder wordt het preciezer uitgelegd.

![git basis](git_basis.png)

Je kunt ook een video bekijken: [YouTube](https://youtu.be/lzIYHH5JbmM), [download](http://richelbilderbeek.nl/git_voor_jonge_tieners.ogv)

## 0. instellen wie je bent

Om de vorige persoon weg te halen (op Windows):

 * Klik op de Windows toets, type 'Referentiebeheer'

![](referentie_beheer.png)

 * Klik op 'Windows Credentials'
 * Zoek 'GitHub' en doe daar 'Verwijderen'


Om in te stellen wie je bent:

Doe in 'Git Bash':

```
git config --global user.name "richelbilderbeek"; git config --global user.email "richel@richelbilderbeek.nl"
```

 * Vul inplaats van `richelbilderbeek` jouw GitHub naam in
 * Vul inplaats van `richel@richelbilderbeek.nl` jouw emailadres naam in

Om uit te vinden wie `git` denkt dat je bent:

```
git config --global user.name; git config --global user.email
```

## 1. `git clone`: klonen van de repo

In een terminal of in Git Bash, type:

```
git clone https://github.com/richelbilderbeek/djog_nanos_2018
```

Nu wordt er een map/folder/directory aangemaakt met de naam `djog_nanos_2018`.

Om in die map te gaan (en dat wil je!), doe je:

```
cd djog_nanos_2018
```


## 2. `git add` en `git commit`: jouw veranderingen opslaan

In de folder `djog_nanos_2018` doe je:

```
git add --all :/
git commit -m "Iets keislims"
```

## 3. `git push`: jouw code delen met de rest

In de folder `djog_nanos_2018` doe je:

```
git push
```

Als `git` een error geeft, update dan eerst jouw code (stap 4, hieronder).

## 4. `git pull`: jouw code updaten met het werk van de rest

In de folder `djog_nanos_2018` doe je:

```
git pull
```

## 5. `git status`: kijken op welke branch je zit

![](git_branches.png)

```
git status
```

## 6. `git checkout richel`: ga naar jouw branch



In de folder `djog_nanos_2018` doe je:

```
git checkout richel
```

om naar de branch van Richel te gaan. Vul in plaats van `richel` jouw voornaam
in (in enkel kleine letters).

De belangrijkste andere branch:

```
git checkout develop
```

Op `develop` staat de nieuwste versie om onze code.

:warning:: vergeet niet `git pull` te doen 

## 7. `git merge develop`: merge develop naar jouw branch

In de folder `djog_nanos_2018` doe je, als je op jouw branch zit:

```
git merge develop
```

:warning:: `develop` moet geupdate zijn

## Links

 * [C++ voor jonge tieners](https://github.com/richelbilderbeek/cpp_voor_jonge_tieners)
 * [Learn git branching](https://github.com/pcottle/learnGitBranching)

