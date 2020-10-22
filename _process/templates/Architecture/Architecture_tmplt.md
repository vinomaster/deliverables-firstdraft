# Title (Ex. 0000: Deliverable Name)
- Authors: [your name](you@github-email) -- email is optional
- Deliverable Type: *Specification - Architecture* 
- Status: [PROPOSED](/README.md#proposed)
- Since: YYYY-MM-DD (date you submit your PR)
- Status Note: (explanation of current status)  
- Supersedes: (link to anything this ToIP Deliverable  supersedes)
- Start Date: YYYY-MM-DD (date you started working on this idea)
- Tags: (see ../../../tags.md)

## Summary

```
One paragraph explanation of the objective of this document.
DELETE THIS COMMENT
```

## Motivation

```Why are we doing this? What use cases does it support? What is the expected outcome?
DELETE THIS COMMENT
```

## Scope

```
Briefly describe the scope of this document – how it presents the architecture of this particular enabler.  Include an explanation of how this architecture relates to Organization Name activity.  If it adds clarity, also describe what is not in the scope of this architecture.  DELETE THIS COMMENT
```

## References

```diff
- Gating Criteria reference requirements
- URL to be added
```

```
The policy for reference lists is:
1.	'ORG_NAME' documents listed should have at least one approved version –
draft-only docs should not be referenced.  Exception exists for
documents that will be approved with or after the referenced doc is
approved (may be part of same enabler package).  In short – approved
docs should not reference unapproved docs.
2.	When a reference is made to an 'ORG_NAME' specification, then 'ORG_NAME' with the TM symbol (™) should be used in the
description.
3.	The name + version (no date) for 'ORG_NAME' specifications are
generally sufficient – dates should be used only if there is a
specific reason to limit the usage.
4.	References to other affiliate docs should similarly provide
sufficient information to uniquely determine the needed document
and should provide the appropriate source information.
5.	The URL for 'ORG_NAME' material (new 'ORG_NAME' and affiliate) should always
be http://www.org_name.org (an exception is Registry that
is reached through http://www.org_name.org/tech/)

Models to use
	[REFLABEL]	<General Model> "Ref Title", Ref information
                (source, date, id), URL:http//<ref-source>/
	['ORG_NAME'DOC]	<'ORG_NAME' Model> "'ORG_NAME' Document Title",{ Version x.y,}
                Organization Name™, 'ORG_NAME' <docname>{ <version>},
                URL:http//www.org_name.org/

If there are no entries in the table – enter ‘none’ to be clear.

DELETE THIS COMMENT
```

### Normative References

<table>
    <caption>Normative References</caption>
    <tbody>
        <tr>
            <td><strong>[OSE]</strong></td>
            <td>"'ORG_NAME' Service Environment", Organization Name™, 'ORG_NAME'-AD-Service-Environment, URL:http://www.org_name.org/</td>
        </tr>
        <tr>
            <td><strong>[RFC2119]</strong></td>
            <td>"Key words for use in RFCs to Indicate Requirement Levels", S. Bradner, March 1997, URL:http://www.ietf.org/rfc/rfc2119.txt</td>
        </tr>
        <tr>
            <td><strong>[[@@@-RD]</strong></td>
            <td>"@@@ Requirements", Organization Name™, 'ORG_NAME'-RD-@@@-Vx_y, URL:http://www.org_name.org/</td>
        </tr>
    </tbody>
</table>

```
Add/Remove reference rows as needed - DELETE This Row
```

### Informative References

```
Check the version of the Dictionary you are using and update the
reference below.  Delete the ['ORG_NAME'DICT] entry if the dictionary
is not used.  In general, use the latest available version unless
seeking alignment with an existing set of specifications.

DELETE THIS COMMENT
```

<table>
  <caption>Informative References </caption>
  <tbody>
    <tr>
      <td><strong>['ORG_NAME'DICT]</strong></td>
      <td>"Dictionary for 'ORG_NAME' Specifications", Version x.y, Organization Name™, 'ORG_NAME'-ORG-Dictionary-Vx_y, URL:http://www.org_name.org/</td>
    </tr>
    <tr>
      <td><strong>['ORG_NAME'-CHG-AD]</strong></td>
      <td>"Charging Architecture", Version 1.1, Organization Name™, 'ORG_NAME'-AD-Charging-V1_1, URL:http://www.org_name.org/</td>
    </tr>
  </tbody>
</table>

```
Add/Remove references as needed - DELETE This Row
```

## Terminology and Conventions
```diff
- Gating Criteria requirement
- URL to be added.
```

### Conventions

The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT", "SHOULD", "SHOULD NOT", "RECOMMENDED", "MAY", and "OPTIONAL" in this document are to be interpreted as described in \[RFC2119\].

All sections and appendixes, except "Scope" and "Introduction", are normative, unless they are explicitly indicated to be informative.

```
If needed, describe or declare using appropriate normative
references the additional conventions that are used.  
DELETE THIS COMMENT >>
```

### Definitions

```
Add definitions in new rows of the following table as needed.  
The following examples show how dictionary references should
be made as well as locally defined terms.  This table should
be maintained in sorted alphabetic order based on the labels
of the terms.

Examples:
	Entity              Use definition #1 from ['ORG_NAME'DICT]
	Interactive Service Use definition from ['ORG_NAME'DICT]
	Local Term          The definition description would be
                        presented directly

DELETE THIS COMMENT
```

<table>
  <caption>Definitions</caption>
  <tbody>
    <tr>
      <td><strong>Example Term</strong></td>
      <td>Example Term Definition</td>
    </tr>
  </tbody>
</table>

```
Add/Remove definition rows as needed - DELETE This Row
```

Kindly consult \['ORG_NAME'DICT\] for more definitions used in this document.

### Abbreviations

```
Add abbreviations as needed to the following table.  No special notation
should be made regarding terms copied from the Dictionary.  This table
should be maintained in alphabetic order.
DELETE THIS COMMENT
```

<table>
    <caption>Abbreviations</caption>
        <tbody>
            <tr>
                <td><strong>'ORG_NAME'</strong></td>
                <td>Organization Name</td>
            </tr>
        </tbody>            
</table>

## Introduction

```
Describe the high level architecture in greater detail than provided in
section 1.  From a market perspective, this section should answer the
following questions (in prose):
o	What is the purpose of this architecture?
o	What problems does this architecture solve?
DELETE THIS COMMENT
```

### Version 1.0

```
This section provides a high level, concise and informative description of
the main functionality supported in the initial enabler or reference release
version described in this AD. The description should be brief, target length
should be a few paragraphs. When the enabler or reference release is
finished, this description should be aligned with the final functionality.  
DELETE THIS COMMENT
```

### Version \<x.y\>

```
This section should be included for each new major or minor version of the enabler
or reference release covered in the AD. It should provide a high level, concise
and informative description of the new or modified functionality introduced in
this version of the enabler or reference release covered in the AD, compared to
the previous version. The description should be brief, target length should be
a few paragraphs. When the enabler or reference release is finished, this
description should be aligned with the final functionality differences.
DELETE THIS COMMENT
```

### Version \<x.y.z\>

```
This section should be included for each new service release covered with the AD.   
It should describe at a high level the main changes made to the AD compared to
the previous version. The description should be brief, target length should be
one paragraph.
DELETE THIS COMMENT
```

## Architectural Model

```
This section defines the enabler’s architectural model. The model identifies:
a) all internal functional components of this enabler, and b) all of the
communication relationships between the components of this enabler and with
other enablers and applications (including those specifications not defined
by 'ORG_NAME').

This section SHOULD contain a diagram of the architecture.  Diagrams in this
section should contain logical entities only and not conflate logical
entities with physical entities. However, mobile terminals and networks may
be shown because of their potential relevance in the design of the architecture.  
The figures are illustrative examples of architectural diagrams and should be
modified to reflect this architecture.

Working Groups SHOULD re-use functions specified by other enablers. Working
Groups should consult other Architecture Documents and Specifications to
identify any of this architecture’s functionality (e.g. its systems,
subsystems, interfaces and/or reference points, etc) that is already
specified.

This section MAY include an explanation and/or diagram to show how this
architecture relates to the various views as defined in  "Inventory of
Architectures and Services". This diagram and explanation, however,
are optional.  

DELETE THIS COMMENT >>
```

### Dependencies

```
This section MUST enumerate all of the dependencies this architecture has,
in order to fulfil the approved enabler requirements (both mandatory and
optional). Dependencies in this context are other 'ORG_NAME' enablers and non-'ORG_NAME'
specifications (e.g. RFC 2616) this enabler calls (i.e. re-uses). Each
dependency MUST include a reference to the document(s) that specifies the
depdency. All of these references MUST also be included in Section 2.1.

The enumeration would be along the lines of a list with entries such as
    - IMAP binary extension [RFC3516]
where the reference (e.g. RFC3516 in this example) would link to the
fully qualifed reference in section 2.1 table.

A dependency is actually to an interface and the intrinsic functions
(required and re-used by this enabler) performed by the component that
exposes that interface.

Note: Dependencies should not be confused with deployment options.

If this architecture has no dependencies, then this section only needs
to contain a statement as such.

If this architecture has dependencies on 'ORG_NAME' Enablers, specific
sub-sections shall describe those enablers and the interfaces used,
as well as the purpose for re-use in the context of this enabler.

Example:

5.1.1 'ORG_NAME' X Enabler

This Enabler makes use of the following Interfaces from 'ORG_NAME' X:

X-1 Interface is exposed by the X Enabler and SHALL be used by this
enabler as detailed in [X_AD];

5.1.2 'ORG_NAME' Y Enabler

This Enabler makes use of the following Interfaces from 'ORG_NAME' Y:

Y-1 Interface is exposed by the Y Enabler and SHALL be used by this
enabler as described in [Y_AD];

DELETE THIS COMMENT
```

### Architectural Diagram

```
This section contains the architectural diagram for the enabler.  
The example figures below, along with their legends, describe
the drawing conventions to be followed. In some cases (an example
figure is not shown here) the resulting architecture diagram may
contain combinations of interfaces and reference points.

DELETE THIS COMMENT
```

```diff
- Gating Criteria requirement
- URL to be added.
```

<figure class="text-center">
    <img src="images/ExampleInterfacesArchitecturalDiagram.svg" alt="Example of the Architectural Diagram using interfaces">
    <figcaption>Example of the Architectural Diagram using interfaces</figcaption>
</figure>

<figure class="text-center">
    <img src="images/ExampleReferencePointsArchitecturalDiagram.svg" alt="Example of the Architectural Diagram usingreference points">
    <figcaption>Example of the Architectural Diagram usingreference points</figcaption>
</figure>

### Functional Components and Interfaces/reference points definition

```
This section describes all of the architecture’s functional
components and the specified interfaces and/or reference points.

As a general guidance, the Architecture Document SHOULD define
interfaces, wherever possible.

Each of the components should be described in a separate
subsection and MUST contain at least the following
information:
o	Name
o	Description
o	Responsibility (e.g. what does the component do/perform)

Each component SHOULD have at least one interface or at least
one reference point that can be used by some other functional
component, enabler, application, etc.

All of the interfaces and/or the reference points should be
described in this section.

Interfaces and reference points MUST be described in a
language-independent way.

Each interface description MUST include at least the following
information:
o	Name
o	Description
o	Entity that exposes the interface

Each reference point description MUST include at least the
following information:
o	Name
o	Description of all the functions exposed between the two
entities
o	The two entities that are linked by this reference point

Each reference point description SHOULD include the following
information:
o	Name of each interface included in the reference point

Description of each interface included in the reference point

Interface/reference point naming convention:

The name of an interface/reference point consists of a minimal
number of characters (e.g. no longer than the WID's registered
name), followed by a dash, followed by a running number
(starting at "1" and counting upwards in steps of 1 for each
new interface/reference point).  Each work group decides about
the character(s) for their interfaces/reference point as long
as there is no duplication with already existing names (work
groups can consult ARC to confirm).  Names should be chosen
in an intuitive way to allow easy recognition of the
interface/reference point.  Some examples are:
     B-1	B stands for "Browsing"
     POC-5	POC stands for "Push to Talk over Cellular"
     MMS-7	MMS stands for "Multimedia Messaging"

Interface re-use convention: In case an interface from another
enabler is re-used (e.g. exactly as is, as a profiled subset,
or extended with additional Attribute Value Pairs), the interface
name is that of the other enabler.  That is, the interface name
does not change, since the interface does not fundamentally
change.  The interface structure and placement of parameters
and/or AVPs are already defined as part of the other enabler.

Reference points re-use convention:
 In case a reference point from another enabler is re-used
(i.e. all of its interfaces, and the two entities, as originally
defined, linked through the reference point) then, the reference
point name is that of the other enabler.  That is, the reference
point name does not change, since the reference point does not
fundamentally change.  The reference point structure and
placement of parameters and/or AVPs are already defined as part
of the other enabler.

Detailed recommendations on how to re-use reference points may
be found in the "Architecture Best Practices" document.

Graphical representation convention:

Reference points are depicted as a line and interfaces are
depicted as an arrow.

DELETE THIS COMMENT
```

### Security Considerations

```
Describe security functionalities based on security requirements
defined in corresponding Requirement Document.

Security functionalities should address and consider at least
the following features:
o	Authentication
o	Authorization
o	Data integrity
o	Confidentiality
o	Non-repudiation

DELETE THIS COMMENT
```

### Charging Considerations

```
Describe charging functionalities based on charging requirements
defined in corresponding Requirement Document.

The following text MAY be used to identify functional components
that may report Chargeable Events.  If used, "X" SHALL be replaced
by the name of the enabler being specified and "['ORG_NAME' X RD]" SHALL
be replaced by a reference to the Requirements Document for the
enabler, and "'ORG_NAME' X functional entity 1,2,.." SHALL be replaced
by a list of functional components of the enabler that may
report Chargeable Events.

DELETE THIS COMMENT
```

The underlying network or other suitable entity may need  to  support the receiving of charging data or charging events triggered from an external mechanism in order to fulfil the charging requirements described in \['ORG_NAME' X RD\]. One such mechanisms is triggering through the 'ORG_NAME' Charging Enabler.

The 'ORG_NAME' Charging Enabler \['ORG_NAME'-CHG-AD\] coordinates charging data triggers and flow from 'ORG_NAME' X enablers into an underlying charging infrastructure, supporting charging mechanisms, e.g. Online, Offline, Price Points.  Functional components that may optionally report Chargeable Events are:

* 'ORG_NAME' X functional entity 1
* 'ORG_NAME' X functional entity 2
* ...

```
If the specification refers to common Charging functionality and
does not involve specific Charging related specifications, this
section MAY end with the following text:

DELETE THIS COMMENT
```

The interaction between these functional entities and the 'ORG_NAME' Charging Enabler is described in \['ORG_NAME'-CHG-AD\]. Description of how charging is performed is beyond the scope of the present specification.

```
If the specification involves specific Charging related
functionality, then this section MAY include following text
for each functional entity listed above.  If used, "'ORG_NAME' X
functional entity i" SHALL be replaced by one of the functional
entities listed above, and "[TS X Charging]" SHALL be replaced
by a reference to the Technical Specification document where the
charging functionality for this functional entity is defined.  
Please don’t forget to add this reference to section 2.2 above!

DELETE THIS COMMENT
```

The interaction between 'ORG_NAME' X functional entity and the 'ORG_NAME' Charging Enabler is described in \[TS X Charging\]. Description of how charging is performed is beyond the scope of the present specification.

```
These texts are guidelines only and this section MAY contain
alternative or additional text to explain the charging
considerations for this enabler, if any.

DELETE THIS COMMENT
```

```diff
- Gating Criteria
- URL to be defined
```

## Appendix Change History (Informative)

### Approved Version x.y History

<table>
    <caption>Approved Version x.y History</caption>
    <thead>
        <tr>
            <th>Reference</th>
            <th>Date</th>
            <th>Description</th>
        </tr>
    </thead>
    <tbody>    
        <tr>
            <td>n/a</td>
            <td>n/a</td>
            <td>No prior version</td>
        </tr>
    </tbody>
</table>

## Appendix Flows (informative)

```
The objective of this section is to describe the high-level logical
flows between the architectural entities.
* These flows should just serve for a better understanding of the
architecture. Therefore it is recommended to add a minimum number of
flows, which should be very high-level.
DELETE THIS COMMENT
```

## Appendix Dependencies

### 'ORG_NAME' Dependencies

```
List relevant documents.  DELETE THIS COMMENT
```

### External Dependencies

```
List relevant documents.  DELETE THIS COMMENT
```

## Appendix Additional Information

```
If needed, add annex to provide additional information to support the
document.  In general, this information should be informative, as
normative material should be contained in the primary body of the
document.
DELETE THIS COMMENT
```

### App Headers

(More text)

#### More Headers

(More text)

##### More Headers

(More text)

<table>
    <caption>Example Table</caption>
    <thead>
        <tr>
            <th></th>
            <th>Column 1</th>
            <th>Column 2</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Row 1</td>
            <td>Grid 1,1 data</td>
            <td>Grid 1,2 data</td>
        </tr>
        <tr>
            <td>Row 2</td>
            <td>Grid 2,1 data</td>
            <td>Grid 2,2 data</td>
        </tr>
    </tbody>
</table>
