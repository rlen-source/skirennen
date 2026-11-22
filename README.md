# ⛷ KI-Spielwerkstatt: Skirennen · AI Game Lab: Ski Race

**Deutsch** · [English](#english)

**Kinder bauen ein Ski-Spiel mit KI – ohne eine Zeile Code selbst zu tippen.**
Ein fertiger Workshop, um Kindern von etwa 10 bis 14 Jahren das Programmieren mit KI näherzubringen – in der Schule, im Ferienkurs, im Coding-Club oder am Zukunftstag. Auf Deutsch und Englisch.

**[▶ Workshop öffnen](https://rlen-source.github.io/skirennen/)** · **[✨ Demo spielen](https://rlen-source.github.io/skirennen/skirennen-v3.html)** · **[📄 Infoblatt (PDF)](https://rlen-source.github.io/skirennen/trainer-de.pdf)** · **[🇬🇧 English version](https://rlen-source.github.io/skirennen/en/)**

[![Startseite des Workshops: drei Schritte und das Demo-Bild](docs/launcher-start.png)](https://rlen-source.github.io/skirennen/)

## Worum es geht

Kinder erleben in diesem Workshop, wie heute mit KI Software entsteht: Sie beschreiben, was ihr Spiel können soll, die KI schreibt den Code, und sie prüfen, ob das Ergebnis stimmt. Vorwissen braucht es keines – weder im Programmieren noch im Umgang mit KI.

Am Ende hat jedes Team sein eigenes Skirennen – mit eigener Strecke, eigener Spielfigur und eigenen Ideen. Und die Kinder haben erlebt, dass die KI ein Werkzeug ist: Sie macht genau das, was man ihr sagt, und manchmal auch Fehler, die man erkennen und beheben muss.

## Wo sich der Workshop eignet

Überall, wo Kinder einen ersten, positiven Zugang zum Programmieren mit KI bekommen sollen, zum Beispiel:

- **Schule:** im Informatik- oder Medienunterricht, in einer Projektwoche oder als Einstieg ins Thema KI
- **Ferienkurse und Coding-Clubs:** als halber Tag oder als Start für eine Reihe mit eigenen Spielideen
- **Zukunftstag und Firmenanlässe:** Kinder erleben, wie Software heute in Firmen entsteht. Hier ist der Workshop entstanden.
- **Bibliotheken, Jugendarbeit und Familienanlässe:** mit einem Laptop oder Tablet pro Team und einer erwachsenen Person, die den Chat bedient
- **Zu Hause:** Eltern und Kinder zusammen – alles läuft im Browser, und eine gespeicherte Version lässt sich später weiterbauen

Der Ablauf lässt sich anpassen: Teil 1 allein dauert etwa eine Stunde, Teil 2 lässt sich beliebig verlängern.

## Warum der Workshop so aufgebaut ist

Eine KI schreibt bei einer ungenauen Bitte jedes Mal etwas anderes. Bei zehn Teams entstehen dann zehn verschiedene Spiele – und wenn eines kaputtgeht, weiss niemand, warum. Für einen Workshop mit Kindern braucht es deshalb **verlässliche Ergebnisse**.

Darum arbeitet der Workshop mit drei Ideen:

1. **Ein fertiges, stabiles Basis-Spiel als Start.** Die Kinder bauen nicht bei null an, sondern verändern ein Spiel, das schon funktioniert. So gibt es von der ersten Minute an etwas zu spielen.
2. **Ein Spiel mit drei klaren Bereichen:** Einstellungen, ein Bereich für eigene Ideen und ein Spiel-Motor, den niemand anfasst. Die KI weiss dadurch immer, wo sie arbeiten darf.
3. **Fertige, genaue Prompts.** Jeder Prompt sagt der KI exakt, was sie ändern darf und was nicht. Die Kinder verstehen trotzdem, was passiert, weil jeder Schritt in einfacher Sprache erklärt ist.

Entstanden ist der Workshop für den Zukunftstag, an dem Kinder Erwachsene an ihren Arbeitsplatz begleiten. Die erste Fassung (2025) liess die Kinder das Spiel Schritt für Schritt neu aufbauen. Dabei war die Qualität des erzeugten Codes nicht verlässlich genug. Die aktuelle Fassung startet deshalb mit dem fertigen Basis-Spiel, und jeder Schritt in Teil 1 ändert nur noch eine oder zwei Zahlen.

## Was die Kinder lernen

- **Genau beschreiben:** Je klarer der Prompt, desto besser das Ergebnis. Ziel, Zahlen und Grenzen gehören dazu („Ändere nur …, sonst nichts“).
- **Prüfen statt glauben:** Jedes Ergebnis wird gespielt und verglichen. Funktioniert es? Hat sich nur das Gewünschte verändert?
- **Computational Thinking:** Ein Spiel in Teile zerlegen (Piste, Tore, Bäume, Kamera), mit Zahlen steuern (Tempo, Reibung, Abstände), mit Ereignissen arbeiten („wenn ein Tor geschafft ist, dann …“) und Welt- und Bildschirm-Koordinaten unterscheiden.
- **Zufall mit Startwert:** Mit der gleichen Seed-Zahl fahren alle die gleiche, faire Strecke.
- **Fehler gehören dazu:** Wenn etwas kaputtgeht, gibt es einen Reparatur-Prompt – und man lernt, wie die KI Fehler macht.
- **Teamarbeit:** Ideen erklären, gemeinsam entscheiden, sich gegenseitig die Spiele zeigen.

## Ablaufvorschlag (ca. 3 Stunden)

| Zeit | Was passiert |
|---|---|
| 15 Min. | Begrüssung, Demo zeigen, Teams bilden (2–3 Kinder pro Gerät) |
| 15 Min. | Basis-Spiel ausprobieren, Bestzeit merken, Datei im Chat hochladen |
| 75 Min. | **Teil 1:** acht Schritte – Kamera, Piste, Lenkung, Regeln, Wald, eigene Strecke |
| 15 Min. | Pause |
| 45 Min. | **Teil 2:** eigene Ideen – Schneefall, Bär, Spielfigur, Farben, eigene Idee |
| 15 Min. | Spiele gegenseitig ausprobieren, Bestzeiten vergleichen, kurze Runde: Was war überraschend? |

Teil 1 lässt sich verkürzen, indem einzelne Schritte übersprungen werden; Teil 2 lässt sich beliebig verlängern.

## So arbeiten die Kinder

Alles passiert auf einer Seite, dem **Launcher**. Er läuft am Laptop und auf dem iPad, ohne Installation.

1. **Spiel ausprobieren:** auf der Startseite „Spiel ausprobieren“ und ein Rennen fahren.
2. **Datei in den Chat:** im Live Editor „Basis-Spiel herunterladen“ und die Datei in einem neuen Chat hochladen.
3. **Schritt wählen und Prompt kopieren:** Jeder Schritt zeigt oben in einfacher Sprache, was die KI tun soll. Die Regeln, die das Spiel stabil halten, werden automatisch mitkopiert.
4. **Antwort testen:** den Code aus der Antwort im Live Editor einfügen und „▶ Spiel anzeigen“. Klappt es, geht es mit „✓ Klappt – nächster Schritt“ weiter.
5. **Teil 2:** Schneefall, ein Bär, der einen jagt, eine Prinzessin oder ein Ninja, neue Farben, eine Kombo-Anzeige – oder eine ganz eigene Idee mit dem Prompt-Generator.

[![Ein Schritt in Teil 1: Aufgabe als Karte, Prompt kopieren, Fortschritt links](docs/launcher-step.png)](https://rlen-source.github.io/skirennen/)

### Wenn etwas klemmt

- **Das Spiel hat einen Fehler:** Über dem Spiel erscheint ein roter Hinweis mit „Reparatur-Prompt kopieren“. Im Chat einfügen, neue Antwort testen.
- **Die Antwort hört mittendrin auf:** Lange Antworten werden manchmal abgeschnitten. Der Launcher merkt das. Den Prompt „↻ Weiter“ schicken und „🧩 Fortsetzung anhängen“ benutzen – die Teile werden automatisch zusammengesetzt.
- **Ein Schritt hat es schlechter gemacht:** „↩ Vorherige Version“ holt die letzte Version zurück.
- **Später weitermachen:** „💾 Meine Version herunterladen“ speichert das Spiel, „📂 Datei öffnen“ lädt es wieder – auch zu Hause.

## Die Demo

[![Demo: Piste mit Bergbeizli, Murmeltier, Publikum und Sternen](docs/demo.png)](https://rlen-source.github.io/skirennen/skirennen-v3.html)

Die [Demo-Version](https://rlen-source.github.io/skirennen/skirennen-v3.html) zeigt zu Beginn, wie weit man kommen kann: Skihütten mit rauchendem Kamin, Bergziegen, Murmeltiere und Hasen, jubelndes Publikum, Sterne zum Sammeln, ein Bär, ein Adler und ein Feuerwerk im Ziel. Der Spiel-Motor ist genau derselbe wie im Basis-Spiel – alles Neue ist mit Prompts aus Teil 2 machbar.

## Vorbereitung für Trainer:innen

- [ ] **Chat-Zugang klären.** Die Kinder brauchen einen Chat mit KI, zum Beispiel ChatGPT oder Claude, in dem man Dateien hochladen kann. Die Anbieter haben Altersgrenzen. Meist läuft der Chat deshalb über das Konto einer erwachsenen Person, die beim Team sitzt.
- [ ] **WLAN testen.** Der Launcher lädt von `rlen-source.github.io`, die Spiel-Bibliothek von `cdn.jsdelivr.net` und die Schrift von `fonts.googleapis.com`. Schul- und Firmen-WLANs blockieren manchmal einzelne davon – am besten vorher einmal auf einem Workshop-Gerät öffnen.
- [ ] **Einen Durchlauf selbst machen**, mindestens Teil 1 bis Schritt 3, mit dem Chat, den die Kinder benutzen.
- [ ] **Infoblatt ausdrucken** und aufhängen: [Deutsch (PDF)](https://rlen-source.github.io/skirennen/trainer-de.pdf) · [English (PDF)](https://rlen-source.github.io/skirennen/trainer-en.pdf). Der QR-Code führt direkt zum Launcher.
- [ ] **Trainer-Modus:** unten im Launcher „👩‍🏫 Trainer-Modus“ einschalten oder den Link mit `?trainer` öffnen. Dann erscheinen auf der Startseite Ziele, Methode und Ablauf und in Teil 1 Lernziele und Gesprächsfragen zu jedem Schritt. Ohne Trainer-Modus sehen die Kinder nur die einfache Startseite.

Gut zu wissen:

- Ein Schritt in Teil 1 zählt als erledigt, wenn ein Kind im Live Editor „✓ Klappt“ drückt – nicht schon beim Kopieren.
- Jede Antwort der KI enthält das ganze Spiel (rund 36 000 Zeichen). Das ist Absicht: So gibt es nie halbe Dateien. In Gratis-Versionen der Chats werden lange Antworten aber manchmal abgeschnitten – dafür gibt es „↻ Weiter“.
- Die Prompts lassen sich im Code des Launchers in den Listen `promptsTeil1` und `promptsTeil2` anpassen.

## iPad und Tablet

- **Steuern:** Finger aufs Spielfeld legen und hin und her ziehen, der Skifahrer folgt. Am Laptop mit ← → oder A / D.
- **Als App:** in Safari **Teilen → Zum Home-Bildschirm**. Dann öffnet sich das Skirennen mit eigenem Symbol und ohne Adressleiste.
- **Dateien:** Beim Herunterladen öffnet sich das Teilen-Menü. Die Datei kann direkt an die ChatGPT- oder Claude-App gehen oder in „Dateien“ gesichert werden.
- Das Tablet am besten quer halten.

## Wie das Spiel gebaut ist

Das Spiel ist eine einzige HTML-Datei mit [p5.js](https://p5js.org). Es hat drei Bereiche:

1. **Einstellungen (`CONFIG`)** – alle Zahlen an einem Ort: Tempo, Anzahl Tore, Strafen, Pistenbreite, Seed
2. **Hier darfst du ändern** – Farben (`THEME`), Spielfigur (`drawPlayer`), Extras (`EXTRAS`) und Ereignisse (`onGatePassed`, `onCrash`, …)
3. **Spiel-Motor – nicht ändern** – Physik, Strecke, Kollisionen, Anzeige

Extras sind kleine Bausteine, die sich ins Spiel einklinken: Wenn ein Extra einen Fehler hat, schaltet der Spiel-Motor nur dieses Extra aus, und das Spiel läuft weiter.

Alle Prompts wurden in simulierten Chats getestet, auf Deutsch und Englisch: Die KI ändert genau das Verlangte, der Spiel-Motor bleibt Zeichen für Zeichen gleich, und alle entstandenen Spiele laufen fehlerfrei.

## Was ist hier drin?

| Datei | Wofür |
|---|---|
| `index.html` | Der Launcher auf Deutsch – Startseite, Teil 1, Teil 2, Live Editor. Beide Spiele sind eingebaut. |
| `skirennen-v2.html` | Das Basis-Spiel, mit dem die Kinder starten |
| `skirennen-v3.html` | Die Demo-Version |
| `en/index.html`, `ski-race-v2.html`, `ski-race-v3.html` | Dasselbe auf Englisch |
| `trainer.html`, `trainer-de.pdf`, `trainer-en.pdf` | Infoblatt mit QR-Code |
| `docs/` | Bilder für diese Seite |

---

## English

**Kids build a ski game with AI – without typing a single line of code themselves.**
A ready-to-use workshop that introduces kids aged about 10 to 14 to coding with AI – at school, in holiday courses, coding clubs or on Future Day ("Zukunftstag"). In German and English.

**[▶ Open the workshop](https://rlen-source.github.io/skirennen/en/)** · **[✨ Play the demo](https://rlen-source.github.io/skirennen/ski-race-v3.html)** · **[📄 Info sheet (PDF)](https://rlen-source.github.io/skirennen/trainer-en.pdf)**

Everything is available in English: the launcher, all prompts, the teaching notes and both games. With the English prompts the AI answers in English too.

### What it's about

In this workshop kids experience how software is made with AI today: they describe what their game should do, the AI writes the code, and they check whether the result is right. No prior knowledge is needed – neither of programming nor of AI.

By the end every team has its own ski race – with its own course, its own player figure and its own ideas. And the kids have seen that AI is a tool: it does exactly what you tell it, and sometimes it makes mistakes you need to spot and fix.

### Where the workshop fits

Anywhere kids should get a first, positive experience of coding with AI, for example:

- **School:** in computer science or media lessons, during a project week, or as an introduction to AI
- **Holiday courses and coding clubs:** as a half day, or as the start of a series with the kids' own game ideas
- **Future Day and company events:** kids see how software is made in companies today. This is where the workshop started.
- **Libraries, youth work and family events:** with one laptop or tablet per team and an adult who handles the chat
- **At home:** parents and kids together – everything runs in the browser, and a saved version can be continued later

The plan is flexible: Part 1 alone takes about an hour, and Part 2 can be extended as long as you like.

### Why the workshop is built this way

Given a vague request, an AI writes something different every time. With ten teams you get ten different games – and when one breaks, nobody knows why. A workshop with kids therefore needs **reliable results**.

So the workshop rests on three ideas:

1. **A finished, stable base game to start with.** The kids don't build from scratch; they change a game that already works. There is something to play from the very first minute.
2. **A game with three clear areas:** settings, an area for their own ideas, and a game engine nobody touches. The AI always knows where it may work.
3. **Ready-made, precise prompts.** Every prompt tells the AI exactly what it may and may not change. The kids still understand what happens, because every step is explained in plain language.

The workshop was created for Future Day, when kids accompany adults to their workplace. The first version (2025) had the kids rebuild the game step by step. The quality of the generated code was not reliable enough. The current version therefore starts from the finished base game, and every Part 1 step only changes one or two numbers.

### What the kids learn

- **Describe precisely:** the clearer the prompt, the better the result. Goal, numbers and limits belong in it ("only change …, nothing else").
- **Check instead of trust:** every result is played and compared. Does it work? Did only the intended thing change?
- **Computational thinking:** break a game into parts (piste, gates, trees, camera), control it with numbers (speed, friction, distances), work with events ("when a gate is passed, then …") and tell world and screen coordinates apart.
- **Randomness with a seed:** with the same seed number everybody gets the same, fair course.
- **Mistakes are part of it:** when something breaks there is a repair prompt – and you learn how AI makes mistakes.
- **Teamwork:** explain ideas, decide together, show each other the games.

### Suggested plan (about 3 hours)

| Time | What happens |
|---|---|
| 15 min | Welcome, show the demo, form teams (2–3 kids per device) |
| 15 min | Try the base game, remember the best time, upload the file in the chat |
| 75 min | **Part 1:** eight steps – camera, piste, steering, rules, forest, own course |
| 15 min | Break |
| 45 min | **Part 2:** own ideas – snowfall, bear, player figure, colours, own idea |
| 15 min | Try each other's games, compare best times, short round: what was surprising? |

Part 1 can be shortened by skipping steps; Part 2 can be extended as long as you like.

### How the kids work

Everything happens on one page, the **launcher**. It runs on laptops and iPads, with no installation.

1. **Try the game:** on the start page choose "Try the game" and do one race.
2. **File into the chat:** in the Live Editor press "Download base game" and upload the file in a new chat.
3. **Pick a step and copy the prompt:** every step shows at the top, in plain language, what the AI should do. The rules that keep the game stable are copied along automatically.
4. **Test the answer:** paste the code from the answer into the Live Editor and press "▶ Show game". If it works, "✓ Works – next step" moves on.
5. **Part 2:** snowfall, a bear that chases you, a princess or a ninja, new colours, a combo display – or a completely new idea with the prompt generator.

#### If something goes wrong

- **The game has an error:** a red notice appears above the game with "Copy repair prompt". Paste it in the chat, test the new answer.
- **The answer stops halfway:** long answers are sometimes cut off. The launcher notices. Send the "↻ Continue" prompt and use "🧩 Append continuation" – the parts are joined automatically.
- **A step made it worse:** "↩ Previous version" brings back the last version.
- **Continue later:** "💾 Download my version" saves the game, "📂 Open file" loads it again – at home too.

### The demo

The [demo version](https://rlen-source.github.io/skirennen/ski-race-v3.html) shows at the start how far you can get: ski huts with smoking chimneys, mountain goats, marmots and hares, cheering spectators, stars to collect, a bear, an eagle and fireworks at the finish. The game engine is exactly the same as in the base game – everything new can be done with the Part 2 prompts.

### Preparation for trainers

- [ ] **Sort out chat access.** The kids need an AI chat such as ChatGPT or Claude that accepts file uploads. The providers have age limits, so the chat usually runs on the account of an adult sitting with the team.
- [ ] **Test the Wi-Fi.** The launcher loads from `rlen-source.github.io`, the game library from `cdn.jsdelivr.net` and the font from `fonts.googleapis.com`. School and company networks sometimes block one of them – open it once on a workshop device beforehand.
- [ ] **Do a run yourself**, at least Part 1 up to step 3, with the chat the kids will use.
- [ ] **Print the info sheet** and put it up: [English (PDF)](https://rlen-source.github.io/skirennen/trainer-en.pdf) · [German (PDF)](https://rlen-source.github.io/skirennen/trainer-de.pdf). The QR code leads straight to the launcher.
- [ ] **Trainer mode:** switch on "👩‍🏫 Trainer mode" at the bottom of the launcher, or open the link with `?trainer`. This shows goals, method and plan on the start page, and learning goals and discussion questions for every Part 1 step. Without it, kids only see the simple start page.

Good to know:

- A Part 1 step counts as done when a kid presses "✓ Works" in the Live Editor – not when the prompt is copied.
- Every AI answer contains the whole game (about 36,000 characters). That is on purpose: there are never half files. Free chat tiers sometimes cut long answers off – that's what "↻ Continue" is for.
- The prompts can be changed in the launcher code, in the lists `promptsTeil1` and `promptsTeil2`.

### iPad and tablet

- **Steering:** put a finger on the game and drag left and right; the skier follows. On a laptop use ← → or A / D.
- **As an app:** in Safari tap **Share → Add to Home Screen** to open the ski race with its own icon and no address bar.
- **Files:** downloads open the share sheet, so the file can go straight to the ChatGPT or Claude app or be saved to Files.
- Landscape works best.

### How the game is built

The game is a single HTML file using [p5.js](https://p5js.org). It has three areas:

1. **Settings (`CONFIG`)** – all numbers in one place: speed, number of gates, penalties, piste width, seed
2. **You may change this** – colours (`THEME`), player figure (`drawPlayer`), extras (`EXTRAS`) and events (`onGatePassed`, `onCrash`, …)
3. **Game engine – do not change** – physics, course, collisions, display

Extras are small building blocks that plug into the game: if an extra has an error, the engine switches off only that extra and the game keeps running.

All prompts were tested in simulated chats, in German and English: the AI changes exactly what is asked, the game engine stays the same character for character, and all resulting games run without errors.

### What's in here?

| File | Purpose |
|---|---|
| `en/index.html` | The English launcher – start page, Part 1, Part 2, Live Editor. Both games are built in. |
| `ski-race-v2.html` | The base game the kids start with |
| `ski-race-v3.html` | The demo version |
| `index.html`, `skirennen-v2.html`, `skirennen-v3.html` | The same in German |
| `trainer.html`, `trainer-en.pdf`, `trainer-de.pdf` | Info sheet with QR code |
| `docs/` | Pictures for this page |
