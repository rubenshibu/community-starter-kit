# welcome bot: A Probot App

a GitHub App built with probot that welcomes new users based off maintainer defined comments that should be located in a .github/config.yml

## What it does

its an open sourse and mono is nice and it will send hello to all your contributers

## Getting started

1. [Install the bot](https://github.com/apps/welcome) on the intended repositories. The plugin requires the following **Permissions and Events**:

- Pull requests: Read & Write
- Issues: Read & Write

2. Create a .github/config.yml file to check for content of the comments:

```
#

You can opt out of having the bot comment on first time pull requests, pull request merges, or new issues by not filling in a value for each app's respective field.

For some inspiration about what kind of content to include in your .github/config files, check out [Electron's Configuration](https://github.com/electron/electron/blob/master/.github/config.yml).

## Need help?

If you need help using this app, we encourage you to:

- Check out the [Getting Started Guide](docs/getting-started.md) in the docs folder of this repository
- If you can't find the answer there, open an issue in this repository and add the label `question`

## Project maintainers

This project is maintained by Monalisa Octocat and friends. Use of this project under the [MIT License](LICENSE.md).
