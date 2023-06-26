# Charter for the TPM-RS Project

This is the organizational charter for the TPM-RS Project (the
"Project"). By adding their name to the
[Steering Committee List], Steering Committee members
agree as follows.

## 1. Sponsorship

"Sponsorship" in the context of this Project means providing any resources
to the Project directly (such as GitHub resources), or to individual
Members or contributors (such as employment).  The intent of this Project
is to function as an Open Source Community including contributions and providing
benefits to the community at large, beyond companies and other organizations
providing resources to the Project as Sponsors.

## 2. Mission

The TPM-RS Project exists to organize and manage a set of related,
Open-Source repositories ("Repos") sponsored by the Trusted Computing Group (TCG) and created
by TCG Promoter & Contributor Members

The Mission of the TPM-RS Project is to support the development of
TPM-related firmware and tools primarily using the Rust language.  This
preference for the Rust langauge is based on its memory-safety properties, but
our Mission does not preclude the use of other languages for any use the
Steering Committee or Repo Maintainers may from time-to-time approve.

## 3. Roles

This Project may include the following roles. Additional roles may be
adopted and documented by individual Repos as described in Repo Governance
below.

**1.1. Steering Committee Members** The Steering Committee Members are
responsible for all technical oversight, Repo approval and oversight, policy
oversight, and trademark management for the Project.

**1.2. Maintainers**. Maintainers are responsible for organizing activities
around developing, maintaining, and updating individual Repos. Maintainers
are also responsible for determining consensus on Repo actions, such as
approving Pull Requests.

**1.3. Contributors**. Contributors are those that have made accepted
contributions to the Project or any Repo.

**1.4. Participants**. Participants in the Project includes all Steering
Committee Members, Maintainers, Contributors and any individiual who agrees to
participate in the Project's activities subject to the Project and
Repo agreements as outlined in this charter.

## 3. Steering Committee

**3.1 Purpose**. The Steering Committee will be responsible for all technical
oversight, Repo approval and oversight, policy oversight, and trademark
management for the Project.  All Steering Committee members will be sponsored
by a sponsoring Trusted Computing Group (TCG) member company, or TCG itself.
Sponsoring companies may influence the direction of the Project through the
Steering Committee as described below.

**3.2 Composition**. The Steering Committee voting members are listed in the
[Steering Committee List] file in the repository. Voting members may be added or
removed by no less than 3/4 affirmative vote of the Steering Committee. The
Steering Committee will appoint a Chair responsible for organizing Steering
Committee activity.

Steering Committee members are individuals, but are "Sponsored" by either TCG
itself, or a member company of TCG at either the Associate, Contributor, or
Promoter level.

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
without a vote with written notice to the Steering Committee.  If the member
was sponsored by TCG itself, the TCG Board of Directors may provide this notice.
A member so removed or replaced (for example due to change in employment status)
remains eligible to be elected to the Steering Committee sponsored by another
entity.

**5.4 Effect of Termination**.  When a Sponsored Steering Committee member is
removed for any reason, their position on the Steering Committee becomes vacant
and may be filled by the Sponsoring entity by written notice to the Steering
Committee.  Such vacated seats are inactive and do not count towards any quorum
or majority requirements for any decisions made by the Steering Committee until
a successor is appointed.  A Sponsored seat may be permanently abandoned and be
removed by written notice from the Sponsoring entity to the Steering Committee.

## 6. Trademarks

Any names, trademarks, service marks, logos, mascots, or similar indicators of
source or origin and the goodwill associated with them arising out of the
Project's activities or Project Repos' activities (the "Marks"),
are controlled by the Project. Steering Committee members may only use the
Marks in accordance with the Project's [Trademark Policy].
If a Steering Committee member is terminated or removed from the Steering
Committee, any rights the Steering Committee member may have in the Marks revert
to the Project.

Any names, trademarks, service marks, logos, mascots, or similar indicators of
goodwill (the "Sponsor Marks") associated with any entity Sponsoring the
Project, any Steering Committee member, and/or any other contributor to any
Repo under the Project's charter remain the property of such Sponsoring
entity.  No contributor or participant of the Project may use Sponsor Marks
without explicit, separate permission from such entity.  The only exception to
this rule is using the name of the sponsoring entity in the
[Steering Committee List] to designate Steering Committee
memberss sponsorship, subject to Section 5.3 Sponsor Revocation above."

## 7. Antitrust Policy

The Steering Committee is bound by the Project's
[Antitrust Policy].

## 8. Confidentiality

Information publicly disclosed by the Project in connection with any of the
Project's activities, including but not limited to meetings, contributions,
and submissions, is not confidential, regardless of any markings or statements
to the contrary.

However, nothing in this section requires individual Participants to
document or record any particular proceedings or activity related to the
Project or any Repo for the purpose of later disclosure.

