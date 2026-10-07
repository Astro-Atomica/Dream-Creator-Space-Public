# Managing reports

Use GitHub Issues as the public record for bugs and feature requests. Track one distinct problem or request per issue.

## Review new issues

1. Check whether the issue duplicates an existing report. Link the original before closing a duplicate.
2. Confirm the report has enough detail to understand the problem. For bugs, ask for missing version/build, browser information, or reproduction steps.
3. Apply the appropriate existing label: `bug`, `enhancement`, `documentation`, or `question`.
4. Record reproduction results and relevant constraints in the issue. Distinguish confirmed behavior from assumptions.
5. Use a milestone only when the work has a concrete release target. An open issue or label alone is not a delivery commitment.

## Resolve issues

Application changes happen in the separate implementation repository. Share a public summary here without copying private source, deployment logs, or internal review notes.

For a bug fix, record the version/build where the fix is available and the verification performed before closing as resolved. A local fix does not establish that the live site has been updated.

For a feature, close as completed when the user-facing result is available. For a duplicate or a request that will not be pursued, explain the reason and link related issues where useful.

## Maintain documentation

Update the user guide when released behavior changes. Check visible control names and links against the site. Keep proposed features in issues until implemented; do not document them as available.
