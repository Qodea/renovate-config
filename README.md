# Base template
Start with all the required security tooling.

Qodia *Strongly Suggests* that all new platform work starts with this template.
We have made efforts to shift left all basic security practises and have implemented these in a standardised way using devcontainers and pre-commit.

## Security checks
This template has pre defined linting (Black, tflint) and security testing for python (bandit) and terraform (trivy). We also scan the workspace for anything that looks like a secret before you can commit it to a VCS.

This is a belt and braces approach. You may choose in some cases to implement these pre-commit checks server side as a project progresses.
