# Portfolio reading guide

## What this repository demonstrates

An academic team exercise in evaluating AI-generated software against a selected SRS scope. The application uses Next.js, TypeScript, and Supabase for campaign/content workflows. Its [scope table](requirements-scope.md) and [assumption record](assumptions.md) distinguish implemented simplifications from unmet requirements and simulated external accounts.

## Evidence that can be inspected

- `sonar-project.properties` provides SonarQube scanner configuration; configuration alone does not prove a completed scan or a quality score.
- `baseline-v1` is a preserved tag. The original evaluation branch is `master`.
- [PR #2](https://github.com/rayyanhasan899/Mashbot/pull/2) and its commits explicitly describe adding intentional quality issues for evaluation.
- Existing documentation discloses AI assistance. It is retained, not replaced by a claim of wholly manual authorship.

The owner recalls SonarQube and/or Jira involvement, but verified individual tool use, Jira issue links, scan exports, and test execution results have not been established by this portfolio review. None is invented here.

## Version boundaries

This portfolio branch adds documentation after grading. It does not overwrite the original branch or tag, and it does not label later remediation as original submission work. No security-sensitive fixes, RLS changes, framework migration, new OAuth integration, or production deployment are included.

## Individual contribution

Syed Muhammad Rayyan Hassan was a team participant. Exact individual implementation and evaluation responsibilities remain unverified. Reviewers should assess the repository as team work rather than assume sole authorship.

## Highest-value follow-up

Create an explicitly scoped remediation change with reproducible before/after tests, the original defect references, and corresponding application/RLS checks. Security-sensitive changes need separate approval and should remain distinct from the preserved baseline.
