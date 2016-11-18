1. Hvað gera eftirfarandi Linux skipanir?
	cd Þetta þýðir change directory og þá hægt að skipta um möppu
	cd ~ fer upp á hæsta drif (drifið sem að git bash er á)
	ls sýnir lista af öllum skrám og möppum í directoryinu sem þú ert í
	pwd sýnir hvaða möppu þú ert í 
	mkdir býr til nýja möppu

	
2. Hvað gera eftirfarandi git skipanir og hvers vegna eru þær gagnlegar?

	git clone   , Kópíar skjöl frá git síðu og færir yfir í current folder sem þú býrð til
	git log   , Sýnir hvaða breytingar hafa verið gerðar, commits.
	git status  hvort að það sé eitthvað inni í geymslunni, repositoryinu.
	git diff   sýnir hvað hefur breyst á milli commits
	git checkout - skiptir um grein og updeitar files í möppunni
    
    3. Hver er munurinn á eftirfarandi git skipunum:
	
	a) git diff    ,  sýnir hvað hefur breyst en ekki enn git addað
	b) git diff --staged , sýnir hvað hefur verið git addað en ekki enn committað
	c) git diff commit1 commit2  sýnir mismun tveggja files,


4. Hvað er version control, hverjir eru helstu kostir við að nota GIT?Version control skráir niður all sem þú gerir og gerir þér kleyft að fara og sækja verkefnið eins og það var á ákveðnum tímapunkti og byrja að vinna í því þar td ef þú gerir fokkar upp. gott að vinna saman, hægt að fara til baka ef villa er gerð


5. Hversu oft telur þú að eigi að gera commit í verkefni, rökstuddu? einusinni fyrir hvern part kanski því þá er hægt að fara til baka þar sem villa var og breyta því.


6. Hvernig eru Working directory, Staging area og Repository frábrugðin í GIT,
   til hvers eru þau? Working directory er ein útgáfa af verkefninu þínu teknar úr git directory og sett á diskinn þinn ef þú villt breyta því.  Staging area er file, sem er í directory þinu og mun tekur niður upplýsingar hvað þú commitar næst 
   
7. Hvenær væri sniðugt að nota branches? Þegar maður fer að vinna í öðru verkefni.