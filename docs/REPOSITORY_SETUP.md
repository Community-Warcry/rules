# Repository administration

This checklist describes owner actions. Files in this repository do not enable GitHub settings or create teams.

## Owner checklist

- [ ] Appoint maintainers publicly and record them in MAINTAINERS.md.
- [ ] Create the rules-maintainers team and grant appropriate repository access.
- [ ] Add CODEOWNERS for that team after the team exists and has access.
- [ ] Protect main: require pull requests, independent review, resolution of conversations, and dismissal of stale approvals.
- [ ] Disable force pushes and deletion of main; minimise bypass access.
- [ ] Keep at least two trusted organisation owners when available and require two-factor authentication.
- [ ] Enable Discussions if the community wants a separate place for broad ideas.
- [ ] Create the labels below and milestones for scheduled patches.

GitHub review requirements support the workflow, but do not replace the council's recorded decision threshold. Check that protection applies to administrators as intended.

## Suggested labels

Type: balance, clarification, playtest, governance, documentation.
Status: needs-evidence, accepted-for-testing, ready-for-review, deferred, out-of-scope.

Issue templates intentionally do not depend on these labels already existing.

## Publication

Keep Markdown as the source of truth. Start with manual tagged releases. Add automation only when the release process is agreed; automation must not publish experimental changes as stable.
