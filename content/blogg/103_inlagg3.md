---
author: bew
published: "2017-12-19"
category:
    - webbutveckling
...
Anax platt
==================================

*Senaste versionen av Anax platt finns nu på GitHub!*  
*Jag har de senaste månaderna arbetat med en uppdatering av det ramverk jag brukar använda som utgångspunkt för mina webbplatser.*
<!--more-->
[FIGURE src="image/blogg/anax.png?" class="center" caption="anax-platt"]

**Kom igång**  

<p>Låt oss börja från ingenting. En tom katalog. Om du jobbar i kursrepot så skall du jobba i katalogen <code>me/anax-flat</code>. Katalogen bör finnas där.</p>

<pre class="hljs"><span class="hljs-comment">Gå till kursrepot</span>
<span class="hljs-built_in">cd</span> me/anax-flat
</pre>

<p>Anax Flat finns på GitHub och på Packagist. Du kan kika på hur paketet <a href="https://packagist.org/packages/mos/anax-flat">Anax Flat presenteras på Packagist</a>.</p>

<p>Vi tar och installerar Anax Flat med composer.</p>

<pre class="hljs"><span class="hljs-comment"># Du står i kursrepot under me/anax-flat</span>
$ composer require mos/anax-flat
$ tree -L 1 .
.                                               
├── composer.json                               
├── composer.lock                               
└── vendor                                      

1 directory, 2 files                            
</pre>

<p>Nu har du en fil <code>composer.json</code> som visar vad composer har installerat. Lockfilen är en snapshot över det som är installerat, om du ändrar i <code>composer.json</code> så matchas den mot lockfilen.</p>
