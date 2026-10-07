# European Sports Data Science Outreach Strategy — Aziz Khayati

**Goal:** a data science / AI / computer vision role (internship, then a full-time job) with a European football or basketball club, or with a sports-tech company that works for clubs.
**Starting point:** based in Tunisia, needs visa sponsorship, former Tunisian basketball national team player, plays football, strong in data science and AI.
**Last updated:** 2026-10-07

> **About contacts.** Clubs almost never publish a direct email for their analytics staff, and guessed addresses bounce or get flagged as spam. Below, every contact is marked:
> - ✅ **Official channel**: a careers portal or published application route. Use it.
> - 🔎 **Find the person**: the role to look up on LinkedIn, then confirm their address with Hunter.io, Apollo or RocketReach (free tiers are enough) before you send.
>
> Check every link before you use it. Club careers pages move often.

---

## 1. Positioning: what you sell

Most club applicants are generic data analysts. You have three things that set you apart. Lead with them in every message:

1. **Elite athlete:** you played for Tunisia's basketball national team. Coaches trust analysts who have played at a high level, and you can talk about the game with them as a peer.
2. **AI and computer vision skills,** not only spreadsheets and dashboards. Clubs' in-house teams are strong on event data but weak on video and pose models.
3. **A working demo** (section 2). This matters more than anything else. A 60-second video of your model running on real footage beats any CV.

**One-line pitch (reuse everywhere):**
> *"Former Tunisia national-team basketball player turned AI engineer. I build computer-vision tools that turn training video into measurable feedback on shooting form, sprint mechanics and decisions."*

---

## 2. Build the portfolio before you send anything (weeks 1–4)

Cold emails with a demo link get replies. Cold emails without one mostly don't. Build **one main project and one smaller one**, and publish them on GitHub with a short Loom or YouTube video.

### Main project: pick ONE, matched to your target sport

| Project | Sport | Stack | Why clubs care |
|---|---|---|---|
| **Shot-form analyzer**: pose estimation on a jump shot (release angle, elbow alignment, knee-load timing, release height, consistency across reps), checked against make/miss | Basketball | MediaPipe / YOLOv8-pose / RTMPose, OpenCV, Python, Streamlit | Your own background makes the story credible. Film yourself. |
| **Broadcast tracking → tactical metrics**: player and ball detection, homography to a 2D pitch, then pressing intensity, line height and space control | Football | YOLOv8 + ByteTrack, homography, `mplsoccer`, SkillCorner open data | The exact problem SkillCorner, Second Spectrum and in-house teams solve |
| **Injury-risk / load model** from GPS-style data (acute:chronic workload, sprint counts) | Both | pandas, scikit-learn / XGBoost, SHAP | What sports science departments need |
| **Recruitment similarity model**: find undervalued players like a target profile | Football | StatsBomb open data, embeddings, clustering | Directly useful to scouting departments, especially at selling clubs |

### Smaller project: an analysis write-up
Publish one piece on Medium or Substack, for example *"What EuroLeague shooting data says about the Tunisian-style 3-point game"* or *"Pressing profiles of the Eredivisie, 2025/26"*. Post it on LinkedIn and on X under #SportsAnalytics. Club analysts read these.

**Free data:** StatsBomb Open Data, SkillCorner Open Data, Metrica sample tracking data, the `euroleague-api` Python package, `nba_api`, and your own phone footage.

---

## 3. Target list (tiered by realistic chance of hiring)

Probability reflects: does the club have an in-house data team, does it hire juniors or interns, and does it sponsor non-EU staff? These are my estimates, not data.

### Tier A — the most realistic first employer (apply first)

**Sports-tech companies.** They hire many CV and ML engineers, often remotely, sponsor visas more readily than clubs, and act as a bridge into clubs later.

