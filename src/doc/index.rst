.. raw:: latex

   \pagestyle{plain}
   \thispagestyle{plain}

.. _wg-charter:

FG-TIDA WGB: WGB-COP-charter (WGBCOP)
=============================================================

Charter Information
-------------------

.. list-table::
   :header-rows: 0
   :widths: 30 70

   * - **Charter version**
     - v0.1

   * - **Date**
     - 2026-11-20

   * - **Status**
     - Draft


1. Group Information
--------------------

..
   MANDATORY

   AUTHOR GUIDANCE:

   Include names and affiliations only in this section.

   Provide the exact repository and issue-tracker link.

   Do not include biographies, honorary titles, or persons who have not
   agreed to serve.

.. list-table::
   :header-rows: 1
   :widths: 38 62

   * - Field
     - Content

   * - Working group name and acronym
     - WGB-COP-charter (WGBCOP)

   * - FG-TIDA theme(s) covered
     - FG-TIDA Theme 25: Age-Aware Identity and Delegated Authority for Agentic AI <https://github.com/FG-TIDA/themes/issues/25>

   * - Chair(s) / co-chairs
     - Gianpaolo Scalone, Vodafone

   * - Editor(s) of the main deliverables
     - Gianpaolo Scalone, Vodafone

   * - Mailing list
     - <Mailing list>

   * - Repository and issue tracker
     - <GitHub repository URL>

   * - Charter status and version
     - Draft, V0.1


2. Background and Problem Statement
-----------------------------------

..
   MANDATORY

   AUTHOR GUIDANCE:

   Write two to four short paragraphs, or a concise numbered list.

   State:

   - what the problem is;
   - who has the problem: people, organizations, AI agents, systems, etc.;
   - why existing work does not adequately solve it;
   - any essential terms needed to understand the rest of the charter.

   Define only essential terms here.

   Do not include:

   - a history of the topic;
   - a literature review;
   - a proposed solution;
   - claims about a particular vendor or product;
   - undefined buzzwords.

A child can ask an assistant to find a product. The assistant can show the
results on the family device, pass the request to a shopping agent, or ask a
merchant to place an order. A guardian may allow the first two steps and
require approval for the third. A control on the device can govern what
appears on screen. By the time an order confirmation appears, the merchant
may already have accepted the purchase.

The same difficulty arises when an agent shares information on a child's
behalf. Across devices, services and networks, each party may see only part
of the interaction. On a shared device, even the account holder and the
person making the request may differ. The question is how the applicable
protection can follow the child, who can enforce it before an action takes
effect, and how much each party needs to learn about the child.


3. Goals
--------

..
   MANDATORY

   AUTHOR GUIDANCE:

   State what the Working Group will produce and why.

   Keep this section to approximately three to six sentences or bullets.

   Make clear whether the WG will:

   - describe: use cases, terminology, gap analysis;
   - specify: formats, interfaces, protocols;
   - recommend: guidelines, principles or best practices.

   The WG should build on relevant existing standards and specifications
   where possible.

   Do not use open-ended language such as "and any other related topics".

   Do not claim authority reserved for ITU-T Study Groups, such as approving
   ITU-T Recommendations.

* The Working Group will Describe how protections can apply both when an agent interacts directly with a child and when it acts on the child's behalf.

* The Working Group will Identify what evidence a service needs to establish who may authorize a particular action, what a guardian has permitted and whether that permission is still current.

* The Working Group will Identify where a device, agent, network or service can apply the protection, and the minimum information it needs to do so.


4. Scope and Non-Goals
----------------------

In Scope
~~~~~~~~

..
   MANDATORY

   AUTHOR GUIDANCE:

   Identify clearly what work belongs to this Working Group.

* The group will examine local controls, action-specific permissions and
privacy-preserving age-related assertions. It will consider which party
can vouch for each assertion, including what a telecommunications operator
can establish about a subscription or a configured family policy. It will
examine how restrictions carry across delegation, how a guardian can change
them and what happens when a downstream service cannot confirm an update.


Out of Scope / Non-Goals
~~~~~~~~~~~~~~~~~~~~~~~~

..
   MANDATORY

   AUTHOR GUIDANCE:

   Explicitly identify what the WG will NOT do.

   This section is important for preventing scope creep.

   Where a neighbouring topic belongs to another FG-TIDA WG, an SG17
   Question, or another organization, identify that relationship.

   Avoid defining the same deliverable under more than one WG.

* General agent identity and delegation architecture fall within ATHENA.
Generic network enforcement mechanisms are covered by the Network-Native
Governance theme. Setting legal age thresholds, determining legal
guardianship, classifying content by age and specifying age-verification
protocols or network API endpoints fall outside this charter.


5. Programme of Work and Deliverables
-------------------------------------

..
   MANDATORY

   AUTHOR GUIDANCE:

   Identify concrete documents the WG intends to produce.

   Every deliverable should have:

   - a clear title;
   - a short description;
   - relevant input documents, where applicable.

   Existing contributions or draft documents should be identified as inputs,
   not automatically treated as adopted WG text.

   Avoid open-ended deliverables such as "ongoing analysis".

