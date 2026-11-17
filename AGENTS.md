# GitHub profile

Profile README and scheduled contribution-snake SVG generation.

## Verify

Keep both third-party actions pinned to full commits and validate the workflow with actionlint and zizmor after changes. The scheduled job writes only the `output` branch.

## Git

- Conventional Commits, one topic per PR.
- Squash unless commits need separate review.
- Force-push only with `--force-with-lease` on own branches.

## Boundaries

- Do not run the profile publishing workflow manually from a local session.
- Keep write permissions limited to the generator job.
