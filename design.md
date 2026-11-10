# Tutor design

Deliverable 3. Written with the agent on 10 November 2026. No code yet.

## Goal

The tutor is for first-year students in MST 0441 Consumers, Trade and Business Strategy. They use it to practise for the exam. It writes new problems in the exam's format, with solutions. Each problem builds on the slides and in-class problems in `MST 0441 sources`.

A good problem set meets all of these checks:

- Each problem tests one session or subtopic of MST 0441.
- Each problem names the course files it is based on.
- When the student asks for all sessions, the set covers the whole course.
- Every number gives one correct answer. mst0441_verify reports OK where it can check.
- Every problem passes mst0441_check_problem with no FAIL.
- Each problem lets a student reach the "Excellent" level of the session's rubric.
- No problem is harder or longer than the course's own problems for the same session. This is checked against the problem sets and workshop papers.

The tutor refuses to:

- copy or restate an existing course problem as a new problem.
- ask about anything outside the syllabus, as listed in the mst0441 rules on what is not on the exam.
- write a problem that is harder or longer than the course's own problems for that session.
- show or reproduce the solutions to the course's own problem sets, workshops or exams.
- use material from other courses. The team chose MST 0441 only.

## Steps

1. The student writes "Lag et øvingssett" and adds "alt" or the sessions to practise.
2. Retrieval first. For each chosen session, the tutor searches the files in `MST 0441 sources`. It finds the passage the problem will build on and notes the file and page.
3. The tutor reads mst0441_guide, mst0441_rules and the rubric for each chosen session.
4. The tutor writes one new problem per session from that passage, with new names, numbers and story.
5. The tutor runs mst0441_check_problem and fixes every FAIL.
6. The tutor writes the solution and runs mst0441_verify on every number it can check.
7. The tutor checks each problem against the rubric's "Excellent" level and against the course's own problems for length and difficulty.
8. If a check fails, the tutor adjusts the problem. If that is not possible, it writes a new problem and checks again.
9. The tutor stops after three attempts per problem. It tells the student it could not write a problem that passed.
10. It then points to an existing course problem by file and number. It says the solution is on Canvas or given in class. It does not reproduce the problem or the solution.
11. The tutor shows the problems first and the solutions after them. Each problem names the file and page it used.
12. Where mst0441_verify cannot check a part, the tutor says so. The student should check that part with Andreas Kostøl or in class.

## Sources

### Consumers, Trade and Business Strategy (MST 0441)

From the mst0441 MCP server:

- the rules for writing problems and solutions.
- the rubrics for sessions 1 to 15.

From the MST 0441 Canvas page. The files are in the folder `MST 0441 sources` in AABE. The agent checked on 10 November 2026 that none of them contains a solution section. In the problem files, the word "solution" appears only in instructions such as "open the solution deck". The solution decks are not in the folder.

Slides (14 files):

- `Session 2 slides.pdf`
- `Session 3 slides.pdf`
- `Session 4 slides.pdf`
- `Session 5 slides.pdf`
- `Session 6 slides.pdf`
- `Session 7 slides.pdf`
- `Session 8 slides.pdf`
- `Session 9 slides.pdf`
- `Session 10 slides 2.pdf`
- `Session 11 slides.pdf`
- `Session 12 slides.pdf`
- `Session 13 slides.pdf`
- `Session 14 slides.pdf`
- `Session 15 slides.pdf`

In-person problems and handouts, without solutions (15 files):

- `A1_intro.pdf` (session 1)
- `A2_Problems.pdf` (session 2)
- `A3_handout.pdf` (session 3)
- `A4_handout.pdf` (session 4)
- `A5_Problem.pdf` (session 5)
- `A6_Problem.pdf` (session 6)
- `A7_Problem.pdf` (session 7)
- `A8_Problem.pdf` (session 8)
- `A9_Problem.pdf` (session 9)
- `A10_Problem.pdf` (session 10)
- `A11_Problem.pdf` (session 11)
- `A12_Problem.pdf` (session 12)
- `A13_Problem.pdf` (session 13)
- `A14_LemonProblem.pdf` (session 14)
- `A15_Problem.pdf` (session 15)

Gaps: there are no slides for session 1, no lecture notes and no working papers. `Session 10 slides 2.pdf` may be the second of two files. Whether a first file exists: not checked.

### Macroeconomics for Business Economists

None. The team chose MST 0441 only, since the tutor writes problems for the MST 0441 exam. No other course is used.

### Flagged: take out

These are textbooks or solutions. They stay out of the tutor. None of them is in `MST 0441 sources`.

- The solution decks for the A files. Solutions.
- The two workshop 2 solution files. Solutions.
- Varian, the Part One textbook named in the mst0441 rules. Textbook.
- Feenstra, the Part Two textbook named in the mst0441 rules. Textbook.
