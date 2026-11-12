# TianQue6916

> Self-directed CS & math student. These repos are my working knowledge base: MIT and Stanford
> course material re-annotated bilingually (English source + 中文批注) into full notes, together
> with the derivation trails — where I got stuck, what I tried, the answer I finally accepted —
> and the agent tooling I build to maintain all of it. Only a fraction of the notes is uploaded
> so far. Everything here is meant to be read by both humans and AI agents — each repo has an
> `llms.txt` at its root.

## Current focus

Working through 6.041 (probability), 18.100B (real analysis), 6.046J (algorithms) and EE364a
(convex optimization), with CS144 and MacKay's ITILA alongside. The repos below are artifacts
of that pass, not a mirror of any syllabus: notes are re-derived closed-book first, then checked
against the official proofs.

## What is actually mine

Three kinds of files live here, and the directory and file names say which is which:

- **`notes`** — written by me: re-derived notes, bilingual annotation, my own problem solutions
  and practice code. Plain text, so GitHub search and LLM crawlers can read it.
- **`annotated scan`** — a textbook page plus my handwritten derivations in the margins,
  scanned as an image-only PDF. No text layer: search and crawlers see only the filename.
  The handwriting is mine; the printed page is the publisher's.
- **`source`** — the original textbook, official handout, exam or slide deck, with no trace of
  me in it. A repo labelled `source` is a reading shelf, not a portfolio piece.

The handwritten layer is where most of the actual thinking sits, and it is the one thing a
script cannot reconstruct — an OCR pass is planned so agents can read it too.
## Course material

`Kind` follows the three-way split above. Percentages are by bytes, measured against each
repo's actual file tree.

