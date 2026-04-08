# Worked Examples

Use these when the right focus is not obvious.

## 1. Seed Startup With Weak Activation

Situation:
`Two founders and two engineers. Activation is weak. The team wants a redesign, analytics rewrite, enterprise feature, infra cleanup, and more interviews. Runway is 5 months.`

Example output:

- `Outcome`
  - Improve activation enough in the next 4-6 weeks to prove users can reach first value.

- `Current Constraint`
  - Weak activation is the bottleneck.
  - Team size and runway make broad parallel work dangerous.

- `Candidate Drivers`
  - fix the highest-friction onboarding step
  - add minimal funnel instrumentation
  - run tightly scoped user calls on failed activation
  - redesign
  - analytics rewrite
  - enterprise feature
  - broad infra cleanup

- `Vital Few`
  - `do now`: minimal instrumentation on the activation path
  - `do now`: one focused activation fix
  - `test first`: validate enterprise demand before building

- `What To Ignore, Defer, Or Delete`
  - defer redesign
  - defer analytics rewrite
  - defer broad infra cleanup unless it directly breaks activation
  - delete any work that does not improve activation or near-term revenue

- `Recommendation`
  - Make activation the company priority for the next month.

- `Smallest High-Leverage Next Step`
  - Instrument 5-7 events on the key path and ship one activation fix within 7 days.

## 2. Reliability Firefighting vs New Feature Promise

Situation:
`A B2B product has a promised new feature, but the current core workflow fails often enough that sales and support are spending time on it every week.`

Example output:

- `Outcome`
  - Preserve trust and stop revenue leakage over the next 30 days.

- `Current Constraint`
  - Reliability on the core workflow is the bottleneck.

- `Candidate Drivers`
  - fix top failure mode on the hot path
  - improve observability on that path
  - ship the promised feature
  - upgrade surrounding infrastructure

- `Vital Few`
  - `do now`: fix the top failure mode
  - `measure first`: tighten observability where incidents happen

- `What To Ignore, Defer, Or Delete`
  - defer the new feature
  - defer infrastructure changes that do not reduce incidents

- `Recommendation`
  - Put the feature on pause until the core workflow stops failing.

- `Smallest High-Leverage Next Step`
  - Review the last 10 failures, fix the most repeated root cause, and track incident rate weekly.

## 3. More Research vs Decision-Relevant Research

Situation:
`There are many interesting questions, but only one unknown changes the launch decision.`

Example output:

- `Outcome`
  - Make a launch decision with enough confidence to move.

- `Current Constraint`
  - One missing answer materially changes the launch decision.

- `Candidate Drivers`
  - broad exploratory research
  - targeted research on the decision-changing unknown
  - internal debate
  - delaying the launch

- `Vital Few`
  - `measure first`: answer the one unknown that changes the decision

- `What To Ignore, Defer, Or Delete`
  - defer broad curiosity research
  - delete analyses that do not change the decision

- `Recommendation`
  - Run one focused research pass tied directly to the gating unknown.

- `Smallest High-Leverage Next Step`
  - Write the decision that would change if the answer flips, then design the cheapest study that resolves it.

## 4. High Leverage Does Not Mean Build Immediately

Situation:
`A new enterprise feature could matter a lot, but confidence is low and sales evidence is weak.`

Example output:

- `Outcome`
  - Learn whether the feature can create revenue without wasting 6 weeks of build time.

- `Current Constraint`
  - Evidence quality is the bottleneck, not engineering speed.

- `Vital Few`
  - `test first`: sell or prototype the feature before building

- `What To Ignore, Defer, Or Delete`
  - defer full implementation

- `Recommendation`
  - Use manual service, clickable mockups, or sales conversations to validate willingness to pay.

- `Smallest High-Leverage Next Step`
  - Book 5 target-customer calls this week with a concrete price and workflow pitch.
