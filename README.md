## Pulkit Chaturvedi — Quality Engineering

Berlin, Germany ·
[LinkedIn](https://www.linkedin.com/in/pulkitchaturvedi87/) ·
[Substack](https://pulkitchaturvedi.substack.com)

I build quality platforms and engineer testing cultures — not just test suites.

Currently Quality Chapter Lead and Senior SDET at Delivery Hero, where I work across teams to raise the quality bar at the org level: from test infrastructure and flakiness reduction to defining quality principles that scale beyond any single team.

Previously led QA at NatWest (RBS) as AVP Test Lead, and built testing capability at Barclays and Fiserv across financial services domains.

---

## Projects

### Quality Gates CI/CD Reference Implementation
**[GitHub Repo](https://github.com/alwayspulkit/Quality-Gates-CI-CD)**

A production-grade quality pipeline demonstrating how to enforce quality gates systematically across the development lifecycle. Every gate has a documented threshold and rationale — not cargo cult rules.

**What it covers:**
- **Gate 1:** Static Analysis (Checkstyle + SpotBugs) — fail fast, zero high-severity bugs
- **Gate 2:** Unit Tests + Coverage (JaCoCo) — 80% line coverage enforced
- **Gate 3:** Integration Tests — full HTTP stack validation with Testcontainers
- **Gate 4:** Security Scanning (OWASP Dependency Check) — no critical CVEs
- **Gate 5:** Performance Testing (k6) — p95 latency < 500ms, error rate < 1%

Built with Java 17, Spring Boot 3, JUnit 5, and GitHub Actions. The point isn't the tools — it's the *thinking*: how to make quality checks scale without becoming gatekeeping theater.

### Flakey Tests Grouping Dashboard
**[GitHub Repo](https://github.com/alwayspulkit/FlakeyTestDashboard)**

A dashboard for identifying the root causes hiding behind flaky tests. Instead of debugging failures one by one, this tool groups them by common failure patterns and infrastructure issues, so you can fix the system, not the symptom.

### Mobile SaaS Test Strategy
**[GitHub Repo](https://github.com/alwayspulkit/mobile-saas-test-strategy)** · 

End-to-end QE strategy for a real cross-platform mobile SaaS (React Native + Expo + Supabase + RevenueCat), anonymized. Demonstrates how a Quality Chapter scales beyond a single team: 20-layer pyramid design, RLS policy coverage matrix, release gates, flake budgets, and a custom quality dashboard built on the same stack as the SUT.

Why it matters: most QE portfolios are framework demos. This one is a strategy, a measurement system, and a chapter playbook applied to a real product.

**Dashboard** · 

<img width="948" height="709" alt="Screenshot 2026-05-17 at 14 43 25" src="https://github.com/user-attachments/assets/d1079b0a-8c2d-4ac7-9312-37bb1a5b6bb7" />
<img width="964" height="734" alt="Screenshot 2026-05-17 at 14 43 14" src="https://github.com/user-attachments/assets/23950b17-a4f3-4d37-828d-9d018834259b" />

---

## What I think about

- **Systemic quality** — finding the 20% of root causes behind 80% of test noise
- **Quality as a platform** — tooling, dashboards, and standards that multiply team output
- **The IC-to-leader transition** — how engineers move from task completion to org impact

---

## Writing

- [Stop Chasing Individual Failures](https://pulkitchaturvedi.substack.com/p/stop-chasing-individual-failures) — why grouping flaky tests by root cause beats debugging them one by one
- [The Career Shortcut Nobody Talks About](https://pulkitchaturvedi.substack.com/p/the-career-shortcut-nobody-talks) — how identifying unowned problems is the real promotion lever

---

## Certifications

ISTQB Advanced Test Manager · Certified Scrum Master · Certified Scrum Product Owner · ISTQB Foundation
