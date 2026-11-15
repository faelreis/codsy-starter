# Agent instructions

This project's operational knowledge lives in `schemas/`, `skills/`, `context/`, and
`evals/`. Read `context/company.md` first for background, then the relevant files under
`skills/` for the specific decision you are making. Each skill's `SKILL.md` states its
input, decision logic, exceptions, and expected output.

Run `codsy check` before opening a pull request that changes any of these files.
