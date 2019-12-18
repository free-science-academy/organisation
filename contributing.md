---
title: "Contributing Guidelines"
author: "Jon Tennant"
date: "18 December 2019"
output:
  word_document: default
  html_document: default
  pdf_document: default
---

These are the main contributing guidelines for the development of this project. We primarily use GitHub for its massive power in version controlled project management.

Feedback and contributions of any form are welcomed. Feel free also to [contact us](mailto:wolass@gmail.com) to discuss anything further.

Right now you are ready to contribute. Our current tasks are grouped in Github projects as standard Kanban boards. If you are taking care of a task - move it to "currently doing" and assign it to yourself. Moving a card to "Done" column is addictively satisfying - [try it yourself! :)](https://github.com/free-science-academy/organisation/projects/1)

## Reporting issues

- **Search for existing issues.** Please check to see if someone else has reported the [same issue](https://github.com/free-science-academy/organisation/issues/).

- **Share as much information as possible.** Include operating system and version, browser and version. Also, include steps to reproduce the bug.

## Content style

This is flexible to each project as required.

## Code style

Flexible, as long as it is consistent. Ideally, all content would be drafted in markdown, for increasing re-use. This can be easily performed in R tudio, for example, which also has a GitHub interface to make collaborating on this project even simpler.

This video from the Open Science MOOC describes how to integrate [Git into RStudio](https://www.youtube.com/watch?v=Q-6jfjSAspA).

## Pull requests

In general, we follow the "fork-and-pull" Git workflow.

- Fork the repo on GitHub
- Clone the project to your own machine
- Commit changes to your own branch
- Push your work back up to your fork
- Submit a Pull request so that we can review your changes

NOTE: Be sure to merge the latest from "upstream" before making a pull request!

- Try not to pollute your pull request with unintended changes – keep them simple and small. If possible, squash your commits.
- Try to share how your code has been tested before submitting a pull request.
- If your PR resolves an issue, include **closes #ISSUE_NUMBER** in your commit message (or a [synonym](https://help.github.com/articles/closing-issues-via-commit-messages)).
- Review
    - If your PR is ready for review, another contributor will be assigned to review your PR
    - The reviewer will accept or comment on the PR.
    - If needed address the comments left by the reviewer. Once you're ready to continue the review, ping the reviewer in a comment.
    - Once accepted your code will be merged to `master`
