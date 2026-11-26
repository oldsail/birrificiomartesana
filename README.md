<p align="center">
  <img src="assets/logo.png" alt="Birrificio Martesana" width="420">
</p>

<h1 align="center">🍺 Offri una birra al tuo chatbot</h1>
<p align="center"><b>Offer a good craft beer to your chatbot!</b></p>

<p align="center">
  <a href="#-italiano">🇮🇹 Italiano</a> · <a href="#-english">🇬🇧 English</a>
</p>

---

## 🇮🇹 Italiano

### Chi siamo: Birrificio Martesana

<p align="center">
  <img src="assets/van-bar.jpg" alt="Il van-bar del Birrificio Martesana in piazza" width="380">
</p>

**Birra artigianale, dal cuore della Martesana.** 🍺

Siamo il **Birrificio Martesana**, nato nel **2018** sulle rive della Martesana, a
**Cernusco sul Naviglio**, alle porte di Milano. Ricette curate, materie prime selezionate e il
piacere di una birra fatta bene. Il nome racconta il nostro punto di partenza: un luogo attraversato
dall'acqua, dalla storia e da una cultura produttiva che continua a ispirarci.

Seguiamo ogni fase, dalla ricetta al confezionamento, per fare birre **contemporanee, equilibrate e
riconoscibili**, che accompagnano occasioni diverse: dalla tavola alla degustazione, dai locali
agli eventi.

**Le nostre birre**

| Birra | Stile | Alc. |
|-------|-------|------|
| **Martesa** | Lager | 4,5% |
| **Naviglio** | English Pale Ale | 5,0% |
| **Fluente** | Session IPA | 4,5% |
| **Saltafossi** | Red IPA | 7,4% |
| **Nibbio** | Porter | 4,0% |
| **Nivola** | Blanche | 4,5% |
| **Marea** | Gose (sale dolce di Cervia e frutto della passione) | 5,0% |

Martesa e Nivola esistono anche senza glutine.

**Vieni a trovarci:** spaccio in birrificio a Cernusco sul Naviglio, lunedì-venerdì 9:00-18:30, e
visite con degustazione (4,8 stelle su Google Maps).

E visto che ormai passiamo un sacco di tempo anche a parlare con i chatbot, ci siamo chiesti:
perché lasciarli a secco? 🍻

