# Contextly

Contextly is a concept for reusable embedded coaching and context-collection experiences for niche apps. It aims to help apps understand what a user needs without repeatedly asking the same questions.

## Established concept

- Apps declare the user context they require.
- With the user's authorization, apps can reuse relevant existing context. Missing context can be collected through Contextly activities embedded in the app experience.
- Apps can be the entry point into Contextly; users do not need to begin with a standalone coach.
- A shared backend maintains two kinds of context:
  - **Durable context:** ideal self, values, and principles.
  - **Time-dependent context:** goals, interests, and challenges.
- Check-ins keep context current as a user's circumstances and priorities change.
- A coach may recommend apps based on the user's needs.

## Privacy and control

Context sharing is scoped and user-controlled. An app should receive only the context the user has authorized for that app, rather than unrestricted access to a user's context. The detailed consent, access, retention, and revocation mechanisms remain to be designed.

## Open decisions

- Which niche app and user need should be the first use case?
- What context schema and freshness rules should be used?
- How should embedded activities and coaching experiences work?
- How should consent, access controls, updates, and deletion be implemented?
- How should app recommendations be selected and presented?
- What is the business model? A percentage of participating apps' profits or another revenue-sharing arrangement has been suggested, but no terms or model have been agreed.
- What implementation stack, architecture, and integration interfaces should be used?

## Project status

Concept-stage repository. No implementation stack has been selected, and no production application is included yet.
