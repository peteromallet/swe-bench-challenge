# Megaplan Autoimprover

A live experiment testing whether open-weight language models, guided by a general-purpose harness, can match or exceed the best closed-source models on the [SWE-bench Verified](https://www.swebench.com) benchmark.

Two open-weight models -- one for execution/planning and one for critique/review -- work together through **Megaplan** to solve 500 real GitHub issues from the SWE-bench Verified dataset. The target to beat: **Claude 4.5 Opus** (76.8%).

## Live Dashboard

**[View the live dashboard](https://peteromallet.github.io/swe-bench-challenge/)**

The dashboard shows:
- Head-to-head score comparison (open-source vs closed-source)
- Score progression chart with zoom controls
- Per-repository pass rate breakdown
- Activity feed and full task list with expandable details

## Related Repositories

- [**Megaplan**](https://github.com/peteromallet/megaplan) -- The general-purpose planning harness that structures LLM work into phases
- [**hermes-agent**](https://github.com/peteromallet/hermes-megaplan) -- Fork of Hermes Agent with automated SWE-bench evaluation tooling (experiment orchestration code)

## Data

`data.json` contains the latest results snapshot and is updated periodically.
