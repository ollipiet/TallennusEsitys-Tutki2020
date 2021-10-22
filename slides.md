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
layout: image-right
image: 'SampoPinoScreenshot.jpg'
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

- HS:n hakukone auttoi löytämään Sammon paperiosaketta omistaneet yhtiöt

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