Participants specifically agree to hold [Security Reports] as
Confidential subject to the Coordinated Vulnerability Disclosure process described in
the [Security Policy].

## 9. Repo Criteria

In order to be eligible to be a Project repository, a Repo must:

* Be approved by the Steering Committee.
* Agree to follow the guidance and direction of the Steering Committee.
* Use only the following outbound licenses or agreements unless otherwise approved:
  * For code, the [Apache-2.0 license].
  * For data, a license on the Open Knowledge Foundation's list of
    [Recommended Conformant Licenses].
  * For specifications, subject to limits described below, a community developed
    and maintained specification agreement, such the
    [Open Web Foundation Agreements] or [Community Specification Agreement].
* Include and adhere to the Project's "Core Policies".
* The Core Policies are: this [TPM-RS Charter],
  the [Trademark Policy],
  the [Antitrust Policy],
  the [Code of Conduct],
  the [Security Policy], and
  the [Contributor License Agreement]
* Not be for the purpose of creating industry-wide specifications.

**9.1 Limitations on Specification Work** The Project exists primarily to
implement code according to existing public specifications; creating new
specifications is more properly a function of one or more Sponsors of the
Project.  No Repo in this Project will attempt to create or
make any Specifications that would, or might seem to, modify, augment, replace,
or compete against Specifications created or maintained by any Sponsor.  For
illustration, and without restricting the generality of the forgoing, any
Specifications created in one or more Repos must only address details
specific to the implementation of one or more Repos within this Project.
For example, a specification regarding how two Repos communicate, (such as
for testing), would be allowed, but producing a generic network protocol
specification that might become an industry standard would be out of scope for
any Repo in the Project.

## 10. Repo Governance

Individual Repos will have their own GOVERNANCE.MD document that describes
how that particular Repo will work.  In order to promote consistency, it is
expected that most Repos will reference and use the
[Default Repo Governance Policy].
However, a repository may adopt custom rules subject to the approval of the
Steering Committee provided that all Repos MUST comply with the "Core
Policies" listed above at all times.

## 11. Contributor License Agreement

Notwithstanding anything else in the Charter and Repo Governance documents,
all Steering Committee Members, Maintainers, and Contributors must agree to the
Contributor License Agreement associated with any Repo they participate in.

## 12. Not Subject To Sponsor Licenses

It is intended that nothing in this Project or this Project's Repos
are subject to the licensing agreements of Sponsoring entities.  In particular,
each Steering Committee Member and Maintainer agrees not to submit content
subject to license agreements not listed in this charter, including but not
limited to the licensing agreements between Trusted Computing Group members as
outlined in the TCG Bylaws. Any contributor should consult with their
appropriate legal advisor, as appropriate, before making any contribution.

## 13. Sponsorship Review

In consideration of the resources provided to the Project from any active
Sponsor(s), the Steering Committee shall, at least annually, provide a written
review of the Organizations' status and progress to such active Sponsors.  Such
review may be provided in any form the Steering Committee may from time to time
determine, such as by posting a review summary in the Project's GitHub
Wiki, or submitting documents to a Repo.  Sponsorship Review documents
are NOT confidential, in accordance with the Confidentiality clause of this
charter.

## 14. Amendments

Amendments to this [TPM-RS Charter], the [Antitrust Policy], the
[Trademark Policy], the [Code of Conduct],
the [Security Policy], and the [Contributor License Agreement]
may only be made with at least a 3/4
affirmative vote of the Steering Committee.

## Attribution

This document adapted from MVG-0.1-beta from GitHub.
See [Attribution and Acknowledgements]. Licensed under the [CC-BY 4.0 License].

[Antitrust Policy]: ./ANTITRUST.md
[Apache-2.0 license]: https://opensource.org/license/apache-2-0
[Attribution and Acknowledgements]: ../project-docs/ACKNOWLEDGEMENTS.md
[CC-BY 4.0 License]: https://creativecommons.org/licenses/by-sa/4.0/
[Code of Conduct]: ./CODE-OF-CONDUCT.md
[Community Specification Agreement]: https://github.com/CommunitySpecification/1.0.
[Contributor License Agreement]: ./CONTRIBUTOR-LICENSE-AGREEMENT.md
[Default Repo Governance Policy]: ./DEFAULT-REPOSITORY-GOVERNANCE.md
[Open Web Foundation Agreements]: https://www.openwebfoundation.org/the-agreements
[Recommended Conformant Licenses]: http://opendefinition.org/licenses
[Security Policy]: ./SECURITY.md
[Security Reports]: ./SECURITY.md
[Steering Committee List]: ./STEERING-COMMITTEE.md
[TPM-RS Charter]: ./CHARTER.md
[Trademark Policy]: ./TRADEMARKS.md
