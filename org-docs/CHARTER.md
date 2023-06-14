# Charter for the TPM-RS Organization

This is the organizational charter for the TPM-RS GitHub Organization (the
"Organization"). By adding their name to the
[Steering Committee.md file](./STEERING-COMMITTEE.md), Steering Committee members
agree as follows.

## 1. Sponsorship

"Sponsorship" in the context of this Organization means providing any resources
to the Organization directly (such as GitHub resources), or to individual
Members or contributors (such as employment).  The intent of this Organization
is to function as an Open Source Community including contributions and providing
benefits to the community at large, beyond companies and other organizations
providing resources to the Organization as Sponsors.

## 2. Mission

The TPM-RS GitHub Organization exists to organize and manage a set of related,
Open-Source projects sponsored by the Trusted Computing Group (TCG) and created
by TCG Promoter & Contributor Members

The Mission of the TPM-RS GitHub Organization is to support the development of
TPM-related firmware and tools primarily using the Rust language.  This
preference for the Rust langauge is based on its memory-safety properties, but
our Mission does not preclude the use of other languages for any use the
Steering Committee or project Maintainers may from time-to-time approve.

## 3. Roles.

This Organization may include the following roles. Additional roles may be
adopted and documented by individual Projects as described in Project Governance
below.

**1.1. Steering Committee Members** The Steering Committee Members are
responsible for all technical oversight, project approval and oversight, policy
oversight, and trademark management for the Organization.

**1.2. Maintainers**. Maintainers are responsible for organizing activities
around developing, maintaining, and updating individual Projects. Maintainers
are also responsible for determining consensus on Project actions, such as
approving Pull Requests.

**1.3. Contributors**. Contributors are those that have made accepted
contributions to the Organization or any Project.

## 3. Steering Committee

**3.1 Purpose**. The Steering Committee will be responsible for all technical
oversight, project approval and oversight, policy oversight, and trademark
management for the Organization.  Sponsoring companies may influence the
direction of the Organization through the Steering Committee as described below,
but the Steering Committee is not limited to Sponsored individuals and entities.
Non-sponsored Community contributors may be included in the Steering Committee
from time to time at the Steering Committee's discretion as described below.

**3.2 Composition**. The Steering Committee voting members are listed in the
steering-committee.md file in the repository. Voting members may be added or
removed by no less than 3/4 affirmative vote of the Steering Committee. The
Steering Committee will appoint a Chair responsible for organizing Steering
Committee activity.

Steering Committee members are individuals, but may be "Sponsored" by one or
more corporate entities that are Members of the Trusted Computing Group at
either the Associate, Contributor, or Promoter level. Steering Committee members
are not required to be sponsored by any particular entity outside of their
individual capacity.

## 4. Voting

**4.1. Decision Making**. The Steering Committee will strive for all decisions
to be made by consensus. While explicit agreement of the entire Steering
Committee is preferred, it is not required for consensus. Rather, the Steering
Committee will determine consensus based on their good faith consideration of a
number of factors, including the dominant view of the Steering Committee and
nature of support and objections. The Steering Committee will document evidence
of consensus in accordance with these requirements. If consensus cannot be
reached, the Steering Committee will make the decision by a vote.

**4.2. Voting**. The Steering Committee Chair will call a vote with reasonable
notice to the Steering Committee, setting out a discussion period and a separate
voting period. Any discussion may be conducted in person or electronically by
text, voice, or video. The discussion will be open to the public. In any vote,
each voting representative will have one vote. Except as specifically noted
elsewhere in this Charter, decisions by vote require a simple majority vote of
all voting members.

## 5. Termination of Membership

In addition to the method set out in section 3.2, the membership of a Steering
Committee member will terminate if any of the following occur:

**5.1 Resignation**. Written notice of resignation to the Steering Committee.

**5.2 Unreachable Member**. If a member is unresponsive at its listed handle for
more than three months the Steering Committee may vote to remove the member.

**5.3 Sponsor Revocation**. If a member was sponsored by a TCG Member company,
that Sponsoring company may remove or replace such Steering Committee member
without a vote with written notice to the Steering Committee.  A member so
removed or replaced (for example due to change in employment status) remains
eligible to be elected to the Steering Committee in an individual capacity as
provided in section 3.2

## 6. Trademarks

Any names, trademarks, service marks, logos, mascots, or similar indicators of
source or origin and the goodwill associated with them arising out of the
Organization's activities or Organization projects' activities (the "Marks"),
are controlled by the Organization. Steering Committee members may only use the
Marks in accordance with the Organization's [trademark policy](./TRADEMARKS.md).
If a Steering Committee member is terminated or removed from the Steering
Committee, any rights the Steering Committee member may have in the Marks revert
to the Organization.

