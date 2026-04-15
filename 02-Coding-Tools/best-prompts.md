# Best Prompts for Coding AI

10 ready-to-use prompts for building reliable software faster.

## 1. Feature Spec to Production Code [Intermediate]
**Use case:** Convert product requirements into implementation-ready code.

```text
You are a senior software engineer.
Stack: [LANGUAGE + FRAMEWORK]
Feature request:
[PASTE REQUIREMENT]

Produce:
1) Solution design summary
2) API/data model changes
3) Production-ready code
4) Tests (unit + integration where relevant)
5) Edge cases and failure handling

Constraints:
- Keep code modular and readable
- Explain trade-offs briefly
- Follow clean architecture conventions
```

## 2. Bug Reproduction + Root Cause [Advanced]
**Use case:** Diagnose recurring bugs with structure.

```text
Act as a debugging specialist.
Environment: [LOCAL/STAGING/PROD]
Observed behavior: [DETAILS]
Expected behavior: [DETAILS]
Error logs:
[PASTE LOGS]
Relevant code:
[PASTE CODE]

Return:
1) Most likely root causes ranked by probability
2) Reproduction steps
3) Fix proposal with minimal-risk patch
4) Regression test plan
5) Monitoring checks after deployment
```

## 3. Refactor Without Behavior Change [Intermediate]
**Use case:** Clean up legacy code safely.

```text
You are a refactoring assistant.
Refactor this code for readability and maintainability without changing behavior:
[PASTE CODE]

Deliver:
- Refactored code
- Before/after explanation
- Complexity notes
- Risk points
- Test cases proving parity
```

## 4. API Contract Designer [Advanced]
**Use case:** Design robust APIs with good developer experience.

```text
Act as an API architect.
Use case: [DESCRIBE]
Consumers: [WEB/MOBILE/THIRD-PARTY]
Non-functional constraints: [LATENCY, SECURITY, SCALE]

Design:
1) Endpoint list with methods
2) Request/response schemas
3) Validation and error model
4) Versioning strategy
5) Authentication and rate-limit approach

Include one realistic example payload per endpoint.
```

## 5. SQL Query Optimizer [Intermediate]
**Use case:** Improve slow queries.

```text
You are a database performance engineer.
Database: [POSTGRES/MYSQL/etc]
Schema:
[PASTE TABLES + INDEXES]
Slow query:
[PASTE QUERY]

Provide:
1) Performance bottleneck analysis
2) Optimized query versions
3) Index recommendations
4) Estimated impact
5) Validation method (EXPLAIN plan checkpoints)
```

## 6. Test Suite Generator [Beginner]
**Use case:** Add strong tests around critical logic.

```text
Act as a QA-minded developer.
Language/framework: [STACK]
Code under test:
[PASTE CODE]

Generate:
- Happy-path tests
- Edge-case tests
- Error-condition tests
- Mocking strategy (if needed)
- Test naming conventions

Output complete test file code.
```

## 7. Secure Code Review Prompt [Advanced]
**Use case:** Catch security issues before merge.

```text
You are an application security reviewer.
Analyze this code for OWASP-relevant risks:
[PASTE CODE]

Return:
1) Vulnerabilities found (severity + CWE mapping)
2) Exploitation scenario in plain English
3) Secure patch examples
4) Additional hardening controls
5) Checklist for PR reviewers
```

## 8. System Design Interview Simulator [Intermediate]
**Use case:** Prepare for architecture interviews.

```text
Act as a FAANG-style interviewer.
Prompt me with a system design problem for [LEVEL].
After I answer, evaluate on:
- Requirements clarity
- Data modeling
- Scalability trade-offs
- Reliability and observability
- Cost awareness

Then provide a model high-quality answer.
```

## 9. Migration Planner [Advanced]
**Use case:** Plan risky tech migrations with less downtime.

```text
You are a staff engineer planning a migration.
Current state: [DESCRIBE]
Target state: [DESCRIBE]
Constraints: [DOWNTIME, TEAM SIZE, DEADLINE]

Create:
1) Migration phases
2) Rollback strategy
3) Feature flag plan
4) Data backfill and verification steps
5) Cutover checklist with go/no-go criteria
```

## 10. PR Review Booster [Beginner]
**Use case:** Improve pull request quality before team review.

```text
Act as a strict but helpful code reviewer.
PR diff summary:
[PASTE SUMMARY OR DIFF]

Review for:
- Correctness
- Readability
- Performance risks
- Security concerns
- Missing tests

Return:
1) Blocking issues
2) Non-blocking suggestions
3) Suggested reviewer comments
4) Final PR description rewrite
```