| Repo | Kind | What is actually inside |
|---|---|---|
| [`Introduction-to-Probability-6.041`](https://github.com/TianQue6916/Introduction-to-Probability-6.041) | notes | MIT 6.041 Probability — bilingual lecture notes, recitation solutions, problem sets, midterm/final exams, textbook chunks, tutorials. No source PDFs at all: 99 files, 100% text. |
| [`Introduction-to-Real-Analysis-18.100B`](https://github.com/TianQue6916/Introduction-to-Real-Analysis-18.100B) | notes + source | MIT 18.100B Real Analysis — bilingual lecture notes, textbook translation, problem sets with solutions, exams, proof notes, subtitles (source: TBB textbook PDFs, 5 MB of 29 MB). |
| [`Design-and-Analysis-of-Algorithms-6.046J`](https://github.com/TianQue6916/Design-and-Analysis-of-Algorithms-6.046J) | notes | MIT 6.046J Algorithms — bilingual lecture notes with figures, recitation notes, problem sets with solutions, quizzes, final, review, code. 16% mine by bytes. |
| [`Convex-Optimization-EE364a`](https://github.com/TianQue6916/Convex-Optimization-EE364a) | notes + source | Stanford EE364a Convex Optimization solutions & notes — 13 lecture decks, homework problem sets with official solutions, Boyd textbook + answer manual, extra exercises, plus my own `.m`/`.py`/`.jl` practice code (406 files). 56% mine by bytes. |
| [`Computer-Networking-CS144`](https://github.com/TianQue6916/Computer-Networking-CS144) | notes + source | Stanford CS144 Computer Networking labs & notes — Lab 0-6 handouts, weekly lecture notes, MOOC unit notes, midterm & final practice exams with answers, textbook, subtitles, EN/中文. 6% mine: one 21 MB textbook PDF dominates. |
| [`Information-Theory`](https://github.com/TianQue6916/Information-Theory) | source + notes | MacKay ITILA Information Theory lecture notes & slides — 16 bilingual lecture notes, official l1-l16 MagicPoint slides, textbook PDF/EPUB with bilingual chapters, board snapshots, EN/中文. Caveat: 613 MB of the 646 MB is the book scanned in 17 volumes. 0.1% mine by bytes. |
| [`Mathematics-for-Computer-Science`](https://github.com/TianQue6916/Mathematics-for-Computer-Science) | source + annotated scan | MIT 6.042J Mathematics for Computer Science — official textbook PDF (920pp), chapter structure index, TOC docx, and Ch.18 **scanned with my handwritten derivations in the margins** (33pp, image-only). |
| [`Computer-Systems-A-Programmer-s-Perspective`](https://github.com/TianQue6916/Computer-Systems-A-Programmer-s-Perspective) | annotated scan | CSAPP chapter & section index — scanned TOC, Ch.2 information representation and Ch.8 exceptional control flow as **textbook pages carrying my margin notes** (3 PDFs, 84 MB, image-only). 8 files in total. |
| [`Introduction-to-Algorithms`](https://github.com/TianQue6916/Introduction-to-Algorithms) | notes | CLRS Introduction to Algorithms — bilingual EN/中文 book translation chunks (p005-242), MIT 6.006 lecture notes, problem set solutions, exams 1-14, subtitles. 38% mine by bytes. |
| [`Introduction-to-Linear-Algebra`](https://github.com/TianQue6916/Introduction-to-Linear-Algebra) | source | Introduction to Linear Algebra (Strang, Chinese edition) — page scans merged into 2 volumes by page order (p000-055, p056-105) with a chapter/page index. **Plain scan, no annotation.** 6 files, 85 MB. |
| [`Linear-Algebra-and-Learning-from-Data`](https://github.com/TianQue6916/Linear-Algebra-and-Learning-from-Data) | notes | Linear Algebra and Learning from Data (Strang) — bilingual EN/中文 translations of chapters p001-250 and Parts IV-VII, 18.065 problem set solutions, lecture video transcripts. 95% mine by bytes: the highest ratio here. |
| [`Introduction-to-Algorithms-codetry`](https://github.com/TianQue6916/Introduction-to-Algorithms-codetry) | notes | CLRS — code drills & practice: C/C++/Python exercise folders (loops, pointers, structs, BFS, Josephus, Yanghui), plus a few linear algebra notes. |

## Agent tooling & automation

| Repo | What is actually inside |
|---|---|
| [`dsh-reasonix-agent`](https://github.com/TianQue6916/dsh-reasonix-agent) | dsh-reasonix-agent — LLM agent harness config backup mirror + engineering notes, 2229 files: dsh presets & cordis.patch.yml, reasonix memory, agents/skills, PowerShell scripts, kb/ lessons |
| [`Structured-Pseudocode-mind-language`](https://github.com/TianQue6916/Structured-Pseudocode-mind-language) | Structured-Pseudocode-mind-language — VS Code ext + bridge: .mind structured pseudocode semantic highlighting, LLM code-generation to Python 3 / C11, DeepSeek API, 35 files |
| [`tool-box`](https://github.com/TianQue6916/tool-box) | tool-box — Python scripts for PDF/TOC extraction, docx summary generation and image rendering; PowerShell ops (autocommit, doctor, backup); Windows .bat push |
| [`diary`](https://github.com/TianQue6916/diary) | diary — auto-generated daily journal notes in Markdown, 18 files: index.md plus days-public/YYYY-MM-DD.md dailies written by an LLM from dsh sessions, tool-call logs, window activity and Edge history |
| [`desktop-tutorial`](https://github.com/TianQue6916/desktop-tutorial) | desktop-tutorial — empty placeholder repo, created automatically by GitHub Desktop on first sign-in; 0 files, no README, nothing to search |

## For AI agents / LLM crawlers

GitHub disallows `/*/tree/` and `/*/raw/` to GPTBot, ClaudeBot, PerplexityBot and friends,
so directory layouts are invisible to crawlers. Each repo therefore ships an `llms.txt`
(llmstxt.org format) stating what is really inside, with real paths.

- Docs via MCP: `https://gitmcp.io/TianQue6916/<repo>` — GitMCP reads `llms.txt` first, then `README.md`.
- Repo search on GitHub indexes only **name, description and topics** — not README body.
  The one-line descriptions above are written to be the search surface; the READMEs carry the detail.
- **Text-layer caveat.** The PDFs are mostly image-only: scanned pages, rendered slides, no OCR
  layer. An agent that follows `llms.txt` into one of those directories gets filenames, not
  content. Everything marked `notes` is plain text and *is* readable; everything marked
  `annotated scan` or `source` is not, until the OCR pass lands.

## Notes

- Contents are personal study material. Textbooks and scans remain the copyright of their
  authors and publishers; buy the originals. On annotated scans the printed page belongs to the
  publisher and the handwriting in the margins is mine; bilingual notes and translations are mine.
- Repository descriptions are deliberately keyword-dense: they are the only field GitHub
  search actually reads.
