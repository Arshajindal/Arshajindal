# Hi, I'm Arsha 👋

I'm a software engineer moving into AI/ML. I spent three years at Schneider Electric building .NET software for electrical design. Now I'm a Master's Computer Science student at Arizona State University and a research aide at the Complex Adaptive Systems Initiative (CASI).

I keep ending up turning messy spreadsheets into software people can rely on, from Excel-driven data pipelines at Schneider to a revenue dashboard at ASU. These days I'm most curious about AI: it's very good at *sounding* right, and I want to build the parts that check whether it actually is.

---

## Where I've worked

**Research Aide · Complex Adaptive Systems Initiative (CASI), Arizona State University**
*Jul 2026 – present · Scottsdale, AZ*

I build internal tools for CASI, and I research and test emerging AI/ML tools and workflows alongside faculty and researchers.

- **Subscription management system:** CASI tracked its subscriptions across a multi-sheet spreadsheet. I designed and built a Flask + PostgreSQL app to replace it: one searchable place for every subscription, with role-based access, encrypted storage for login credentials, and audit logging so you can see who changed what. I also designed it to plug into the analytics dashboard, so at renewal time the team can weigh what each subscription costs against how often its sources get cited.
- **Analytics dashboard:** a Flask app built on CASI's curated research index, a shared spreadsheet of journal articles, websites, books and reports. It breaks the index down by topic, contributor and date.

`Python` `Flask` `PostgreSQL`

**Volunteer Research Assistant · Arizona State University**
*Oct 2025 – May 2026 · Tempe, AZ*

Built a Unity XR workflow that loads 3D models from the cloud when you scan a QR code, and helped label and manage metadata for scanned 3D models.

**Software Design Engineer · Schneider Electric**
*Aug 2022 – Jul 2025 · Bengaluru, India*

Joined as a graduate engineer trainee after a six-month internship, and moved up to Software Design Engineer in May 2023.

- Built core features of an electrical design plugin for Autodesk Revit: the property grid, converters, and keyline and single-line diagrams, developed test-first with xUnit. `C#` `.NET WPF` `MVVM` `Syncfusion`
- Built the backend for SpecBuilder's localization portal: authentication, Excel validation, and Excel → C# → SQL parsing. Took multi-language support from proof of concept to production, and led new-country deployments from dev through prod. `ASP.NET Core` `MySQL` `Azure`
- Ran the team's standups and sprint demos, and reviewed teammates' pull requests.

---

## What I'm working on right now

**Does "thinking mode" make AI more honest?**
For CSE 598 (Operationalizing Deep Learning), my team is testing whether turning on a model's thinking mode makes its chain-of-thought more honest.

**North American AI Challenge**
I'm competing with a team of three in ASU Spark Center's challenge (Oct–Nov 2026), where I lead AI ethics and product strategy.

---

## Things I've built

**[EMS Dashboard](https://github.com/Arshajindal/EMS-Dashboard)**

At my facilities job at ASU SkySong, booking revenue was tracked by cross-referencing three messy, merged-cell Excel exports from the Event MAnagement System booking system by hand. I built a Flask app to replace that process. It parses all three exports into one interactive view with six tabs (revenue trends, client segments, operations, discounts, bookings and data quality), served through a JSON API and charted with Chart.js.

`Python` `Flask` `Chart.js` `pytest` `Render`

**[Celano Lab Tools](https://github.com/Arshajindal/Celano-Lab-XR-WebApplication)** 

A web app for ASU's Celano Nanoelectronics Metrology & Failure Analysis Lab. Each research instrument gets its own page with specs, manuals, photos and video. It's built for real lab staff: adding a new tool means editing one JSON file, with no code changes.

`Next.js 14` `TypeScript` `Docker` `Google Cloud Run`

---

## What I work with

**Languages:** Python, C#, TypeScript, SQL
**AI / ML:** PyTorch, Hugging Face Transformers, scikit-learn, LLM APIs (OpenAI, Anthropic), prompt evaluation, Claude Code
**Data:** pandas, NumPy, Jupyter
**Backend:** Flask, ASP.NET Core, REST/JSON APIs
**Frontend & desktop:** Next.js, React, Chart.js, WPF (MVVM, XAML)
**XR:** Unity
**Databases & cloud:** PostgreSQL, MySQL, Azure, Docker, Google Cloud Run, Render
**Testing & quality:** TDD, pytest, xUnit, SonarQube, code review

---

## How I work

- **I test first when I can**, a habit from building test-driven at Schneider.
- **I write down the decision before I write the code**, usually as a short decision record, so the reasoning outlives my memory of it.
- **I use AI coding tools every day**, and I treat their output like a pull request from a fast junior teammate: read it, test it, push back.

---

## Say hi

I'm looking for **AI/ML engineering and software engineering roles in the US**, starting **May 2027**.

📧 [Email](arshajindal@gmail.com)
💼 [LinkedIn](https://www.linkedin.com/in/arsha-jindal/)

Email is the fastest way to reach me.
