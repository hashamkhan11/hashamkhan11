# Hasham Mubarak
Software Engineer from Faisalabad, Pakistan. I design and build complete systems, from backend APIs and applications to the hardware they interact with.

## Latest Project

### [RosterLoop](https://github.com/hashamkhan11/roster_loop): every parent in the loop

[![RosterLoop](https://raw.githubusercontent.com/hashamkhan11/roster_loop/main/docs/banner.png)](https://github.com/hashamkhan11/roster_loop)

A mobile app for youth sports teams. Coaches build the schedule, message parents and run carpool and snack sign-ups. Parents tap Going, Maybe or Out for their child, and get a push alert the moment practice is moved or cancelled. A web panel lets the league manage teams and coaches.

- **One app, two roles:** the same account can coach one team and be a parent on another, so roles are stored per team.
- **Nothing gets missed:** every change lands in an in-app inbox first, then goes out as a Firebase push. Automatic reminders go out a day before and two hours before each event.
- **Rules on the server:** coach-only actions and private player details are checked by the API, not just hidden in the app.
- **Tested:** 25 Laravel feature tests covering schedules, RSVPs, reminders, sign-ups and the admin panel.

`Flutter` `Riverpod` `Laravel` `Sanctum` `Firebase Cloud Messaging` `SQLite`

## More Projects

### [KhataBol](https://github.com/hashamkhan11/khatabol): speak your khata

[![KhataBol](https://raw.githubusercontent.com/hashamkhan11/khatabol/main/docs/banner.png)](https://github.com/hashamkhan11/khatabol)

A bookkeeping system for small traders that works from WhatsApp. The trader sends a message, an Urdu voice note or a photo of a parchi. The bot reads the entry back, and saves it only after the trader replies "Haan". A Flutter app shows balances, stock and profit, and updates live.

- **Built for a real user:** my uncle runs a cloth business and never filled in forms in ledger apps, so I made the app work through WhatsApp instead.
- **AI with guardrails:** Gemini only extracts the entry. PostgreSQL functions check every field, and nothing is saved without confirmation.
- **Ledger you can trust:** append-only records, mistakes fixed with reversing entries, and balances calculated rather than stored.
- **Tested:** database tests on in-memory Postgres (PGlite), Flutter tests and GitHub Actions CI.

`Flutter` `Supabase` `PostgreSQL` `TypeScript` `Gemini` `WhatsApp Cloud API`

### [FitHub](https://github.com/hashamkhan11/fit-hub): from the front desk to the front door

[![FitHub](https://raw.githubusercontent.com/hashamkhan11/fit-hub/main/docs/banner.png)](https://github.com/hashamkhan11/fit-hub)

A multi-tenant gym platform. Staff run the gym from a Laravel/Livewire dashboard. Members check in with a QR code and book classes in a Flutter app. An ESP32 controller opens the door from the member's phone or with a fingerprint.

**Live:** [Website and dashboard](https://fithub.ranksol.net/) · [Android app on Google Play](https://play.google.com/store/apps/details?id=com.ranksol.fithub_app)

`Laravel` `Livewire` `Flutter` `MySQL` `ESP32` `Stripe`

### [PropNest](https://github.com/hashamkhan11/propnest): find a place that feels like yours

[![PropNest](https://raw.githubusercontent.com/hashamkhan11/propnest/main/docs/banner.png)](https://github.com/hashamkhan11/propnest)

A real estate marketplace for buyers, agents and admins. Buyers search on a map by radius or a drawn area, compare homes and get email alerts for saved searches. Agents pay for subscriptions and featured listings through Stripe, with prorated refunds. Admins moderate listings and watch analytics. Covered by 280+ PHPUnit tests and PHPStan level 5.

**Live demo:** [propnest.gencodix.com](https://propnest.gencodix.com)

`Laravel` `Livewire` `Tailwind CSS` `Stripe` `Leaflet` `Docker`

### [QiradSync](https://github.com/hashamkhan11/qiradsync): two partners, one ledger

[![QiradSync](https://raw.githubusercontent.com/hashamkhan11/qiradsync/main/docs/banner.png)](https://github.com/hashamkhan11/qiradsync)

**Research project, in progress.** An offline-first ledger for Mudaraba (Islamic profit-sharing) partnerships. Every phone keeps the full history as signed, hash-chained records that merge as a CRDT, so both partners always reach the same balances. The relay server only stores and forwards records; it decides nothing. I'm now evaluating it against sync, performance and security attack scenarios.

`Dart` `Flutter` `Ed25519` `CRDT` `Laravel`

## How I Work
1. Understand the problem and define the goal.
2. Clarify requirements, constraints, and edge cases.
3. Evaluate different solutions and their trade-offs.
4. Design a simple, scalable, and maintainable system.
5. Choose the right architecture and technology for the job.
6. Build in small, testable parts and keep changes safe.
7. Deploy, monitor, and verify the system in production.
8. Fix issues, learn from real usage, and improve continuously.

## Stack

- Backend: PHP, Laravel, Livewire, Java, MySQL, PostgreSQL, Supabase
- Mobile: Dart, Flutter, Riverpod
- Web: TypeScript, Next.js, React, Tailwind CSS
- AI: Gemini (text, speech and image understanding)
- Hardware: ESP32, C++ (PlatformIO)
- Integrations: Stripe, Firebase, Twilio, WhatsApp Cloud API

## Find me
[LinkedIn](https://www.linkedin.com/in/hashammubarak11)
