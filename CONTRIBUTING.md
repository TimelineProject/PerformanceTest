First of all, thank you for taking the time to contribute! 

### Code of Conduct

See [Code of Conduct](CODE_OF_CONDUCT.md) for details.

### How to Contribute

#### Discuss

Questions will be accepted and reviewed by StackOverflow. 
Find an existing discussion or start a new one if necessary.

If you suspect an issue, perform a search in the [Github issue tracker](https://github.com/TimelineProject/PerformanceTest/issues), using a few different keywords.
When you find related issues and discussions, prior or current, it helps you to learn and it helps us to make a decision.

#### Create a Ticket

Reporting an issue or making a feature request is a great way to contribute. Your feedback
and the conversations that result from it provide a continuous flow of ideas. 

Before you create a ticket, please take the time to [research first](#discuss).

If creating a ticket after a discussion on StackOverflow, please provide a self-sufficient description in the ticket, independent of the details on StackOverview. We understand this is extra work but the issue tracker is an important place of record for design discussions and decisions that can often be referenced long after the fix version, for example to revisit decisions, to understand the origin of a feature, and so on.

When ready create a ticket in the [Github issue tracker](https://github.com/TimelineProject/PerformanceTest/issues).

#### Submit a Pull Request

You can contribute a source code change by submitting a pull request.

1. If you have not previously done so, please sign the [Contributor License Agreement](https://cla.pivotal.io/sign/spring). You will also be reminded automatically when you submit a pull request.

1. For all but the most trivial of contributions, please [create a ticket](#create-a-ticket). The purpose of the ticket is to understand and discuss the underlying issue or feature. We use the GitHub issue tracker as the preferred place of record for conversations and
conclusions. In that sense discussions directly under a PR are more implementation detail oriented and transient in nature.

1. Always check out the `master` branch and submit pull requests against it (for target version see [settings.gradle](settings.gradle)).
Backports to prior versions will be considered on a case-by-case basis and reflected as the fix version in the issue tracker.

1. Use short branch names, preferably based on the GitHub issue (e.g. `22276`), or otherwise using succinct, lower-case, dash (-) delimited names, such as `fix-warnings`.

1. Choose the granularity of your commits consciously and squash commits that represent multiple edits or corrections of the same logical change. See [Rewriting History section of Pro Git](http://git-scm.com/book/en/Git-Tools-Rewriting-History)
for an overview of streamlining commit history.

1. Format commit messages using 55 characters for the subject line, 72 lines for the description, followed by the issue fixed, e.g. `Fixes #22276`. See the [Commit Guidelines section of Pro Git](http://git-scm.com/book/en/Distributed-Git-Contributing-to-a-Project#Commit-Guidelines) for best practices around commit messages and use `git log` to see some examples.

1. List the GitHub issue number in the PR description.

If accepted, your contribution may be heavily modified as needed prior to merging.
You will likely retain author attribution for your Git commits granted that the bulk of your changes remain intact. You may also be asked to rework the submission.

If asked to make corrections, simply push the changes against the same branch, and your pull request will be updated. In other words, you do not need to create a new pull request when asked to make changes.

### References

Templates are revised from [Spring Contributor](https://github.com/spring-projects/spring-framework/blob/master/CONTRIBUTING.md).
