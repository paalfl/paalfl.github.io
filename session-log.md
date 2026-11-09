AABE course folder, version 2026-1
2026-10-29

## 2026-10-29, session 1, part 1: language models
- Did: read the part, ran the small task, answered the three check questions.
- Result: the agent summed up AGENTS.md in five lines. It named made-up sources and numbers as a common model error, checked against SSB, Norges Bank or the original paper.
- Checks: question 2 (context window vs. log) needed a second try. All three answered correctly in the end.

## 2026-10-29, session 1, part 2: skills and folders
- Did: small task, and both "Talk it through" questions.
- Result: the agent drew the course folder tree. folder-context started and asked about storage and the parent project. master-thesis/ created in OneDrive with README.md, AGENTS.md, CLAUDE.md and seven folders.
- Global install of folder-context: declined by the student. Course rules stay in AABE. master-thesis keeps its AGENTS.md.

## 2026-10-29, session 1, part 3: what an agent is
- Did: small task, and the tutor exercise with three programs.
- Result: the agent listed each step with its tool and result. It judged the session goal partly checkable. "Take me through part 1" had no clear end, and the log was empty until now.
- Tutor: chatbot (lacks tools and loop), Excel macro (lacks model), inflation chart program (agent). All answered correctly.

## 2026-10-29, other
- my-page/index.md: name set to Pål Flø, GitHub link to paalfl/paalfl.github.io added.

## 2026-10-29, addition to the part 2 and part 3 entries
The entries above only summarised the results. This entry adds the results as the agent produced them earlier in the same session. The entries above are unchanged.

### Part 2: the course folder tree, as drawn by the agent

```
AABE/
├── AGENTS.md                  rules the agent reads first
├── CLAUDE.md                  one line pointing Claude Code to AGENTS.md
├── session-log.md             the log (start line and date so far)
├── .agents/skills/
│   └── folder-context/SKILL.md   skill copy for Codex (hidden)
├── .claude/skills/
│   └── folder-context/SKILL.md   skill copy for Claude Code (hidden)
├── my-page/
│   └── index.md               your GitHub page template
├── session1/
│   ├── 01-language-models.md
│   ├── 02-skills-and-folders.md
│   └── 03-what-an-agent-is.md
└── skills/
    └── folder-context/SKILL.md   the course's copy, to read
```

### Part 2: the agent's proposal for the thesis folder

```
master-thesis/
├── README.md        what the thesis is about, and a "Folder context" section
├── AGENTS.md        rules for the agent in this project
├── CLAUDE.md        one line pointing to AGENTS.md
├── data-raw/        data exactly as you got it, never edited
├── data/            cleaned data made by scripts
├── scripts/         Stata or Python code that turns data-raw into data and results
├── literature/      papers you read
├── notes/           dated notes, e.g. 2026-10-29-supervisor-meeting.md
├── drafts/          thesis.docx under one stable name, no "final-final"
└── outputs/         figures and tables made by the scripts
```

1. One project: the thesis gets its own folder, separate from AABE and other course folders.
2. Instructions at the top: README.md and AGENTS.md sit in the root.
3. Raw data kept raw: data-raw/ is never changed. Scripts write to data/ and outputs/.
4. Names that sort: dated files start with the date in the form 2026-10-29. No spaces.

### Part 3: the agent's account of its steps

