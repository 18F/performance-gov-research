# Performance.gov Team practices

This document describes the conventions the Performance.gov team has agreed to work under.
For information about licensing, code of conduct and contributing to this project,
see the [CONTRIBUTING](CONTRIBUTING.md) file.


## Sprints

We do two-week sprints, with a weekly Wednesday sprint progress check-in with
our partner and a sprint retro every other Tuesday. We have daily Slack standups
with our 18F team.


## Calendar

We use a [team
calendar](https://calendar.google.com/calendar?cid=Z3NhLmdvdl91bmZrNXBtOWRiNjVyc2gwOWd1cGUydWU0MEBncm91cC5jYWxlbmRhci5nb29nbGUuY29t)
to track project related meetings, deadlines, and events. Folks should feel free
to attend any meeting on the calendar even if you were not explicitly invited.
Please add any upcoming Out of Office time to the calendar.

**Tip:** create the calendar event on the performance.gov calendar and add
yourself as a guest. Other members can see the event and add themselves if they
wish.


## Issues

We use Github
+ [Zenhub](https://chrome.google.com/webstore/detail/zenhub-for-github/ogcgkffhplmphkaahpmffcafajaocjbd)
for [issue tracking](https://app.zenhub.com/workspace/o/18f/performance.gov/boards?repos=106470255).

We create issues as necessary to capture stories and articulate requirements for
specific tasks. Kanban tasks move through the columns from left to right. Our
kanban columns for describing the state of issues are:


### Icebox

Default for created issues.

The Icebox is where items go that have lower priority or we are unsure of their
state. This tends to be a collection of things we'd like to do but there are
many other things with higher priority.


#### Exit criteria

- When reviewing priorities, we may pull items out of the Icebox.
- Items move to Backlog for grooming.


### Backlog

Items ready to be groomed and prioritized in preparation to be pulled into the
In Progress column for the current/upcoming sprint.


#### Exit criteria

- Item has defined acceptance criteria reviewed by the Product Owner.
- Item is groomed and shovel-ready.
- Item has been prioritized against other work in the Backlog.
- When a team member is ready to take on new work, they pull the first
  unassigned item from the top of the Backlog.


### In progress

The work has been started. Limit 2 per assignee.


#### Exit criteria

- Acceptance criteria has been met.
- Any artifacts, documents, assets, or code is included in the issue or a PR and
  available for the team.


### Review/Validate

PR opened and/or task ready for team feedback.


#### Exit criteria

- Work has been peer reviewed and acceptance criteria is confirmed to have been
  met.
- Any validation or usability testing has been performed.
- Any follow-on work such as new hypotheses or next steps have been created as
  new issues.


### Closed

Issue completed and validated.


## Pull Requests

All code changes should happen through pull requests (PRs) to the `master`
branch.

New PRs should be assigned to the person who opens the PR.
If a PR is not ready for review and merge, add the `WIP` label to it,
and prefix the PR name with `[WIP]`.

All PRs should be reviewed by one other team member.
As a reviewer, you are not expected to review `WIP` PRs unless specifically requested.
Prioritize PR reviews over other work, so that PRs do not block other team members.

When a PR has an accepted review, either the reviewer or the owner (assignee)
may merge the PR.