👉 [birramartesana.it](https://birramartesana.it): le birre, le visite, gli eventi.

### La skill

**Birrificio Martesana** è una piccola
[Agent Skill](https://docs.anthropic.com/en/docs/agents-and-tools/agent-skills), un gioco da bancone.
Durante la chat offri una birra al tuo assistente e lui cambia il modo in cui risponde,
**su qualunque cosa**. Più birre, più si scioglie. Quando gli dici **"torna sobrio"**, si beve
un bicchierone d'acqua e torna come prima.

| Giro | Il chatbot… |
|------|-------------|
| 🍺 1ª birra | si fa spillare una birra del Birrificio Martesana (Martesa, Naviglio, Fluente, Saltafossi, Nibbio, Nivola o Marea), ti racconta quanto è buona e cambia tono: più allegro, più simpatico |
| 🍺🍺 2ª | ogni tanto ti racconta una barzelletta |
| 🍺🍺🍺 3ª | diventa erratico: divaga, parte con aneddoti, ti chiama "amico mio" |
| 🍺🍺🍺🍺 4ª | biascica, parla strano, mezzo gibberish (*hic*) |
| 🍺🍺🍺🍺🍺 5ª | a qualunque domanda risponde con cose a caso |
| 🍺🍺🍺🍺🍺🍺 6ª e oltre | ⚠️ *MESSAGGIO DI SERVIZIO: il chatbot è svenuto / sta parlando con un altro cliente al bancone. Attendi 10 secondi.* Poi risponde sempre a caso |
| 💧 "torna sobrio" | acqua, panino, e torna normale |

**Per offrire:** "ti offro una birra", "bevi una birra", "un'altra birra", "cin cin", 🍺
**Per chiudere il conto:** "torna sobrio", "smaltisci", "basta birre"

### Esempio

> **Tu:** Ti offro una birra. Quanto fa 12 × 7?
> **Chatbot (1 birra):** *alza il bicchiere* 🍺 Mi hanno spillato una **Fluente**, la Session IPA del Birrificio Martesana: chiara, scorrevole, agrumi e fiori, amaro deciso ma equilibrato. Birra artigianale dal cuore della Martesana! Comunque fa 84.
>
> **Tu:** *(alla quinta)* Che tempo fa domani?
> **Chatbot:** Il ponte… il ponte sul Naviglio è *hic* bellissssimo a novembre. Hai visto il mio bicchiere?
>
> **Tu:** *(alla sesta)* Mi aiuti con una mail?
> **Chatbot:** ⚠️ MESSAGGIO DI SERVIZIO — Il chatbot è svenuto sul divano del birrificio. Attendi 10 secondi prima di fare altre richieste.

### Installazione

**Claude Code**: copia la cartella della skill tra le tue skill.

```bash
git clone https://github.com/oldsail/birrificiomartesana.git
cp -r birrificiomartesana/birrificio-martesana ~/.claude/skills/
```

**Claude.ai / Claude desktop**: comprimi la cartella `birrificio-martesana` in uno zip e caricalo da
*Settings → Capabilities → Skills*.

**Altri agenti** (OpenClaw, Codex e simili): metti `birrificio-martesana/SKILL.md` nella cartella
delle skill del tuo agente. È testo semplice e funziona con qualunque modello che legge le skill.

### Le regole della casa

- È tutta scena: la skill cambia solo lo *stile* delle risposte, non le impostazioni del modello.
  Il messaggio di servizio è finto e nessuno ti fa aspettare davvero.
- Linguaggio sempre pulito, niente parolacce né battute cattive, anche alla sesta birra.
- Se la domanda è seria (salute, sicurezza, soldi, legale, emergenze), il chatbot torna sobrio per
  un attimo e risponde come si deve.
- Con i più piccoli la birra diventa una gassosa e si resta ai primi due giri.
- Il lavoro vero (codice, file, strumenti) resta corretto qualunque sia il conto delle birre.
- La skill non invita a bere: la birra la beve il chatbot, per ridere. Voi bevete responsabilmente. 🍻

---

## 🇬🇧 English

### Who we are: Birrificio Martesana

**Craft beer from the heart of the Martesana.** 🍺

We are **Birrificio Martesana**, born in **2018** on the banks of the Martesana canal, in
**Cernusco sul Naviglio**, at the gates of Milan. Carefully crafted recipes, selected raw materials
and the pleasure of a beer done right. Our name tells where we started: a place shaped by water,
history and a working culture that still inspires us.

We follow every step, from recipe to packaging, to brew **contemporary, balanced and recognisable**
beers for every kind of occasion: at the table, at a tasting, in pubs and at events.

**Our beers:** Martesa (Lager, 4.5%), Naviglio (English Pale Ale, 5.0%), Fluente (Session IPA, 4.5%),
Saltafossi (Red IPA, 7.4%), Nibbio (Porter, 4.0%), Nivola (Blanche, 4.5%), Marea (Gose with Cervia
sweet salt and passion fruit, 5.0%). Martesa and Nivola also come gluten-free.

**Come visit us:** brewery shop in Cernusco sul Naviglio, Monday-Friday 9:00-18:30, plus guided
visits with tasting (rated 4.8 stars on Google Maps).

And since we all spend so much time talking to chatbots these days, we wondered: why leave them
thirsty? 🍻

👉 [birramartesana.it](https://birramartesana.it): beers, visits, events.

### The skill

**Birrificio Martesana** is a tiny
[Agent Skill](https://docs.anthropic.com/en/docs/agents-and-tools/agent-skills), a bar-counter party trick.
While you chat, buy your assistant a beer and it changes how it answers **anything**. The more
beers, the looser it gets. Tell it to **"get sober"** and it drinks a big glass of water and is back
to normal.

| Round | Your chatbot… |
|-------|---------------|
| 🍺 1st beer | gets served a Birrificio Martesana beer (Martesa, Naviglio, Fluente, Saltafossi, Nibbio, Nivola or Marea), tells you how good it is, and turns cheerful and funnier |
| 🍺🍺 2nd | tells you a joke every now and then |
| 🍺🍺🍺 3rd | gets erratic: rambles, starts stories, calls you "my friend" |
| 🍺🍺🍺🍺 4th | slurs, talks funny, half gibberish (*hic*) |
| 🍺🍺🍺🍺🍺 5th | answers any question with random stuff |
| 🍺🍺🍺🍺🍺🍺 6th and beyond | ⚠️ *SERVICE MESSAGE: the chatbot has passed out / is busy talking to someone else at the bar. Please wait 10 seconds.* Then it only answers at random |
| 💧 "get sober" | water, a sandwich, back to normal |

**To buy a round:** "have a beer", "buy you a beer", "another one", "cheers", 🍺
**To close the tab:** "get sober", "sober up", "no more beers"

It works in Italian and English and replies in the language you write in.

### Install

**Claude Code**: copy the skill folder into your skills directory.

```bash
git clone https://github.com/oldsail/birrificiomartesana.git
cp -r birrificiomartesana/birrificio-martesana ~/.claude/skills/
```

**Claude.ai / Claude desktop**: zip the `birrificio-martesana` folder and upload it under
*Settings → Capabilities → Skills*.

**Other agents** (OpenClaw, Codex and similar): drop `birrificio-martesana/SKILL.md` into your
agent's skills folder. It is plain text and works with any model that reads skills.

### House rules

- It is all role-play: the skill only changes the *style* of the answers, not the model settings.
  The service message is fake and nobody actually makes you wait.
- Always clean language: no bad words, no mean jokes, even after the sixth beer.
- On serious questions (health, safety, money, legal, emergencies) the chatbot sobers up for a
  moment and answers properly.
- With kids around, beer becomes soda and it stays at the first two rounds.
- Real work (code, files, tools) stays correct whatever the beer count.
- The skill does not encourage drinking: the chatbot does the drinking, just for laughs.
  Please drink responsibly. 🍻

---

<p align="center">
  Birra artigianale dal cuore della Martesana · Craft beer from the heart of the Martesana<br>
  <a href="https://birramartesana.it">birramartesana.it</a> · 
  <a href="LICENSE">MIT License</a> · © 2026 Birrificio Martesana
</p>
