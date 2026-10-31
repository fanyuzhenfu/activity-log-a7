# O-Level Gated Deploy evidence

## Successful gated deployment

- Run: https://github.com/fanyuzhenfu/activity-log-a7/actions/runs/41183350663
- Build, Validate, and Deploy all completed successfully.
- Live site returned HTTP 200.

## Deliberate failure

- Failure Run: https://github.com/fanyuzhenfu/activity-log-a7/actions/runs/41183626360
- Deliberate commit: https://github.com/fanyuzhenfu/activity-log-a7/commit/423f787ff0e4c634ec4b6f78d709e5a519a08b82
- Build succeeded.
- Validate failed because the README end activity marker was intentionally changed.
- Deploy was skipped.
- The previously deployed live site still returned HTTP 200 and showed Recent activity.

## Recovery

- Recovery commit: https://github.com/fanyuzhenfu/activity-log-a7/commit/fb0ea7543018360ff510480cf72d38cb4635a7f2
- Recovery Run: https://github.com/fanyuzhenfu/activity-log-a7/actions/runs/41183714027
- Build, Validate, and Deploy all succeeded after restoring the marker.

GitHub also displayed Node.js 20 deprecation and ubuntu-latest migration warnings. These were recorded but did not affect the successful results.
