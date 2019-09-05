# Avalaible and planned actions

- [x] `actions-audit` - Run `npm audit` and check for vulnarabilities
- [x] `actions-coverage` - Run Code Coverage
- [x] `actions-deploy` - Deploy a zip file to tangro-static file server
- [ ] `actions-licenses` - Licenses of packages listed in package.json
- [ ] `actions-otrs` - Check issues and PRs for OTRS links and notify the OTRS tickets and reformat the URLs
- [ ] `actions-release` - Build a release on milestone close
- [x] `actions-test` - Run Tests
- [x] `tangro-actions-template`- Action template with a workflow to automatically build the action

# [actions-audit](https://github.com/tangro/actions-audit)

An action that runs `npm audit --json` and fails the job if there are `high` or `critical` vulnerabilities. Also sets a status to the commit.

# [actions-coverage](https://github.com/tangro/actions-coverage)

An action that collects the code coverage and sets a status to the commit with a summary.

# [actions-deploy](https://github.com/tangro/actions-deploy)

An action to deploy a static site contained in a zip file to the tangro-static server.

# [actions-test](https://github.com/tangro/actions-test)

An action that runs the tests and collects the test results. Annotations will be added directly to the files for failing tests. Also a status with the summary will be added.

# [tangro-actions-template](https://github.com/tangro/tangro-actions-template)

A template for actions that have a workflow ready to automatically build the action and some basic dependencies and code snippets already ready.
