# release-tests
The primary purpose of this repo is to test integration with [Intuit Auto](https://intuit.github.io/auto/docs)

Auto is used to generate the CHANGELOG.md file, as well as the tags in this repository.
It includes jira integration to link to any mentioned jira tickets.
The same workflow that generates changelogs also creates a new release branch.

Auto is executed by a github workflow that executes on demand.
