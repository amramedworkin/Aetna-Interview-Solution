# ADR-003: Security and Authentication
- Decision: Use Amazon Cognito + JWT + Spring Security
- Context: API must be securely accessed, with user-level roles and tokens.
- Alternatives Considered: Auth0, custom JWT handling, OAuth2 libraries.
- Justification: Seamless AWS integration, secure token management, scalable auth flows.
- Consequences: Requires Cognito configuration and developer familiarity with JWT concepts.


