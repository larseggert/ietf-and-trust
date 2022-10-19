---
title: "The Relationship between the IETF and its Trust"
abbrev: The IETF and the IETF Trust
category: bcp

docname: draft-eggert-ietf-and-trust-latest
submissiontype: IETF
number:
date:
consensus: true
v: 3
area: ""
workgroup: "IETF"
# keyword:
#  - next generation
#  - unicorn
#  - sparkling distributed ledger
venue:
  group: GENDISPATCH
  type: Working Group
  mail: gendispatch@ietf.org
  arch: https://mailarchive.ietf.org/arch/browse/gendispatch/
  github: larseggert/ietf-and-trust
  latest: https://larseggert.github.io/ietf-and-trust/#go.draft-eggert-ietf-and-trust.html

author:
 -
  name: Lars Eggert
  org: NetApp
  street: Stenbergintie 12 B
  city: Kauniainen
  code: "02700"
  country: FI
  email: lars@eggert.org
  uri: "https://eggert.org/"
  # role: editor
 -
  ins: R. Housley
  name: Russ Housley
  org: Vigil Security, LLC
  abbrev: Vigil Security
  street: 516 Dranesville Road
  city: Herndon, VA
  code: 20170
  country: US
  email: housley@vigilsec.com

normative:

informative:
  TRUST:
    title: IETF Trust
    date: false
    author:
    - org:
    target: https://trustee.ietf.org/
  TAV2:
    title: Second Amended and Restated Trust Agreement
    date: 2018-11-6
    author:
    - org:
    target: https://trustee.ietf.org/documents/founding-documents/second-amended-trust-agreement-2018/
  APIT:
    title: Administrative Procedures of the IETF Trust
    date: 2020-5-26
    author:
    - org:
    target: https://trustee.ietf.org/documents/policies-and-procedures/administrative-procedures/
  COIP:
    title: Conflict of Interest Policy
    date: 2016-4-21
    author:
    - org:
    target: https://trustee.ietf.org/documents/policies-and-procedures/conflict-of-interest-policy/
  # RRMP:
  #   title: IETF Trust Records Retention and Management Policy
  #   date: 2016-6-16
  #   author:
  #   - org:
  #   target: https://trustee.ietf.org/documents/policies-and-procedures/records-retention-policy/
  OPPD:
    title: Obsolete Policies, Procedures & Drafts
    date: false
    author:
    - org:
    target: https://trustee.ietf.org/documents/policies-and-procedures/obsolete-policies-procedures/
  PM:
    title: IETF - Past Meetings
    date: false
    author:
    - org:
    target: https://www.ietf.org/how/meetings/past/
  AREG:
    title: Asset Register
    date: false
    author:
    - org:
    target: https://trustee.ietf.org/assets/asset-register/
  TAL:
    title: Trademarks and Logos
    date: false
    author:
    - org:
    target: https://trustee.ietf.org/assets/trademarks-and-logos/
  MIN:
    title: Minutes
    date: false
    author:
    - org:
    target: https://trustee.ietf.org/documents/minutes/
  FIN:
    title: Financials
    date: false
    author:
    - org:
    target: https://trustee.ietf.org/about/financials/
  ANN:
    title: Announcements
    date: false
    author:
    - org:
    target: https://trustee.ietf.org/about/announcements/
  FAQ:
    title: Frequently Asked Questions
    date: false
    author:
    - org:
    target: https://trustee.ietf.org/about/faq/
  TLP:
    title: Trust Legal Provisions (TLP)
    author:
    - org:
    target: https://trustee.ietf.org/documents/trust-legal-provisions/
  TLPINT:
    title: tlp-interest - Discussion of proposed revisions to the Trust Legal Provisions
    author:
    - org:
    target: https://www.ietf.org/mailman/listinfo/tlp-interest
  APP:
    title: Appeals
    date: false
    author:
    - org:
    target: https://trustee.ietf.org/documents/appeals/
  IICA:
    title: IANA IPR Community Agreement
    date: 2016-9-30
    author:
    - org:
    target: https://trustee.ietf.org/wp-content/uploads/Community-Agreement-2016-09-30-Executed.pdf
  BSD3CLAUSE:
    title: The 3-Clause BSD License
    date: false
    author:
    - org:
    target: https://opensource.org/licenses/BSD-3-Clause
  CCBY40:
    title: Attribution 4.0 International — CC BY 4.0
    date: false
    author:
    - org: Creative Commons
    target: https://creativecommons.org/licenses/by/4.0/


