## Hi, I'm Sufiyaan 👋

Final-year **BSc Information Technology** student at Richfield Graduate Institute of
Technology, based in Johannesburg — and someone who would rather ship something than
read about shipping it.

I'm open to **graduate programmes, internships and junior developer roles**.

### Why I build

I like the moment a problem stops being abstract. Somebody needs to know what they can
cook with what's in the cupboard, or a practice needs to stop losing patient enquiries in
a WhatsApp thread — and the fix is a schema, a few endpoints and an interface that gets
out of the way. That's the part I find genuinely satisfying, and it's why most of what's
on this profile is deployed rather than sitting in a folder.

In September 2026 I spent a month as a **software development intern at Solvemed**, a
South African healthtech company whose practice management software runs 90+ optometry
practices. I specified, built, tested and shipped a recurring appointment scheduling
feature into production — migration, API endpoints, Next.js screens and all. Writing code
that real practitioners depend on, against a live schema, under POPIA, taught me more in
four weeks than any tutorial has. It is also where I learned that the interesting bugs
hide in the edges: a monthly series starting on 31 January quietly rolling into the
following month, for instance.

Three things I care about in the code I write:

- **Security belongs in the database, not the interface.** Anyone can open DevTools and
  call the API directly, so my access rules live in PostgreSQL as Row Level Security
  policies, column permissions and triggers — not in a front-end `if` statement.
- **If it isn't tested, it isn't finished.** My CRM has 151 automated checks across
  database policies, API validation and browser journeys, including deliberate attempts
  to bypass the UI.
- **Someone else has to read this.** Every repo here has a real README explaining what
  the thing does, why it's built that way, and what the trade-offs were.

### Featured projects

**🩺 [Focal Point Optometry CRM](https://github.com/sufiyaansafy/FUTURE_FS_02)** · [Live demo](https://focal-point-crm.vercel.app)
A lead management system for an optometry practice. Patients book an eye test on a public
page; every request lands in a staff-only dashboard that tracks it from new → contacted →
converted, with notes, follow-up reminders and an automatic audit history. Role-based
access is enforced in PostgreSQL itself, including a masking function that hides patient
contact details from view-only accounts. **React 19 · Supabase · Edge Functions · RLS · 151 tests**

**🧑‍💻 [Personal Portfolio & Contact Pipeline](https://github.com/sufiyaansafy/FUTURE_FS_01)** · [Live site](https://sufiyaansafy.vercel.app)
My portfolio, pre-rendered to static HTML at build time so search engines and social
previews read real content instead of an empty React root. The contact form runs through a
serverless function with validation, honeypot filtering and rate limiting before it touches
the database. **React 19 · Vite 8 · Deno · PostgreSQL · WCAG AA**

**🥘 [Pantry Pal](https://github.com/sufiyaansafy/PantryPal)** — native Android app
Tracks what's actually in your pantry and suggests only the recipes you can cook *in full*.
The interesting part is the matching engine I wrote from scratch: it resolves plurals and
local names (mielie meal and maize meal are the same thing), converts every quantity to a
common base unit, and refuses to compare weight against volume — because a cup of flour and
a cup of sugar don't weigh the same. **Java · Android Studio · Supabase · 12 JUnit tests**

### Tech I work with

**Languages**
`JavaScript` `TypeScript` `Java` `C#` `Python` `C++` `SQL` `HTML5` `CSS3`

**Frameworks & Libraries**
`React 19` `Next.js` `ASP.NET Core MVC` `Entity Framework Core` `Vite` `Node.js` `Material 3`

**Backend & Databases**
`PostgreSQL` `Supabase` `Edge Functions (Deno)` `REST APIs` `Row Level Security` `Auth`

**Tools**
`Git` `GitHub` `VS Code` `Visual Studio` `Android Studio` `Vercel` `Gradle` `JUnit`

**Studying**
`Cloud Computing` `Machine Learning & AI` `Cyber Security` `Big Data & IoT`

### Skills

- **Claude Code** — I use it as a working part of my development process: scaffolding,
  refactoring, reviewing my own code before I commit, and getting unstuck faster on
  unfamiliar parts of a stack.
- **Full stack delivery** — schema design through to a deployed URL, including CI via
  Vercel and written documentation.
- **Database-level security design** — RLS policies, column permissions, triggers and
  masking functions.
- **Automated testing** — unit tests, API validation tests and end-to-end browser journeys.
- **Working in a real team** — Git branching, pull requests, acting on code review, and
  writing handover documentation someone else can pick up.
- **Accessible, responsive UI** — WCAG AA contrast, keyboard navigation, mobile-first layouts.

### What I'm working on

- 🎓 Final year of my BSc IT
- 🌱 Scrimba's Full Stack Developer Career Path
- 🔭 Building out the .NET side of my stack with ASP.NET Core MVC and EF Core
- 🚧 Task 3 of the Future Interns track — repo goes public when it ships

### Let's connect

📫 [sufiyaansafy11@gmail.com](mailto:sufiyaansafy11@gmail.com) &nbsp;·&nbsp;
💼 [LinkedIn](https://www.linkedin.com/in/MohammedSufiyaanSafy-SWE) &nbsp;·&nbsp;
🌐 [sufiyaansafy.vercel.app](https://sufiyaansafy.vercel.app) &nbsp;·&nbsp;
📍 Johannesburg, South Africa
