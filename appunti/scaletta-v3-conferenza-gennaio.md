# Scaletta v3 - Conferenza Minerva 9 Gennaio 2025

**Data**: Venerdì 9 Gennaio 2025, 10:00-11:30 (90 min)
**Brainstorm**: 18 Dicembre 2024
**Update**: Call 18 Dicembre 2024

---

## Struttura Completa

### 1. APERTURA - Gioco completamento/conoscenza (~3 min)

**Obiettivo**: Hook che riprenderai dopo per spiegare come funzionano gli LLM

| Domanda | Risposta pubblico | Cosa dimostra (dopo) |
|---------|-------------------|----------------------|
| "Mogli e buoi..." | Tutti | Pattern visto 1000 volte |
| "Tanto va la gatta..." | Tutti | Pattern visto 1000 volte |
| "Nel mezzo del cammin..." | Molti | Scuola |
| "Volume della sfera..." | Pochi (4/3 πr³) | Studiato, dimenticato |
| "Config Kubernetes..." | Nessuno | Mai visto |
| "2 + 2" | Tutti | → Tool calling (calcolatrice) |
| "234 × 12" | Pochi (2808) | → Tool calling palese |
| "Assessore sport Verbania" | Nessuno (o 1 locale) | → Limite conoscenza locale |
| "Che ore sono?" | Guardano orologio | → Tool calling (tempo reale) |
| "Che tempo fa?" | Guardano telefono | → Tool calling (API meteo) |
| "Prima pagina oggi?" | Nessuno | → Tool calling (ricerca web) |

---

### 2. INTRO PERSONALE (~1 min)

- "Sono un appassionato, non uno studioso/accademico"
- Toglie aspettativa di lezione frontale
- Crea vicinanza col pubblico

---

### 3. COINVOLGIMENTO PUBBLICO (~2 min)

**Opzioni interattive:**
- "Alzi la mano chi ha usato ChatGPT" (capisci il livello)
- "Alzi la mano chi ha paura dell'IA" (rompi il ghiaccio)
- Raccogli titoloni/headline che hanno visto
- Mini-sondaggio: "IA più opportunità o più minaccia?"
- Opzionale: post-it con paure/domande da ripescare dopo

---

### 4. BLOCCO ASIMOV + LIBRO PAPA' (~3 min)

**Testo:**

> Vi voglio parlare di questo signore qua, quello sulla locandina.
>
> Isaac Asimov. Nasce nel 1920 in Russia, in un paesino che manco esiste più. A 3 anni la famiglia emigra in America, cresce a Brooklyn.
>
> Studia chimica, si laurea a Columbia, fa il dottorato in biochimica. Quindi: uno scienziato, non un informatico. I computer ai suoi tempi occupavano stanze intere - pensate che la scheda del vostro microonde oggi ha più potenza di calcolo del computer che trent'anni dopo avrebbe portato l'uomo sulla Luna.
>
> Ma questo qui aveva una fantasia pazzesca. A 19 anni inizia a scrivere racconti di fantascienza e li vende alle riviste. Nel 1941 scrive una storia che lo rende famoso: "Nightfall", su un pianeta che vede il buio solo una notte ogni duemila anni.
>
> Ma la cosa per cui ce lo ricordiamo oggi sono i robot. Nel 1940 inizia a scrivere racconti sui robot - poi raccolti nel libro "Io, Robot" - e si inventa una cosa che non esisteva: le **Tre Leggi della Robotica**.
>
> Pensateci: nel 1942 questo signore si stava già chiedendo: "Se costruiamo macchine intelligenti, che regole gli diamo?"
>
> Ah, e sapete la parola "robotica"? L'ha inventata lui. Non esisteva prima.

**Momento emotivo**: Mostrare libro sull'IA ereditato da papà (Lele Fasoli)

---

### 5. DA ASIMOV A CHATGPT (~5 min)

**Struttura:**

**1. Il cervello come ispirazione** (30 sec)
> I ricercatori si sono chiesti: come fa il cervello? Miliardi di neuroni collegati tra loro, ognuno semplice, ma insieme fanno cose incredibili. Proviamo a copiarlo.

**2. Le reti neurali** (1 min)
> Anni '50-'60: costruiscono i primi "neuroni artificiali". Semplificazioni estreme del cervello. Funzionano, ma poco. Poi si bloccano - non riescono a farle imparare cose complesse.
>
> Per 20-30 anni: silenzio. Gli "inverni dell'IA" - tutti pensano sia un vicolo cieco.

**3. La svolta: più potenza, più dati** (1 min)
> Anni 2000-2010: i computer diventano abbastanza potenti. Internet genera montagne di dati. Le reti neurali tornano, e stavolta funzionano.
>
> 2012: una rete neurale riconosce le foto meglio degli umani. Boom.

**4. Il momento "cazzo, funziona"** (1 min)
> 2016: AlphaGo batte il campione mondiale di Go.
>
> Go non è scacchi - le combinazioni possibili sono più degli atomi nell'universo. Non puoi vincere a forza bruta. La macchina ha dovuto *imparare*.

