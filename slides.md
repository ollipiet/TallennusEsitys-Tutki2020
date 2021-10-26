---
# try also 'default' to start simple
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://source.unsplash.com/collection/94734566/1920x1080
# apply any windi css classes to the current slide
class: 'text-center'
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# show line numbers in code blocks
lineNumbers: false
# some information about the slides, markdown enabled
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
# persist drawings in exports and build
drawings:
  persist: false
---

# Ruudunluku ja kuvatunnistus tekstille

Case Sampo kadonneet osakkeet ja pappien rötökset

<div class="abs-br m-6 flex gap-2">
  <a href="https://github.com/slidevjs/slidev" target="_blank" alt="GitHub"
    class="text-xl icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div>

<!--
Olemme esittelemässä ruudunlukusovellusta ja tekstin tunnistamista paperidokumenteista. Matala aloitustaso, paljon esimerkkejä.
-->

---
layout: center
class: text-center
---

# Ruudunluku

[Dokumenttikäsittelijä Cometdocs](cometdocs.com) · iPhone SE

<!--
1. IMPORTANT: Log in to Your Session 20 Minutes Before It Starts for Tech Check.
2. Be as Concrete and Practical as Possible
This is a training conference, and we need you to be as practical as possible. Your colleagues should leave your session having learned how to better investigate a story or use a new tool or technique. Your talk should focus on useful methods and strategies, with practical examples.
Do not use a lot of time talking about your story or yourself.
The biggest complaint we get on attendee surveys is that speakers talked about themselves instead of how they did their work.
Most sessions are 75 minutes long, and most speakers will have 10 to 15 minutes to speak. Your moderator will be in touch to discuss your presentation.
3. Talk About the Methods Used in Your Work:
If talking about a story, explain what kinds of sources you used. How did you find them?
What kind of data or documents did you use? How did you get them?
What was the breakthrough in investigating your story?
Did you work in a team or by yourself? If a team, how did you collaborate?
How did you solve your toughest challenges? How did you deal with security?
How did you produce, present and roll out the story for maximum impact?
What would you recommend to other journalists doing a similar project?
4. Speak Clearly, Use Slides and Media
Many in the audience speak English as a second language, so please speak clearly. Please also note that some sessions are being translated, and it is very important that our interpreters can hear you as clearly as possible. It’s also helpful to illustrate your key points with media such as photos and videos in a PDF, Powerpoint or similar presentation. Do not read your presentation. We prepared some PowerPoint templates which you can download and adapt for your own presentation.
5. Be Aware: Sessions Will Be Recorded and “On the Record”
This is a conference of journalists and what you say may be quoted and tweeted. All sessions except networking ones will be recorded and accessible for attendees on the Pathable platform exclusively for 6 months. After that time, the recordings will be uploaded to GIJN’s YouTube channel and available to the public.
6. Tipsheets & Presentations
It’s very helpful for the audience if you prepare a tipsheet. The most popular tipsheets are those that provide specific details: documents and data to get, websites to use, relevant stories and sources. You can download and use our tipsheet template to create your own.
-->

---
layout: default
class: content
---

# Kuvanluku koneellisesti eli OCR

- Lue kuva tekstinä kuvatiedostosta (pdf) tai valokuvasta (jpg)
- Perinteisesti ollut haastavaa - haasteena kuvien laatu ja tietokoneiden hahmotuskyky
- Helpottunut kun kuvatietoja mylläävistä koneista on tullut tehokkaampia ja kamerat mm. iPhoneissa ovat kehittyneet.

---
layout: default
---

# Esimerkki 1: Ruudunraavinta esimerkit

