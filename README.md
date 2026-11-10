## Temesgen Tilahun

I lead technology delivery, ten years of it across telecommunications, banking,
government and enterprise IT, and currently at **Safaricom Ethiopia**. The work is turning
business requirements into systems that go live and stay up: multiple vendors, hard
deadlines, and the kind of integration where nobody owns the whole picture. I tend to be
the person who finds the thing nobody tested.

Outside work I design and ship mobile products end to end: architecture, implementation,
security, store release and everything that goes wrong afterwards.

### What I've built

**[Gubae](https://play.google.com/store/apps/details?id=com.gubae.app)** — a spiritual
super app for the Ethiopian Christian community, live on Google Play. One place for what a
believer needs daily: the full Bible in Amharic and English, an archive of over 2,400
worship hymn lyrics, a nationwide directory of churches and upcoming conferences, private
prayer tracking and reading plans — all working **completely offline** from a local Isar
database. Bookmarks, notes and highlights sync across devices through Supabase, with
row-level security, migrations and TypeScript edge functions. Bilingual throughout, with
both the Ethiopian and Gregorian calendars, plus a companion website on Cloudflare.

**[Karde](https://github.com/Karde-app/karde)** — an offline vault for bank cards and
identity documents. The `INTERNET` permission is removed from the manifest, so Android
itself refuses any network request the app makes. That single constraint drove every other
decision: no crash reporting, so silent failures had to be made visible by design; no
update check, so the app hands you to the Play Store instead; backups that are written to a
folder you choose, never uploaded. AES-256-GCM with non-exportable hardware Keystore keys
and per-use biometric authentication, 274 tests, three languages. The source is public so
the "nothing leaves your phone" claim can be checked rather than believed.

### How I work

I start from a written specification and verify against the artefact rather than the
intention — the released bundle, the device in my hand, the rendered screen. It is the
habit that catches the bundle that silently went stale, the permission a library merged in
behind your back, the screen that overflows on a phone you do not own. I use AI coding
agents heavily and treat their output the way I treat any vendor's: useful, fast, and
wrong often enough that you check.

Most of what I have learned is about judgement rather than syntax — which features not to
build, which audit findings are simply incorrect, and what "done" means when the thing has
to survive a store review and real users on real phones.

### Currently

Flutter and Dart, Kotlin, Supabase and PostgreSQL, TypeScript, Next.js. Moving deliberately
toward Python, agentic systems and production AI engineering.

📍 Addis Ababa, Ethiopia · ✉️ contactemesgen@gmail.com
