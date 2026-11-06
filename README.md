# Island Socionics Simulation

Agent-based simulation of four initially isolated groups on one large uninhabited island.

## Scenario

- 64 participants, ages 20–30.
- Four settlements of 16 people, one socionic quadra per settlement.
- Each of the 16 socionic types is represented by four participants (two men and two women).
- All participants begin without tools or stored supplies, but retain ordinary knowledge and experience from their previous lives.
- The island regions differ geographically, while access to essential resource categories remains broadly comparable.
- The settlements begin unaware of one another and may discover one another over time.

## Current narrative checkpoint

The first month has been simulated narratively. All four groups have fire, temporary shelters, basic tools, and early food-gathering systems. None has yet demonstrated a reliably sufficient food supply. There have been no deaths or major disasters.

The detailed starting roster and the month-one chronology should be transferred into structured data in a later step. Until then, this repository does not treat unrecorded details as measured facts.

## Project structure

- `data/` — participants, settlements, resources, and initial conditions.
- `simulation/` — agent rules, environment, time progression, and event mechanics.
- `events/` — chronological event log.
- `analysis/` — metrics, comparisons, and visualizations.
- `docs/` — assumptions, methodology, and model limitations.

## Methodological principles

1. Separate observed events from interpretations and hypotheses.
2. Do not assign skills, jobs, leadership, values, or actions solely from a socionic type.
3. Model individual biographies, skills, health, fatigue, geography, weather, chance, learning, and social ties.
4. Keep individual variation within each quadra; members of a group may disagree.
5. Treat socionics as a hypothesis being explored in the simulation, not as an established causal law or scientific validation.
6. Avoid false precision: label estimates and uncertainty explicitly.
7. In narrative records, always write each participant's socionic type next to their name in parentheses.

## Development status

- [x] GitHub repository created.
- [x] Initial project documentation.
- [ ] Transfer the 64-person roster into structured data.
- [ ] Record the first month as an event log.
- [ ] Define measurable state variables and update rules.
- [ ] Implement a minimal Python model.
- [ ] Evaluate and revise the model before adding complexity.

## Technology

The initial implementation is planned in Python. Mesa may be considered later if its agent-based modeling abstractions prove useful; it is not a prerequisite for the first prototype.
