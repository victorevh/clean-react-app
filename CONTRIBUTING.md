# Contributing

We love contributors! Clean React App is maintained and contrbuted to by developers just like you.

## Raising issues

Before raising an issue, make sure you have checked the open and closed issues to see if an answer is provided there.

Please provide the following information with your issue to enable us to respond as quickly as possible.

- The relevant versions of the packages you are using.
- The steps to recreate your issue.
- An executable code example where possible.

## Key Branches

* `main` - this is the current main version supporting the 1.x.x release line. Most investment will be here, including major new features, enhancements, bug fixes, security patches etc.

## I want to contribute code but don't know where to start

If you're not sure where to start, look for the [open issues](https://github.com/rubemfsv/clean-react-app/issues).

## I'm ready to contribute code

Awesome! We have some guidelines here that will help your PR be accepted:

### Commit messages

Clean React App uses the [Conventional Changelog](https://github.com/bcoe/conventional-changelog-standard/blob/master/convention.md)
commit message conventions. Please ensure you follow the guidelines, as they
help us automate our release process.

You can take a look at the git history (`git log`) to get the gist of it.

If you'd like to get some CLI assistance, getting setup is easy:

```shell
npm install commitizen -g
npm i -g cz-conventional-changelog
```

`git cz` to commit and commitizen will guide you.

#### Release notes

Commit messages with `fix` or `feat` prefixes will appear in the release notes. 
These communicate changes that users may want to know about.

* `feat(<scope>):` or `feat:` messages appear under "New Features", and trigger minor version bumps.
* `fix(<scope>):` or `fix:` messages appear under "Fixes and improvements", and trigger patch version bumps.

If your commit message introduces a breaking change, please include a footer that starts with `BREAKING CHANGE:`.
For more information, please see the [Conventional Changelog](https://github.com/bcoe/conventional-changelog-standard/blob/master/convention.md)
guidelines.

(Also, if you are committing breaking changes, you may want to check with the other maintainers on slack first).

Examples of `fix` include bug fixes and dependency bumps that users of pact-js may want to know about.

Examples of `feat` include new features and substantial modifications to existing features.

Examples of things that we'd prefer not to appear in the release notes include documentation updates, 
modified or new examples, refactorings, new tests, etc. We usually use one of `chore`, `style`, 
`refactor`, or `test` as appropriate.

## Code style and formatting

We use [Prettier](https://prettier.io/) for formatting, and for linting we use [ESLint](https://eslint.org/) (for TypeScript).

The recommended approach is to configure Prettier to format on save in your editor 👌. If not, don't worry, our lint step will catch it.

## Pull requests

- Please write tests for any changes
- Please follow existing code style and conventions
- Please separate unrelated changes into multiple pull requests
- For bigger changes, make sure you start a discussion first by creating an issue and explaining the intended change
