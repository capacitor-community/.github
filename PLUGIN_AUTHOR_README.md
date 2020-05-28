# For authors of this plugin from the Capacitor core team

This is a welcome message to all new plugin authors in the Capacitor Community organization.

First of all, welcome! We look forward to having your awesome plugin and contributions in this organization and are available for help if need be (easiest way is to ping one of us on Twitter).

## Project Setup

One of the goals of the Capacitor Community initiative is to have a set of github repos that follow a set of conventions around READMES, package naming

### README format

### Package Naming

Packages should be named as simply as possible, without any `capacitor` or `plugin` words in the package name itself. Packages must be published in the `@capacitor-community` npm scope.

For example, a Google Maps plugin would be published under `@capacitor-community/google-maps`.

### Publishing

Projects should use the `np` package for publishing which will correctly update tags and manage the entire publish process.

### Changelogs

Projects should follow the [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) process (more info soon)

### Recognizing Contributors

Recognizing contributors is important. Every project in the `capacitor-community` GitHub org is automatically set up to use [All Contributors](https://allcontributors.org/) and maintainers should recognize any community members that contribute by following the [All Contributors usage guide](https://allcontributors.org/docs/en/bot/usage).

### Code Formatting

Capacitor uses a slightly less conventional code style for iOS and Android. The main differences are using two spaces and curly braces opening on the same line. Please adjust your editor settings or use a code formatter. In the future we will distribute a prettier config to make this easier.
