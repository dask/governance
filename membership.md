Membership and Commit Rights
============================

This document covers processes to be granted membership in the Dask
GitHub organization and commit rights to Dask repositories.


Owners
------

The [Steering Council](./governance.md#steering-council) members have ownership
privileges over the entire GitHub organization.  As a result, they have commit
rights to all repositories and are involved in creating and removing members.
These individuals are listed at https://github.com/orgs/dask/people.

We ask that owners ensure that their membership is public.

Members
-------

New members can be made by any owner if the following criteria are met:

1.  At least two steering council members from separate employers agree membership
    is a good idea.
2.  The new member has supported the project several times, either through code
    or otherwise, and has demonstrated a willingness to help solve other
    people's problems, not just their own.
3.  The new member demonstrates some degree of familiarity of open source
    practices and online courtesy.

Write privileges
----------------

Individuals can be given write privileges to any repository by an owner by the
above conditions and the following:

1.  The maintainer(s) of that repository thinks it's a good idea
2.  The member has demonstrated technical familiarity with git and GitHub (and
    so, for example, is unlikely to accidentally mess with history or merge PRs
    in an unclean state)
3.  The member has demonstrated a commitment to resolving other peoples' problems
    and not just their own problems or the problems of their organization.

In the case of the more critical repositories (dask/dask, dask/distributed)
then at least three steering council members should agree to give privileges.

Teams
-----

We acknowledge that write permissions to individual projects may be better handled by teams.  Team membership will be handled similar to write permissions.


Removing write privileges
-------------------------

Non-steering Council members permissions can be removed in a two-step process:

1.  After a year of inactivity they are sent a private message noting that they
    have been inactive and asking if they'd still like to maintain their
    permissions.  No further activity after a suitable time (two weeks) will
    default in removal of permissions.
2.  After two years of inactivity their permissions are removed regardless.

We intentionally call out that "activity" can mean a great many things
including but not limited to writing code, documenting, being active on issues,
supporting users, etc..  Activity should be more than token events to maintain
permissions.

Any steering council member may temporarily remove permissions of any non-owner
if there is some pressing reason to do so, such as insecure credentials.
A consensus of steering council members can remove permissions of anyone long-term.
We ask that a majority of steering council members respond for quorum, and that those
votes come from people employed/associated with more than one institution.


Exception Handling
------------------

All decisions here are subject to the Steering Council and BDFL as discussed in
the governance document.  This document is meant to be a guideline, and is not
binding in the same way that the governance document is.  In any case where the
two documents should differ, the governance document shall take precedence.


History
-------

Conversation around this proposal originally occurred in
[dask/dask #3223](https://github.com/dask/dask/issues/3223).
