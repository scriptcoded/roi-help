---


---

<h1 id="acs-lilla-fusklapp-">ACs lilla fusklapp :)</h1>
<p>Halloj AC!<br>
Här kommer en liten fusklapp med saker som kan vara bra att veta när du arbetar med karriärssidorna (och kanske vid andra tillfällen också ;).</p>
<h2 id="text">Text</h2>
<p>Alla formateringar på text du vill göra fungerar på samma sätt. Den text du vill modifiera klämmer du alltid in mellan två <em>taggar</em>. Den ena taggen öppnar, den andra stänger. Det ser alltså ut såhär:</p>
<pre><code>ett två tre &lt;tagg&gt;fyra&lt;/tagg&gt; fem
</code></pre>
<p>I exemplet ovan formaterar vi alltså texten <code>fyra</code>. Den omgivs av en hittepåtagg med namnet <code>tagg</code>. Lägg märke till att den andra taggen också innehåller ett snedstreck. Det innebär att den “stänger” paret.</p>
<p>Vissa taggar kan också ha så kallade attribut. Attribut används för att ändra hur en tagg beter sig eller ser ut. Attribut skrivs in i den första taggen i ett par.</p>
<pre><code>ett två tre &lt;tagg attribut="värde"&gt;fyra&lt;/tagg&gt; fem
</code></pre>
<p>I exemplet ovan har taggen ett attribut med namnet <code>attribut</code> och värdet <code>värde</code>.</p>
<h3 id="gör-text-till-en-länk">Gör text till en länk</h3>
<pre><code>Vår hemsida hittar du här.
</code></pre>
<p>Blir till</p>
<pre><code>Vår hemsida hittar du &lt;a href="https://roirekrytering.se"&gt;här&lt;/a&gt;.
</code></pre>
<p><strong>Resultat:</strong></p>
<blockquote>
<p>Vår hemsida hittar du <a href="https://roirekrytering.se">här</a>.</p>
</blockquote>
<p>Lägg märke till att det som är innanför <code>&lt;a&gt;</code> och <code>&lt;/a&gt;</code> är det som blir till en länk. Punkten efter är alltså <em>inte</em> en del av länken.</p>
<p>Här ser du också ett attribut. <code>href</code> bestämmer var länken går till. I detta fallet råkar det vara <code>https://roirekrytering.se</code>.</p>
<h3 id="textstilar">Textstilar</h3>
<p>Du kan ändra stilen på text med ett gäng taggar.</p>

<table>
<thead>
<tr>
<th>Tagg</th>
<th>Stil</th>
<th>Applicerat</th>
</tr>
</thead>
<tbody>
<tr>
<td><code>b</code></td>
<td>Fet (Bold)</td>
<td><b>Fet (Bold)</b></td>
</tr>
<tr>
<td><code>i</code></td>
<td>Kursiv (Italic)</td>
<td><i>Kursiv (Italic)</i></td>
</tr>
<tr>
<td><code>s</code></td>
<td>Struket (Strikethrough)</td>
<td><s>Struket (Strikethrough)</s></td>
</tr>
<tr>
<td><code>small</code></td>
<td>Liten text</td>
<td><small>Liten text</small></td>
</tr>
</tbody>
</table><br>
<pre><code>Jag känner mig riktigt fet!
</code></pre>
<p>Blir till</p>
<pre><code>Jag känner mig &lt;b&gt;riktigt&lt;/b&gt; fet!
</code></pre>
<p><strong>Resultat:</strong></p>
<blockquote>
<p>Jag känner mig <b>riktigt</b> fet!</p>
</blockquote>
<h2 id="skapa-en-ny-karriärssida">Skapa en ny karriärssida</h2>

