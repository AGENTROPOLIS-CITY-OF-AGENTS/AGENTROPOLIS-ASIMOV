# HUGO — Embodied Entertainment Research Candidate

Status: RESEARCH ONLY — not integrated, approved, deployed, or confirmed compatible.
District: ASIMOV
Track: Embodied Entertainment & Social Robotics

## Scope
Evaluate Dynamic Creatures' HUGO as a reference for expressive humanoid character interaction in theme parks, museums, hospitality and entertainment. HUGO is not a Boston Dynamics product; any relationship between its team and Boston Dynamics must not be presented as a product integration.

## Proposed ASIMOV Mapping
- ASIMOV-SENSE: audience proximity, environmental context and consent-aware perception.
- ASIMOV-PLAN: bounded scripted character routines.
- ASIMOV-GUARD: risk classification, motion/force limits, crowd separation, geofencing and local emergency stop.
- ASIMOV-TELEOP: explicit, attributable operator sessions; no undisclosed autonomous fallback.
- ASIMOV-MOVE: locomotion and body positioning only after supported hardware interfaces and safety controls are verified.
- ASIMOV-AUDIT: operator, robot identity, permissions, commands, safety events and outcomes.

## Adapter Candidate
Provisional name: ASIMOV-ADAPTER-HUGO-RESEARCH. This is a proposed interface study, not a working adapter. Investigate documented APIs, SDKs, ROS 2 bridge feasibility, licensing, telemetry access, local safety authority, disconnect behavior and operator controls. Do not assume SnowJay OS provides an open API.

## Promotion Gates
1. Document vendor identity, official technical documentation and source provenance.
2. Verify hardware/software availability, interfaces, licensing and permission to integrate.
3. Threat-model camera/audio collection, bystander privacy, network links and teleoperation.
4. Prototype with simulator or mock adapter only; no real-world motion commands.
5. Independently test safety stop, command expiry, disconnect fail-safe, proximity limits and human override.
6. Obtain explicit human approval and auditable deployment receipt before any physical pilot.

## Proposed Demonstration
A simulated museum greeter: an operator-approved greeting, safe gesture, bounded navigation zone, no biometric identification, no unsanctioned recording, and full audit receipt.

## Evidence / Open Questions
- Verify primary-source HUGO technical specifications and operational maturity.
- Confirm whether a developer program or supported API exists.
- Confirm supported autonomy versus teleoperation modes.
- Confirm relevant physical safety certifications before any deployment claims.

No procurement, credentials, external vendor access, deployment, or hardware control is authorized by this document.
