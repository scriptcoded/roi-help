# Text
Alla formateringar på text du vill göra fungerar på samma sätt. Den text du vill modifiera klämmer du alltid in mellan två *taggar*. Den ena taggen öppnar, den andra stänger. Det ser alltså ut såhär:

	ett två tre <tagg>fyra</tagg> fem
I exemplet ovan formaterar vi alltså texten `fyra`. Den omgivs av en hittepåtagg med namnet `tagg`. Lägg märke till att den andra taggen också innehåller ett snedstreck. Det innebär att den "stänger" paret.

Vissa taggar kan också ha så kallade attribut. Attribut används för att ändra hur en tagg beter sig eller ser ut. Attribut skrivs in i den första taggen i ett par.

	ett två tre <tagg attribut="värde">fyra</tagg> fem

I exemplet ovan har taggen ett attribut med namnet `attribut` och värdet `värde`.

## Gör text till en länk
	Vår hemsida hittar du här.

Blir till

	Vår hemsida hittar du <a href="https://roirekrytering.se">här</a>.

**Resultat:**
> Vår hemsida hittar du <a href="https://roirekrytering.se">här</a>.

Lägg märke till att det som är innanför `<a>` och `</a>` är det som blir till en länk. Punkten efter är alltså *inte* en del av länken.

Här ser du också ett attribut. `href` bestämmer var länken går till. I detta fallet råkar det vara `https://roirekrytering.se`.


## Textstilar

Du kan ändra stilen på text med ett gäng taggar.

|Tagg   |Stil                   |Applicerat                    |
|-------|-----------------------|------------------------------|
|`b`    |Fet (Bold)             |<b>Fet (Bold)</b>             |
|`i`    |Kursiv (Italic)        |<i>Kursiv (Italic)</i>        |
|`s`    |Struket (Strikethrough)|<s>Struket (Strikethrough)</s>|
|`small`|Liten text             |<small>Liten text</small>     |

<br>

    Jag känner mig riktigt fet!

Blir till

	Jag känner mig <b>riktigt</b> fet!

**Resultat:**
> Jag känner mig <b>riktigt</b> fet!
