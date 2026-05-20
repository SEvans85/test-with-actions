# Pull Request

## Summary
<!-- What changed and why? -->

## Linked Work Item
<!-- Jira / incident / ticket -->

---

# General Checks

- [ ] PR title is clear and meaningful
- [ ] Linked Jira ticket
- [ ] Self-reviewed the changes
- [ ] No commented-out code or debug logging left behind

---

# Application Change

## PR Author Checklist

- [ ] Local testing completed
- [ ] Existing functionality verified
- [ ] Relevant tests added/updated
- [ ] API/interface compatibility considered
- [ ] Documentation updated if needed

## Reviewer Checklist

- [ ] I understand the purpose of this change
- [ ] Testing evidence sufficient
- [ ] No obvious regressions identified
- [ ] Security concerns reviewed
- [ ] Documentation/comments are sufficient

---

# Platform / Infrastructure Change

## PR Author Checklist

- [ ] Local testing completed
- [ ] Crossplane lifecycle/deletion impact reviewed
- [ ] Values schema updated if required

## Reviewer Checklist

- [ ] Deployment behaviour understood
- [ ] No unintended deletion risk identified
- [ ] Least privilege applied
- [ ] No sensitive information, secrets, or credentials committed
- [ ] Documentation/comments are sufficient

---

# Reviewer Notes
<!-- Anything reviewers should pay special attention to? -->

## Screenshots / Evidence
<!-- Logs, screenshots, test evidence, Grafana panels, etc. -->
