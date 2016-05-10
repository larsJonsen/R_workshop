Øvelse 1
---------
Brug datsæt Cars93

1. Scaterplot Price vs MPG hvad er usædvanlige ?
2. Lav plot der undersøger datas fordeling, fx Price MPG
3. Lav plot der undersøger datas fordeling relateret til faktorer som fx Origin 
4. Brug aggregate()` til at udregne passende statistik


Øvelse 2
--------

1. Lav en funktion cirkel der tager radius som indput og returnerer omkreds $C = \pi r$
2. Lav en funktion der heder kugle der tager radius som indput og returnerer diameter, omkreds, volume og areal som en liste
3. Lav en funktion der heder kugle2 der tager et data.frame med bla kolonnen radius  og returnerer et data.frame med radius, diameter, omkreds, volume og areal som kolonner
4. Jordens omkreds er 40,000km. Lad os nu lege at funktionen der giver omkredsen er meget kompliceret og ikke kan løses analytisk. Brug i stedet den opskrevne funktion  ion og find den værdi for r der giver en omkreds på 40,000km. Hint: funktionen `uniroot()` bør indgå i løsningen.

Øvelse 3
---------

1. Lav regression på Father-Son datasættet dels med matrix regning dels `lm()
2. plot data og tilføj regression linjen
3. Er sønner højere en deres far?

Øvelse 4
---------

1. Indlæs records.csv. Data for verdensrekorder i løb. Plot `time ~ dist`, prøv at tilføj `log = "xy"` og `col = sex`
2. Lav en linær regression logaritme transformeret data. Hvad viser analysen?
3. Boxplot residualer efter sex resid(m1) ~ records$sex`
4. Lave nye regressioner med sex tilføjet: `+ sex` og `:sex`
5. Undersøg model matrix og se hvad der sker

Øvelse 5
--------

1. Lav et data frame med et y og et x. x skal være 30 tilfældige uniform fordelte tal mellem 1 og 10, y skal være $y = 2 + 3 x + \epsilon$ hvor $\epsilon \sim N(0,\sigma^2)$ og $\sigma=2$
2. lave en linear regression af `y ~ x`g find koefficienter og sigma
3. Tag oveståemde og byg udtræk af tilfældige tal ind i en funktion der tager antallet af rækker i dataframet som argument (med 30 som default) og returnere en vektor med koefficienter og sigma
4. Lave nu et eksperiment hvor forsøge gentages 100 gange og resultaterne gemmes i et data frame.
5. Kan det gøres uden `for` loop?
