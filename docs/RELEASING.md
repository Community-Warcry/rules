# Release process

## Stable releases and development

The default branch contains development work. Tagged GitHub releases are the stable publication record. Do not publish a setup commit as a balance release.

Use vMAJOR.MINOR.PATCH:
- MAJOR: a new official baseline or an incompatible format or core-policy change.
- MINOR: gameplay balance changes within the existing baseline.
- PATCH: editorial corrections that do not change gameplay.

A point-cost or gameplay-wording change is never merely an editorial PATCH.

## Before the first release

- Appoint the council and ratify governance.
- Agree the official baseline, Matched Play restrictions, scenario assumptions, allies and blessings.
- Evaluate the evidence for each proposed change; defer untested changes.
- Agree a release calendar. The starting proposal is two balance releases per year.

## Release checklist

1. Open a release pull request listing the included changes and their approval records.
2. Verify the cumulative patch contains every active change and no unapproved proposals.
3. Check exact wording, costs, links and compatibility. Have another maintainer proofread.
4. Record council votes under GOVERNANCE.md.
5. Set the version, publication date and effective date; normally allow at least four weeks before effectiveness.
6. Move Unreleased gameplay entries into the named release in CHANGELOG.md.
7. Merge, tag the approved commit and publish a GitHub release containing the cumulative Markdown patch and release notes.
8. If distributing a PDF, generate it from that same tagged source and check it against the Markdown.
9. Link the release from README.md and communicate compatibility and adoption guidance.

Organisers retain their announced version. A new release does not override an event pack.

## Emergency changes and rollback

Reserve emergency gameplay releases for serious exploits or errors. Use the normal approval threshold and record why the ordinary schedule cannot wait. Explain any shortened notice.

Publish a new corrective release rather than changing the contents of an existing tag. Document reversals and affected versions. If official rules change, review compatibility before updating the baseline.
