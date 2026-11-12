# Java 30 — The Learning Lab

An interactive 30-day journey from Java fundamentals to building a secure, tested Spring Boot REST API.

**The goal:** become comfortable writing modern Java 21, solving interview-style problems, understanding concurrency, and shipping a backend service.

<p align="center">
  <a href="https://Markkaruga254.github.io/java-30-days/"><strong>🚀 Open the interactive learning hub</strong></a>
  ·
  <a href="https://github.com/Markkaruga254/java-30-days">Browse the source</a>
</p>

## Start here

The learning hub is the easiest way to navigate the challenge. It includes:

- **30-day roadmap** — browse by week, search topics, and open each lesson.
- **Daily lesson view** — reads the lesson Markdown directly from this repository.
- **Progress dashboard** — track completed days, LeetCode problems, reviews, and capstone tasks.
- **LeetCode tracker** — filter by difficulty and pattern, then open the problem.
- **Weekly reviews** — reflect on what stuck and what needs more work.
- **Capstone checklist** — track the final secure API deliverables.

Progress checklists are stored in the current browser using local storage. They are not synced between devices or written back to GitHub. Keep the daily logs and LeetCode notes in the repository as the permanent learning record.

## The daily rhythm

Plan for approximately 2–3 hours:

1. **Learn (30–45 min):** use official documentation and type every example yourself.
2. **Build (60–90 min):** complete the day's challenge from scratch.
3. **LeetCode (45–60 min on even days):** attempt two problems; start brute force, then optimize.
4. **Document (15 min):** commit your work and complete the daily log.

### Ground rules

- Use Java 21 (LTS).
- Plain Java and the JDK until Day 24; frameworks come later.
- Every challenge needs at least one test from Day 15 onward.
- Missed a day? Resume the next day and move the schedule forward. Consistency beats cramming.
- Understand the solution before moving on. Do not measure progress by copied code.

## Curriculum

| Days | Focus | Milestone |
|---|---|---|
| 01–07 | Syntax, methods, OOP, exceptions, collections | Library Management CLI |
| 08–14 | Generics, lambdas, streams, modern Java, I/O | Checkpoint 2 |
| 15–21 | JUnit, threads, executors, JVM, design patterns | Checkpoint 3 |
| 22–28 | Build tools, JDBC, Spring Boot, JPA, security, Docker | Working REST API |
| 29–30 | Capstone implementation and retrospective | Secure API v1.0 |

Each `day-NN/` folder contains its lesson plan, daily log, and starter code. Open the [roadmap](https://markkaruga254.github.io/java-30-days/) to navigate all 30 days.

## Repository structure

```text
java-30-days/
├── .github/
│   └── workflows/
│       └── pages.yml          # Deploy the learning hub to GitHub Pages
├── assets/
│   ├── css/site.css           # Responsive design
│   ├── js/app.js              # Navigation, progress, and interactions
│   └── favicon.svg
├── day-01/ ... day-30/         # Daily plan, log, and src/
├── leetcode/                   # Tracker + one folder per problem
├── weekly-reviews/             # Week 1–4 reflection templates
├── capstone/                   # Final project brief and CI template
├── index.html                  # Interactive learning hub
├── CONTRIBUTING.md
└── README.md
```

## Run a day's starter code

For the plain-Java exercises (Days 1–21):

```bash
cd day-01
javac -d out src/*.java
java -cp out Main
```

Days 22–30 introduce Maven/Gradle, Spring Boot, and the capstone. Follow the setup instructions in each day's guide.

## LeetCode workflow

Two problems every even day. For each problem:

1. Explain the input, output, and constraints.
2. Write a brute-force approach before optimizing.
3. Explain time and space complexity.
4. Add the solution in `leetcode/NNNN-problem-name/Solution.java`.
5. Record the approach, edge cases, complexity, and lessons in `NOTES.md`.
6. Revisit problems you could not solve independently after three days, then again at the end of the week.

See the [LeetCode tracker](leetcode/README.md).

## Weekly reviews

- [Week 1](weekly-reviews/week-1.md)
- [Week 2](weekly-reviews/week-2.md)
- [Week 3](weekly-reviews/week-3.md)
- [Week 4](weekly-reviews/week-4.md)

## Capstone

The final project is a secure Expense or Library REST API. It should demonstrate Spring Boot, JPA/PostgreSQL, authentication and authorization, validation, consistent error handling, tests, CI, and Docker.

Read the [capstone brief](capstone/README.md).

## Resources

- [dev.java](https://dev.java/) and [Java SE API docs](https://docs.oracle.com/en/java/javase/21/docs/api/)
- *Effective Java* — Joshua Bloch
- *Java Concurrency in Practice* — Brian Goetz
- [Baeldung](https://www.baeldung.com/)
- [NeetCode 150](https://neetcode.io/roadmap)

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for folder conventions, daily workflow, and contribution guidelines.

---

**Learn. Build. Ship.** One deliberate day at a time.
