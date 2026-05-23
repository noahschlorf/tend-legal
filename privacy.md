# Privacy Policy

**Effective Date:** May 23, 2026
**App:** Tend — Golf Scorecard
**Contact:** hello@tendgolf.app

---

## 1. What We Collect

We collect only what is necessary to operate Tend. For this launch build, rounds and score history are local-first and stay on your device unless you choose to submit feedback or a course request.

| Data | Why we collect it |
|---|---|
| **Email address** | Linked to your Sign in with Apple account so we can identify you across devices. |
| **Name / display name** | Shown in the app so your scorecard feels personal. Stored on your device for launch. |
| **Voice / audio** | Captured when you tap the mic button to speak your score. Audio is streamed in real time to our speech-recognition provider (Deepgram) and is **not stored** after transcription. |
| **Golf scores and round data** | Hole scores, putts, fairways hit, GIR, and related stats. Stored locally on your device for launch and not uploaded to Tend servers. |
| **Lightweight app events** | Round started, round finished, selected course/tee labels, hole count, total strokes, app version, and whether voice was enabled. Used to confirm the app works for real users and diagnose product issues. |
| **Feedback text** | Optional bug reports, feature requests, voice feedback, and related app version metadata you submit from the app. |
| **Course request text and photos** | Optional course names, notes, links, directory source details, scorecard issue descriptions, and scorecard photos used to add or correct course data. |

We do **not** collect location data, contacts, advertising identifiers, or any data unrelated to golf scoring and course support.

---

## 2. How We Use Your Data

- **Golf scores** — stored locally on your device so you can review round history and stats. Tend does not provide cloud round sync in this launch build.
- **Lightweight app events** — used to confirm users can start and finish rounds and to diagnose app-quality issues. These events do not include hole-by-hole scorecards.
- **Feedback text** — used to fix bugs, prioritize feature requests, and improve voice scoring.
- **Voice audio** — processed once for speech-to-text, then discarded. We never record ambient audio; the mic is only active while you have it toggled on.
- **Course request text and photos** — used to review missing-course and correction requests.
- **Email / name** — used for account identification only. We do not send marketing emails unless you explicitly opt in.

---

## 3. Third-Party Processors

We share data with the following processors to operate the service:

| Processor | What they receive | Why |
|---|---|---|
| **Supabase** (supabase.com) | Account authentication data, lightweight app events, feedback text, course request text/photos, tester-code status, and Edge Function requests | Authentication, feedback and course request queues, account deletion, and short-lived Deepgram token minting |
| **Deepgram** (deepgram.com) | Audio stream while mic is active | Real-time speech-to-text transcription |
| **Apple** (apple.com) | Subscription purchase + receipt data | Process Tend Pro subscriptions through the App Store |
| **Railway** (railway.app) | (a) Beta application form data: name, email, Reddit handle, handicap, iPhone model, rangefinder, current scoring app, next round date, free-text notes, and a /24-truncated IP address (for rate limiting). (b) Misparse reports voluntarily submitted via the "Voice got it wrong?" button: the original voice transcript, the parsed score fields, your written correction, hole number, par, course name, app version, and Supabase user ID. | Stores beta study applications + voluntary voice-misparse reports used to improve the parser |

These processors are bound by data processing agreements and do not use your data for their own purposes. No data is sold to advertisers or brokers.

---

## 4. Data Retention

- **Golf scores and round data**: stored locally on your device. They are removed from the device when you sign out, delete your account in the app, delete the app, or clear local app data.
- **Account data**: retained as long as your account is active. Server-side account records are deleted within 30 days of account deletion.
- **Lightweight app events, feedback text, and course request submissions**: retained while we review product quality and support requests, unless you delete your account or ask us to remove them earlier.
- **Voice audio**: never stored. Discarded after each transcription request (Deepgram opted out of model-improvement retention via `mip_opt_out=true`).
- **Misparse reports**: retained as long as needed to improve the parser. You can request deletion of your reports by emailing hello@tendgolf.app with your Supabase user ID.

---

## 5. Your Rights

You have the right to:

- **Access** — request a copy of all data we hold about you.
- **Deletion** — delete your account and all associated data. Use the **Delete Account** button in Settings within the app, or email hello@tendgolf.app. Deletion is processed within 30 days.
- **Correction** — update your name or profile information directly in the app at any time.
- **Portability** — request a JSON export of your golf round data by emailing hello@tendgolf.app.

If you are in the European Economic Area (EEA) or California, you may have additional rights under GDPR or CCPA respectively. Contact us at hello@tendgolf.app to exercise them.

---

## 6. Children

Tend is not directed at children under 13. We do not knowingly collect data from anyone under 13. If you believe a child has provided us data, contact hello@tendgolf.app and we will delete it promptly.

---

## 7. Security

All data is transmitted over TLS and stored with encryption at rest via Supabase's infrastructure (hosted on AWS). We use Sign in with Apple so we never handle or store your Apple password.

---

## 8. Apple App Privacy Disclosures

The following data types are collected and linked to your identity (as reported to Apple's App Privacy label):

- **Contact Info** — email address and name (linked to identity, used for app functionality)
- **User Content** — optional feedback text, course request text/photos, and active voice audio. Golf scores and round history are local-only for launch and are not uploaded to Tend servers.
- **Audio Data** — voice audio streamed for speech-to-text only, NOT linked to your identity and NOT retained by us or our processor (Deepgram MIP opt-out)
- **Identifiers** — Supabase user ID linked to your Sign in with Apple account (used for app functionality)
- **Purchases** — purchase history of Tend Pro subscriptions (linked to identity, used for app functionality)
- **Usage Data** — product interaction events (analytics; not used for tracking)

No data is used for tracking or advertising.

---

## 9. Changes to This Policy

If we make material changes, we will update the Effective Date and notify you within the app. Continued use after changes constitutes acceptance.

---

## 10. Contact

Questions or requests: **hello@tendgolf.app**
