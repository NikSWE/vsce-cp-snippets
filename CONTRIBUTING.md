# Contributing Guidelines

## Found an Issue?

If you find a bug in the source code or a mistake in the documentation, you can help us by submitting an issue [here][issues]. Even better, you can submit a PR with a fix.

Before you submit an issue, search the archive, maybe your question was already answered.

If your issue appears to be a bug, and hasn't been reported, open a new issue. Help us to maximize the effort we can spend fixing issues and adding new features, by not reporting duplicate issues. Providing the following information will increase the chances of your issue being dealt with quickly:

- **Overview of the Issue** - if an error is being thrown a non-minified stack trace helps
  - **Version** - what version is affected (e.g. 0.1.2)
    - **Motivation for or Use Case** - explain what are you trying to do and why the current behavior is a bug for you
- **Reproduce the Error** - provide a live example or a unambiguous set of steps
  - **Related Issues** - has a similar issue been reported before?
- **Suggest a Fix** - if you can't fix the bug yourself, perhaps you can point to what might be
  causing the problem (line of code or commit)

## Want a Feature?

You can _request_ a new feature by submitting an issue [here][issues]. If you would like to _implement_ a new feature, please submit an issue with a proposal for your work first, to be sure that we can use it.

### Submitting a Pull Request (PR)

Search [here][pulls] for an open or closed PR that relates to your submission. You don't want to duplicate effort.
Before you submit your Pull Request (PR) consider the following guidelines:

- Make your changes in a new git fork
- Commit your changes using a descriptive commit message
- Push to your GitHub fork
- In GitHub, send a pull request:

  - If we suggest changes then:

    - Make the required updates.
    - Rebase your fork and force push to your GitHub repository (this will update your Pull Request):

    ```shell
    git rebase master -i
    git push -f
    ```

That's it! Thank you for your contribution!

[issues]: https://github.com/muj-programmer/vsce-cp-snippets/issues
[pulls]: https://github.com/muj-programmer/vsce-cp-snippets/pulls
