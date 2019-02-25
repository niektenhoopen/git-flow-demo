# Git flow demo

![img](https://wac-cdn.atlassian.com/dam/jcr:b5259cce-6245-49f2-b89b-9871f9ee3fa4/03%20(2).svg?cdnVersion=lb "Gitflow (Atlassian)")

## Configuratie ##

Stap 1: (alleen de admin van een team)

Maak **per team** een fork van deze repository (op Github, rechtsbovenin het scherm) Deze fork wordt de repository die je als groep gaat gebruiken voor de volgende opdrachten.

Stap 2: (alleen de admin van een team)

Ga naar **settings** van de fork-repository, en dan naar **branches**.
Stel onder **protection rules** voor de "master" branche in dat er altijd een pull request nodig is en dat dit ook voor administrators geldt.

Stap 3: (alleen de admin van een team)

Voeg je teammembers toe als collaborators van het team


## Opdrachten ##

Hulpmiddelen:

[Using branches tutorial van Atlassian](https://cs.atlassian.com/git/tutorials/using-branches)

Branches:

- Overzicht branches:
```git branch```
- Branch toevoegen: ```git branch blabla```
- Wisselen naar ‘blabla’ branch: ```git checkout blabla```
- Alles in 1x: (deze maakt een branch aan en wisselt er naartoe) ```git checkout -b blabla```
- Alle branches bekijken: (incl remote) ```git branch -a```


Pushen:

- Pushen doe je naar je eigen branch: ```git push origin blabla```

Weergeven tree:

- De ‘tree’ weergeven in de command line: ```git log --graph --all```
- Of one-line: ```git log --graph --oneline --all```



#### Opdracht 1: We missen families! ####

Voeg de volgende families toe:

- [Griffin (Family Guy)](https://en.wikipedia.org/wiki/Griffin_family)
  - Peter
  - Lois
  - Meg
  - Chris
  - Stewie
  - Brian
- [Dunphy (Modern Family)](https://en.wikipedia.org/wiki/List_of_Modern_Family_characters)
  - Phil
  - Claire
  - Haley
  - Alex
  - Luke
- [Pritchett-Delgado (Modern Family)](https://en.wikipedia.org/wiki/List_of_Modern_Family_characters)
  - Jay
  - Gloria
  - Manny
  - Joe
  - Stella
- [Tucker-Pritchet (Modern Family)](https://en.wikipedia.org/wiki/List_of_Modern_Family_characters)
  - Mitchel
  - Cameron
  - Lily
  - Larry

#### Werkwijze: ####

- Per familie een eigen feature branch
- Per familie 1 overzichtspagina (zie Simpson/Duck familie)
- Per familielid 1 html bestand (gelinkt vanaf de familiepagina)
- Op de index.html moet een link naar de familie komen
- Klaar? Push de feature branch naar Github en maak een pull request aan om het in de master te zetten.

### LET OP: ###
*Het zou kunnen dat Github bij het aanmaken van een pull request in eerste instantie voorstelt om het naar niektenhoopen/git-flow-demo:master te mergen. Pas dit aan naar de master branch van je fork repository*


#### Opdracht 2: Familie "Duckf?" ####
Er zitten fouten in de namen van de Duck familieleden. Corrigeer de fouten.

#### Werkwijze: ####
- Per familie een eigen feature branch.
- Per correctie (dus per familielid) 1 commit binnen de feature branch.
- Klaar? Push de feature branch naar Github en maak een pull request aan om het in de master te zetten
