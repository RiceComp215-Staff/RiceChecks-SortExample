# RiceChecks: "Sort" Example

This repo is a demonstration project for the [RiceChecks](https://github.com/RiceComp215-Staff/RiceChecks/) Java autograder.

In this hypothetical project, students are asked to implement three sorting algorithms;
their work is tested with [QuickTheories](https://github.com/quicktheories/QuickTheories),
generating hundreds of random inputs.

The initial state of this repository has all tests passing. Feel free
to introduce bugs to the student assignment and see how RiceChecks responds.

## Gitpod

Here's a link that will drop you into the Gitpod web-based IDE using
this codebase:
- https://gitpod.io/github.com/RiceComp215-Staff/RiceChecks-SortExample

(You can replace this URL with any public GitHub repository with
`gitpod.io` before the usual `github.com`.)

From the Gitpod terminal shell, run `./gradlew autograder`. 

## Make Your Own Copy

GitHub just announced [template repositories](https://github.blog/2019-06-06-generate-new-repositories-with-repository-templates), which seems like a generalization of GitHub Classroom,
except instead of clone links, you get a *Use this template* button. Go ahead and click it.

## Travis-CI / GitHub Actions

If you're a beta-tester for GitHub Actions, this repository is configured to run the
autograder as a GitHub Action on every push. A suitable Travis-CI configuration
is also included. You can see the results of the autograder by clicking the
"Commits" tab. Try introducing bugs, committing and pushing, to see how RiceChecks
responds.
