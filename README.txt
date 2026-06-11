==========================================================================
  NAPLEX / UMPJE 2026 — PRACTICE QUIZ SYSTEM
  John Williams, PharmD, MS · PGY1 Pharmacy Resident, Confluence Health (Wenatchee, WA)
  Live site: https://j121williams.github.io/naplex-quiz/
  Last updated: 2026-06-10
==========================================================================

WHAT THIS IS
------------
A self-contained set of NAPLEX 2026 practice-quiz web apps, each built from a
fact-checked question bank and calibrated to the 2026 NABP content outline and
current guidelines. Open the hub (index.html / NAPLEX2026_StudyHub.html) to
reach every topic from one page. This is a LIVING PROJECT — topics and question
batches are added/expanded over time; updates just replace the matching file.

Current totals: ~1,093 questions across 11 banks.

Each quiz app includes:
  - Dashboard: full bank OR pick subtopics; filter by Domain (D1-D5) and
    Tier (T1 core / T2 integration / T3 exam-trap); choose how many questions.
  - Three item types: single-best MCQ, multiple-response SATA (all-or-nothing),
    and numeric fill-in / constructed-response (type the number; graded against
    the answer with a tolerance + units). Calculations is built mostly on the
    fill-in type to match how NABP tests math.
  - Answers hidden until you submit, with a dense rationale + NABP tag.
  - Progress tracking: attempt history, accuracy by domain & subtopic.
  - "Retest my missed" — a persistent pool of questions you got wrong.
  - Anti-cueing: options shown plain and shuffled each session (no "always B");
    a length-tell audit keeps the correct option from being the giveaway.
  - Works on phone, tablet, or computer. No login, no ads, no data leaves the device.

TOPICS (current counts; banks grow as batches are added)
--------------------------------------------------------
CLINICAL TOPIC BANKS
  - Infectious Disease / Antimicrobials .... 220 Q, 14 topics (bacterial; TB incl.)
  - Diabetes ............................... 191 Q, 14 topics
  - Antivirals & Vaccines .................. 124 Q, 7 topics (ACIP; HIV separate)
  - Heart Failure .......................... 103 Q, 8 topics
  - Antifungals ............................ 94 Q, 6 topics
  - Hypertension ........................... 87 Q, 13 topics  [NEW — 2025 ACC/AHA guideline]
  - Anticoagulation & Antithrombotics ...... 78 Q, 11 topics [NEW]
  - Dispensing & Medication Safety ......... 44 Q (+ pharmacy calculations)
  - PGx & Drug Interactions ................ 42 Q
  - Lab Interpretation ..................... 40 Q (+ TDM/calculations)

FOUNDATIONS & CALCULATIONS
  - Pharmaceutical Calculations ............ 70 Q, all 9 sub-domains 1C1-1C9
        [NEW — numeric fill-in: CrCl/IBW/BSA, days supply, IV drip rates,
         dose conversions/MME, concentrations/ratio strength/alligation,
         compounding/aliquot, TPN, biostatistics, pharmacokinetics]

  (More on the way — e.g., the Foundations/Professional-Management cluster
   covering the 5 new 2025 subdomains, HIV/antiretrovirals, and more disease states.)

NOTE ON CURRENCY: the Hypertension bank reflects the NEW 2025 AHA/ACC guideline
(universal <130/80 target, race-neutral first-line, PREVENT >=7.5% to start in
Stage 1, single-pill combos for Stage 2, aprocitentan in the resistant pathway),
not the older 2017/JNC framework.

HOW TO USE
----------
ONLINE (recommended): just open the live site on any device and bookmark /
"Add to Home Screen" it:
  https://j121williams.github.io/naplex-quiz/
Direct topic links (open any single quiz):
  https://j121williams.github.io/naplex-quiz/Hypertension_QuizApp.html
  https://j121williams.github.io/naplex-quiz/Anticoagulation_QuizApp.html
  https://j121williams.github.io/naplex-quiz/PharmaceuticalCalculations_QuizApp.html
  https://j121williams.github.io/naplex-quiz/NAPLEX2026_<Topic>_QuizApp.html
  (Older banks use the NAPLEX2026_ prefix; the three newest do not — easiest is
   just to use the hub and tap a card.)

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
       - Adding a NEW topic: upload its <Topic>_QuizApp.html, AND upload the
         refreshed index.html / NAPLEX2026_StudyHub.html so the new topic
         appears as a card on the hub. (The hub is hand-coded, so a new quiz
         file alone will NOT appear until the hub is updated with its card.)
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