**5. Arriviamo a ChatGPT** (1.5 min)
> 2017: un gruppo di ricercatori pubblica un paper con un titolo strano: "Attention Is All You Need". Inventano un'architettura nuova: i **Transformer**.
>
> Idea base: invece di leggere una frase parola per parola, guardi tutto insieme e capisci cosa è importante.
>
> 2020: GPT-3 - inizia a sembrare magia
>
> Novembre 2022: ChatGPT - e il mondo impazzisce

---

### 6. PAYOFF: TRANSFORMER = COMPLETAMENTO (~2 min)

Riprendi il gioco iniziale!

> "E come avete fatto voi all'inizio?
>
> I proverbi? Facilissimo. Li avete sentiti mille volte.
> Dante? Scuola, ce l'avete ancora in testa.
> Volume della sfera? Boh, l'avete studiato ma chi se lo ricorda.
> Kubernetes? Mai visto in vita vostra.
>
> **Ecco, l'LLM funziona uguale.** Completa quello che ha visto tante volte.
>
> Ma... 2+2? Quello l'avete detto tutti. E anche ChatGPT risponde 4.
>
> Solo che c'è un trucco: **lui non lo sa davvero.**
>
> Se gli chiedete 347 per 892, lui non calcola. Chiama la calcolatrice. Di nascosto."

---

### 7. AUTOCOMPLETE SMARTPHONE (~3 min)

> "Ok, ma come funziona 'sta cosa? Ve lo spiego con una roba che fate tutti i giorni.
>
> Prendete il telefono. Aprite WhatsApp. Scrivete 'Buong...'
>
> Cosa vi suggerisce? Buongiorno. Sempre.
>
> Perché? Perché il telefono ha VISTO quella sequenza miliardi di volte. Non è intelligente. È statistico. Ha imparato: dopo 'Buong' la gente scrive 'iorno'.
>
> Ecco, ChatGPT è QUESTO. Solo che invece di completare una parola, completa paragrafi interi.
>
> Ha letto libri, articoli, Wikipedia, forum, ricette. Milioni di testi.
>
> Quando gli chiedete 'scrivi ricetta carbonara', lui 'ricorda' di aver visto 10.000 ricette simili, e vi sputa fuori qualcosa che statisticamente assomiglia a una ricetta vera.
>
> **Non capisce cos'è il guanciale. Ma sa che nelle ricette della carbonara, il guanciale c'è sempre.**"

---

### 8. TOOL CALLING (~2 min)

Collegamento alle domande iniziali:

> "Le ore? Le avete dette a caso, o avete guardato l'orologio?
> Ecco, anche ChatGPT guarda l'orologio. Non le 'sa'. Le chiede a qualcuno.
>
> Vedete? Alcune cose le SAPETE perché le avete viste mille volte.
> Altre le CALCOLATE con uno strumento.
> Altre le CERCATE in tempo reale.
>
> ChatGPT fa UGUALE. Non è magia. È un sistema che:
> - Completa quello che ha letto
> - Chiama la calcolatrice quando serve
> - Cerca online quando non sa
>
> **Proprio come voi.**"

---

### 9. DEMO LIVE (~20 min)

**Accendi proiettore, Twitch streaming, apri ChatGPT**

| # | Demo | Cosa dimostra |
|---|------|---------------|
| **E** | "Voi per cosa lo usate? Cosa gli chiedete?" | Esplorativo, coinvolgi, scopri il livello |
| **Carbonara assurda** | "Voglio cuocere l'acqua nel colapasta" / "Uso pastelli invece di spaghetti" | Come reagisce GPT alle cazzate? → **Non fidarti ciecamente** |
| **Verbania** | Poesia su Verbania / Lago Maggiore | Locale, ridono, si sentono coinvolti |
| **Lettera** | Lettera al comune per le buche | Uso pratico. Poi: "riscrivila più incazzata" / "più formale" → **Puoi guidarlo e raffinare** |

---

### 10. AI vs AGI (~? min)

**Ispirazione**: Wait But Why "The AI Revolution" (2015)

**I 3 livelli:**

| Livello | Nome | Cosa fa | Esempio |
|---------|------|---------|---------|
| **ANI** | IA Ristretta | Bravissima in UNA cosa | ChatGPT, GPS, Netflix |
| **AGI** | IA Generale | Brava in TUTTO come un umano | Non esiste ancora |
| **ASI** | Super-Intelligenza | Più intelligente di tutti gli umani insieme | Fantascienza (per ora) |

**Concetti chiave:**

**1. L'analogia del viaggio nel tempo**
> "Immaginate di prendere un contadino del 1750 e portarlo nel 2024. Auto, aerei, smartphone. Muore di infarto.
>
> Ora, quel contadino torna nel 1750 e prende uno del 1500 e lo porta nel 1750. Shock? Sì, ma sopravvive. Il mondo è cambiato, ma non così tanto.
>
> Il progresso ACCELERA. Non va dritto, va in curva."

**2. Il problema del pensiero lineare**
- Collegare con: popolazione mondiale che si stabilizza, ricchezza che cresce
- Noi pensiamo che i prossimi 30 anni = ultimi 30 anni. Sbagliato.

