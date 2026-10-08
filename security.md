# Security Policy

## Intended Users
The code, documentation, and data in this repository are intended solely for:
- Course instructors and teaching assistants at the University of Connecticut (UConn).
- Authorized project team members collaborating on course assignments.

## Risk Assessment
If the contents of this repository fell into the wrong hands, potential security and academic risks include:
- **Academic Integrity:** Exposure of proprietary coursework solutions, homework answers, or project implementations that could be plagiarized by others.
- **Sensitive Data & Credentials:** Accidental leakage of API keys, database credentials, authentication tokens (such as JWT secrets), or configuration files.
- **Intellectual Property:** Unauthorized reuse or redistribution of proprietary team software components.

## Security Measures
To mitigate these risks and keep this repository secure, the following steps have been taken:
- **Exclusion of Secrets:** Environment files (`.env`), private keys, and build artifacts are strictly excluded via `.gitignore` to prevent accidental commits.
- **Access Control:** Repository visibility is properly configured, and sensitive code changes are managed through pull requests and code reviews among teammates.
- **Credential Hygiene:** No hardcoded passwords, API tokens, or production credentials exist in the source code.
