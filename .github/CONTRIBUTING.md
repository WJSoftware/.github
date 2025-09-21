# Contributing

The philosophy behind all software in the **WJ Software** organization is to be highly focused and non-trivial.  You won't find a repository of the likes of `is-even` here.

Contributions are very welcome, but they must satisfy certain requirements.

## Contributing Documentation

Contributing documentation is much more straightforward.  Feel free to contribute pull requests to correct typos or grammar, or to add more detailed examples or clarifications.  The better the documents, the better experience for everyone.

### Documentation for Artificial Intelligence (AI)

Additions to the root `AGENTS.md` file are welcome, but only in English.  Contents should be well structured using proper Markdown title hierarchy, and it should be kept simple.  Preferably, very short paragraphs, lots of bullet and numbered lists, and lots of code samples.

## Contributing Code

This is a bit more limited.  Usually, the contribution should match at least one of the following categories:

1. Developer experience improvement
2. Bug fix of current functionality
3. New feature

Developer experience is very important for the owner of this repository.  If something is difficult to use, it is probably not worth using it.  Improvements in API, or in the case of TypeScript projects, in TypeScript typing for better Intellisense are very welcome.

For the other two, please follow this checklist in order before opening a pull request:

[ ] An issue has already been open and discussed
[ ] The issue has been acknowledged as a bug or new feature request

It has happened in the past:

- Guy123: "Hey, here's a pull request for you that adds Feature X."
- Me: "I don't understand this very well, please explain to me this Feature X.  What's the use case?"
- Guy123:  "It is for this and that."
- Me: "Bro, just do ABC.  No need for this."

So to save your time and effort, please be sure to **start with an issue**.

### Requisites

For a pull request to be accepted, it must:

1. Pass CI testing (tests are run automatically by Github Actions)
2. For bug fixing, must carry at least one new unit test that fails before the fix, and succeeds after the fix
3. For new features, must carry new unit tests that test the new functionality and (ideally) doesn't touch existing unit tests
4. The project's README, if applicable, has been updated

### Updating README

If the repository contains a README that is technical in nature, describing every feature (or a lot of them), and a new feature is being added, it is ideal of the new README's section describing it starts with a quote block that states its minimum version.  Example:

```markdown
## New Feature X

> Since **v2.5.0**

Blah blah blah.
```