<div class="container mx-auto">
  <div class="cols">
  <h3>Jalkapalloliiga</h3>
  <div class="grid">
    <a class="item" href="" style="--hue: 200deg"><span class="icon base" id="blur0" aria-hidden="true">📄</span><span class="icon base" aria-hidden="true">📄</span><span class="icon midl" aria-hidden="true" style="background-image: -moz-element(#blur0)">📄</span><span class="icon grey" aria-hidden="true">📄</span>henkilö</a>
  </div>
  <p class="otsake">Etunimi, Sukunimi, ammatti 
  </p><p> Essi Enteilijä, valmentaja <br>
    Annika Ahvenainen, jalkapalloilija <br>
    Malka Antoinette, jalkapalloilija <br>
    Mikale Mahtipallo, maalivahti <br>
    Kalle Kultamitalisti, huoltaja <br>
    Pia Opoto, huoltaja
  </p>
  <h3>Kuljettajaluettelo</h3>
  <div class="grid">
    <a class="item" href="" style="--hue: 0deg"><span class="icon base" id="blur0" aria-hidden="true">🚒</span><span class="icon base" aria-hidden="true">🚒</span><span class="icon midl" aria-hidden="true" style="background-image: -moz-element(#blur0)">🚒</span><span class="icon grey" aria-hidden="true">🚒</span>henkilö</a>
  </div>
  <p class="otsake">Etunimi, Sukunimi, ammatti</p>
  <p>Piia Palovartija, esimies <br>
    Jaro Poltinpaja, pelastaja <br>
    Raija Repo, pelastaja <br>
    Piia Palkola, pelastaja <br>
    Teijo Tekijä, nuorempi pääl. <br>
    Olga Positova, pelastaja <br>
  </p> 
  <h3>TAI Vakuutetut omistajat</h3>
  <div class="grid">
    <a class="item" href="" style="--hue: 64deg"><span class="icon base" id="blur0" aria-hidden="true">🏘</span><span  class="icon base" aria-hidden="true">🏘</span><span class="icon midl" aria-hidden="true" style="background-image: -moz-element(#blur0)">🏘</span><span class="icon grey" aria-hidden="true">🏘</span>asunto</a>
  </div>
  <p class="otsake">nimi, y-tunnus</p>
  <p>Asunto-osakeyhtiö Sture, 1-2215339<br>
  Asunto-osakeyhtiö Strömsön Kultapossut, 1-23... <br>
  Asunto-osakeyhtiö Porin Pulikoijat, 1-2221339 <br>
  </p>
  </div>
</div> 
<v-click>
<div class="abs-br m-6 flex">
  <div>
      <p contenteditable="true"> Asunto-osakeyhtiö Turku kultakerho, 1-2345678 <br>
  Asunto-osakeyhtiö Kulta Vuolija, 23456-345<br></p>
  </div>
</div>
</v-click>

