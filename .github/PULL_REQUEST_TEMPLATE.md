## Problem:

< Brief overview of problem >

_Jira ticket:_ < Link to jira >

## Solution:

Brief description of what was implemented and how - highlight any considerations that are important to call out >

## Impacted Areas:

Other areas of the application that were affected by this PR that might not be obvious e.g. refactor of a component/function used across multiple areas of the app >

## Definition of Done Checklist:

### Dev Standards:

* [ ] 2 Code reviews
* [ ] Follows progressive enhancement
* [ ] Accessibility standards met
* [ ] Performance profile included. In devtools > performance > set CPU throttling 4x slowdown > record > execute changed code > Take a screen grab, right click and save JSON file and add these to your PR description > add equivalent for target branch. [Tutorial here](https://building.calibreapp.com/debugging-react-performance-with-react-16-and-chrome-devtools-c90698a522ad)

### Testing:

* [ ] All acceptance criteria met
* [ ] CI Green
* [ ] Checked In Dev Enviroment
* [ ] Signed off by PO

### Housekeeping:

* [ ] Squashed and rebased


## Checklist

Please ensure the branch and pull request adhere to the following checklist prior to merging.

- [ ] The pull request title has the following format: `<type>(<category>): <description>`
- [ ] The issue the PR fixes/resolves is in the PR description prefixed with `fixes` or `resolves`.
- [ ] There are no `package-lock.json` files... an indication `npm` has been used instead of `yarn`.
- [ ] Dependencies and devDependencies are all listed in the `package.json`, and are the correct way round.
- [ ] Linting passes on the branch without any errors or warnings.
- [ ] Unit tests pass and code coverage is 100% on the branch.
- [ ] The pull request has been reviewed and approved by any code owners and one other contributor.
