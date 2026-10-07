# European Sports Data Science Outreach Strategy — Mohamed Aziz Khayati

**Goal:** a **6-month end-of-studies internship (PFE) starting January 2027** in data science / AI for a European football or basketball club, or a sports-tech company that works for clubs, with a full-time job afterwards as the target.
**Profile (from CV):** final-year engineering student at ESPRIT (Bac+5, Data Science, graduating 2027) · **8 years of basketball, 3 of them with Tunisia's national team** · internships at Sopra HR Software (data science), Naxxum Group, Elite.com · French C1, English C1, Arabic native, **German B1/B2** · internship agreement (*convention de stage*) provided by ESPRIT.
**Contact block for every email:** `+216 27 888 536 · medaziz.khayati@gmail.com · linkedin.com/in/khayati-mohamed-aziz1 · github.com/azizkhayati1`
**Last updated:** 2026-10-07

> **About contacts.** Clubs almost never publish a direct email for their analytics staff, and guessed addresses bounce or get flagged as spam. Below, every contact is marked:
> - ✅ **Official channel**: a careers portal or published application route. Use it.
> - 🔎 **Find the person**: the role to look up on LinkedIn, then confirm their address with Hunter.io, Apollo or RocketReach (free tiers are enough) before you send.
>
> Check every link before you use it. Club careers pages move often.

> ⏰ **Timing is tight.** Clubs and companies settle January internships between **October and early December**. The plan in section 5 is compressed to **8 weeks** for that reason. Start sending in week 2, not after the portfolio is finished.

---

## 1. Positioning: what you sell

Most applicants to club analytics teams are generic data analysts. You have three advantages. Lead with them in every message:

1. **Elite athlete:** 3 years on Tunisia's national basketball team. Coaches trust analysts who have played at a high level, and you can talk about the game with them as a peer.
2. **An engineer who ships decision tools, not just reports.** At Sopra HR you turned 6 messy sources into a prediction model's inputs, built a **scenario simulator** and a KPI dashboard, and covered it with 350 automated tests, all in 2 months.
3. **Languages:** French, English and **German**. This opens France, Belgium, Switzerland, Germany and Austria, where many non-EU applicants can't compete.

**One-line pitch (reuse everywhere):**
> *"Final-year Data Science engineer and former Tunisia national-team basketball player. I build models and decision tools that turn performance data into choices coaches can act on."*

### Your experience, in football and basketball terms

Clubs won't make the link themselves. Make it for them:

