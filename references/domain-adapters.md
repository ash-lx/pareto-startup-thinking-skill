# Domain Adapters

Use these when the question is about a specific startup workstream.

## Product

Ask:
- which flow or decision most affects activation, retention, revenue, or trust?
- where are users actually blocked?
- what change most improves the main outcome fastest?

Bias toward:
- critical user journeys
- high-friction decision points
- fewer high-impact bets over many small tweaks

Quantify:
- conversion by step
- time-to-value
- top 3 reasons users stall or drop

Usually not a real constraint:
- "the roadmap already includes it"
- "competitors have it"
- "design debt feels embarrassing"

Good smallest next step:
- instrument one key path and ship one blocking-fix this week

## Architecture

Ask:
- what decision simplifies the system while protecting the critical path?
- what is premature infrastructure?
- where is the real scaling, reliability, or developer-speed bottleneck?

Bias toward:
- simpler systems
- fewer abstractions
- postponing non-load-bearing infrastructure

Quantify:
- deploy friction
- incident frequency on the hot path
- time lost to current system pain

Usually not a real constraint:
- "serious startups use this stack"
- "we will need it eventually"

Good smallest next step:
- patch the current bottleneck and set a trigger for when heavier architecture is justified

## Backend

Ask:
- where are the hot paths or failure-prone paths?
- what complexity is being added without present payoff?
- what would reduce operational burden fastest?

Bias toward:
- profiling before tuning
- fixing failure-prone paths
- simpler operating models unless evidence demands more

Quantify:
- latency on the hot path
- top error sources
- operational burden per week

Usually not a real constraint:
- "cleanup will probably help everything"

Good smallest next step:
- instrument the hot path, fix the top failure mode, and leave broader cleanup for later

## Frontend

Ask:
- which screens or flows affect completion or conversion most?
- where do users drop off or get confused?
- what should be polished now versus ignored?

Bias toward:
- clarity and completion
- critical flows
- not spreading polish evenly

Quantify:
- drop-off by step
- rage clicks or support complaints
- time to complete the core task

Usually not a real constraint:
- "the whole UI needs a refresh"

Good smallest next step:
- choose one critical flow, cut confusion, and ignore broad cosmetic work

## Research

Ask:
- which unknown most changes the decision?
- where is the cost of being wrong highest?
- what research blocks action versus what is merely interesting?

Bias toward:
- decision-relevant unknowns
- fast learning when risk is low
- deeper work only when the decision really depends on it

Quantify:
- which unknown would change the decision
- cost of being wrong
- how quickly an answer can be obtained

Usually not a real constraint:
- "we need more confidence on everything"

Good smallest next step:
- run the cheapest study that can change the launch or build decision

## Brainstorming

Ask:
- which few ideas deserve prototype or experiment time?
- what should be killed early?
- what is exciting but not actually load-bearing?

Bias toward:
- broad divergence first
- hard convergence after
- experiments instead of giant idea inventories

Quantify:
- number of ideas worth prototyping
- expected learning per experiment
- carry-cost if the idea succeeds

Usually not a real constraint:
- "we should keep all options open"

Good smallest next step:
- cut the list to 1-3 experiments and kill the rest for now
