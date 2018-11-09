# moment2
 
### Automatiserings-processens syfte är ###
Få så minifierade filer som möjligt, filerna tar mindre plats och onödig kod utesluts. 
Man kan lätt arbeta med andra på en onlineserver och ser omedelbart när andra gjort ändringar i koden.

### Paket och verktyg som använts ### 
NPM installation av Gulp - paketet.
**De paket som används för automatisering är:** 
* gulp-clean-css 
* gulp-concat 
* gulp-imagemin
* gulp-uglify
* gulp-watch 


**Verktyg:** Visual Studio Code, Kommandotolken, samt git och Github för uppladdning. 

### Systemet, tasks och hur det startas ###

Systemet är uppbygt med en mapp som heter src och innehåller samtliga filer för webbplatsen, dvs. HTML, CSS, JS och images. 
Den har även en fil som heter gulpfile.js och innehåller alla tasks för att minifiera och sätta ihop filerna som då hamnar i mappen "pub" med diverse namn för de filer där koden som blivit sammanslagen och minifierad hamnar. 

För att starta upp gulp-filerna: 
Spara filerna i en mapp på skrivbordet. 
Gå in i en kommandotolken. 
skriv in cd Desktop - enter 
cd MAPPNAMN - enter 
gulp - enter 

Sen är du igång! 
