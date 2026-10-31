# Assignment 7 Requirement Checklist

## A

- [x] Public repository and live Pages site verified.
- [x] Pages source is `main` / `/`.
- [x] Branch-based Pages build is successful.
- [x] Live URL returns HTTP 200 and renders the Assignment 7 Activity Log page.
- [ ] Browser screenshot evidence still needs to be captured for the final report.

## E

- [x] PAT with expiration created by fanyuzhenfu (confirmed by the user; value never read).
- [x] Repository secret `TOKEN` configured (name confirmed by API; value never read).
- [x] Activity workflow uses TheDanniCraft/activity-log@v1.
- [x] Six-hour schedule enabled only after TOKEN verification.
- [x] Activity Workflow → README commit → Pages build → Live page verified.

## O

- [ ] GitHub Actions Pages source enabled after E evidence.
- [ ] Build, Validate, and Deploy jobs have explicit dependencies.
- [ ] Deliberate validation failure blocks Deploy.
- [ ] Previous live site remains available during failure.
- [ ] Corrected run deploys successfully.