| Company | Base | Why | Channel |
|---|---|---|---|
| **SkillCorner** | Paris | Broadcast tracking, already in football and basketball | ✅ [Jobs + open application](https://www.welcometothejungle.com/en/companies/skillcorner/jobs) · 🔎 Head of CV / CTO |
| **Hudl / StatsBomb** | Bath / London / remote | Biggest football data company | ✅ hudl.com/jobs · 🔎 Data science leads |
| **Kinexon** | Munich | Basketball and handball tracking (EuroLeague, NBA) | ✅ kinexon.com/careers |
| **Catapult** | Leeds / global | Wearables and video | ✅ catapult.com/careers |
| **SciSports** | Amersfoort, NL | Recruitment AI | ✅ scisports.com (careers) |
| **Track160 / Sportlogiq / Stats Perform** | Various | Tracking and CV | ✅ their careers pages |
| **Synergy Sports (Sportradar)** | Global | Basketball video and data, EuroLeague | ✅ sportradar.com/careers |
| **Twenty First Group, Zelus Analytics (Teamworks), Analytics FC** | London | Club consultancies | ✅ careers pages · 🔎 founders |

### Tier B — clubs known for data departments and junior/intern intakes

| Club | Country | Why it fits | Channel |
|---|---|---|---|
| **FC Midtjylland** | 🇩🇰 | Runs a **First Team Data Analyst Intern** programme (2026 cycle published) | ✅ fcm.dk, look for "First Team Data Analyst Intern" · 🔎 Head of Analytics |
| **Brentford FC** | 🏴 | Data-first; offers a PhD studentship in data science | ✅ brentfordfc.com, Careers · 🔎 Head of Performance Insights |
| **Brighton & Hove Albion** | 🏴 | Strong data culture (Starlizard link) | ✅ brightonandhovealbion.com, Careers |
| **AZ Alkmaar** | 🇳🇱 | Has hired "Football Data Scientists" ([example](https://apfa.io/job/az-alkmaar-alkmaar-netherlands-46-football-data-scientist)) | ✅ az.nl vacancies |
| **Toulouse FC** | 🇫🇷 | Data-driven owner (RedBird); **French helps** | ✅ toulousefc.com, recrutement · 🔎 Head of Data |
| **RC Lens, LOSC Lille, Stade Rennais, OGC Nice, Olympique de Marseille** | 🇫🇷 | French-speaking advantage; growing data teams | ✅ club "recrutement" pages · 🔎 Data/performance leads |
| **SL Benfica (Benfica LAB)** | 🇵🇹 | Benfica LAB innovation and sports science centre | ✅ slbenfica.pt · 🔎 Benfica LAB leads |
| **FC Barcelona: Barça Innovation Hub** | 🇪🇸 | Innovation hub, startup and research calls, **football and basketball** | ✅ barcainnovationhub.fcbarcelona.com (programmes, calls) · first.last@fcbarcelona.cat format ([source](https://www.clay.com/dossier/fc-barcelona-email-format)): **verify before sending** |
| **Southampton, Everton, Crystal Palace** | 🏴 | Posted data scientist/analyst roles in 2026 | ✅ club careers pages, [Jobs in Football](https://jobsinfootball.com/categories/data-science/) |
| **Red Bull football network (Leipzig, Salzburg)** | 🇩🇪🇦🇹 | Large central data group | ✅ redbull.com/jobs |

### Tier C — basketball (fewer roles, but your story is strongest here)

| Club | Country | Channel |
|---|---|---|
| **FC Barcelona Basket** | 🇪🇸 | Via Barça Innovation Hub (above) |
| **Real Madrid Baloncesto** | 🇪🇸 | ✅ realmadrid.com, Trabaja con nosotros |
| **ASVEL Lyon-Villeurbanne** | 🇫🇷 | ✅ ldlcasvel.com · 🔎 performance staff (French) |
| **AS Monaco Basket, Paris Basketball** | 🇫🇷/🇲🇨 | 🔎 GM / performance director (French) |
| **Fenerbahçe, Anadolu Efes** | 🇹🇷 | 🔎 performance/analytics staff |
| **Olympiacos, Panathinaikos** | 🇬🇷 | 🔎 video/analytics coordinator |
| **Žalgiris Kaunas, Partizan, Crvena Zvezda** | 🇱🇹🇷🇸 | 🔎 video coordinator / assistant coach |
| **EuroLeague (league office)** | 🇪🇸 Barcelona | ✅ [EuroLeague jobs (Personio)](https://euroleague-entertainment-services-slu.jobs.personio.de/job/2672764) |
| **FIBA** | 🇨🇭 Mies | ✅ fiba.basketball/jobs |

> **Basketball tip:** many EuroLeague clubs have no "data scientist" at all. Analytics is done by the **video coordinator or an assistant coach**. Pitch yourself as *"a video coordinator who can automate shot and form analysis"*, not as a "data scientist".

### Job boards to check weekly
- [Jobs in Football: data science](https://jobsinfootball.com/categories/data-science/)
- [APFA](https://apfa.io/) (Association of Professional Football Analysts)
- TeamWork Online (Europe filter), Global Sports Jobs, LinkedIn alerts: "football data scientist", "performance analyst", "computer vision sport"
- [Welcome to the Jungle](https://www.welcometothejungle.com/), for French sports-tech

---

## 4. How to find the right person (15 minutes per club)

1. Search LinkedIn for `"<Club name>" AND (data OR analytics OR "performance insights" OR "video coordinator")`.
2. Pick **two people**: the head of the department (decision-maker) and someone 1–3 years in (who will actually read your email and pass it on).
3. Find their email: Hunter.io domain search, then the pattern (e.g. `firstname.lastname@club.com`), then **verify with Hunter's verifier**. Don't send if the address isn't verified.
4. Send a LinkedIn connection request with a 300-character note (template E), **then** the email 2–3 days later.

Track everything in a sheet with these columns: `Club | Tier | Person | Role | Email (verified?) | LinkedIn | Date sent | Follow-up 1 | Follow-up 2 | Status | Notes`.

---

## 5. Sending plan (12 weeks)

| Week | Action | Volume |
|---|---|---|
| 1–4 | Build the main project, record the demo, update LinkedIn headline to the one-line pitch, publish the write-up | — |
| 3 | Apply through official portals to every open Tier A/B role | all open roles |
| 5 | Cold emails to **Tier A** (sports-tech) | 10 |
| 6 | Cold emails to **Tier B** (football clubs) | 10 |
| 7 | Cold emails to **Tier C** (basketball) + follow-ups for week 5 | 8 + follow-ups |
| 8–9 | Follow-ups, second project, post results on LinkedIn | — |
| 10–12 | Second wave to non-responders' colleagues, conferences (below) | 10–15 |

**Rules**
- **Send Tuesday–Thursday, 08:30–10:00 club local time** (CET, or GMT for the UK).
- Write **one email per person**, never BCC'd. Mention something specific to their club in the first line.
- Send **two follow-ups at most**: day 5–7 and day 14. Each one must add something new (a new result, a club-specific mini-analysis).
- Write in **French** to French clubs, and in English to everyone else.
- Attach the CV as a **PDF named `Aziz_Khayati_CV_Sports_Data_Science.pdf`**. Put the demo **link** in the body, never a video attachment.
- **Avoid** the window from 1 June to 1 September (transfer window and preseason) for clubs. October–March is best.

**Events where you can meet the people above**
- Barça Sports Tech Conference / Innovation Hub events (Barcelona)
- StatsBomb Conference (London), OptaForum, Sloan's European counterparts
- MIT Sloan Sports Analytics Conference (research paper track, which accepts remote submissions)
- Online communities: "Friends of Tracking", the Soccermatics/Twelve community, EuroLeague analytics Twitter/X

---

## 6. Visa and location: address it before they ask

Clubs drop non-EU candidates when sponsorship looks complicated. Make it simple for them:

- **Say you are open to remote or contract work first** (paid via Deel or as a freelancer). It costs them almost nothing to try you.
- **France:** the *Passeport Talent* visa and a VIE-style internship agreement. An internship needs a *convention de stage*, so if you are a student or graduate of a Tunisian university, ask your school for one. Tunisian–French bilateral agreements help.
- **Germany:** EU Blue Card (lower salary threshold for IT), Opportunity Card (Chancenkarte) to job-hunt locally.
- **Netherlands:** Highly Skilled Migrant permit (sponsor must be registered; Ajax, PSV and AZ often are).
- **Denmark:** Pay Limit / Fast-track scheme (FC Midtjylland).
- **UK:** Skilled Worker visa (Premier League clubs are sponsors). The Graduate route applies only to UK graduates.
- **Fallback:** a one-year **Master's in Sports Analytics** at a European university (e.g. Johan Cruyff Institute, Barcelona; Loughborough; INEFC). The degree comes with internships and a post-study work permit.

One sentence for your emails: *"I'm available to start remotely immediately, and I'm eligible for [EU Blue Card / Passeport Talent] for an on-site role."*

---

## 7. Email templates

Replace everything in `[brackets]`. Keep cold emails **under 150 words**.

### A. Cold email: football club data / performance department (English)

**Subject:** Ex-national team athlete + computer vision: [project name] for [Club]

> Hi [First name],
>
> I'm Aziz Khayati, a former Tunisia national-team basketball player and data scientist specialising in AI and computer vision.
>
> I've followed [specific thing: e.g. "Brentford's set-piece work" / "FCM's analytics internship"] and built something in that direction: **[project name]**, a model that [one-line result, e.g. "turns broadcast footage into pressing-intensity and line-height metrics per phase"]. 60-second demo: [link]
>
> I'd love to contribute to [Club]'s [department], as an intern, on a project basis, or remotely to start. I'm based in Tunisia and eligible for [visa route].
>
> Would you have 15 minutes in the next two weeks? I'd be happy to run the model on a [Club] match first.
>
> Best,
> Aziz Khayati
> [LinkedIn] · [GitHub] · [phone, with +216]

### B. Cold email: basketball club (to video coordinator / assistant coach)

**Subject:** Former Tunisia NT player: automated shot-form analysis for [Club]

> Hi [First name],
>
> I played for Tunisia's national basketball team for [X] years and now work in AI. I built a computer-vision tool that measures shooting mechanics (release angle, elbow alignment, timing and consistency across reps) from ordinary training video: [demo link]
>
> For a video staff, it means [benefit: "shot-form reports on every player after each session, with no manual tagging"].
>
> I'd like to offer [Club] a free 2-week pilot on your training footage, remotely, with no commitment. If it's useful, I'd love to discuss a longer role.
>
> Could I send you a sample report?
>
> Best regards,
> Aziz Khayati
> [LinkedIn] · [GitHub] · [phone]

### C. Cold email in French (French clubs: Toulouse, Lens, Lille, Rennes, ASVEL, Monaco…)

**Objet :** Ancien international tunisien de basket & IA – [nom du projet] pour [Club]

> Bonjour [Prénom],
>
> Je m'appelle Aziz Khayati, ancien joueur de l'équipe nationale tunisienne de basket et data scientist spécialisé en IA et vision par ordinateur.
>
> J'ai suivi [élément précis : « l'approche data du TFC en recrutement »] et j'ai développé **[nom du projet]**, un outil qui [résultat en une ligne]. Démo de 60 secondes : [lien]
>
> Je serais ravi de contribuer à la cellule [performance / data] du [Club], en stage, en mission ou à distance dans un premier temps. Je réside en Tunisie et suis éligible au Passeport Talent.
>
> Auriez-vous 15 minutes dans les deux prochaines semaines ? Je peux d'abord appliquer le modèle à un match du [Club].
>
> Cordialement,
> Aziz Khayati
> [LinkedIn] · [GitHub] · [+216 …]

### D. Sports-tech company (SkillCorner, Kinexon, Hudl…) / open application

**Subject:** Computer Vision Engineer, athlete background: open application

> Hi [First name],
>
> [Company]'s [product, e.g. "broadcast tracking"] is exactly the work I want to do. I'm a data scientist and AI engineer with [X years / key skills from CV: Python, PyTorch, YOLO, SQL…] and a former Tunisia national-team basketball player.
>
> Recent work: [project name], which [result with a number, e.g. "tracks 22 players at 25 fps with 0.91 MOTA on SoccerNet clips"]. Code and demo: [GitHub link]
>
> I'm open to remote or on-site roles in [city] and can start [date]. CV attached.
>
> Would you be open to a short call?
>
> Best,
> Aziz Khayati

### E. LinkedIn connection note (≤ 300 characters)

> Hi [Name], former Tunisia national-team basketball player now building computer-vision tools for performance analysis (e.g. [project]). I really like [Club]'s work on [X]. I'd love to connect and learn from your experience.

### F. Follow-up 1 (day 5–7, reply in the same thread)

> Hi [First name], just following up on my note below. Since then I ran the model on [Club]'s match vs [opponent]: [1 insight + link/screenshot]. Happy to share the full output if useful.
> Best, Aziz

### G. Follow-up 2 (day 14, final)

> Hi [First name], I know the schedule is busy, so this is my last note. If a project-based or remote trial would ever help [department], I'd be glad to help. Otherwise, could you point me to the right colleague?
> Thanks again, Aziz

### H. Reply to an official job posting (cover letter body)

> Dear [Hiring Manager / Head of Performance],
>
> I'm applying for the **[Role]** at [Club]. As a former member of Tunisia's national basketball team, I've lived the performance environment from the inside. As a data scientist, I've built [main CV achievement, quantified].
>
> Three things I would bring:
> 1. **[Skill 1 matched to posting]:** [evidence from CV].
> 2. **[Skill 2 / computer vision]:** [project + result + link].
> 3. **Coach-facing communication:** I speak the language of players and staff, and turn models into decisions [example].
>
> I'm based in Tunisia, eligible for [visa], and available from [date], including remotely during onboarding. I'd welcome the chance to discuss how I can support [Club]'s [specific goal from posting].
>
> Kind regards,
> Aziz Khayati

---

## 8. CV adjustments for sports roles

Your current CVs are tailored to SeatGeek (data analyst) and Etyo (supply chain). For clubs, make a separate sports version:
- **Headline:** "Data Scientist & Computer Vision Engineer | Former Tunisia National Basketball Team Player"
- Move a **"Sport"** section to the **top third**: national team years, competitions, position, any captaincy.
- Add a **"Sports AI Projects"** section with your demo links above the general experience.
- Rename skills in football and basketball language: "tracking data", "event data", "pose estimation", "xG / shot quality", "load monitoring".
- Keep it to one page, PDF only.

---

## 9. Realistic expectations

- About 60 well-targeted emails usually lead to roughly 8–12 replies, 3–5 calls and 1–2 trials or offers. A strong demo moves these numbers more than anything else.
- The most likely path: **remote contract or internship at a sports-tech company or a data-driven mid-size club**, then an on-site full-time job with visa sponsorship after 6–12 months.
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