--- abstract

This document describes the expectations the IETF community has on the
structure and operation of the IETF Trust.


--- middle

# Introduction

The IETF Trust {{TRUST}} was created on December 15, 2005. The
purposes of the Trust is to acquire, hold, maintain and license
existing and future intellectual property (IPR) and other property
used in connection with the Internet standards process and the IETF.
The Second Amended and Restated Trust Agreement {{TAV2}} is the
revision of the original founding document currently in effect.

Various RFCs, summarized in {{rfcs}}, discuss the relationship of the
Trust to different aspects of the IETF standards process. This
document intends to complement these existing documents, capturing
the expectations the IETF community has about the structure and
operation of the Trust. In addition, this document clarifies the
relationship between the Trust and the IETF and the applicability of
BCPs that cover the IETF as a whole, without specific mention of the
Trust.

{:aside}
> The content of this document is written as if the IETF community had
  already established consensus on its expectations for the Trust.
  That consensus will obviously still need to be be estanblished
  through community discussion and IETF Last Call.


# Community Expectations about the IETF Trust {#expect}

The Trust Agreement {{TAV2}} is the foundational document of the IETF
Trust, and defines the purpose of the Trust as

>(...) the advancement of education and public interest by acquiring,
 holding, maintaining and licensing certain existing and future
 intellectual property and other property used in connection with the
 Internet standards process and its administration, for the
 advancement of the science and technology associated with the
 Internet and related technology.

It also defines the powers, rights and obligations of the Trustees and
the Trust.

At a minimum, the IETF community expects the Trust to comply with the
requirements placed upon it by its foundational document {{TAV2}}.

In addition, the IETF community expects the Trust to operate
transparently whenever possible, similar to how the IETF itself
operates. It is also in the interest of the IETF and the Trust is a
diverse set of IETF participants is able to volunteer to serve as
Trustees. Transparency helps understand IETF participants the Trust,
and allows them to decide whether they can volunteer.

## Relationship of the IETF Trust to the IETF {#relate}

The IETF community considers the Trust to be a core part of the IETF
that is critical to the ongoing function of the IETF.

Consequently, the IETF community expects all RFCs that apply to the
IETF to apply to the Trust, even if the Trust is not specifically
referenced.

The Trust's administrative procedures {{APIT}} under point 9 indicate
that the Trust partly agrees with this community expectation, when it
comes to licensing:

>The Trust shall be guided by IETF process documents, decisions of
 the IETF leadership, IETF consensus, and any legally binding
 agreements when licensing use of its intellectual property in
 accordance with the Trust Agreement.

The IETF community, however, expects the Trust to more broadly follow
IETF consensus and leadership decisions, unless they would conflict
with the Trust's purpose {{TAV2}}.

## Compliance with Foundational Documents {#comp}

{{TAV2}} requires the Trust to publish a number of procedures, including:

1. Procedures for administration of the Trust

   These have been published {{APIT}} and revised, with some - but not all -
   prior revisions available {{OPPD}}.

2. Procedures for reimbursement by Trustees of their fees and expenses
   from the Trust

   {{APIT}} contains a statement about reimbursements (under point 8),
   but does not describe a procedure.

3. Procedures for management of the Trust assets

   No such procedures seem to be published at the time of writing.

4. Procedures for conflicts of interest

   These have been published {{COIP}}.

5. Standards of conduct

   No such standards of conduct seem to be published at the time of writing.

The IETF community expects the Trust to comply with its founding
document, and hence expects it to publish the missing procedures.

This is especially true for procedures for management of the Trust
assets, which is the Trust's main responsibility. (The Trust does
maintain a lengthy FAQ {{FAQ}}, but that does not take the place of a
procedural document on management of the Trust assets.)

## Asset Licensing

