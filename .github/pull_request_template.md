# Pull Request Checklist

## Summary
<!-- What does this PR do? Why is it needed? -->

## Type of Change
- [ ] Bug fix
- [ ] New feature
- [ ] Breaking change
- [ ] Refactor
- [ ] Documentation update
- [ ] CI/CD change
- [ ] Infrastructure / platform change
- [ ] Security improvement
- [ ] Dependency update

---

# General Checks

- [ ] PR title is clear and meaningful
- [ ] Linked Jira / work item included
- [ ] Self-reviewed the changes
- [ ] No commented-out code or debug logging left behind
- [ ] Documentation updated where required
- [ ] CHANGELOG / release notes updated (if applicable)
- [ ] No sensitive information, secrets, or credentials committed
- [ ] Version numbers updated where required

---

# Testing

- [ ] Local testing completed
- [ ] Existing tests pass
- [ ] New tests added where appropriate
- [ ] Manual validation completed
- [ ] Edge cases considered

---

# Kubernetes / Helm

- [ ] Helm templates render successfully
- [ ] Values schema updated if required
- [ ] Resource requests/limits reviewed
- [ ] Liveness/readiness probes validated
- [ ] Labels and annotations applied consistently
- [ ] RBAC permissions reviewed
- [ ] NetworkPolicy reviewed (if applicable)
- [ ] ArgoCD sync behaviour considered
- [ ] Sync waves/order reviewed (if applicable)

---

# Crossplane / AWS Resources

- [ ] managementPolicies reviewed
- [ ] Deletion behaviour understood and validated
- [ ] External names and observe-only resources checked
- [ ] IAM permissions reviewed
- [ ] Encryption enabled where required
- [ ] Backup/snapshot implications considered
- [ ] Cost impact considered
- [ ] Changes validated in lower environment first

---

# Security

- [ ] Least privilege applied
- [ ] Input validation considered
- [ ] Sensitive logs/errors avoided
- [ ] TLS/encryption requirements met
- [ ] Dependency vulnerabilities reviewed
- [ ] Authentication/authorization impacts reviewed

---

# Observability

- [ ] Logging added/updated where needed
- [ ] Metrics exposed/updated where needed
- [ ] Alerts reviewed or added
- [ ] Dashboards updated if required

---

# Deployment / Rollback

- [ ] Deployment strategy considered
- [ ] Rollback plan understood
- [ ] Backward compatibility checked
- [ ] Database migration impact reviewed
- [ ] Downtime impact assessed

---

# Reviewer Notes
<!-- Anything reviewers should pay special attention to? -->

## Screenshots / Evidence
<!-- Logs, screenshots, test evidence, Grafana panels, etc. -->
