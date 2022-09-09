---
title: "The Relationship between the IETF and its Trust"
# abbrev: "TODO - Abbreviation"
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
  github: https://github.com/larseggert/ietf-and-trust
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

normative:

informative:
  TRUST:
    title: IETF Trust
    date: false
    author:
    - org:
    target: "https://trustee.ietf.org/"
  TAV2:
    title: Second Amended and Restated Trust Agreement
    date: 2018-11-6
    author:
    - org:
    target: "https://trustee.ietf.org/documents/founding-documents/second-amended-trust-agreement-2018/"

--- abstract

TODO Abstract


--- middle

# Introduction

The IETF Trust {{TRUST}} was created on December 15, 2005. The
purposes of the Trust is to acquire, hold, maintain and license
existing and future intellectual property (IPR) and other property
used in connection with the Internet standards process and the IETF.
The Second Amended and Restated Trust Agreement {{TAV2}} is the
revision of the original founding document currently in effect.

# RFCs about the IETF Trust

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
  module holding the keys used to provide IETF Secretariat signature
  for Internet-Drafts.

* {{?RFC5378}}, aka BCP78, is the key document that details which
  rights IETF contributors provide to the Trust.

There are numerous other RFCs that mention the Trust in passing,
reiterating various aspects of its purpose, process or operation. Yet
others are older RFCs that have been obsoleted by the ones mentioned
above.

<!--
# Conventions and Definitions

{::boilerplate bcp14-tagged}
-->

# Security Considerations

The usual security considerations {{?RFC3552}} do not apply to this
document.

# IANA Considerations

This document does not request any IANA actions.

--- back

<!--
# Acknowledgments
{:numbered="false"}

TODO acknowledge.
-->
