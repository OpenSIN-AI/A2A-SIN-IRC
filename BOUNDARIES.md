# A2A-SIN-IRC Boundaries

## Role
`A2A-SIN-IRC` owns IRC messaging integration, chat workflows, and IRC-specific contracts.

## This repo should own
- IRC messaging routing, coordination, and automation flows
- IRC evidence, recovery, auth, and session handling
- IRC contracts used by downstream automation agents
- runbooks tied to chat-platform automation and monitoring

## This repo must not own
- unrelated messaging platform logic
- organization SSOT docs or architecture canon
- downstream business logic unrelated to IRC ownership

## Hard rules
- Keep changes scoped to IRC messaging integration and monitoring.
- Move non-IRC behavior back to the repos that own it.
- Keep reusable contracts focused on chat coordination and monitoring.
