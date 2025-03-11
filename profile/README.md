# GovRadar
Welcome to GovRadar!

## Contributing

### Pull Requests
Every contribution to the main branch should be peer reviewed through a pull request.

#### Naming
When opening a pull request follow the conventional commit [specification](https://www.conventionalcommits.org/en/v1.0.0/):
- Start with feat/fix/chore/ci/build/docs/refactor/test/perf
- Followed by the area/scope where most changes have been made
- Followed by a brief description of the change
- Followed by a reference to the Azure DevOps task, e.g. AB#0000 in square brackets

An example:

**feat(tenders): Add new filter options [AB#1234]**

#### Description
Descriptions are partially auto-generated upon opening a PR but you can and should add the following manually:
- Azure DevOps task number, e.g. AB#0000
- Brief description of purpose of the change

#### Closing
Close pull requests using squash&merge while using the PR title as commit message. This way we ensure that tickets can be traced to individual commits after the PR was closed.
