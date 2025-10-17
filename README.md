# Python Code Quality Tools  

## [🐳Interactive Tutorial](https://lgtkgtv.github.io/code_quality_security_tools_training_v1/)

***

### 📊 Currently Supported Tools 
| Tool | Purpose | What It Catches |
|------|---------|-----------------|
| **🔒 Bandit** | Security scanner | Hardcoded secrets, injection vulnerabilities, weak crypto |
| **📏 Flake8** | Style checker | PEP 8 violations, complexity issues, unused imports |
| **🎨 Black** | Code formatter | Inconsistent formatting, line length, quote styles |
| **🔍 MyPy** | Type checker | Type errors, None handling, API misuse |
| **📦 Isort** | Import sorter | Import organization, grouping, order |
| **🧪 Pytest** | Test runner | Test discovery, coverage, assertions |

***

### TBD -- Plan to cover additional tools

**Advanced Security Scanning**
- **semgrep** - Advanced static analysis with custom security rules
- **safety** - Scan Python dependencies for known vulnerabilities
- **pip-audit** - Supply chain security auditing for Python packages

**Container Security & Infrastructure**
- **hadolint** - Dockerfile best practices and security linting
- **trivy** - Container image and filesystem vulnerability scanner
- **dockle** - Container image security checker and best practices
- **grype** - Container and filesystem vulnerability scanner

**Secrets & Credentials Protection**
- **detect-secrets** - Prevent secrets from entering codebase
- **gitleaks** - SAST tool for detecting hardcoded secrets in git repos
- **git-secrets** - Scan Git history for accidentally committed secrets
- **trufflehog** - Deep Git history and filesystem secrets scanning

**Software Bill of Materials (SBOM)**
- **syft** - Generate SBOMs for container images, filesystems, and archives
- **cyclonedx** - Create and validate CycloneDX format SBOMs
- **spdx-tools** - Generate and validate SPDX format SBOMs
- **bomber** - Scan SBOMs for known vulnerabilities

**Compliance & Governance**
- **prowler** - CIS compliance checking for AWS, Azure, GCP
- **checkov** - Static analysis for Terraform, CloudFormation, Kubernetes
- **kics** - OWASP Infrastructure as Code security scanning
- **openscap** - NIST compliance and security automation

