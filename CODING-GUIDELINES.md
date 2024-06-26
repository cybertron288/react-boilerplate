## Git Conventions

### Commit messages

I use the following convention:

```
type: subject

body
```

The goal of this convention is to communicate clear goal.

#### Type

The types are based on our GitHub label:

- `fix` – When fixing an issue.
- `chore` – When doing some cleanup, working on tooling, some refactoring.
- `doc` – When writing documentation.
- `feat` – When working on a feature.

#### Subject

The subject of a commit should be a summary of what the commit is about. It should not describe what the code is doing:

- `feat: what the feature is`
- `fix: what the problem is`
- `chore: what the PR is about`
- `doc: what is documented`

Examples:

- `feat: introduce combobox primitive`
- `fix: popover is not correctly aligned`
- `chore: refactor checkbox to use radix`
- `doc: update storybook for button`

> ⚠️ For a `fix` commit the message should explain what the commit is fixing. Not what the solution is.

### Branches

Use `kebab-case` to name your branches: `prefix/branch-name-something`

**Branch naming convention**

- `fix`: When fixing an issue: `fix/some-bug`
- `chore`: When doing some cleanup, working on tooling, some refactoring: `chore/code-refactoring`
- `docs`: When writing documentation: `doc/documentation-subject`
- `feat`: When you are working on a feature. Start by creating a `feat/name-of-feature` branch & create tasks branches with the feature name as prefix:
