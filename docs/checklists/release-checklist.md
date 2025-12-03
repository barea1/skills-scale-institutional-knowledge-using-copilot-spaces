# Release Checklist

This checklist is used by the Release Manager and Release Engineer to ensure a complete, controlled release process.

---

## Pre-Release Validation

- [ ] All planned features and fixes are merged to the release branch
- [ ] Code freeze is in effect
- [ ] All automated tests pass (unit, integration, e2e)
- [ ] QA Coordinator has provided testing sign-off
- [ ] Security scan completed with no critical/high vulnerabilities
- [ ] Performance testing completed and within acceptable thresholds
- [ ] Release notes drafted and reviewed by Product Owner
- [ ] Documentation updated for new features/changes
- [ ] Rollback plan documented and reviewed
- [ ] Stakeholder notification list confirmed

---

## Deployment Steps

- [ ] Notify team of deployment start time
- [ ] Create deployment ticket/issue for tracking
- [ ] Back up current production state (database, configurations)
- [ ] Deploy to staging/pre-production environment
- [ ] Run smoke tests on staging
- [ ] Obtain final go/no-go approval from Release Manager
- [ ] Deploy to production environment
- [ ] Monitor deployment logs for errors
- [ ] Verify deployment health checks pass
- [ ] Update deployment ticket with completion status

---

## Post-Release Verification

- [ ] Run production smoke tests
- [ ] Verify key user flows are functioning
- [ ] Check application logs for errors or warnings
- [ ] Confirm monitoring dashboards show healthy metrics
- [ ] Verify feature flags/toggles are set correctly
- [ ] Test any new integrations or APIs in production
- [ ] Confirm no unexpected alerts or incidents

---

## Stakeholder Notifications

- [ ] Send release announcement to stakeholders
- [ ] Update status page or changelog
- [ ] Notify support team of new features and known issues
- [ ] Inform Customer Success/Sales of customer-facing changes
- [ ] Post internal announcement (Slack, email, etc.)
- [ ] Update project board with release status

---

## Rollback Plan

- [ ] Rollback procedure documented and accessible
- [ ] Rollback tested in staging prior to release
- [ ] Database rollback scripts prepared (if applicable)
- [ ] Clear rollback decision criteria defined
- [ ] Rollback notification plan in place
- [ ] Team members on-call and aware of rollback procedure

### Rollback Decision Criteria
Initiate rollback if any of the following occur:
- Critical functionality is broken
- Security vulnerability discovered post-deployment
- Data integrity issues detected
- Service degradation exceeds acceptable thresholds
- Stakeholder/leadership requests immediate rollback

---

## Sign-Off Criteria

| Role | Sign-Off Item | Signature | Date |
|------|---------------|-----------|------|
| Release Manager | Pre-release validation complete | | |
| QA Coordinator | Testing sign-off provided | | |
| Technical Lead | Technical readiness confirmed | | |
| Release Manager | Go/no-go decision | | |
| Release Manager | Post-release verification complete | | |
| Stakeholder Liaison | Stakeholders notified | | |

---

## Notes

Use this section to capture any release-specific notes, issues encountered, or lessons learned.

| Item | Details |
|------|---------|
| Release Version | |
| Release Date | |
| Release Lead | |
| Issues Encountered | |
| Lessons Learned | |
