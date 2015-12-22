<!--
title: 06 - Sponsorship
featured: true
-->

# Sponsorship

## Sponsorship Types

![org-sponsorship levels](/images/org-sponsorships.png)

Let's say we have an Organization, `@ag_org`. This Organization
was created by user `@ag_dubs`, and therefore she is the Super 
Admin. Being a Super Admin, she adds 3 members to her team:

- Jacques Derrida
- Carl Sagan
- Emma Goldman

There are three types of Sponsorship that can occur:

- Paid by Current Organization
- Paid by Self or Another Organization
- Not Paid

- ### Paid by Current Organization

  When Super Admin, `@ag_dubs`, added `JacquesDerrida` to the Organization,
  `JacquesDerrida` did not already belong to an organization nor did he have a
  subscription to private packages.

  By default, when the Super Admin added him to the Organization, `JacquesDerrida`
  was set as a member of the Organization, **paid by the current organization**.

  As a result, `JacquesDerrida` can:
    - Be added to any/all of the Organization's teams
    - See the teams he is on
    - See the members of those teams
    - Collaborate on and publish any package that his team membership grants him
      access to

  `JacquesDerrida` cannot:
    - See all of the Organization's teams
    - See all members of the Organization

- ### Paid by Self or Another Organization

  - #### Paid for by Another Organization
  
    When Super Admin, `@ag_dubs`, added `CarlSagan` to the Organization, `CarlSagan`
    already belonged to another Organization, (`@nasa-org`, duh).

    By default, when `CarlSagan` was added to the Organization, he was set as a member
    of the Organization, **paid by another scope**. This appears in the UI like this:

    ![paid, but not by the org](images/sponsorship-grey.png)

    As a result, `CarlSagan` has the same permissions as `JacquesDerrida`, above.

  - #### Paid for by Self
  
    As a subscriber to Private Packages, you can understand yourself as "sponsoring
    yourself". As a result, a subscriber to private packages would have had the same
    default behavior as occured for `CarlSagan`, i.e., the previous sponsorship would
    trump the possibility of a new Organization sponsorship. A subscriber to private
    packages will appear in the Organization dashboard as someone who is `paid` but
    `not by the current org`. This appears in the UI the same as above:

    ![paid, but not by the org](images/sponsorship-grey.png)`

  - #### Changing Sponsorship

    If a user is a subscriber to private packages, this sponsorship scope will
    trump all other potential sponsorships. If you would like to change this, i.e.
    offer sponsorship to a user who already has another sponsorship (org or private pkgs),
    please contact [support@npmjs.com](mailto:support@npmjs.com). 

- ### Not Paid

  When Super Admin, `ag_dubs`, added `EmmaGoldman` to the Organization, `EmmaGoldman`
  did not subscirbe to private packages nor did she belong to another Organization.

  Like `JacquesDerrida`, `EmmaGoldman` was set as **paid by the current organization,
  `@ag-org`** by default. However, Super Admin, `@ag_dubs` opted to cancel `@ag-org`'s
  sponsorship of `EmmaGoldman`. This status appears in the UI like this:

  ![not paid](images/sponsorship-red.png)

  As a result, `EmmaGoldman` can:
    - Be added to any/all of the Organization's teams
    - See the teams she is on
    - See the members of those teams
    - Collaborate on and publish public, scoped or unscoped packages, that her team
      membership grants her access to

  `EmmaGoldman` cannot:
    - See all of the Organization's teams
    - See all members of the Organization
    - Collaborate on and publish any private packages, even if her team membership
      would otherwise grant her access
    
