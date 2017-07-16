# ci-sandbox
Simple Repo to test continuous integration with iOS and Android projects on different branches in the same repository.

This repo is to test using Travis-CI to build iOS and Android projects from a single repository with the following branch strategy.

Branch Strategy:

- ***master*** - holds production code across all projects.  A simple single branch to merge all underlying projects.
- ***ios*** - holds latest production iOS code in ios subfolder.
- ***android*** - holds latest production Android code in android subfolder.