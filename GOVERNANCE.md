# Ayo.js Project Governance

The Ayo.js project is governed by its Members, a group of committees that handle
top-level matters such as technical direction and community management, and on
occasion a group of temporary Elected Final Arbiters (EFA) which have the
responsibility of holding a decisive vote in situations where no consensus can
be reached.

## Members

The [ayo](https://github.com/ayo) GitHub organization is
maintained by Members who are added by the committees on an ongoing basis.

Individuals identified as making significant and valuable
contributions of any kind across any Ayo.js repository may be made Members and
given commit access to the relevant project, as well as invited into the
GitHub organization. Activities taken into consideration include
(but are not limited to) the quality of:

* code commits and pull requests
* documentation commits and pull requests
* comments on issues and pull requests
* contributions to the Ayo.js website
* assistance provided to end users and novice contributors
* participation in Working Groups
* other participation in the wider Ayo.js community

If individuals making valuable contributions do not believe they have been
considered for commit access, they may log an issue or contact a committee
directly.

Modifications of the contents of the ayojs/ayo repository are made on
a collaborative basis. Anybody with a GitHub account may propose a
modification via pull request and it will be considered by the project
Members. All pull requests must be reviewed and accepted by a
Member with sufficient expertise who is able to take full
responsibility for the change. In the case of pull requests proposed
by an existing Member, an additional Member is required
for sign-off.

If one or more Members oppose a proposed change, then the change can not
be accepted unless:

* Discussions and/or additional changes result in no Members objecting to
  the change. Previously-objecting Members do not necessarily have to
  sign-off on the change, but they should not be opposed to it.
* The change is escalated to the Technical Committee and the Technical
  Committee votes to approve the change.
  This should only happen if disagreements between Members cannot be
  resolved through discussion.

Members may opt to elevate significant or controversial modifications to
the Technical Committee by assigning the `tc-review` label to a pull request or
issue. The Technical Committee should serve as the final arbiter where required.

* [Current list of Members](./README.md#current-project-team-members)
* [A guide for Members](./COLLABORATOR_GUIDE.md)

### Member Activities

Typical activities of a Member include:

* helping users and novice contributors
* contributing code and documentation changes that improve the project
* reviewing and commenting on issues and pull requests
* participation in adjacent projects
* merging pull requests

Past Members are typically given _Emeritus_ status. Emeriti
may request that they be restored to active status.

## Committees

The Ayo.js project has multiple top-level committees that are responsible for
managing a part of the project. These committees and their responsibilities are:

* Technical Committee (technical governance, the Ayo.js codebase)
* Community Committee (community management, inclusivity, conduct and
  enforcement)
* Infrastructure Committee (website, test servers, github account, other
  resources concerning project operation)

All committees should have at least 3 members at any time.

The respective charters for the committees and their elections are documented in
the [ayojs/charter][] repository.

## Elected Final Arbiters

Elected Final Arbiters (EFA) are Members of the Ayo.js project that serve to
resolve issues where there is no consensus. They are elected on a per-issue
basis.

There should always be multiple EFAs, a recommended number is 3-5.

EFAs have the authority to establish a decisive vote on issues where no
consensus can be reached by the Project or the committees. They do not place
above the committees in the hierarchy, for they are Members. A EFA should not be
a member of any committee, such as not to take sides.

## Consensus Seeking Process

The committees and EFAs follow a [Consensus Seeking][] decision making model.

[Consensus Seeking]: http://en.wikipedia.org/wiki/Consensus-seeking_decision-making
[ayojs/charter]: https://github.com/ayojs/charter