| On your CV | How to present it to a club |
|---|---|
| Sopra HR **turnover prediction** (structured 6 sources, fed 18 model variables) | Same pipeline as **player availability or injury-risk prediction**: messy medical, GPS and wellness sources turned into validated model inputs |
| Sopra HR **scenario simulator + KPI dashboard** | **Squad-planning or load-planning simulator**: "what if we add 3 sessions this week?" |
| Data-reliability work (schema checks, confidence per value, 17 missing cases flagged, not guessed) | Exactly what performance departments struggle with when cleaning tracking and wearable data |
| Naxxum **adaptive tests** (difficulty adjusts to each student's performance data) | **Individualised training load** that adjusts to each athlete's data |
| **Multi-agent systems** project (autonomous agents, compared with a baseline under different loads) | Basis for **tactical simulation**: players as agents, pressing and spacing scenarios |
| ARIMA / Prophet / LSTM / XGBoost forecasting | Forecasting **fatigue, form and injury risk** over a season |

---

## 2. Portfolio: one sports project, built while you send (weeks 1–4)

Your CV has no sports or computer vision project yet. **One** good public project fixes that and makes every email credible. Publish it on GitHub (`github.com/azizkhayati1`) with a README, results and a 60-second Loom or YouTube demo.

### Pick ONE

| Project | Sport | Stack | Why it fits you |
|---|---|---|---|
| **⭐ Shot-form analyzer**: pose estimation on your own jump shot (release angle, elbow alignment, knee-bend timing, release height, consistency across 100 reps), compared with make/miss | Basketball | MediaPipe or YOLOv8-pose, OpenCV, pandas, Streamlit | **Recommended.** It uses your national-team background, you can film it yourself, and it gives you real computer vision experience fast. |
| **Injury / availability risk model** on public or synthetic GPS-style load data (acute:chronic workload, sprint counts) with SHAP explanations and a FastAPI endpoint | Both | pandas, XGBoost, SHAP, FastAPI | The closest match to your Sopra HR work (prediction plus reliable data). Lowest risk. |
| **Pressing simulator**: multi-agent model of a pressing block, calibrated on StatsBomb 360 or SkillCorner open data | Football | Python, Mesa, mplsoccer | Reuses your multi-agent project. Unusual and memorable. |
| **Recruitment similarity tool**: find players statistically similar to a target profile | Football | StatsBomb open data, scikit-learn, Streamlit | Directly useful to scouting departments at selling clubs |

**Free data:** StatsBomb Open Data, SkillCorner Open Data, Metrica sample tracking data, the `euroleague-api` Python package, `nba_api`, and your own phone footage.

**Bonus (1 evening):** a LinkedIn post or Medium article about the project, e.g. *"I filmed 200 of my own jump shots and measured what changes when I miss"*. Tag #SportsAnalytics. Club analysts read these.

---

## 3. Target list (tiered by realistic chance of hiring)

Probability reflects: does the club have an in-house data team, does it hire juniors or interns, and can it take a non-EU intern with an internship agreement? These are my estimates, not data.

### Tier A — the most realistic first employer (apply first)

**Sports-tech companies.** They take many data and ML interns, often run proper internship programmes, and act as a bridge into clubs later.

| Company | Base | Why | Channel |
|---|---|---|---|
| **SkillCorner** | Paris 🇫🇷 | Broadcast tracking for football and basketball; French; accepts open applications | ✅ [Jobs + open application](https://www.welcometothejungle.com/en/companies/skillcorner/jobs) · 🔎 Head of Data / CTO |
| **Kinexon** | Munich 🇩🇪 | Basketball and handball tracking (EuroLeague, NBA); **your German helps** | ✅ kinexon.com/careers |
| **Hudl / StatsBomb** | London / Bath / remote 🇬🇧 | Biggest football data company | ✅ hudl.com/jobs · 🔎 Data science leads |
| **Catapult** | Leeds / global | Wearables and load monitoring | ✅ catapult.com/careers |
| **SciSports** | Amersfoort 🇳🇱 | Recruitment AI | ✅ scisports.com (careers) |
| **Sportradar (incl. Synergy basketball)** | St. Gallen 🇨🇭, Munich 🇩🇪, global | Basketball video and data, EuroLeague | ✅ sportradar.com/careers |
| **Stats Perform, Sportlogiq, Track160** | Various | Tracking and computer vision | ✅ their careers pages |
| **Twenty First Group, Analytics FC, Zelus (Teamworks)** | London | Club consultancies | ✅ careers pages · 🔎 founders |

### Tier B — clubs with data departments and junior/intern intakes

| Club | Country | Why it fits | Channel |
|---|---|---|---|
| **French clubs: Toulouse FC, RC Lens, LOSC Lille, Stade Rennais, OGC Nice, Olympique de Marseille, Paris FC** | 🇫🇷 | **Best fit for a PFE**: French C1 and an ESPRIT internship agreement; Toulouse has a data-driven owner (RedBird) | ✅ club "recrutement" pages · 🔎 Head of Data / Performance |
| **German clubs: TSG Hoffenheim, RB Leipzig, Bayer Leverkusen, VfB Stuttgart, Borussia Dortmund** | 🇩🇪 | Hoffenheim is a pioneer in sports tech; German B1/B2 is a real advantage | ✅ club "Karriere" / "Jobs" pages · 🔎 Leiter Datenanalyse / Performance |
| **Red Bull network (Leipzig, Salzburg)** | 🇩🇪🇦🇹 | Large central data group, German | ✅ redbull.com/jobs |
| **FC Midtjylland** | 🇩🇰 | Runs a **First Team Data Analyst Intern** programme (2026 cycle published) | ✅ fcm.dk, look for "First Team Data Analyst Intern" · 🔎 Head of Analytics |
| **Brentford FC, Brighton & Hove Albion** | 🏴 | Data-first clubs | ✅ club careers pages · 🔎 Head of Performance Insights |
| **AZ Alkmaar** | 🇳🇱 | Has hired "Football Data Scientists" ([example](https://apfa.io/job/az-alkmaar-alkmaar-netherlands-46-football-data-scientist)) | ✅ az.nl vacancies |
| **SL Benfica (Benfica LAB)** | 🇵🇹 | Innovation and sports science centre | ✅ slbenfica.pt · 🔎 Benfica LAB leads |
| **FC Barcelona: Barça Innovation Hub** | 🇪🇸 | Research and startup calls, **football and basketball** | ✅ barcainnovationhub.fcbarcelona.com · first.last@fcbarcelona.cat format ([source](https://www.clay.com/dossier/fc-barcelona-email-format)): **verify before sending** |
| **Southampton, Everton, Crystal Palace** | 🏴 | Posted data scientist/analyst roles in 2026 | ✅ club careers pages, [Jobs in Football](https://jobsinfootball.com/categories/data-science/) |

### Tier C — basketball (fewer roles, but your story is strongest here)

| Club | Country | Channel |
|---|---|---|
| **ASVEL Lyon-Villeurbanne, Paris Basketball, AS Monaco Basket** | 🇫🇷/🇲🇨 | ✅ club sites · 🔎 GM / performance director / video coordinator (write in French) |
| **FC Bayern Basketball, ALBA Berlin** | 🇩🇪 | 🔎 Athletiktrainer / video coordinator (German); ALBA is known for youth development |
| **FC Barcelona Basket** | 🇪🇸 | Via Barça Innovation Hub (above) |
| **Real Madrid Baloncesto** | 🇪🇸 | ✅ realmadrid.com, Trabaja con nosotros |
| **Fenerbahçe, Anadolu Efes** | 🇹🇷 | 🔎 performance/analytics staff |
| **Olympiacos, Panathinaikos, Žalgiris Kaunas, Partizan, Crvena Zvezda** | 🇬🇷🇱🇹🇷🇸 | 🔎 video coordinator / assistant coach |
| **EuroLeague (league office)** | 🇪🇸 Barcelona | ✅ [EuroLeague jobs (Personio)](https://euroleague-entertainment-services-slu.jobs.personio.de/job/2672764) |
| **FIBA** | 🇨🇭 Mies | ✅ fiba.basketball/jobs |
| **French Basketball Federation (FFBB) / LNB** | 🇫🇷 | 🔎 performance / data staff, in French |

> **Basketball tip:** many EuroLeague clubs have no "data scientist" at all. Analytics is done by the **video coordinator or an assistant coach**. Pitch yourself as *"a former national-team player who can automate shot and load analysis"*, not as a "data scientist".

### Job boards to check weekly
- [Jobs in Football: data science](https://jobsinfootball.com/categories/data-science/)
- [APFA](https://apfa.io/) (Association of Professional Football Analysts)
- [Welcome to the Jungle](https://www.welcometothejungle.com/), search "stage data sport", for French sports-tech
- LinkedIn alerts: "stage data analyst sport", "football data scientist intern", "Praktikum Datenanalyse Sport", "performance analyst intern"
- TeamWork Online (Europe), Global Sports Jobs

---

## 4. How to find the right person (15 minutes per club)

1. Search LinkedIn for `"<Club name>" AND (data OR analytics OR "performance" OR "video coordinator")`.
2. Pick **two people**: the head of the department (decision-maker) and someone 1–3 years in (who will actually read your email and pass it on).
3. Find their email: Hunter.io domain search, then the pattern (e.g. `firstname.lastname@club.com`), then **verify with Hunter's verifier**. Don't send if the address isn't verified.
4. Send a LinkedIn connection request with a short note (template E), **then** the email 2–3 days later.

Track everything in a sheet with these columns: `Club | Tier | Country | Language | Person | Role | Email (verified?) | LinkedIn | Date sent | Follow-up 1 | Follow-up 2 | Status | Notes`.

---

## 5. Sending plan (8 weeks, for a January 2027 start)

| Week | Dates (approx.) | Action | Volume |
|---|---|---|---|
| 1 | 7–14 Oct | Update LinkedIn headline to the one-line pitch; make a sports version of the CV (section 8); start the project; apply through portals to every open Tier A/B internship | all open roles |
| 2 | 14–21 Oct | Cold emails to **Tier A** (sports-tech), with the project marked "in progress" | 10 |
| 3 | 21–28 Oct | Cold emails to **French and German clubs** (Tier B), in their language | 12 |
| 4 | 28 Oct–4 Nov | **Publish the project and demo**; follow-up 1 to weeks 2–3, **with the demo link** | follow-ups |
| 5 | 4–11 Nov | Cold emails to **Tier C** (basketball) + other Tier B clubs | 12 |
| 6 | 11–18 Nov | Follow-up 2 to weeks 2–3; follow-up 1 to week 5; LinkedIn post about the project | follow-ups |
| 7–8 | 18 Nov–2 Dec | Second wave to colleagues of non-responders; interviews; start visa paperwork as soon as you have an offer | 10–15 |

**Rules**
- **Send Tuesday–Thursday, 08:30–10:00 club local time** (CET, or GMT for the UK).
- Write **one email per person**, never BCC'd. Mention something specific to their club in the first line.
- Send **two follow-ups at most**, each adding something new (the demo, a small analysis of their team).
- Write in **French** to French, Belgian and Swiss-French clubs, and in **German** (or English, with a German closing line) to German and Austrian clubs. Use English for everyone else.
- Attach the CV as a **PDF named `Khayati_Aziz_CV_Sports_Data_Science.pdf`**. Put the demo **link** in the body, never a video attachment.
- Clubs are busiest from June to August, so October–March is the best period, which matches your timeline.

**Events and communities**
- Barça Sports Tech / Innovation Hub events (Barcelona), StatsBomb Conference (London), Sport Unlimited Tech (Lille / Paris)
- Online: "Friends of Tracking" (YouTube), the Soccermatics/Twelve community, EuroLeague analytics on X and LinkedIn

---

## 6. Visa: make it easy for them

Your status as an **intern with an ESPRIT internship agreement** is the easiest case for an employer. Say so in every email.

- **France:** "stagiaire" long-stay visa (VLS-TS stagiaire), based on the tripartite internship agreement (ESPRIT, host, you). The host only signs the agreement and pays the legal internship stipend (*gratification*). This is the **easiest route**, so prioritise French targets.
- **Germany:** internships that are a mandatory part of a foreign degree usually go through a simplified process with the Federal Employment Agency (BA). Check with the German embassy in Tunis. After graduation: EU Blue Card, or the Opportunity Card (Chancenkarte) to job-hunt locally.
- **Netherlands / Denmark / UK:** possible but heavier (sponsor registration, UK Temporary Worker or Skilled Worker visas). Keep them in Tier B, but don't count on them.
- **Fallback:** a remote internship with a European company, if the agreement allows it. Ask ESPRIT.

Sentence for your emails: *"ESPRIT provides the internship agreement, and I will handle the visa application myself to keep the process simple for your team."*

---

## 7. Email templates (filled in from your CV)

Keep cold emails **under 150 words**. Replace only the `[club-specific]` parts. **Until the project is published, use the "in progress" sentence; afterwards, swap in the demo link.**

### A. Cold email: football club data / performance department (English)

**Subject:** Former Tunisia national-team athlete, data science intern (Jan 2027) for [Club]

> Hi [First name],
>
> I'm Aziz Khayati, a final-year Data Science engineering student at ESPRIT (Tunis) and a former Tunisia national-team basketball player (3 years).
>
> [Club-specific line, e.g. "Brentford's use of data in recruitment is the reason I'm writing."] This summer at Sopra HR Software, I built a prediction pipeline from 6 messy data sources plus a scenario simulator for decision-makers. The same approach applies to player availability and load planning. I'm now building [project name]: [demo link / "demo available early November"].
>
> I'm looking for a **6-month end-of-studies internship from January 2027**. ESPRIT provides the internship agreement, and I'll handle the visa myself.
>
> Would you have 15 minutes in the next two weeks?
>
> Best regards,
> Aziz Khayati
> +216 27 888 536 · linkedin.com/in/khayati-mohamed-aziz1 · github.com/azizkhayati1

### B. Cold email: basketball club (to video coordinator / performance staff)

**Subject:** Former Tunisia NT player: shot-form analysis from training video, [Club]

> Hi [First name],
>
> I played basketball for 8 years, including 3 with Tunisia's national team, and I'm now a final-year Data Science engineer at ESPRIT.
>
> I'm building a tool that measures shooting mechanics (release angle, elbow alignment, timing and consistency across reps) from ordinary training video: [demo link / "first results in early November"]. For a video staff, it means shot-form reports on every player after each session, with no manual tagging.
>
> I'm looking for a 6-month internship from January 2027 and would love to build this with [Club]'s staff, on your footage. ESPRIT provides the internship agreement, and I'll handle the visa myself.
>
> Could I send you a sample report?
>
> Best regards,
> Aziz Khayati
> +216 27 888 536 · linkedin.com/in/khayati-mohamed-aziz1 · github.com/azizkhayati1

### C. French: clubs and companies in France, Belgium, Switzerland, Monaco

**Objet :** Stage de fin d'études Data (janv. 2027) : ancien international tunisien de basket – [Club]

> Bonjour [Prénom],
>
> Je m'appelle Aziz Khayati, élève ingénieur en dernière année à ESPRIT (spécialité Data Science) et ancien joueur de l'équipe nationale tunisienne de basket (3 ans).
>
> [Phrase spécifique : « L'approche data du TFC en recrutement est la raison de mon message. »] Cet été, chez Sopra HR Software, j'ai construit un pipeline de prédiction à partir de six sources hétérogènes, ainsi qu'un simulateur de scénarios pour aider à la décision. C'est la même logique que la prédiction de disponibilité des joueurs ou la planification de la charge. Je développe actuellement [nom du projet] : [lien démo / « démo disponible début novembre »].
>
> Je recherche un **stage de fin d'études de 6 mois à partir de janvier 2027**. ESPRIT fournit la convention de stage et je me charge moi-même de la demande de visa.
>
> Auriez-vous 15 minutes dans les deux prochaines semaines ?
>
> Cordialement,
> Mohamed Aziz Khayati
> +216 27 888 536 · linkedin.com/in/khayati-mohamed-aziz1 · github.com/azizkhayati1

### D. German: clubs and companies in Germany and Austria

> Have a German speaker check this before sending (your level is B1/B2). Better a short, correct German email than a long one with mistakes. Replying in English afterwards is fine.

**Betreff:** Pflichtpraktikum Data Science (ab Januar 2027) – ehemaliger tunesischer Basketball-Nationalspieler – [Verein]

> Hallo [Vorname],
>
> mein Name ist Aziz Khayati. Ich studiere im letzten Jahr Informatik (Schwerpunkt Data Science) an der ESPRIT in Tunis und habe drei Jahre in der tunesischen Basketball-Nationalmannschaft gespielt.
>
> Bei Sopra HR Software habe ich eine Vorhersage-Pipeline aus sechs heterogenen Datenquellen und einen Szenario-Simulator für Entscheidungsträger entwickelt. Derselbe Ansatz lässt sich auf Belastungssteuerung und Verletzungsprävention übertragen. Aktuelles Projekt: [Projektname] – [Link].
>
> Ich suche ein **sechsmonatiges Pflichtpraktikum ab Januar 2027**. Die ESPRIT stellt den Praktikumsvertrag aus, und um das Visum kümmere ich mich selbst.
>
> Hätten Sie in den nächsten zwei Wochen 15 Minuten Zeit? Gerne auch auf Englisch.
>
> Viele Grüße
> Mohamed Aziz Khayati
> +216 27 888 536 · linkedin.com/in/khayati-mohamed-aziz1 · github.com/azizkhayati1

### E. Sports-tech company (SkillCorner, Kinexon, Hudl…): open application

**Subject:** Data Science intern (6 months, from Jan 2027): athlete + engineer

> Hi [First name],
>
> [Company]'s [product, e.g. "broadcast tracking data"] is exactly the work I want to do. I'm a final-year Data Science engineering student at ESPRIT and a former Tunisia national-team basketball player.
>
> Relevant experience: at Sopra HR Software, I turned 6 heterogeneous sources into validated model inputs, with schema checks, per-value confidence and 350 automated tests, and shipped a scenario simulator in 2 months. I've also built forecasting models (XGBoost, LSTM, Prophet, ARIMA). Sports project: [project + link].
>
> I'm looking for a 6-month internship from January 2027 in [city]. ESPRIT provides the internship agreement, and I'll handle the visa myself. CV attached.
>
> Would you be open to a short call?
>
> Best regards,
> Aziz Khayati

### F. LinkedIn connection note (≤ 300 characters)

> Hi [Name], former Tunisia national-team basketball player and final-year Data Science engineer. I'm building performance-analysis tools and looking for a Jan 2027 internship in sports data. I really admire [Club]'s work on [X] and would love to connect.

French: *Bonjour [Prénom], ancien international tunisien de basket et élève ingénieur Data Science en dernière année. Je développe des outils d'analyse de la performance et je cherche un stage dès janvier 2027. J'admire le travail de [Club] sur [X] et serais ravi d'échanger.*

### G. Follow-up 1 (about 7 days later, reply in the same thread)

> Hi [First name], a quick follow-up with something concrete: I've just published [project name] ([demo link]). In short: [one result, e.g. "my release angle drops 4° on missed shots late in a session"]. Happy to adapt it to [Club]'s data.
> Best, Aziz

### H. Follow-up 2 (about 14 days later, final)

> Hi [First name], I know this period is busy, so this is my last note. If a January 2027 intern could help [department], I'd love to talk. Otherwise, could you point me to the right colleague?
> Thanks again, Aziz

### I. Cover letter for a posted job (English, about 1 page)

> Dear [Hiring Manager / Head of Performance],
>
> I'm applying for the **[Role]** at [Club]. I spent 8 years in basketball, including 3 with Tunisia's national team, and I'm now finishing my engineering degree in Data Science at ESPRIT. I know the performance environment from the inside, and I want to build the tools that support it.
>
> This summer at Sopra HR Software, I turned six heterogeneous sources (CSVs, PDFs, scanned documents) into validated inputs for a prediction model, and built a scenario simulator and KPI dashboard so decision-makers could test hypotheses before acting. I treated data reliability as the priority: of 143 documents tested, all 17 cases of missing data were flagged rather than guessed. The work was delivered in two months, in direct contact with end users. That is the same discipline a performance department needs with tracking, GPS and wellness data.
>
> I've also built forecasting models (ARIMA, Prophet, LSTM, XGBoost) and an agent-based simulation project, and I'm currently building [sports project + link]. Just as important, I can explain models to coaches and players in their own language, because I used to be one of those players.
>
> I'm available for a 6-month internship from January 2027. ESPRIT provides the internship agreement, and I'll handle the visa application myself. I'd welcome the chance to discuss how I could support [Club]'s [specific goal from the posting].
>
> Kind regards,
> Mohamed Aziz Khayati

---

## 8. CV changes for sports roles

Your current CVs are tailored to SeatGeek (data analyst) and Etyo (supply chain). Make a sports version, with an English and a French copy:

- **Title line:** "Data Science Intern, Sports Performance | Former Tunisia National Basketball Team Player | Available Jan 2027 (6 months)"
- **Move basketball up.** Today it's one line at the very bottom. Make it a short **"Sport"** section right under the profile: *8 years of basketball, 3 years with Tunisia's national team*, plus competitions, position and any captaincy.
- **Add a "Sports Data Project" section** above experience, with the GitHub and demo links.
- **Reword the Sopra HR bullets** in performance language (see the table in section 1): "prediction pipeline from heterogeneous sources", "scenario simulator for decision-makers", "data-reliability checks".
- **Skills:** bring Python, scikit-learn, XGBoost, LSTM, Prophet and FastAPI to the front. Add "tracking/event data" and "pose estimation" **only once the project is done**. Drop Oracle APEX, Symfony, Java and C++ from the sports version.
- **Remove the ESPRIT admissions internship** from the sports version to save space.
- Keep it to one page, PDF only.

---

## 9. Realistic expectations

- About 60 well-targeted emails usually lead to roughly 8–12 replies, 3–5 calls and 1–2 offers. A published sports project moves these numbers more than anything else.
- **Most likely outcome:** a January internship at a **French or German sports-tech company or a data-driven mid-size club**, then a job offer after the internship (many clubs hire their PFE interns).
- **If nothing is signed by early December:** take the best data internship you can get (like Etyo), keep the sports project going on the side, and run this plan again in spring 2027 for full-time roles after graduation. Your project and contacts will carry over.
- Every reply, even a no, is a contact. Ask each one: *"Who else should I speak to?"*

---

### Sources
- [FC Midtjylland: First Team Data Analyst Intern 2026](https://www.fcm.dk/app/uploads/First-Team-Data-Analyst-Intern-2026.pdf)
- [Everton: Data Scientist, Men's First Team](https://www.uksport.gov.uk/global/jobs/everton-football-club/2026/01/02/data-scientist--mens-first-team)
- [AZ Alkmaar: Football Data Scientist](https://apfa.io/job/az-alkmaar-alkmaar-netherlands-46-football-data-scientist)
- [Jobs in Football: Data Science](https://jobsinfootball.com/categories/data-science/)
- [Euronews: UK club data hiring (Aug 2026)](https://euronews.com/business/2026/08/24/why-is-uk-football-club-hiring-booming-with-data-analyst-roles-surging)
- [SkillCorner jobs](https://www.welcometothejungle.com/en/companies/skillcorner/jobs)
- [EuroLeague jobs](https://euroleague-entertainment-services-slu.jobs.personio.de/job/2672764)
- [FC Barcelona email format](https://www.clay.com/dossier/fc-barcelona-email-format)
