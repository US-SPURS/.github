# Repository Setup Checklist

Use this checklist when creating a new repository for the US-SPURS GitHub organization.

## Required Files

### Legal and Licensing
- [ ] **LICENSE** - CC0 1.0 Universal public domain dedication (copy from .github repo)
- [ ] **DISCLAIMER.md** - Federal agency disclaimer (copy from .github repo)

### Community Health Files
- [ ] **README.md** - Project overview, installation, usage instructions
- [ ] **CODE_OF_CONDUCT.md** - Will inherit from .github repo if not present
- [ ] **CONTRIBUTING.md** - Project-specific contribution guidelines (or inherit from .github repo)
- [ ] **SECURITY.md** - Security policy (or inherit from .github repo)
- [ ] **SUPPORT.md** - How to get help (or inherit from .github repo)

### Governance and Documentation
- [ ] **CODEOWNERS** - Define code owners for automatic PR review requests
- [ ] **MAINTAINERS.md** - List of project maintainers
- [ ] **CHANGELOG.md** - Track all notable changes
- [ ] **code.json** - Federal Source Code Policy metadata

### GitHub-Specific Files
- [ ] **.github/ISSUE_TEMPLATE/** - Issue templates (bug report, feature request, etc.)
- [ ] **.github/PULL_REQUEST_TEMPLATE.md** - Pull request template
- [ ] **.github/workflows/** - GitHub Actions workflows (CI/CD, linting, etc.)
- [ ] **.github/FUNDING.yml** - Funding information (use template from .github repo)

### Configuration Files
- [ ] **.gitignore** - Appropriate for your project's language/framework
- [ ] **.editorconfig** - Consistent coding styles (optional but recommended)
- [ ] **package.json** or equivalent - Project dependencies and metadata

## Repository Settings

### General Settings
- [ ] Set repository description
- [ ] Add relevant topics/tags
- [ ] Enable/disable wikis (as needed)
- [ ] Enable/disable projects (as needed)
- [ ] Disable "Allow merge commits" if using squash or rebase
- [ ] Enable "Automatically delete head branches"

### Access and Security
- [ ] Configure branch protection for `main`/`master`
  - [ ] Require pull request reviews before merging
  - [ ] Require status checks to pass before merging
  - [ ] Require conversation resolution before merging
  - [ ] Require signed commits (recommended)
- [ ] Enable Dependabot alerts
- [ ] Enable Dependabot security updates
- [ ] Enable Secret scanning
- [ ] Configure CODEOWNERS review requirements

### Integrations
- [ ] Enable relevant GitHub Apps (if any)
- [ ] Configure webhooks (if needed)
- [ ] Set up continuous integration (GitHub Actions recommended)
- [ ] Configure deployment environments (if applicable)

## Code Quality

### Testing
- [ ] Set up testing framework
- [ ] Add test coverage reporting
- [ ] Configure CI to run tests on PRs
- [ ] Set minimum coverage requirements

### Linting and Formatting
- [ ] Add linting configuration
- [ ] Add code formatting configuration
- [ ] Configure pre-commit hooks (optional)
- [ ] Add linting to CI pipeline

### Documentation
- [ ] API documentation (if applicable)
- [ ] Architecture/design documentation
- [ ] Deployment documentation
- [ ] User guides/tutorials

## Compliance

### Federal Requirements
- [ ] Ensure code.json is accurate and complete
- [ ] Verify license is CC0 1.0 (public domain)
- [ ] Include DISCLAIMER.md
- [ ] Follow accessibility guidelines (Section 508)
- [ ] Ensure no sensitive information is committed

### Security
- [ ] Review for hardcoded credentials
- [ ] Configure secrets properly (use GitHub Secrets)
- [ ] Set up security scanning
- [ ] Document security reporting process

## Before Going Public

### Final Checks
- [ ] Review all documentation for accuracy
- [ ] Test installation/setup instructions
- [ ] Verify all links work
- [ ] Check for any internal-only information
- [ ] Ensure commit history is clean (no secrets, etc.)
- [ ] Get approval from US-SPURS Open Source Program Office

### Communication
- [ ] Announce repository to relevant teams
- [ ] Update US-SPURS repository listing
- [ ] Consider a blog post or press release (for significant projects)

## Ongoing Maintenance

### Regular Tasks
- [ ] Review and merge dependabot PRs
- [ ] Triage new issues weekly
- [ ] Review and merge pull requests
- [ ] Update CHANGELOG.md for releases
- [ ] Tag releases appropriately
- [ ] Monitor security alerts

### Periodic Reviews
- [ ] Quarterly: Review and update documentation
- [ ] Quarterly: Review and update dependencies
- [ ] Annually: Review project goals and roadmap
- [ ] Annually: Review and update contributor guidelines

## Resources

* [US-SPURS .github Repository](https://github.com/US-SPURS/.github) - Templates and examples
* [Federal Source Code Policy](https://code.gov)
* [GitHub Community Health Files](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions)
* [DSACMS Repo Scaffolder](https://github.com/DSACMS/repo-scaffolder) - Automated repository setup tool

## Questions?

Contact the US-SPURS Open Source Program Office at opensource@us-spurs.gov
