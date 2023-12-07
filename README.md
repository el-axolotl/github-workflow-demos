# github-workflow-demos
A collection of github actions to implement into code pipelines.

## Trufflehog
### What is it?
According to GitGuardian, 10 million new secrets were detected in public repositories within GitHub commits in 2022. Evidence shows that this can happen to the most careful of organizations. It is of utmost importance to implement a secret scanner within your CI/CD pipeline. 

TruffleHog is a tool that can be implemented as a pre-commit hook or a GitHub action that can scan all of your repository's previous commits, for secrets. For implementation, see ./.github/workflows/trufflehog.yml

For more information, see https://github.com/trufflesecurity/trufflehog