<style>
  .cols {
    max-width: 1100px;
    margin: 20px auto;
    column-count: 3;
    overflow:  auto;
    height:  100%;
  }
  .otsake {
    text-decoration: underline rebeccapurple double;
  }
  .grid a {
    padding: 0.75em 0 0.375em;
    display: grid;
    text-decoration: none;
  }
  
  .item {
    --hl: 0;
    width: 5em;
    color: hsl(var(--hue), calc(var(--hl)*100%), 65%);
    text-align: center;
    text-decoration: none;
    transition: color 0.3s;
  }
  .item:focus {
    outline: none;
  }
  .item:hover, .item:focus {
    --hl: 1 ;
  }

  .icon {
    grid-area: 1/1;
    place-self: center;
    font-size: 2.5em;
  }

  .base {
    z-index: 1;
    transform: translate(calc(var(--hl)*.375em), calc(var(--hl)*-.25em)) rotate(calc(var(--hl)*22.5deg));
    opacity: var(--hl);
    filter: sepia(1) hue-rotate(calc(var(--hue) - 50deg)) saturate(3) blur(var(--r, 0));
    transition: 0.3s;
  }
  .base[id*=blur] {
    --r: 5px;
    position: fixed;
    bottom: 100vh;
  }

  .midl {
    z-index: 2;
    color: transparent;
    backdrop-filter: blur(5px);
    -webkit-mask: linear-gradient(red 0 0) text;
  }
  @supports (background: -moz-element(#hl)) {
    .midl {
      background-color: #fff;
      background-clip: text;
      backdrop-filter: none;
    }
  }

  .grey {
    z-index: 3;
    filter: grayscale(1) opacity(0.35);
  }
    
</style>


---
layout: image-right
image: './SampoPinoScreenshot.jpg'
class: 'content-center'
---
# Case Sampo
- Helsingin Sanomilla on hallussaan iso
nippu paperisia asiakirjoja, joissa on
Sammon osakeyhtiöomistajat vuodelta
1987
- Mutta miten paperille painettu tieto
muuttuu hyödylliseksi hakukoneeksi?


---
layout: default
---
## HS:n hakukoneeksi

HS:n hakukone auttoi löytämään Sammon paperiosaketta omistaneet yhtiöt

<div class="abs-tr m-6 flex gap-2">
  <button class="text-xl icon-btn opacity-50 !border-none !hover:text-white">
    <carbon:edit />
  </button>
  <a class="text-xl icon-btn opacity-50 !border-none !hover:text-white">
    <p>👨‍💻</p>
  </a>
</div>

<style>
h2 {
  background-image: linear-gradient(150deg
    , #84fab0 0%, #8fd3f4 100%);
    background-repeat: no-repeat;
    background-repeat-x: no-repeat;
    background-repeat-y: no-repeat;
    background-size: 100% 0.2em;
    background-position: 0 88%;
}
</style>

---
layout: image
image: './SturenkatuVirallinenLehti.jpg'
---
<!--4 326 asunto-osakeyhtiötä hakukoneessa. https://www.hs.fi/talous/art-2000005018542.html-->


---

# iPhone kuvien kopioimisen perusperiaate - Live Text
- Kuvan ottamisen jälkeen kuvagalleriaan tulee kuvaan merkki oikeaan alakulmaan, jolloin kuvan sisältämän tekstin saa näkyviin
- **iPhonen ruudulta voi valita tekstiä ja kopioida sen** 
  - Viestin voi lähettää itselleen tai eteenpäin esimerkiksi sähköpostilla, Whatsapilla jne...
  
- Ominaisuus vaatii iOS15-päivityksen ja vuoden 2018 tai tuoreemman puhelimen (iPhone Xs, 11, SE 2020 ja  uudemmat)
- [Tarkemmin Live Text-ominaisuudesta iGeeksBlog](https://www.igeeksblog.com/how-to-use-live-text-on-iphone-ipad/)

---

# Toimistotyökalut: kuinka printteri-skannerilla saa digitoitua asiakirjat

- Printterin OCR-ominaisuudet.

---

# Cometdocs

- Asiakirjojen kääntäjä, ja kuvantunnistaja erityisesti pdf-tiedostoista
- Perusversio ilmainen, **vaatii rekisteröitymisen**.
- Tukee hyvin suomenkielisiä tekstejä, ja tunnistaa suurella tarkkuudella myös skannattuja papereita
- **Cometdocs.com**
- Nimet, koodit, listat ylennyksistä 

- [Fukushima](https://olli.xyz/BkFGSh)

---
layout:standard
---
<iframe style="width: 100%; height: 100%;" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vQRE3H9EBRa00ySnkSp2xY4i5NkyQUsK55Ze3wzWATGSo3iri3Q0ZAHka2NdvtVi2aGeVunxxGNvdGh/pubhtml?gid=91846639&amp;single=true&amp;widget=true&amp;headers=false"></iframe>

---

# Kysymyksiä - muiden kokeilemia sovelluksia?

<div class="gridholder">
    <div class="grid">
      <a class="item" href="" style="--hue: 64deg"><span class="icon base" id="blur0" aria-hidden="true">🏘</span><span  class="icon base" aria-hidden="true">🏘</span><span class="icon midl" aria-hidden="true" style="background-image: -moz-element(#blur0)">🏘</span><span class="icon grey" aria-hidden="true">🏘</span>Tuomo</a>
  </div>
  <div class="grid">
      <a class="item" href="" style="--hue: 180deg"><span class="icon base" id="blur0" aria-hidden="true">👨‍💻</span><span  class="icon base" aria-hidden="true">👨‍💻</span><span class="icon midl" aria-hidden="true" style="background-image: -moz-element(#blur0)">👨‍💻</span><span class="icon grey" aria-hidden="true">👨‍💻</span>Olli</a>
  </div>
</div>

<style>
  .gridholder {
    display:  grid;
    grid-auto-flow: row;
    place-self: center;
  }
  .grid a {
    padding: 1.9em 0 0.375em;
    display: grid;
    text-decoration: none;
  }
  
  .item {
    --hl: 0;
    width: 5em;
    color: hsl(var(--hue), calc(var(--hl)*100%), 65%);
    text-align: center;
    text-decoration: none;
    transition: color 7s;
    gap: 10px;
  }
  .item:focus {
    outline: none;
  }
  .item:hover, .item:focus {
    --hl: 1 ;
  }

  .icon {
    grid-area: 1/1;
    place-self: center;
    font-size: 2.5em;
  }

  .base {
    z-index: 1;
    transform: translate(calc(var(--hl)*.375em), calc(var(--hl)*-.25em)) rotate(calc(var(--hl)*22.5deg));
    opacity: var(--hl);
    filter: sepia(1) hue-rotate(calc(var(--hue) - 50deg)) saturate(3) blur(var(--r, 0));
    transition: 7s;
  }
  .base[id*=blur] {
    --r: 14px;
    position: fixed;
    bottom: 100vh;
  }

  .midl {
    z-index: 2;
    color: transparent;
    backdrop-filter: blur(5px);
    -webkit-mask: linear-gradient(red 0 0) text;
  }
  @supports (background: -moz-element(#hl)) {
    .midl {
      background-color: #fff;
      background-clip: text;
      backdrop-filter: none;
    }
  }

  .grey {
    z-index: 3;
    filter: grayscale(1) opacity(0.35);
  }
    
</style>