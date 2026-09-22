# DefensePoint

Open-source security tooling for [Keycloak](https://www.keycloak.org/).

## Adaptive MFA

Risk-based adaptive multi-factor authentication for Keycloak. Evaluates login risk in real time using local ML inference and enforces step-up MFA based on the returned risk level.

| Repository | Language | Role |
| --- | --- | --- |
| [keycloak-adaptive-mfa-engine](https://github.com/DefensePoint/keycloak-adaptive-mfa-engine) | Python | Risk evaluation engine + Docker Compose stack |
| [keycloak-adaptive-mfa](https://github.com/DefensePoint/keycloak-adaptive-mfa) | Java | Keycloak SPI plugin |
| [keycloak-adaptive-mfa-admin-ui](https://github.com/DefensePoint/keycloak-adaptive-mfa-admin-ui) | TypeScript | Keycloak Admin UI extension |
| [keycloak-monitoring](https://github.com/DefensePoint/keycloak-monitoring) | Go | Keycloak monitoring and audit platform |

## Getting Started

See the [keycloak-adaptive-mfa-engine](https://github.com/DefensePoint/keycloak-adaptive-mfa-engine) repository for the full Docker Compose stack and setup instructions.

## License

All repositories are licensed under Apache-2.0.
