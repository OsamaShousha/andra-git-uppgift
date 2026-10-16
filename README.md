# Fråga 1:
## Versionshantering vs vanliga filer:
### Tidslinje av ögonblicksbilder: 


         **  
         - Git skapar en tidslinje av commits.En commit är en ögonblicksbild av projektets sparade innehåll, inte bara en kopia av en enskild ändring. Git lagrar dessutom data effektivt genom att återanvända objekt när innehåll är oförändrat. Varje commit är en sparad version av projektets innehåll vid en viss tidpunkt. En commit innehåller också information som ett unikt ID, ett commit-meddelande och vem som gjorde ändringen.

         - När jag klickar på min första commit på GitHub och fortfarande ser alla tre TODO i koden, trots att filen på min dator har ändrats, visar det att Git bevarar tidigare versioner. Den första committen har inte skrivits över av mina senare ändringar. I stället har jag skapat nya commits som visar hur projektet har utvecklats steg för steg. Därför kan jag jämföra versionerna och förstå vad som ändrades mellan dem.

          **

# Fråga 2:
## Arbetsytan, Staging och Commits
### Kommandona i Git
    1- git status:
      ** 
      visar vilka filer som har ändrats, vilka som är staged och vilka som inte spåras av Git
      ***
    2- git add:
    **
    väljer vilka ändringar som ska ingå i nästa commit.
     **

    3- git commit :
    ** 
    sparar de staged ändringarna som en ny version i Git-historiken.
    **

    - ** 
        Jag tänker på arbetsytan som ett ark på skrivbordet där jag gör ändringar i filerna. Med git add lägger jag de ändringar jag vill spara i ett kuvert, vilket motsvarar staging, och med git commit lägger jag dem i arkivlådan, som representerar Git-historiken. Om jag ändrar en fil men kör git commit utan att först köra git add, kan Git svara no changes added to commit eftersom inga av de nya ändringarna har valts till staging. Därför kontrollerar jag ändringarna med git status och git diff innan jag stag­ar och committar.
    **

 # Fråga 3:
 ## Lådan hemma vs Montern på GitHub
 ** 
 Det lokala repot finns på min dator och innehåller filerna och Git-historiken som jag arbetar med. GitHub-repot är den fjärrversion som finns online och som andra kan se om repot är publikt. Kommandot git push skickar mina lokala commits till GitHub.
 **

 ** Jag tänker på det lokala repot som en låda hemma och GitHub som en glasmonter online. När jag sparar en fil ändras arbetsytan, när jag gör en commit uppdateras den lokala Git-historiken och när jag kör git push skickas de nya commitsen till GitHub. Om jag bara ändrar en fil men inte stag­ar och committar ändringen finns det ingen ny commit att skicka, så git push kan svara Everything up-to-date. Det betyder att den lokala commit-historiken inte innehåller något nytt att överföra, även om filen på datorn har ändrats.
 **
   