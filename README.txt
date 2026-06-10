==========================================================================
  NAPLEX / UMPJE 2026 — PRACTICE QUIZ SYSTEM
  John Williams, PharmD, MS · PGY1 Pharmacy Resident, Confluence Health (Wenatchee, WA)
  Live site: https://j121williams.github.io/naplex-quiz/
==========================================================================

WHAT THIS IS
------------
A self-contained set of NAPLEX 2026 practice-quiz web apps, each built from a
fact-checked question bank and calibrated to the 2026 NABP content outline and
current guidelines. Open the hub (index.html / NAPLEX2026_StudyHub.html) to
reach every topic from one page. This is a LIVING PROJECT — topics and question
batches are added/expanded over time; updates just replace the matching file.

Each quiz app includes:
  - Dashboard: full bank OR pick subtopics; filter by Domain (D1-D5) and
    Tier (T1 core / T2 integration / T3 exam-trap); choose how many questions.
  - Answers hidden until you submit, with a dense rationale + NABP tag.
  - Progress tracking: attempt history, accuracy by domain & topic.
  - "Retest my missed" — a persistent pool of questions you got wrong.
  - Anti-cueing: options shown plain and shuffled each session (no "always B").
  - Works on phone, tablet, or computer. No login, no ads, no data leaves the device.

TOPICS (current; question counts grow as batches are added)
-----------------------------------------------------------
  - Infectious Disease / Antimicrobials .... ~200 Q, 13 topics (bacterial; TB incl.)
  - Diabetes ............................... ~170 Q, 13 topics
  - Heart Failure .......................... ~92 Q, 7 topics
  - Antifungals ............................ growing (azoles, echinocandins,
        amphotericin, flucytosine, disease-state selection, dermatophytes)
  - Lab Interpretation ..................... ~34 Q (+ TDM/calculations)
  - PGx & Drug Interactions ................ ~32 Q
  - Dispensing & Medication Safety ......... ~38 Q (+ pharmacy calculations)
  (More topics on the way — e.g., antivirals, and additional clinical areas.)

HOW TO USE
----------
ONLINE (recommended): just open the live site on any device and bookmark /
"Add to Home Screen" it:
  https://j121williams.github.io/naplex-quiz/
Direct topic links follow the pattern:
  https://j121williams.github.io/naplex-quiz/NAPLEX2026_<Topic>_QuizApp.html

OFFLINE: double-click NAPLEX2026_StudyHub.html (or any single quiz .html).
Keep ALL files together in one folder so the hub links resolve.

NOTE: progress (scores, attempt history, "retest my missed") is stored locally
PER BROWSER/DEVICE — your phone and laptop each keep their own history; the
quizzes themselves are identical everywhere.

UPDATING / ADDING MATERIAL (this project grows over time)
---------------------------------------------------------
The site is hosted on GitHub Pages from the repo: j121williams/naplex-quiz
To publish new or updated content (all via the GitHub website, no command line):

  1. Go to the repo -> "Add file" -> "Upload files".
  2. Drag in the changed/new file(s):
       - Updating an existing quiz (new batch added): upload the same-named
         .html file; it overwrites the old one and the link stays identical.
       - Adding a NEW topic: upload its NAPLEX2026_<Topic>_QuizApp.html, and
         upload the refreshed index.html / NAPLEX2026_StudyHub.html so the new
         topic appears as a card on the hub.
  3. Commit changes. The live site refreshes in ~1-2 minutes (hard-refresh:
     Cmd-Shift-R if you don't see the update right away).

The study-guide / Q-Bank documents each carry a "Practice quiz" link at the top
that points to the matching hosted app, so reading -> quiz is one tap.

HOSTING NOTES
-------------
Already hosted on GitHub Pages (above). Equivalent free static hosts if ever
needed: Netlify Drop (app.netlify.com/drop), Cloudflare Pages, Vercel — drag
the whole folder, get an https link. AVOID Google Drive / Dropbox / iCloud
(they show the HTML as code instead of running it).

==========================================================================
  Built for the NAPLEX + UMPJE, 2026. Study smart. — JW
==========================================================================
