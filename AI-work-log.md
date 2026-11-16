# AI Work Log

This log records significant project decisions and AI-assisted work for the Streaming Services Data Visualization Challenge. Entries distinguish completed work from recommendations and plans.

## 2026-11-13 — Workspace setup

### Workspace instructions

- **Request:** Create a workspace context file that AI reads when answering questions, and suggest its name.
- **Decision:** Use `.github/copilot-instructions.md` for workspace-level Copilot instructions.
- **Completed:** Created the file with the challenge context, the brief as the source of truth, guidance to inspect the available data, and quality expectations for the Power BI dashboard.
- **AI time spent:** ~2 minutes (active-time estimate).

### AI participation and showcase

- **Request:** Make clear that the goal is to enter the challenge with AI doing as much of the work as practical, while investigating and showcasing AI's capabilities and results.
- **Completed:** Added this goal to the workspace instructions, including the need to validate results and be candid about limitations, assumptions, and manual work.
- **AI time spent:** ~1 minute (active-time estimate).
- **Request:** Recommend a form for showcasing AI's work and how it was done.
- **Recommendation:** Keep a working log and distill it into a short companion case study (PDF or presentation) covering AI tasks, representative prompts and outputs, human decisions or corrections, validation, outcomes, and limitations. The Power BI dashboard remains the main challenge entry.
- **AI time spent:** ~1 minute (active-time estimate).
- **Completed:** Added the companion case study to the workspace instructions.
- **AI time spent:** ~1 minute (active-time estimate).

### Logging setup

- **Request:** Log the discussion and the creation of the instruction file, and set up ongoing logging.
- **Completed:** Created this log with the setup discussion and added an instruction to keep it updated as significant work is completed.
- **AI time spent:** ~2 minutes (active-time estimate).

## 2026-11-13 — Measuring speed

- **Hypothesis:** AI can help build a Power BI dashboard faster.
- **Request:** Add this hypothesis to the workspace instructions and include time spent in the log.
- **Completed:** Added the hypothesis and guidance to record AI time, record elapsed time when known, and mark estimates clearly.
- **AI time spent:** ~1 minute (active-time estimate). Earlier setup work was not timed.

## 2026-11-13 — Git repository

- **Request:** Initialize the workspace as a Git repository and push it to the project's GitHub repository.
- **Completed:** Initialized the local `main` branch and configured the GitHub repository as `origin`. Confirmed the remote was public and empty.
- **Human input:** Confirmed redistribution is authorized and chose to exclude the presentation because it contains a SharePoint sharing link.
- **Limitation:** The presentation remains local and is excluded from Git.
- **AI time spent:** ~3 minutes (active-time estimate).

## 2026-11-16 — Exploring dashboard stories

- **Request:** Inspect the data and brainstorm possible dashboard storylines together.
- **Completed:** Read the challenge brief and profiled all three CSVs, including catalog sizes, content types, release years, genres, missing values, and possible title matches.
- **Findings:** The files contain 9,668 Amazon, 1,450 Disney+, and 8,807 Netflix records. They describe historical catalogs, not current availability; genre labels differ across sources, and Amazon is missing most country and date-added values.
- **Ideas for discussion:** Compare catalog character and release eras; explore family and short-form content; or investigate potential title overlap. No storyline has been selected.
- **Validation:** Calculated counts and percentages directly from the CSVs. Title matches based on title, release year, and type are only candidates, not proof of exclusivity.
- **Human input:** Requested a collaborative brainstorm; audience and direction remain open.
- **AI time spent:** Approximately 2 minutes elapsed; active time not separately measured.

## 2026-11-16 — Teaching themes

- **Request:** Propose suitable teaching themes.
- **Completed:** Proposed applied themes spanning health, sustainability, inclusion, technology, and education; checked sample documentary descriptions in the supplied CSVs for illustrative candidates.
- **Limitation:** Keyword-based examples are discussion starters, not validated teaching recommendations; theme coverage, educational quality, viewing rights, and current availability remain unverified.
- **AI time spent:** Less than 1 minute (active-time estimate).

## 2026-11-16 — Simplifying the story

- **Human input:** The SDG approach feels too complicated, and no time or resources are available for reviewing title matches. Also, the focus of this challenge is to explore the data and create a dashboard, not create a complicated dataset or validate external data. The story should be simple, and the dashboard should be built from the supplied CSVs.
- **Completed:** Explored stories using only existing fields, especially movie duration and release year; calculated platform comparisons directly from the CSVs.
- **Human decision:** Explore a student-oriented story about viewing time, without external data or manual matching.
- **Validation and limitations:** Movie-duration percentages use records with valid minute durations; three Netflix movies lack durations. Catalogs are historical and cannot establish current availability.
- **AI time spent:** Less than 1 minute (active-time estimate).

## 2026-11-16 — Storyline document

- **Request:** Store the storyline in a separate file for review.
- **Completed:** Created [Dashboard-storyline.md](./Dashboard-storyline.md) with the audience, dashboard journey, verified duration comparison, data sources, and limitations.
- **AI time spent:** Less than 1 minute (active-time estimate).

## 2026-11-16 — Broadening the audience

- **Human input:** Include both students with time between classes and employees with extra time after asking AI to perform a task.
- **Completed:** Updated [Dashboard-storyline.md](./Dashboard-storyline.md) to frame the dashboard around finding something to watch within available free time, while retaining the duration comparison and historical-data limitations.
- **AI time spent:** Less than 1 minute (active-time estimate).

## 2026-11-16 — University-oriented external data

- **Request:** Explore additional data and connect the dashboard to a university's work.
- **Completed:** Investigated UN Sustainable Development Goals, Wikidata, MovieLens, IMDb and TMDB as possible enrichment sources; checked provider documentation on access and reuse.
- **Ideas for discussion:** Learning themes and SDGs; representation in film; and an educational exploration of recommendation and rating bias.
- **Human decision:** Explore streaming for learning first; the specific teaching themes and external sources remain open.
- **Limitations:** Catalogs are historical, external title matching and coverage need validation, and educational relevance or rights cannot be inferred from metadata alone. Source licenses and redistribution rules need checking before use.
- **AI time spent:** Approximately 2 minutes elapsed; active time not separately measured.
