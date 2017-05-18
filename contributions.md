# Contribution Guide

- [Bug Reports](#bug-reports)
- [Core Development Discussion](#core-development-discussion)
- [Which Branch?](#which-branch)
- [Pull Request Guideline](#pull-request-guideline)

<a name="bug-reports"></a>
## Bug Reports

To encourage active collaboration, we strongly encourages pull requests, not just bug reports.

However, if you file a bug report, your issue should contain a title and a clear description of the issue. You should also include as much relevant information as possible and a code sample that demonstrates the issue. The goal of a bug report is to make it easy for yourself - and others - to replicate the bug and develop a fix.

Remember, bug reports are created in the hope that others with the same problem will be able to collaborate with you on solving it. Do not expect that the bug report will automatically see any activity or that others will jump to fix it. Creating a bug report serves to help yourself and others start on the path of fixing the problem.

The developersnepal source code is managed on Github.

<a name="core-development-discussion"></a>
## Core Development Discussion

You may propose changes to the Developers Nepal Internals [slack #request channel](https://developersnepal.slack.com).

Informal discussion regarding bugs, new additions, and tweaking of existing parts takes place in the `#general` channel of the [DevelopersNepal](https://developersnepal.slack.com) Slack team. People are generally there and someone will response on it.

<a name="which-branch"></a>
## Which Branch?
**All** features should always be sent to the `gh-pages` branch, which contains latest stable codes.
**Bug-fixes** should be sent to the `gh-pages` branch.
If you are unsure if your changes qualifies as a major or minor, discuss it in [DevelopersNepal](https://developersnepal.slack.com) `#general` channel.

<a name="pull-request-guideline"></a>
## Pull Request Guideline

Always send PR based on the tweaks/additions, issues you are working on. If it's new changes then send it against `gh-pages` branch.

1. Label your PR as `ready-for-review` and choose reviewers. These reviewers may not be immediately available to review the PR. Usually PR is reviewed in 1-2 hours however it may also take 2-3 days based on the availability of the contributors.
2. Once PR has been discussed, it will be labeled as `review passed` which means it can be merged to `gh-pages` branch and will go live.
3. In case something needs to be fixed in the PR before it can be merged, it will be labeled as `waiting for updates`.
4. Once PR comments are addressed, it should be labeled as `updated` so PR reviewer gets notified about it and will review the PR again.
5. step 3-4 can repeat multiple throughout PR lifecycle. Once reviewer is convinced, PR will be labeled as `review passed` and will be merged to `gh-pages` branch. Merge will be done as `squash and merge`.

#### PR Lifecycle State Diagram
![PR Lifecycle state diagram](https://cloud.githubusercontent.com/assets/760855/26187654/c526ce5c-3bc4-11e7-9318-50824eb2e759.png)