Any names, trademarks, service marks, logos, mascots, or similar indicators of
goodwill (the "Sponsor Marks") associated with any entity Sponsoring the
Organization, any Steering Committee member, and/or any other contributor to any
project under the Organization's charter remain the property of such Sponsoring
entity.  No contributor or member of the Organization may use Sponsor Marks
without explicit, separate permission from such entity.  The only exception to
this rule is using the name of the sponsoring entity in the
[Steering Committee.md file](./STEERING-COMMITTEE.md) to designate Steering Committee
members who are "Sponsored" and thus subject to revocation as described in
Section 5.3 Sponsor Revocation above."

## 7. Antitrust Policy

The Steering Committee is bound by the Organization's
[antitrust policy](./ANTITRUST.md).

## 8. No Confidentiality

Information disclosed in connection with any of the Organization's activities,
including but not limited to meetings, Contributions, and submissions, is not
confidential, regardless of any markings or statements to the contrary.

## 9. Project Criteria

In order to be eligible to be a Organization project, a project must:

* Be approved by the Steering Committee.
* Agree to follow the guidance and direction of the Steering Committee.
* Use only the following outbound licenses or agreements unless otherwise approved:
  - For code, the [Apache-2.0 license](https://opensource.org/license/apache-2-0/).
  - For data, a license on the Open Knowledge Foundation's list of
    [Recommended Conformant Licenses](http://opendefinition.org/licenses/).
  - For specifications, subject to limits described below, a community developed
    and maintained specification agreement, such the
    [Open Web Foundation Agreements](https://www.openwebfoundation.org/the-agreements)
    or [Community Specification Agreement](https://github.com/CommunitySpecification/1.0).
* Include and adhere to the Organization's "Core Policies".
* The Core Policies are: this TPM-RS Charter,
  the [trademark policy](./TRADEMARKS.md),
  the [antitrust policy](./ANTITRUST.md), and
  the [code of conduct](./CODE-OF-CONDUCT.md) and
  the [contributor license agreement](./CONTRIBUTOR-LICENSE-AGREEMENT.md)
* Not be for the purpose of creating industry-wide specifications.

**9.1 Limitations on Specification Work** The Organization exists primarily to
implement code according to existing public specifications; creating new
specifications is more properly a function of one or more Sponsors of the
Origanization.  No Project in this organization will attempt to create or
make any Specifications that would, or might seem to, modify, augment, replace,
or compete against Specifications created or maintained by any Sponsor.  For
illustration, and without restricting the generality of the forgoing, any
Specifications created in one or more Projects must only address details
specific to the implementation of one or more Projects within this Organization.
For example, a specification regarding how two Projects communicate, (such as
for testing), would be allowed, but producing a generic network protocol
specification that might become an industry standard would be out of scope for
any Project in the Organization.

## 10. Project Governance

Individual Projects will have their own GOVERNANCE.MD document that describes
how that particular project will work.  In order to promote consistency, it is
expected that most projects will reference and use the
[Default Project Governance Policy](./DEFAULT-PROJECT-GOVERNANCE.md).
However, a project may adopt custom rules subject to the approval of the
Steering Committee provided that all projects MUST comply with the "Core
Policies" listed above at all times.

## 11. Contributor License Agreement

Notwithstanding anything else in the Charter and Project Governance documents,
all Steering Committee Members, Maintainers, and Contributors must agree to the
Contributor License Agreement associated with any project they participate in.

## 12. Not Subject To Sponsor Licenses

It is intended that nothing in this Organization or this Organization's projects
are subject to the licensing agreements of Sponsoring entities.  In particular,
each Steering Committee Member and Maintainer agrees not to submit content
subject to license agreements not listed in this charter, including but not
limited to the licensing agreements between Trusted Computing Group members as
outlined in the TCG Bylaws. Any contributor should consult with their
appropriate legal advisor, as appropriate, before making any contribution.

## 13. Sponsorship Review

In consideration of the resources provided to the Organization from any active
Sponsor(s), the Steering Committee shall, at least annually, provide a written
review of the Organizations' status and progress to such active Sponsors.  Such
review may be provided in any form the Steering Committee may from time to time
determine, such as by posting a review summary in the Organization's GitHub
Wiki, or submitting documents to a Project repo.  Sponsorship Review documents
are NOT confidential, in accordance with the No Confidentiality clause of this
charter.

## 14. Amendments

Amendments to this charter, the [antitrust policy](./ANTITRUST.md), the
[trademark policy](./TRADEMARKS.md), or the
[code of conduct](./CODE-OF-CONDUCT.md) may only be made with at least a 3/4
affirmative vote of the Steering Committee.

# Attribution

This document adapted from MVG-0.1-beta from GitHub.
See [Attribution and Acknowledgements](../org-docs/ACKNOWLEDGEMENTS.md)
Licensed under the [CC-BY 4.0 License](https://creativecommons.org/licenses/by-sa/4.0/).
