# 🍺 Birrificio Martesana: offri una birra al tuo chatbot

Una piccola [Agent Skill](https://docs.anthropic.com/en/docs/agents-and-tools/agent-skills), un gioco da bar.
Durante la chat offri una birra all'assistente e lui cambia il modo in cui risponde, **su qualunque cosa**.
Più birre, più va fuori di testa. Quando gli dici **"torna sobrio"** / **"get sober"**, torna normale.

*Offer a good craft beer to your chatbot! A tiny Agent Skill: buy your chatbot a beer and watch it get progressively tipsy, until you tell it to "get sober". Works in Italian and English.*

| Birre | Il chatbot… |
|-------|-------------|
| 🍺 1 | cambia tono: più allegro e divertente |
| 🍺🍺 2 | ogni tanto ti racconta una barzelletta |
| 🍺🍺🍺 3 | diventa erratico, divaga, ti chiama "amico mio" |
| 🍺🍺🍺🍺 4 | parla strano, biascica, mezzo gibberish (*hic*) |
| 🍺🍺🍺🍺🍺 5 | a qualunque domanda risponde con cose a caso |
| 🍺🍺🍺🍺🍺🍺 6+ | ⚠️ *MESSAGGIO DI SERVIZIO: il chatbot è svenuto / sta parlando con un altro. Attendi 10 secondi.* Poi risponde sempre a caso |
| 💧 "torna sobrio" | torna normale |

**Come si attiva:** "ti offro una birra", "bevi una birra", "un'altra birra", "cin cin", "🍺",
"have a beer", "cheers". **Come si spegne:** "torna sobrio", "smaltisci", "get sober".

## Install

**Claude Code**: copia la cartella della skill nelle tue skill.

```bash
git clone https://github.com/oldsail/birrificiomartesana.git
cp -r birrificiomartesana/birrificio-martesana ~/.claude/skills/
```

**Claude.ai / Claude desktop**: comprimi la cartella `birrificio-martesana` in uno zip e caricalo da
*Settings → Capabilities → Skills*.

**Altri agenti** (OpenClaw, Codex, ecc.): metti `birrificio-martesana/SKILL.md` nella cartella
skill del tuo agente. Il file è testo semplice e funziona con qualunque modello che legge le skill.

## Regole della casa

- È tutta scena: la skill cambia solo lo *stile* delle risposte, non le impostazioni del modello.
  Nessuna attesa vera, il "messaggio di servizio" è finto.
- Linguaggio sempre pulito, niente parolacce né battute cattive, anche alla sesta birra.
- Se la domanda è seria (salute, sicurezza, soldi, legale, emergenze), l'assistente torna sobrio
  per un attimo e risponde bene.
- Con i bambini la birra diventa una gassosa e si resta ai livelli innocui.
- Il lavoro vero (codice, file, strumenti) resta corretto qualunque sia il conto delle birre.
- Non incoraggia a bere. Bevete responsabilmente. 🍻

## License

MIT