Assets held by the Trust are critically important to the operation of
the IETF and the broader Internet industry. The IETF community hence
expects the Trust to license those assets freely, in a manner that
preserves its core rights in the assets.

The Trust Legal Provisions {{TLP}} have been fulfilling this
expectation, allowing broad use of the Trust assets both within and
and outside the IETF standards process. Code components and other
materials are available under the Revised BSD License
{{BSD3CLAUSE}} or a Creative Commons Attribution 4.0 license {{CCBY40}},
respectively.


## Transparency of Operation

The IETF community expects the Trust to operate transparently whenever
possible, matching the level of transparency demonstrated by other
parts of the IETF.


### Assets {#assets}

The purpose of the Trust is {{TAV2}}

>(...) maintaining and licensing certain existing and future
 intellectual property and other property used in connection with the
 Internet standards process (...)

An up-to-date detailed public asset register is a key requirement to
fulfill this purpose. While the Trust website contains an asset
register {{AREG}}, the information presented there is not detailed
and likely out-of-date.

At the time of writing, for example, "IETF contributions" is one type
of asset mentioned without further detail such as whether a copyright
was granted for contributions predating {{?RFC5378}}. Another example
is that no "licenses to others" are being shown after 2015. A third
is that the IRTF logo is missing from {{TAL}}, for which the Trust
was given the copyright in 2012.

In order to fulfill its purpose, the IETF community expects the Trust
to maintain an up-to-date detailed public record on the assets it
manages, the licenses under which different asset types may be
licensable, and the license requests it receives and grants.  This
should as a minimum include:

* The current known licensing position of every RFC.

* A list of every logo, badge or other graphical asset for which the
  Trust holds the copyright.

* A list of every website for which the Trust holds the copyright.

* A list of every domain name registered to the Trust.

* All other assets that are maintained by the Trust, such as the
  hardware security module holding the keys used to provide IETF
  Secretariat signatures for Internet-Drafts {{?RFC5485}}.

The IPR associated with IANA, which was transferred from ICANN to the
IETF Trust {{IICA}}, should be included in the detailed record of
assets above.


### Reporting {#reporting}

{{TAV2}} requires

>The Trustees shall report annually to the IETF community concerning
 the activities of the Trust, including grants or licenses given by
 the Trust (...)

The Trust presents at the IETF plenary to report to the IETF
community, and its presentations are available as part of the IETF
proceedings {{PM}}.

The Trust presents roughly once a year, which while strictly
conforming to {{TAV2}} is notably less frequent than the other parts
of the IETF that report at every plenary.  The Trust should match the
level of reporting of the other parts of the IETF and present at
every plenary.

The Trust also makes information available on its website
{{TRUST}}, and sends occasional announcements to the IETF community by
email {{ANN}}.

However, its presentations and announcements to the community do not
include information on grants or licenses given by the Trust, and the
asset register on its website {{AREG}} is not suitable, as described
in {{assets}}.

The Trust publishes financial information {{FIN}}, including annual
budgets and monthly statements, fulfilling the IETF community
expectations on financial transparency.


### Community Interactions

The IETF community expects to be able to have public discussions with
the Trust and the Trustees. Many IETF bodies maintain public
discussion email lists for this purpose, hold "office hour" sessions
during IETF meetings, or allow questions during their working
meetings. The Trust should explore these options to strengthen
interactions with the community.

The Trust operates the "tlp-interest" mailing list {{TLPINT}}, which
was originally created for questions related to the Trust Legal
Provisions {{TLP}}. The Trust has since informally indicated that
this list should be seen as their general public discussion list.
However, the list is not described or advertised as such on the
Trust website.

The Trust holds regular meetings and publishes their minutes
{{MIN}}. In order to further increase transparency and improve
community interactions, the Trust should consider announcing the
meetings to the public, and let observers join and ask questions.


## Funding

{{TAV2}} charges the Trust to

>(...) use reasonable efforts to secure contributions or commitments
 from third parties to contribute or make available sufficient funds
 to or on behalf of the Trust to administer the Trust and to maintain
 the Trust Assets (...)

Under {{?RFC8711}}, the IETF LLC is responsible for raising money on
behalf of the IETF, specifically to avoid confusion about who is
responsible for representing the IETF to sponsors.

