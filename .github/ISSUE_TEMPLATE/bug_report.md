---
name: Bug report
about: Create a report to help us improve
---

## Description

Please provide a clear and concise description of the issue you are encountering, and a reproduction of your configuration (see the `.projenrc.js` and explain the combinaison of parameters ou uses. The reproduction MUST be executable by running `npx run build && npx cdk deploy ` without any further changes.

If your request is for a new feature, please use the `Feature request` template.

- [ ] ✋ I have searched the open/closed issues and my issue is not listed.

## ⚠️ Note

Before you submit an issue, please perform the following first:

1. Remove the local `node_modules` directory (! ONLY if state is stored remotely, which hopefully you are following that best practice!): `rm -rf .terraform/`
2. Re-initialize the project root to pull down modules: `npx projen`
3. Re-attempt build and check if the issue still persists `npx projen build`
4. Re-deploy your stack `npx cdk deploy`


## Versions

- Module version [Required]:

- Terraform version:
<!-- Execute terraform -version -->
- Provider version(s):
<!-- Execute: terraform providers -version -->

## Reproduction Code [Required]

<!-- REQUIRED -->

Steps to reproduce the behavior:

<!-- Are you using workspaces? -->
<!-- Have you cleared the local cache (see Notice section above)? -->
<!-- List steps in order that led up to the issue you encountered -->

## Expected behavior

<!-- A clear and concise description of what you expected to happen -->

## Actual behavior

<!-- A clear and concise description of what actually happened -->

### Terminal Output Screenshot(s)

<!-- Optional but helpful -->

## Additional context

<!-- Add any other context about the problem here -->