| # | Tool | What came back | How I decided the next step |
|---|---|---|---|
| 1 | Bash: list the folder, print `AGENTS.md` | The folder contents and the rules | `AGENTS.md` says to write a start line if the log is empty |
| 2 | Bash: write the start line and date to `session-log.md` | The log with two lines | I wrote this without asking first. I told you in my next answer |
| 3 | Bash: print the three session 1 files | Part 1 printed, then a zsh error on `=====` | I ran it again in a loop, and parts 2 and 3 printed |
| 4 | No tool | I answered the part 1 task from the copy of `AGENTS.md` I had already read | I asked check question 1. You moved to the part 2 task instead, so it is still unanswered |
| 5 | Skill: folder-context. Bash: list every file | The skill's rules and the folder tree | The skill says to ask about storage and the parent project before writing |
| 6 | Bash: look for Dropbox, OneDrive and thesis folders | A zsh error for Dropbox, then your `~/Documents` listing with no thesis folder | The OneDrive check did not run, so I said I had not checked it |
| 7 | AskUserQuestion | You rejected it | You wrote "Ask me again", so I asked the same questions again |
| 8 | AskUserQuestion | OneDrive, new standalone project | I needed the exact OneDrive path |
| 9 | Bash: list OneDrive, print `Master Thesis.url` | The OneDrive path, your course folders, and a shortcut to a OneNote notebook | I proposed a path and asked three questions |
| 10 | Bash: create folders and files, then list them | `master-thesis/` with seven folders and three files | I asked about the log. You said wait |
| 11 | Read: `my-page/index.md` | The template with "# Your name" | I did not know your name, so I asked instead of guessing |
| 12 | Edit: put your name in line 1 | Saved | I showed you the file first, as you asked |
| 13 | No tool | You pasted a GitHub link with placeholders | I explained the placeholders and asked what you wanted |
| 14 | Edit: add the GitHub link | Saved | I showed the line first. Whether the repository exists: not checked |

Goal: follow AGENTS.md, go through session 1, ask before changing files, and log the work. Checked: the thesis folder exists, and the name and link are in index.md. Not precise enough: "take me through the first part" had no clear end, "log what we did" was not done at the time, and "ask before you change any file" was broken once, in step 2.

## 2026-11-09, session 2, part 1: tools and the agent loop
- Did: small task and the tutor exercise.
- Result: the agent listed its tools in four groups (files, workflow, publishing, other). It rewrote "Make my GitHub page better" three times. Version 3: the page at paalfl.github.io shows the name Pål Flø and the list "What I built in this course", one line per finished part of sessions 1 and 2, at least one link to a repository under github.com/paalfl, all links working. Whether the page is live: not checked.
- Tutor: Sunday opening in five cities. Prediction: Sunday revenue. Judgment: whether the surplus is worth the cost to staff and customers. Student's goal: a table with expected revenue in NOK per Sunday for each of the five cities, based on actual Sunday revenue in stores of similar size open on Sundays in Bergen and Oslo sentrum. Open point: how to transfer the figures to the other three cities. The student did not confirm the final wording.
- Checks: question 1 (who runs a tool) answered wrong, the agent gave the answer: Claude Code. Question 2 (how the loop ends) half answered, the agent gave the second half: the agent is stuck. Both should be repeated at the start of part 2.

## 2026-11-09, session 2, part 2: MCP, workshop 2 task
- Did: asked the agent to make a new version of workshop 2 with the mst0441 server.
- Result: the agent did not find workshop 2 on the mst0441 MCP server. The guide lists only rules and rubrics s01 to s15. Searches for "Workshop 2" returned no workshop. Section ids such as workshop-2 and w2 returned "Unknown section id". The student then put the workshop 2 paper in AABE/Workshop 2, and the agent read the topics from the exam paper (sessions 8 to 11).
- Problems: the agent wrote a new workshop 2 (5 problems, sessions 8 to 11). mst0441_check_problem gave one FAIL ("tariffs" in an option in problem 5), fixed. Problems 2 and 3 verified with mst0441_verify, problems 1, 4 and 5 not machine-checked.
- Student's solution: all numbers in problems 2 and 3 OK with mst0441_verify. Problem 1 correct by hand check, not machine-checked. Problem 5: 10 of 10 correct. Errors: 2(d) explanation has 4 sentences, cap is 3. 2(a) frontier described in text, not drawn. Missing in 1(d): exposure vs adoption said explicitly.
- Hand-in page: my-page/mcp.md created in AABE, as the student asked. It holds the problems, the student's solution verbatim and the check result. Two sections are left for the student: what an MCP server is and why they trust mst0441, and what they changed. Not yet on GitHub.
- Tutor: question 1 (what an MCP server sends) mostly right. Missing: server instructions go straight to the agent. Question 2 (what an untrusted server can make the agent do) not answered yet.
- Tutor, end: the student stopped after question 1. Question 2 was not answered.
- Hand-in page, end state: the student wrote what an MCP server is and one reason to trust mst0441 (they trust the professor who made it). The agent suggested adding what the student checked. The student declined. "What I changed" is still empty. Uploaded to GitHub: not checked.
