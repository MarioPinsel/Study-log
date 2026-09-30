# Study-log

Public record of my learning journey as a backend developer (Java / Spring Boot).
I upload exercises, notes and a weekly journal here.

- **Start date:** September 30, 2026
- **Goal:** be ready for my professional internship (June 2027) and land my first backend developer job in Colombia.
- **Full projects:** they live in separate repositories (links at the bottom).

## How I study

1. I read a short section (10-15 min).
2. I type it out myself, no copy and paste.
3. I break it on purpose to understand why it works.
4. I write down in my own words what it does and when to use it (`notes/` folder).

I prefer text, documentation and hands-on exercises over videos.

## Repository structure

```
study-log/
├── README.md        # this file
├── weekly-log.md    # one entry per week
├── sql/             # pgexercises solutions and my own queries
├── java/            # MOOC.fi and Exercism solutions
└── notes/           # notes by topic, in my own words
```

## 8-week plan

Estimated time: 8 to 10 hours per week, on top of university.

### Weeks 1-2: SQL basics + starting Java
- [ ] pgexercises.com: basic queries, JOINs, aggregations
- [ ] PostgreSQL in Docker with a sample database (Pagila or dvdrental)
- [ ] MOOC.fi Java Programming: part I
- [ ] Exercism (Java track): starter exercises

### Weeks 3-4: Advanced SQL + deeper Java
- [ ] Subqueries, window functions, indexes, `EXPLAIN ANALYZE`, transactions
- [ ] MOOC.fi part II: collections, OOP
- [ ] Streams, exceptions and basic concurrency (dev.java/learn)
- [ ] Paper design of the Spring Boot project (data model and endpoints)

### Weeks 5-6: Spring Boot project
- [ ] Spring Data JPA with PostgreSQL (avoid the N+1 problem)
- [ ] Spring Security with JWT
- [ ] Tests from the start: JUnit, Mockito, Testcontainers
- [ ] spring.io/guides applied to the project

### Weeks 7-8: Deployment + going to market
- [ ] `Dockerfile` and `docker-compose`
- [ ] CI with GitHub Actions running the tests
- [ ] Deployment on OCI with credentials kept out of the code
- [ ] Project README, CV and first internship applications

### Ongoing
- [ ] A little time each week on my Rust side project, no pressure

## Resources

| Topic | Resource | How I use it |
|---|---|---|
| SQL | [pgexercises.com](https://pgexercises.com) | I solve without looking at the answer; if I fail, I rewrite the solution from scratch the next day |
| SQL | Sample database in Docker | I practice indexes and `EXPLAIN ANALYZE` |
| Java | [MOOC.fi Java Programming](https://java-programming.mooc.fi) | I read one part, do its exercises, then move on |
| Java | [Exercism, Java track](https://exercism.org/tracks/java) | Daily exercises with tests on my machine |
| Java | [dev.java/learn](https://dev.java/learn) | Official reference for specific topics |
| Spring | [spring.io/guides](https://spring.io/guides) | I follow a guide and apply the same thing in my project |
| Spring | [Baeldung](https://www.baeldung.com) | I go there when I hit a concrete problem |
| Testing | [testcontainers.com/guides](https://testcontainers.com/guides) | Tests with a real database in a container |
| Interviews | [System Design Primer](https://github.com/donnemartin/system-design-primer) | One topic at a time, explained out loud |

## Projects

- _Pending: Spring Boot project (repo link)_
- _Pending: personal API Gateway (repo link)_

## Notes

- I don't copy course material; only my own solutions and notes.