.. list-table::
   :header-rows: 1
   :widths: 6 29 45 20

   * - #
     - Deliverable
     - Short description
     - Input documents

   * - 1
     - Child Online Protection for Agentic AI (Technical Report)
     - The report will describe child-specific requirements through one
       shopping example. A child may compare products, while a purchase
       requires guardian approval. The report will trace what happens if
       the guardian withdraws approval before the merchant accepts the
       order. At each step it will identify who can act, who can enforce
       the restriction and what each party needs to know.
     - Theme 25 and its discussion, with Themes 34 and 10 as architectural
       inputs.

   
6. Milestones
-------------

..
   MANDATORY

   AUTHOR GUIDANCE:

   Define dated, checkable milestones aligned with the FG-TIDA meeting
   calendar.

   Typical milestones include:

   - first draft available;
   - WG agreement;
   - submission to the FG-TIDA plenary.

   Keep dates realistic.

   Milestones may be updated without rechartering when the scope itself has
   not changed.

   Do not set dates beyond the lifetime of the Focus Group.

.. list-table::
   :header-rows: 1
   :widths: 30 70

   * - Target date
     - Milestone

    * - January 2027 FG-TIDA meeting
     - Make a first draft available for discussion, including the report outline and the worked example.


7. Coordination, Dependencies and Liaisons
------------------------------------------

..
   MANDATORY

   AUTHOR GUIDANCE:

   Identify only organizations or groups with a real dependency.

   Include, where relevant:

   - other FG-TIDA Working Groups;
   - ITU-T SG17 Questions;
   - other ITU-T groups;
   - external standards-development organizations;
   - industry or research communities.

   State briefly what the coordination concerns.

   Do not imply that a formal liaison or agreement exists unless one has
   actually been established.

.. list-table::
   :header-rows: 1
   :widths: 35 65

   * - Group / Organization
     - Coordination or dependency

   * **ATHENA (Theme 34).** Use the guardian-to-agent delegation in the example
  to identify what evidence a downstream service needs about the source,
  scope and current status of the permission.
  * **Network-Native Governance and Trust Enforcement (Theme 10).** Examine
  what a network can observe or enforce and where the merchant must check
  approval before accepting the order.
  * **ITU-T SG17 Q1/17.** Seek input from the PARCEP work on parental controls
  so the report can identify which assumptions carry over when an agent
  acts on a child's behalf.


8. Terminology
--------------

..
   OPTIONAL

   AUTHOR GUIDANCE:

   Include this section only where WG-specific terminology is needed.

   Prefer a reference to FG-TIDA terminology work.

   Limit this section to approximately three to five terms.

   Do not create a complete glossary here.

The Working Group will use the common FG-TIDA terminology where applicable. 
Should the Working Group define new terminology, this shall be communicated to the FG-TIDA terminology & use cases WG that maintains the common terminology repository. 

.. list-table::
   :header-rows: 1
   :widths: 30 70

   * - Term
     - Meaning

   * - <Term>
     - <Definition>

9. Use Cases
--------------

..
   OPTIONAL

   AUTHOR GUIDANCE:

   Include this section only where WG-specific use cases is needed.

   Prefer a reference to FG-TIDA use cases work.

   Limit this section to approximately three use cases.

   Do not create a complete set of use cases here.

The Working Group will define use cases relevant to this problem domain. 
This shall be communicated to the FG-TIDA terminology & use cases WG that maintains the common use cases repository. 

10. Working Methods
------------------

..
   OPTIONAL

   AUTHOR GUIDANCE:

   Include only working practices that differ from the general FG-TIDA
   working methods.

   Examples include:

   - how GitHub issues are used;
   - how draft documents are adopted;
   - special interim calls.

   Do not repeat ITU-T or FG-TIDA general procedural rules.

<Describe any WG-specific working methods, or delete this section if none.>


11. Security and Privacy Considerations
---------------------------------------

..
   OPTIONAL - RECOMMENDED

   AUTHOR GUIDANCE:

   Provide a short paragraph identifying the security and privacy
   concerns that the WG's deliverables must consider.

   Examples may include:

   - impersonation;
   - unauthorized delegation;
   - linkability;
   - surveillance;
   - misuse of identity information;
   - loss of human control;
   - accountability for agent actions.

   Avoid generic disclaimers.

The report will examine shared accounts, a sub-agent exceeding a guardian's
permission and a service relying on an outdated approval. It will consider
when protection can be applied locally, when a merchant needs only an
action-specific decision and when an age-related assertion is necessary.
It will examine whether repeated checks could link a child's activities
across services.


12. Success Criteria and Conclusion
-----------------------------------

..
   OPTIONAL

   AUTHOR GUIDANCE:

   State how the WG will know its chartered work is complete.

   Examples include:

   - all deliverables submitted to the FG-TIDA plenary;
   - findings transferred to the relevant SG17 Question;
   - no remaining chartered deliverables.

   Do not describe future approval by SG17 as guaranteed.

The Working Group will have completed its chartered work when
<success criterion>.

Following completion, <describe the expected next step, if applicable>.


13. Revision History
--------------------

..
   MANDATORY

   AUTHOR GUIDANCE:

   Update this table whenever the scope or charter text changes.

   Changes to milestones alone may be managed separately where appropriate.

.. list-table::
   :header-rows: 1
   :widths: 18 22 60

   * - Version
     - Date
     - Change

   * - 0.1
     - 2026-11-20
     - First draft of the proposed WGB-COP charter.