The IETF community therefore expects the Trust to direct its
fundraising solely at the IETF LLC, and conversely expects the IETF
LLC to fund the operations of the Trust. Should the IETF Trust need
to demonstrate a diversity of funding, the IETF LLC is expected to
manage that.


## Accountability

The Trust consists of five Trustees. Three are appointed by the IETF
NomCom, one by the IESG, and one by the Internet Society (ISOC) Board
of Trustees {{?RFC8714}}. Trustees appointed by the NomCom may be
recalled per {{?RFC8713}}. Trustees appointed by the IESG or by the
ISOC Board of Trustees may be recalled by the appointing body.

Individual decisions or actions by the Trust may also be appealed by
community members {{APP}} following the process in {{?RFC2026}}, with
the IAB and the ISOC Board of Trustees as the appeal chain. The Trust
documents appeals and responses {{APP}}.

Additionally, the IETF community as beneficiaries of the Trust, has
legal standing to take action against the Trust if they believe it is
not acting in their best interests.

Together, these mechanisms provide sufficient community
accountability.

In the event of the Trust changing its legal structure then these
three layers of accountability must be maintained.


# Security Considerations

The usual security considerations {{?RFC3552}} do not apply to this
document.


# IANA Considerations

This document does not request any IANA actions.


--- back

# RFCs about the IETF Trust {#rfcs}

This section gives a brief overview of the various current RFCs that
make statements about the Trust.

* {{?RFC9281}}, aka BCP11, describes the role of the Trust in the
  context of other entities involved in the IETF standards process.

* {{?RFC9280}} defines the role of the Trust in Version 3 of the RFC
  Editor Model.

* {{?RFC8722}} defines that the Trust holds - on behalf of the IETF -
  any intellectual property rights of IETF protocol parameter
  assignment information, including the registry and its contents,
  and all registry publications.

* {{?RFC8721}} describes the desires of the IETF regarding outbound
  rights to be granted in IETF Contributions.

* {{?RFC8714}} updates the process for selection of Trustees for the
  IETF Trust under Version 2 of the IETF Administrative Support
  Activity (IASA) {{?RFC8711}}; {{?RFC8717}} updates the related IETF
  terminology. Together, these three RFCs form BCP101.
  {{?RFC8715}} captures the rationale for the changes introduced in
  {{?RFC8714}}.

* {{?RFC8713}}, a part of BCP10, defines the selection, confirmation,
  and recall process of IETF nominating and recall committees,
  including for Trustees.

* {{?RFC8712}} describes the IETF-ISOC relationship and reiterates
  that ISOC selects one of the Trustees.

* {{?RFC8179}}, aka BCP79, sets out the IETF policies concerning
  IPR related to technology worked on within the IETF.

* {{?RFC8090}} outlines the procedures by which the IETF makes
  appointments to the Community Coordination Group (CCG), which
  provides advice and guidance to the IETF Trust in matters related
  to the IANA trademarks and the IANA domain names.

* {{?RFC5745}}, {{?RFC5744}}{{?RFC4846}} and {{?RFC5743}} clarify that
  the Trust also manages the copyrights associated with RFCs
  published on the IAB, Independent and IRTF RFC streams.

* {{?RFC5485}} that the Trust logically owns the hardware security
  module holding the keys used to provide IETF Secretariat signatures
  for Internet-Drafts.

* {{?RFC5378}}, aka BCP78, is the key document that details which
  rights IETF contributors provide to the Trust.

There are numerous other RFCs that mention the Trust in passing,
reiterating various aspects of its purpose, process or operation. Yet
others are older RFCs that have been obsoleted by the ones mentioned
above.


# Changelog

{:aside}
> RFC Editor, please remove this appendix before publication.

<!-- For future PRs, please include a bullet below that summarizes the change
     and link the issue number to the GitHub issue page. -->

## draft-eggert-ietf-and-trust-00

Initial submission.


# Acknowledgments
{:numbered="false"}

These individuals suggested improvements to this document:

<ul spacing="compact">
<li><t><contact fullname="Jay Daley"/></t></li>
<li><t><contact fullname="Glenn Deen"/></t></li>
</ul>
