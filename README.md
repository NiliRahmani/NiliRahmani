# Niloufar (Nili) Rahmani

### I go looking for the place where a model is confident and wrong.

Most of what I do lives in that gap — the distance between what a system reports and what's actually true.

I got there sideways. I started out as an electrical engineer, where the real job, underneath every project, was the same: find the signal buried in the noise, and don't trust the clean-looking number until you know what it's hiding. Denoising a biomedical recording taught me that instinct before I ever touched a neural network.

Then came a run of research assistant roles that had nothing obvious in common — binary neural networks on histopathology slides, autonomous robots in simulation, forecasting COVID from wastewater. Somewhere in the middle of them I noticed the part I couldn't put down wasn't *building* the model — it was cross-examining it. Where does it break? Which failures is the headline metric quietly hiding? When it hands me an explanation, is that explanation faithful, or just plausible?

That question is the through-line, and it's why the work I want sits on the **validation and data quality** side rather than the model-building side. Somebody has to be the named person who independently checks whether the number holds up before a decision gets made on it — who asks what one row means, whether the test could have detected the problem, and what the report isn't saying. That's the part of the job I'd pick on purpose.

### 🔍 What that looks like in practice

- **[bank-churn-model-validation](https://github.com/NiliRahmani/bank-churn-model-validation)** — an independent review of someone else's churn model, not another churn model. The submission reports AUC 0.905. The version that could actually run in production scores 0.666, because one of its inputs is only filled in *after* the customer has already given notice. Eight findings, a signed validation report, and an outcome of **not approved for use**.
- **[toronto-ksi-collisions](https://github.com/NiliRahmani/toronto-ksi-collisions)** — twenty years of Toronto's killed-or-seriously-injured collisions, from the City's live open data. The published file is one row per *person*, not per collision — so the obvious query overstates every headline figure by 2.3x to 3.7x. Establish the denominator, *then* count. It also turned up six records where the two severity columns contradict each other.
- **[Scispot_LabBridge](https://github.com/NiliRahmani/Scispot_LabBridge)** — turns messy instrument exports into clean, QC-checked, fully audited data. Clean data is necessary; *validated* data is what's actually safe to make a decision on.
- **[FoldGate](https://github.com/NiliRahmani/FoldGate)** — a curation gate for protein structure datasets. Auditing 300 PDB entries that had *already* passed the usual filter turned up two things worth knowing: 40% of a random test split has a near-relative sitting in the training set, and 58% of chains are missing residues the deposited sequence says are there.
- **[SensorSentinel](https://github.com/NiliRahmani/SensorSentinel)** — anomaly detection where the hard part isn't the model, it's refusing to cheat. Leak-free thresholds and event-aware metrics, because a well-known shortcut lets a *random* detector beat the state of the art on the usual benchmark.

Different domains, same project every time: don't trust the number until you've tried to break it. Every one of these ends in a written document rather than a score — a validation report, an audit, a findings register — because in this kind of work the deliverable is a conclusion somebody can be held to.

Alongside them I've spent three years as a volunteer **Data Analyst with Data for Good**, which is where a lot of the unglamorous half lives: reconciling sources, chasing definitions, and finding out that two teams have been counting the same thing differently.

### Tools I actually reach for

**SQL**, **Python** (pandas, NumPy, scikit-learn), **Excel**, **Power BI** and **Tableau** for the reporting end. Data validation and reconciliation, QC pipelines, audit trails, and evaluation harnesses are the things I've built most often. There's a signal-processing, computer-vision and time-series background underneath from the engineering degrees, which I still use — mostly as intuition about how measurements go wrong.

### 🚀 Currently

Open to **model validation / model risk, data quality and governance, and data & BI analyst** roles — Toronto, GTA, or Canada-remote. I hold an **open work permit and a provincial nomination**, so I need no sponsorship and there's no restriction on where in Canada I work.

If your team cares whether the number is *actually* right — not just whether the dashboard loads — we'll get along.

### 🎨 Off the clock

Gym and group fitness classes, acrylic painting, and a steady diet of social-psychology books — that last one is probably why *"why did it really do that?"* is my favorite question to ask, whether the subject is a person or a model.

**[LinkedIn](https://www.linkedin.com/in/niloufar-rahmani/)** · nilrahmani100@gmail.com