**3. Da calcolatrice a dio**
> "Oggi abbiamo calcolatrici superintelligenti. Fanno UNA cosa benissimo.
> AGI sarebbe un umano artificiale.
> ASI? Sarebbe come spiegare internet a una formica."

**DA SVILUPPARE**: "L'uomo ha sempre cercato di creare Dio" (Prometeo, Golem, Frankenstein, Torre di Babele, "a immagine e somiglianza"). Oggi non più mito, è ingegneria. Chi decide le regole?

---

### 11. SHOWCASE TOOL (~? min)

| Tool | Cosa mostra |
|------|-------------|
| **Perplexity** | Ricerca conversazionale |
| **Google AI Mode** | IA dentro Google |
| **NotebookLM** | Podcast automatico da documenti |
| **Midjourney** | Generazione immagini |
| **Suno** | Generazione musica |
| **Gamma** | Presentazioni automatiche (opzionale) |

---

### 12. MULTIMODALITÀ (~3 min)

**Concetto chiave**: L'AI converte TUTTO in numeri.

> "Fino a poco fa l'AI capiva solo testo. Ora capisce e GENERA tutto: testo, immagini, audio, video.
>
> Il trucco? Converte TUTTO in numeri. Testo, immagini, audio - diventano tutti liste di numeri. Una volta che sono numeri, per l'AI è tutto uguale. Poi riconverte i numeri in quello che serve.
>
> È come un traduttore che parla 100 lingue: nella sua testa traduce tutto in una lingua segreta intermedia.
>
> Per questo ora funziona tutto insieme. Non sono 10 AI diverse - è UNA AI che parla tutte le lingue dei media."

**Schema visivo:**

```
FOTO 🖼️  ──→ [numeri] ──→ TESTO 📝
AUDIO 🎵 ──→ [numeri] ──→ TESTO 📝
TESTO 📝 ──→ [numeri] ──→ IMMAGINE 🖼️
```

---

### 13. AGENTE PERSONALE (~5 min)

**Obiettivo**: Far capire la differenza tra ChatGPT generico e un agente con contesto personale.

> "Questi tool che vi ho fatto vedere sono fighi. Ma hanno un limite: non vi conoscono.
>
> Se io chiedo a ChatGPT 'devo comprare un drone', mi dà una risposta generica. Tipo 'dipende dal budget, dall'uso...'
>
> Ma se avessi un assistente che SA che io ho un certo budget, che lo uso per foto aeree del lago, che ho già provato certi modelli... la risposta sarebbe completamente diversa.
>
> Stessa cosa per gli investimenti, per le email, per qualsiasi cosa.
>
> **Un agente personale è ChatGPT che ha letto il vostro diario.** Conosce il contesto. E questo cambia tutto."

**Behind the scenes** (battuta):
> "A proposito... questa presentazione? L'ho preparata insieme a un agente personale. Lui conosce Minerva, sa cosa ho fatto l'anno scorso, ricorda le domande che mi avete fatto. Non lo dico per vantarmi - lo dico perché è già realtà."

---

### 14. ETICA / FUTURO (~? min)

DA DEFINIRE

---

### 15. CHIUSURA / TAKE-HOME MESSAGE (~? min)

DA DEFINIRE - Una frase da portare a casa

---

## Timing Attuale

| Blocco | Min | Status |
|--------|-----|--------|
| 1-8. Apertura → Tool calling | ~21 | Sviluppato |
| 9. Demo live | ~20 | Struttura ok |
| 10. AI vs AGI | ~? | Struttura ok, "creare Dio" da sviluppare |
| 11. Showcase tool | ~? | Lista ok |
| 12. Multimodalità | ~3 | ✅ Sviluppato |
| 13. Agente Personale | ~5 | ✅ Sviluppato |
| 14. Etica/Futuro | ~? | Da definire |
| 15. Chiusura | ~? | Da definire |
| **TOTALE** | **~49+ min** | ~40 min per resto |

---

## Decisioni Call 18 Dicembre

- ~~Comet Browser~~: eliminato (concept figo, pratica inutilizzabile)
- ~~Sora Social~~: eliminato (non fa ciccia come contenuto)
- **Multimodalità**: spiegazione "tutto diventa numeri"
- **Agente Personale**: ponte dopo showcase ("questi tool fighi MA senza il vostro contesto")
- **Behind the scenes**: battuta veloce nel blocco Agente Personale

---

## Da Fare (Prossime Sessioni)

- [ ] Sviluppare "L'uomo cerca di creare Dio" (tema delicato)
- [ ] Definire blocco Etica/Futuro
- [ ] Definire Take-home message (1 frase)
- [ ] Timing preciso showcase tool + AI vs AGI
- [ ] Preparare demo live (account, link, backup)

---

## File Correlati

- `capitoli/capitolo-1-introduzione.md` (vecchia versione)
- `capitoli/capitolo-2-cos-e-ia.md` (vecchia versione)
- `capitoli/capitolo-3-applicazioni-pratiche.md` (vecchia versione)
- `log/2025/2025-12-03-minerva-brainstorm-conferenza-gennaio.md`
