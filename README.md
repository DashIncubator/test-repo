# Purpose of `test-repo`

This repository was created for testing purposes related to https://trello.com/c/m8w82CvE/184-incubator-on-github.  We will likely keep this repo and the accompanying [test project](https://github.com/orgs/DashIncubator/projects/1/views/1) for ongoing testing.

### Projects

Our [DashIncubator organization](https://github.com/DashIncubator) here on GitHub has access to the new [GitHub Projects (beta)](https://github.com/features/issues/) feature.  The Incubator is most likely moving its project managment entirely from Trello to GitHub.

I've created a test project for us to play around with.  In Projects you can configure multiple views of the same underlying data.  Here are two main views as examples:

* [Spreadsheet view](https://github.com/orgs/DashIncubator/projects/1/views/1)
* [Kanban view](https://github.com/orgs/DashIncubator/projects/1/views/6)

### Issues

In Dash Incubator we work on tasks (individual units of work with accompanying Dash rewards) and bounties (collections of tasks, categorized as concept tasks, specification tasks, producution tasks, and QA tasks).  My initial thought is that we can represent both tasks and bounties as GitHub issess, with bounties being issues that track other issues.  An issue can "track" other issues by creating a checklist in the original issue description that references other issues.  This is recognized by GitHub by creating a two way link between tracking and tracking issues.  See [Issue 1](https://github.com/DashIncubator/test-repo/issues/1) for an example of an issue (a Bounty in Incubator terms) that tracks other issues (tasks in both Incubator and GitHub terms).

### Original Concept

The idea to move our project management from Trello to GitHub was originally documented on [our Trello board](https://trello.com/c/6XAuy9DW/94-request-new-concept#comment-614ce5673031a4043ef3d479).  The following is a copy of the content, for easier reference.

##### Title

Incubator on GitHub

##### Value Proposition

Bounty management, discussions, on-boarding/training, document storage, and other Incubator work and workflows on the industry-leading platform for developers, co-located with our Incubator-funded public repos.

##### Functional Requirements

Currently we are using Trello for bounty management. We have done work towards a custom app to replace Trello, but it may be best to postpone that and have it focus on what GitHub can't do (Dash payments, for example).

GitHub has most of the features we need for effective bounty management with its new [projects (beta) features](https://github.com/features/issues/). This has most (if not all) of the features we use from Trello, with the added benefits of spreadsheet views and being natively integrated with code repositories. Incubator contributors would only need a GitHub account (rather than both GitHub and Trello accounts).

Some examples of things we could move to (or start doing in) GitHub:
1. Bounty management (as discussed above)
2. [Forms and templates](https://github.blog/changelog/2021-06-23-issues-forms-beta-for-public-repositories/) (Incubator signup, new concepts, spec, QA, etc)
3. Tie most bounty tasks clams to pull requests (PRs)
4. Tie QA process to code reviews and PR merges
5. Simplify/automate task claims process/documentation
6. On-board and train new members and admins using labs
7. Bounty and Incubator discussions using GitHub discussions
8. General automation using GitHub actions
9. A formal process whereby code moves from personal accounts to the /dashincubator org, and then later to its own org if/when it graduates from being Incubator funded
10. Site hosting, code collaboration, CI/CD, and many other GitHub features

In addition to the benefits this migration would have for Incubator admin, this would also get us closer to non-Incubator developers. Some devs interested in Incubator may not have (or want) Trello accounts. Establishing a GitHub-oriented workflow would also open the door to generalizing the 'pay DASH for commits/PRs' process so orgs and projects not related to Incubator could potentially adopt the same compensation model.

Migrating processes to GitHub would require further specification (along with QA) just like any other bounty.

##### Supporting Links

[GitHub Issues/Projects](https://github.com/features/issues/)
[GitHub Actions](https://github.com/features/actions)
[GitHub Discussions](https://docs.github.com/en/discussions)
[Incubator Projects](https://github.com/orgs/dashincubator/projects?type=beta)
[GitHub Learning Lab](https://lab.github.com/docs)
[Projects Announcement](https://www.youtube.com/watch?v=64xO030aneI)
[Projects Demo 1](https://www.youtube.com/watch?v=SI1ra-XHWHM)
[Projects Demo 2](https://www.youtube.com/watch?v=lLGzd36x3Ho&t=2539s)
[First suggestion to move to GitHub](https://discord.com/channels/670271785974890526/670271785974890529/677921124616634379)

##### Additional Info (optional)

There are of course risks to moving so much of our process to GitHub, but I think the benefits outweigh the costs. We should discuss these in the #dash-incubator channel of the Dash Devs Discord.
