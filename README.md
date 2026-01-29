# DevSecOps CI/CD Security Pipeline

## Technical Architecture

**Infrastructure Automation:**
- **Terraform:** Automated provisioning of AWS EC2 instances with security group configurations
- **Ansible:** Configuration management and automated server hardening
- **GitLab CI/CD:** 7-stage automated pipeline with security integration

**Security Controls Implemented:**
- Automated security group configuration with least-privilege access
- SSH hardening and key-based authentication
- Continuous compliance testing with Chef InSpec
- Penetration testing with OWASP ZAP
- Infrastructure state management with remote backend

**Pipeline Stages:**
1. **Validate** - Terraform syntax and configuration validation
2. **Plan** - Infrastructure change preview and artifact generation
3. **Apply** - Automated infrastructure deployment
4. **Configure** - Ansible-based server configuration
5. **Continuous Compliance** - Chef InSpec security controls testing
6. **Penetration Testing** - OWASP ZAP vulnerability scanning
7. **Destroy** - Manual infrastructure teardown

## Security Features
- Security group isolation with GitLab Runner-only SSH access
- Automated security testing in CI/CD pipeline
- Infrastructure as Code (IaC) with version control
- Compliance validation against AWS security benchmarks
- Automated vulnerability scanning

## Technologies
`Terraform` `Ansible` `GitLab CI/CD` `AWS EC2` `Chef InSpec` `OWASP ZAP` `Docker` `Infrastructure as Code` `Security Automation`

## Project Files
- `/configs` - Terraform infrastructure code and CI/CD pipeline configuration
- `/scripts` - Ansible playbooks for automated configuration
- `/proof` - Deployment screenshots and validation evidence
- `/diagnostics` - Error resolution and troubleshooting documentation
