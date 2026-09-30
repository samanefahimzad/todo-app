Varför är .map ett löpande band?

.map går igenom alla saker i en array, en i taget.
I min kod går .map igenom varje todo och gör om den till en <li>.
Jag kan tänka på .map som ett löpande band eftersom varje todo kommer en efter en och blir omgjord till en lista. Sedan går den vidare till nästa todo.

Varför är .filter en sil och inte en kniv?

.filter går igenom alla saker i en array och kollar vilka som passar ett villkor.
De saker som passar får vara kvar, medan de andra tas bort.
Jag kan tänka på .filter som en sil eftersom den släpper igenom vissa saker och stoppar andra. Den är inte en kniv eftersom den inte delar eller ändrar sakerna, utan bara väljer vilka som ska vara kvar.

Vad gör key — och vad är den INTE?
key hjälper React att hålla koll på vilken lista varje element tillhör.
I min kod har jag key={todo} på varje <li>. Då kan React se skillnad på de olika uppgifterna när listan ändras.
key är inte det som visar texten på sidan och den är inte heller ett vanligt värde som jag använder i appen. Den används av React för att hålla koll på elementen i listan.