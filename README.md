## Hi, I'm Kareem — Flutter Developer in Cairo, Egypt

I build production Flutter apps for healthcare, payments and real-time communication, and ship them to Google Play, the App Store and Windows. I work in Clean Architecture with Bloc/Cubit, and I care about the unglamorous parts too: tests, release pipelines and not leaking user data.

Most of my professional code belongs to clients and lives in private repositories. The apps themselves are public:

| App | What I built | Get it |
| --- | --- | --- |
| **Hayai** — patient healthcare platform | Architected the patient app: 16 care verticals behind one configurable home, gated on live server capability; patient medical file (vitals with danger thresholds, prescriptions, vaccinations, child records); 2,556 automated tests | [Google Play](https://play.google.com/store/apps/details?id=com.hayai.app) |
| **Hayai Partner** — provider & practice management | One codebase for hospitals, clinics, doctors, insurers and delegated staff, with navigation, permissions and APIs resolved per role at runtime; subscription plan gating; 2,207 automated tests | [Google Play](https://play.google.com/store/apps/details?id=com.hayai.partner) |
| **Hayai Partner Desktop** — Windows | Windows build from the shared codebase; Inno Setup packaging and an in-app self-updater with SHA-256 installer verification and a 3-day grace period | [get.hayaihealthcare.com](https://get.hayaihealthcare.com) |
| **REKAZ AUTO** — vehicle service subscriptions (KSA) | Subscription billing on Moyasar (cards, Apple Pay) and Tabby BNPL with idempotent activation; Socket.IO chat with voice notes and attachments; bilingual Arabic tax invoices as in-app PDFs | [Google Play](https://play.google.com/store/apps/details?id=com.sinaeiati.www) |
| **I'M IN** — online learning & consultations | ZEGOCloud video consultations and ticketed live events; referrals, reviews, deep-linked push; migrated 259 files to an Arabic/English RTL design system | |
| **Bareeq / Bareeq Operation** — field operations (KSA) | Multi-role apps: geo-verified branch visits with GPS and photo evidence, a 50 km job-pool radius filter, OpenStreetMap location picker, XLSX/PDF reports | |

### What I work with

- **Flutter & Dart** on iOS, Android and Windows
- **Architecture:** Clean Architecture, SOLID, Repository pattern, Bloc/Cubit, Provider, GetIt, GoRouter, Dartz
- **Networking & real-time:** Dio/REST, WebSocket, Socket.IO, Firebase Cloud Messaging, ZEGOCloud
- **Payments & auth:** Moyasar, Tabby, Tap, Paymob, Apple Pay (PassKit), JWT, OTP, Google/Apple sign-in
- **Maps & data:** Google Maps, OpenStreetMap (flutter_map), SQLite, PDF generation, XLSX export, Arabic RTL (gen-l10n)
- **Shipping:** unit, widget and integration tests; Play Console (App Signing, closed testing, staged rollout); App Store Connect; Inno Setup

### Public repositories here

Earlier personal projects, kept public as learning history:

- [Islami_App](https://github.com/kareemalaa2/Islami_App) — Quran, Hadith, radio and tasbeeh app with Arabic/English localization and Provider state management
- [system_of_talbat](https://github.com/kareemalaa2/system_of_talbat) — service-booking app structured in Clean Architecture layers (data / domain / presentation) with Cubit and GetIt

### Contact

kareemflutdev@gmail.com · [LinkedIn](https://www.linkedin.com/in/kareem-alaa-0a1235277/)
