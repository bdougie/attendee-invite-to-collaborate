# attendee-invite-to-collaborate

**attendee-invite-to-collaborate** is a GitHub App built with [probot](https://github.com/probot/probot) that automatically invites new contributors to your repository's organization once they comment on an issue. This project was inspired and cloned from [erickzhao/invite-contributors](https://github.com/erickzhao/invite-contributors)

## Usage

1. Configure the GitHub App.
2. attendee-invite-to-collaborate will automatically invite new comment
   on an issue in your organization.
3. More options are available if you add a `.github/invite-contributors.yml` file into your repository such as below.

```
# If true, this will add new contributors as outside collaborators
# to the repo their PR was merged in. Team name is ignored if this
# flag is set to true.
isOutside: false

# Specify team name to add new contributors to a specific team
# within your organization.
# Use team name or team-name-slug
team: MY TEAM NAME
```

## Contributing

Anyone can contribute with [issues](https://github.com/bdougie/attendee-invite-to-collaborate/issues) and [PRs](https://github.com/bdougie/attendee-invite-to-collaborate/pulls). If you're submitting a pull request, always create a new branch to work your changes, and try squashing commits down if possible. Always test any new code and make sure `npm test` passes and code coverage is adequate before opening a PR.
