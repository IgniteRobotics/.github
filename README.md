# .github

Org-wide settings for IgniteRobotics.

- `.github/workflows/pr-policy.yml`: every Monday (or on demand from the Actions tab), sets "who can open pull requests" to **collaborators only** on every public, non-archived repo. GitHub has no org default for this, so new public repos are caught here. Needs the `ORG_REPO_ADMIN_TOKEN` secret: a fine-grained token owned by IgniteRobotics with access to all repositories and **Administration: read and write**. When it expires, the run fails; make a new one.
