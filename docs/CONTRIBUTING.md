<!-- omit in toc -->
# Contributing to StevenJDH's Projects

A big welcome and thank you for considering contributing to StevenJDH's open source projects! It’s people like you that create the motivation behind these projects and for the users in our community.

Reading and following these guidelines will help us make the contribution process easy and effective for everyone involved. It also communicates that you agree to respect the time of the developers managing and developing these open source projects. In return, we will reciprocate that respect by addressing your issues, assessing changes, and helping you finalize your pull requests.

And if you like the project, but just don't have time to contribute, that's fine. There are other easy ways to support the project and show your appreciation, which we would also be very happy about:
* Star the project.
* Tweet about it.
* Refer this project in your project's README.
* Mention the project at local meetups and tell your friends/colleagues.

<!-- omit in toc -->
## Table of Contents

- [Code of Conduct](#code-of-conduct)
- [Getting Started](#getting-started)
  - [Issues](#issues)
  - [Enhancements](#enhancements)
  - [Pull Requests](#pull-requests)
  - [Reviews](#reviews)
- [Style Guides](#style-guides)
  - [Git Commit Messages](#git-commit-messages)
  - [.NET](#net)
  - [Java](#java)
- [Recognition Model](#recognition-model)
- [Getting Help](#getting-help)

## Code of Conduct

We take our open source community seriously and hold ourselves and other contributors to high standards of communication. By participating and contributing to this project, you agree to uphold our [Code of Conduct](https://github.com/StevenJDH/.github/blob/main/docs/CODE_OF_CONDUCT.md).

## Getting Started

Contributions that are made to StevenJDH repositories via Issues and Pull Requests (PRs) must follow a few general guidelines that cover both:

* Search for existing Issues and PRs before creating your own.
* We work hard to makes sure issues are handled in a timely manner, but depending on the impact, it could take a while to investigate the root cause. A friendly ping in the comment thread to the submitter or a contributor can help draw attention if your issue is blocking.
* If you've never contributed before, labels like `help wanted` or `good first issue` can help you get started.

### Issues

Issues should be used to report problems with a library, to request a new feature, or to discuss potential changes before a PR is created. When you create a new Issue, a template will be loaded that will guide you through collecting and providing the information we need to investigate.

If you find an Issue that addresses the problem you're having, please add your own reproduction information to the existing issue rather than creating a new one. Adding a [reaction](https://github.blog/2016-03-10-add-reactions-to-pull-requests-issues-and-comments/) can also help to be an indicator to our maintainers that a particular problem is affecting more than just the reporter.

### Enhancements

 Enhancements include completely new features and minor improvements to existing functionality. To submit a good enhancement suggestion, begin by including the following:
 * A clear and descriptive title for the issue to identify the suggestion.
 * A step-by-step description of the suggested enhancement in as many details as possible.
 * A description of the current behavior, and explain which behavior you expected to see instead and why.
 * Screenshots and animated GIFs that help you demonstrate the steps.
 * An explanation as to why this enhancement would be useful.

### Pull Requests

PRs to our repositories are always welcome and can be a quick way to get your fix or improvement slated for the next release. In general, PRs should:

* Only fix/add the functionality in question **OR** address wide-spread whitespace/style issues, but not both.
* Add unit or integration tests for fixed or changed functionality (if a test suite already exists).
* Address a single concern in the least number of changed lines as possible.
* Include any documentation changes associated with the fix or change in the repo.
* Be accompanied by a complete Pull Request template (loaded automatically when a PR is created).
* Meet all legal criteria such as the content being 100% authored by the contributor and may be provided under the project license.

For changes that address core functionality or would require breaking changes (e.g. a major release), it's best to open an Issue to discuss your proposal first. This is not required but can save time creating and reviewing changes.

In general, we follow the ["fork-and-pull" Git workflow](https://github.com/susam/gitpr)

1. Fork the repository to your own GitHub account.
2. Clone the project to your machine.
3. Create a local branch off the `develop` branch if present with a short but descriptive name.
4. Commit changes to the branch.
5. Following any formatting and testing guidelines specific to the repo.
6. Push changes to your fork.
7. Open a PR in our repository, and follow the PR template so that we can efficiently review the changes.

### Reviews

Reviews help make content better by discussing improvements and making the necessary changes before merging the contribution. To achieve this goal, please observe following:

> * Reviews are always respectful, acknowledging that everyone did the best possible job with the knowledge they had at the time.
> * Reviews discuss content, not the person who created it.
> * Reviews are constructive and start conversation around feedback.

[source: [GitHub](https://github.com/github/docs/blob/main/CONTRIBUTING.md)]

## Style Guides

Please follow the style guides listed below, and for anything not listed, assume the default style guidelines for that particular platform.

### Git Commit Messages

* Use the past tense ("Added feature" not "Add feature").
* Limit the length to 50 characters or less if possible, but no more than 72 characters.
* Add references to Issues and Pull Requests if present.
* Write in the imperative mood ("Make a git commit..." not "Makes a git commit...").

### .NET

* Variables marked as `const` should be in all uppercase with underscores for spaces like in the Java code style guidelines.
* Avoid using `var` for value types and strings.
* Follow David Fowler's [Async Guidance](https://github.com/davidfowl/AspNetCoreDiagnosticScenarios/blob/master/AsyncGuidance.md).
* When choosing a variable's name, ensure that its type can be inferred by its name when possible.
* Always opt to use curly bracket when they are optional.

### Java

* Follow the [Java Coding Style Guidelines](https://www.cs.cornell.edu/courses/JavaAndDS/JavaStyle.html).

## Recognition Model

As a contributor, your GitHub username will be added to the changelog of the next release unless you explicitly state otherwise to opt out.

## Getting Help

Of the many channels available to leverage the open source community to get support, one of the best places is [Stack Overflow](https://stackoverflow.com/questions/). Benefits here include:

* Thousands of people willing to help from the Stack Overflow community.
* Questions and answers stay available for public viewing so your question and or answer might help someone else.
* A voting system to assure that the best answers are prominently visible.