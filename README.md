# 30-Day Java Challenge

A 30-day plan to go from Java fundamentals to intermediate, with a daily challenge, a LeetCode set every 2 days, and everything documented.

**Goal:** by Day 30, write clean, tested, concurrent, modern Java (17/21), build and secure a REST API with Spring Boot, and solve medium LeetCode problems in Java.

## How it works

Daily rhythm, about 2 to 3 hours:

1. **Learn (30 to 45 min):** official docs or the recommended chapter. Type every example yourself.
2. **Build (60 to 90 min):** do the day's challenge from scratch.
3. **LeetCode (even days, 45 to 60 min):** two problems, brute force then optimized, then a note.
4. **Document (15 min):** commit and fill in the daily log.

Rules:

- Plain Java and the JDK until Day 24. No frameworks before then.
- Every challenge needs at least one test from Day 15 onward.
- Missed a day? Pick it up the next day and push the schedule back by one.
- Use Java 21 (LTS).

## Repo structure

```
java-30-days/
├── README.md
├── day-01/ ... day-30/      daily plan, log, and src/
├── leetcode/                tracker and one folder per problem (Solution.java + NOTES.md)
├── weekly-reviews/          week-1.md ... week-4.md
└── capstone/                final project requirements and CI template
```

Run a day's starter code (Days 1 to 21):

```bash
cd day-01
javac -d out src/*.java && java -cp out Main
```

Days 22 to 30 use Maven or Gradle and Spring Boot. Create those projects inside the day's folder (or in `capstone/`) as the plan says.

## Progress

| Day | Topic | LeetCode | Done |
|---|---|---|---|
| 1 | [Setup, syntax, types, control flow](day-01/README.md) | - | [ ] |
| 2 | [Methods, arrays, strings](day-02/README.md) | 283, 242 | [ ] |
| 3 | [Classes and encapsulation](day-03/README.md) | - | [ ] |
| 4 | [Inheritance, polymorphism, interfaces](day-04/README.md) | 125, 14 | [ ] |
| 5 | [Exceptions and enums](day-05/README.md) | - | [ ] |
| 6 | [Collections I: List and iteration](day-06/README.md) | 1, 217 | [ ] |
| 7 | [Collections II and Checkpoint 1](day-07/README.md) | - | [ ] |
| 8 | [Generics](day-08/README.md) | 49, 347 | [ ] |
| 9 | [Lambdas and functional interfaces](day-09/README.md) | - | [ ] |
| 10 | [Streams API](day-10/README.md) | 238, 128 | [ ] |
| 11 | [Modern Java features](day-11/README.md) | - | [ ] |
| 12 | [File I/O and JSON](day-12/README.md) | 20, 155 | [ ] |
| 13 | [Date/Time, formatting, regex](day-13/README.md) | - | [ ] |
| 14 | [Checkpoint 2](day-14/README.md) | 704, 121 | [ ] |
| 15 | [Unit testing](day-15/README.md) | - | [ ] |
| 16 | [Concurrency I: threads](day-16/README.md) | 3, 11 | [ ] |
| 17 | [Concurrency II: executors and futures](day-17/README.md) | - | [ ] |
| 18 | [Concurrent collections and deadlocks](day-18/README.md) | 206, 141 | [ ] |
| 19 | [JVM internals](day-19/README.md) | - | [ ] |
| 20 | [Design patterns](day-20/README.md) | 226, 102 | [ ] |
| 21 | [Checkpoint 3](day-21/README.md) | - | [ ] |
| 22 | [Build tools and logging](day-22/README.md) | 98, 200 | [ ] |
| 23 | [Databases with JDBC](day-23/README.md) | - | [ ] |
| 24 | [Spring Boot and REST](day-24/README.md) | 207, 70 | [ ] |
| 25 | [Spring Data JPA, validation, error handling](day-25/README.md) | - | [ ] |
| 26 | [Securing a Java API](day-26/README.md) | 198, 322 | [ ] |
| 27 | [API testing and containerization](day-27/README.md) | - | [ ] |
| 28 | [Performance and code quality](day-28/README.md) | 215, 146 | [ ] |
| 29 | [Capstone build day](day-29/README.md) | - | [ ] |
| 30 | [Capstone finish and retrospective](day-30/README.md) | 23, 46 | [ ] |

## Weekly reviews

- [ ] [Week 1](weekly-reviews/week-1.md)
- [ ] [Week 2](weekly-reviews/week-2.md)
- [ ] [Week 3](weekly-reviews/week-3.md)
- [ ] [Week 4](weekly-reviews/week-4.md)

## Resources

- [dev.java](https://dev.java) and the Java SE API docs
- *Effective Java* by Joshua Bloch (a few items per week from Week 2)
- *Java Concurrency in Practice* by Brian Goetz (Week 3)
- [Baeldung](https://www.baeldung.com) for quick references
- [NeetCode 150](https://neetcode.io/roadmap) for pattern-based LeetCode practice

## Day 30 self-check

- [ ] Explain `equals`/`hashCode`, immutability, and why `ArrayList` beats `LinkedList` in most cases
- [ ] Write streams and lambdas fluently and know when a plain loop is clearer
- [ ] Use records, sealed types and pattern matching naturally
- [ ] Reproduce and fix a race condition and a deadlock
- [ ] Describe how the heap and garbage collector work and read a thread dump
- [ ] Write tests first, mock dependencies, keep coverage meaningful
- [ ] Build, secure, test and containerize a Spring Boot API
- [ ] Solve most easy and many medium LeetCode problems in Java within 30 minutes and explain the complexity
