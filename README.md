# Article 1, Tips for git and web development

## 1. Use a visual git environment
Most web developers I know have used git at one point or another, but most still use the command line. This has always left me to scratch my head, while the command line is certainly usable, it's a lot of extra work. You have to remember all the different commands, and you have to type it out yourself, which is prone to errors. 
This is why I recommend a GUI client, the most popular tools currently are, SourceTree, Gitkraken and Github Desktop. All of these work for both windows and MAC.

My personal favorite is SourceTree so I'll show you some example and features and how it's an improvement to the commandline. 
### 1. visual branches
![image](https://github.com/mordock/weekly-nerd-1920/blob/master/docs/img/Screenshot_1.png)
Tools such as SourceTree visualise your branches and give your a clear layout of who did what and where. This is especially usefull if you team has a git master who is in charge of things such as merging. 
This also allows you to easily switch to different branches/commits and back.

### 2. build in merge conflict tools
![image](https://github.com/mordock/weekly-nerd-1920/blob/master/docs/img/sourcetree-conflict-02.jpg)
When merging or pulling changes from others, it's always such a pain in the behind when you get merge conflicts. This pain is severely dampend when with the click of 2 buttons you can tell git to use either your or their version without having to go searching through the code. This saves a lot of time(especially at the end of the day when you want to go home).

### 3. actual buttons
![image](https://github.com/mordock/weekly-nerd-1920/blob/master/docs/img/Screenshot_2.png)
When you want to commit, fetch, push, pull or almost any git command, there is a button for it. You dont have to type or remember the specific command or branches. All you need to do is press the correct button and select the right branches, and maybe type a commit message. 

### 4. possible drawbacks
One common argument I hear for the use of the command line is the fact that it's more powerful. This is true, if you only compare the interface to the commandline. There are a few commands the interface cannot do or doesn't support. However, you are not forced to only use the interface when you decide to use it. All of these programs have a terminal build in, if you ever need one. So use the easier interface until you have to switch. Which for most developers will only be 5-10 percent of the time. 

## 2. Establish clear rules and promote someone to git master
This may seem like 2 points, but they're very similair. At the start of a new project it's a good idea to call together all developers and set up some rules. These can be things such as, never make changes directly on the master, make sure at least one other person tests your changes to make sure you didn't miss anything and who is allowed to merge branches.  
This is were the git master comes in, he is to make sure these rules are adhered to and understood. The git master might have some special privileges such as being allowed to make changes to the master branch.  
All of this is based on what you decide to do as team. If you work in a team which is very experienced with git, the git master can take it easy and let the team guide themselves. If not, he'll need to do a lot of work making sure everybody is up to speed and that changes are regularly merged together.  

With the rules in place and a git master chosen, one more important decision will need to be made. Is your team going to work feature based or developer based? So what does that mean? Feature based mean that per feature you will make a new branch, and discard is when you're done. Developer based mean that every developer has one branch where he/she will be working on.   
Both of these methods have their advantages, feature based give you a very clear list of things which has been done, you can simply check which features have already been merged. However this method can become quite cluttered if not propperly mananged.  
Developer based is usually a bit faster and allows you to and is more git beginner friendly. On the other hand you can quickly lose the overview over what has and hasn't been done yet. Because of this the git master will need to be a little more involved into what everybody is doing to make sure time isn't lost.  

## 3. commit as much and as often as possible
During web development things change quickly and several decisions are made every day. This is why it's a good idea to commit your changed as ofteh as possible. This allows you to go back to a certain state if features need to be changed, added or removed.  
This also gives you and the git master a clear overview over what has been completed and what still need to be done. With this point also comes the tip to always write consise and clear commit messages. The next day the message "update to page" might still say something, but after a few week this will have lost all its meaning. At the same time you need to make sure you don't write an assay everytime you write a commit message, find that right balance for you and your team.

That concludes this article, hopefully you learned some usefull tips for using git.

## Resources
 - https://github.com/StefanGerrits2/Lyvup-prototype/blob/master/GitRules.txt
 - https://www.sourcetreeapp.com/

# Weekly Nerd @cmda-minor-web · 2019-2020

Elke week is er op woensdagmiddag de Weekly Nerd: 
Workshops, praatjes en lezingen van bedrijven en designers over het vakgebied. Nerd alert.

## Leerdoelen
- Kennismaken met het beroepenveld
- Orienteren op het vakgebied
- Vakgerelateerde artikelen leren schrijven

## Werkwijze
Elke week wordt er een presentatie gegeven door iemand uit het vakgebied. 
Dit proberen we zo veel mogelijk bij bedrijven te organiseren. 
Zo krijg je een goed beeld van het vakgebied en krijg je contacten in het werkveld. 
Dat kan handig zijn voor als je een afstudeerstage zoekt, of een afstudeeropdracht. 


Van iedere presentatie maak je **sketch-notes / aantekeningen** die je op een blog verzamelt. 
Schrijf ook altijd een link-lijstje met (interessante) onderwerpen die aan bod zijn gekomen.
3 keer schrijf je een uitgebreid artikel over een relevant onderwerp. 
Bijvoorbeeld een eigen onderzoek naar een techniek of een (technische) analyse van een website die in een Weekly Nerd is behandeld. 
Zorg voor juiste verwijzingen, bronvermelding en goede leesbare teksten. 
Engels wordt aangeraden.  

Tip: Fork deze repo en publiceer je blog via GitHub Pages!


## Criteria
Er wordt van je verwacht dat je alle Weekly Nerds bijwoont. 
Je mag niet meer dan 1 Weekly Nerd missen. 
Als je meer dan 1 Weekly Nerd mist dan krijg je een vervangende opdracht.

Je blog met de verslagen en artikelen moet voor de laatste week van de Meesterproef ingeleverd zijn.


### Voorbeelden van voorgaande jaren

* https://medium.com/@vincentkempers_/functional-light-programming-helped-me-a-lot-99856a9ac0ff
* https://codepen.io/servinnissen/post/plan-then-code
* https://github.com/Jamerrone/weekly-nerd-blog/blob/master/articles/article-3.md
* https://github.com/muise001/Weekly_Nerd#bruce-lawson---w3c-over-webstandards
* https://medium.com/@vincentkempers_/my-experience-at-nlhtml5-x-cssday-df855997a191


## Programma

### Workshops, praatjes en lezingen


| Datum  |  Wat/Wie | Waar  | Link | 
|---|---|---|---|
| 13 Februari  | Hidde de Vries - Toegankelijkheid en CSS expert bij W3C  | BPH 01B11  |   |
|   |   |   |   |   |




