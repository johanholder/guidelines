# Data Classification Guideline

## Purpose

The purpose of this Guideline is to establish a framework for classifying data based on its level of
sensitivity, value and criticality to an organisation (e.g. impact of applicable laws and regulations).
Classification of data will aid in determining baseline security controls for the protection of data and
assessing Impact Levels. It further defines roles and responsibilities for implementing this approach to
mitigate the risk of a data breach.
It is useful to recognise two contexts in which data is used:

-  Usage 1: Controlled within a System of Record that is operated under the direction of an identified
Data Steward.
- Usage 2: Outside of a System of Record by employees using the data in the course of their work.

Mitigating risk of breach in Usage #2 is the objective of this Guideline. Employees may not have a deep
understanding of the risks of a breach associated with each confidential data type. Hence, a Data
Classification is assigned to the various data types to allow an organisation to control and report
appropriately on the data usage.
Risk of breach in Usage #1 is mitigated primarily by processes incorporated into the operation of Systems
of Record as directed by Data Stewards.

## Definitions

**Breach​** is a loss of confidentiality, integrity, or availability that has the potential to cause some level of
negative impact to the organisation or to individuals.

**Confidential Data​** is a generalized term that typically represents data classified as Restricted, according
to the data classification scheme defined in this Guideline. This term is often used interchangeably with
sensitive data.

**Data Steward​** is a senior-level employee of the University who oversees the lifecycle of one or more sets
of Institutional Data. See the Information Security Roles and Responsibilities for more information.

**Data Type​** is a specific category of information (e.g. personally identifiable information, protected health
information, financial records, etc).

**Data Classification​** is a simple and high level means of identifying the level of security and privacy
protection to be applied to a Data Type. One of ​ **Public​** ,​ **Internal​** , or ​ **Restricted​** (defined below).

**Impact Level​** is a summary assessment of degree of impact in case of data breach that begins to suggest
the security safeguards used to protect the data. One of ​ **High​** , ​ **Medium​** , ​ **Low​** or ​ **None​** (defined below).

**Non-public Information​** is defined as any information that is classified as Private or Internal Information
according to the data classification scheme defined in this Guideline.

**Sensitive Data​** is a generalized term that typically represents data classified as Restricted, according to
the data classification scheme defined in this Guideline. This term is often used interchangeably with
confidential data.

## Data Classification

Data classification, in the context of information security, is the classification of data based on its level of
sensitivity and the impact to an organisation should that data be disclosed, altered or destroyed without
authorization. The classification of data helps determine what baseline security controls are appropriate

### for safeguarding that data. Data should be classified into one of three sensitivity levels, or classifications:


| Data Classification  | Definition                                                                                                                                                                                                                                                                                                                                             | Impact Level         |
| ==================== | =========                                                                                                                                                                                                                                                                                                                                              | ==================== |
| Restricted Data      | Confidential information requiring the highest level of security and privacy protection. Data should be classified as Restricted when the unauthorized disclosure, alteration or destruction of that data could cause a significant level of risk to the organisation or its affiliates.                                                               | High, Medium         |
| Internal             | Confidential information requiring diligent security and privacy protection. Information may be shared within the organisation on a need to know basis. Data should be classified as Internal when the unauthorized disclosure, alteration or destruction of that data could result in a moderate level of risk to the organisation or its affiliates. | Low                  |
| Public               | Information may be published and shared freely. Data should be classified as Public when the unauthorized disclosure, alteration or destruction of that data would results in little or no risk to the organisation and its affiliates.                                                                                                                | None                 |

## Calculating Classification

The goal of information security, is to protect the confidentiality, integrity and availability of an
organization's Data. Data classification reflects the level of impact to an Organization if confidentiality,
integrity or availability is compromised.
The following standards, drawn from Federal Information Processing Standards (FIPS) publication 199, the
ISO (the International Organization for Standardization) and IEC (the International Electrotechnical


Commission) 27000 family, which all discuss the categorization of information and information systems,
and form the basis for assigning an Impact Level of a data breach.
**Impact Level
Security Objective LOW MEDIUM HIGH
Confidentiality**
Preserving authorized
restrictions on
information access and
disclosure, including
means for protecting
personal privacy and
proprietary information.
The unauthorized
disclosure of
information could be
expected to have a
limited adverse effect
on organizational
operations,
organizational assets,
or individuals.
The unauthorized
disclosure of
information could be
expected to have a
**serious​** adverse effect
on organizational
operations,
organizational assets,
or individuals.
The unauthorized
disclosure of
information could be
expected to have a
**severe or catastrophic**
adverse effect on
organizational
operations,
organizational assets,
or individuals.
**Integrity**
Guarding against
improper information
modification or
destruction, and
includes ensuring
information
non-repudiation and
authenticity.
The unauthorized
modification or
destruction of
information could be
expected to have a
**limited​** adverse effect
on organizational
operations,
organizational assets,
or individuals.
The unauthorized
modification or
destruction of
information could be
expected to have a
**serious​** adverse effect
on organizational
operations,
organizational assets,
or individuals.
The unauthorized
modification or
destruction of
information could be
expected to have a
**severe or catastrophic**
adverse effect on
organizational
operations,
organizational assets,
or individuals.
**Availability**
Ensuring timely and
reliable access to and
use of information.
The disruption of
access to or use of
information or an
information system
could be expected to
have a ​ **limited​** adverse
effect on organizational
operations,
organizational assets,
or individuals.
The disruption of
access to or use of
information or an
information system
could be expected to
have a ​ **serious​** adverse
effect on organizational
operations,
organizational assets,
or individuals.
The disruption of
access to or use of
information or an
information system
could be expected to
have a ​ **severe or
catastrophic​** adverse
effect on organizational
operations,
organizational assets,
or individuals.
Maintaining Confidentiality, Integrity, and Availability are the three objectives that security safeguards can
hope to meet. Impact Level and Data Classification discussions focus primarily on Confidentiality and
occasionally on Integrity. Availability is primarily a function of how systems are operated, for which
appropriate security safeguards are chosen by other means, notably by IT Services.

## Data Types


Data Types are used in this guideline to make the process efficient and standardized yet observant of
specific requirements that occur in context. The Information Security Office and the Office of General
Counsel have defined several types of Restricted data based on state and federal regulatory
requirements. They're defined as follows:
Data Type Description & Examples Data
Classification
Authentication
Verifier
An Authentication Verifier is a piece of information that is
held in confidence by an individual and used to prove that
the person is who they say they are. An Authentication
Verifier may also be used to prove the identity of a system
or service. Examples include, but are not limited to:
● Passwords
● Shared secrets
● Cryptographic private keys
Restricted
Client Privileged
Information
Confidential communications between a client and a
lawyer for the purpose of securing legal advice. For the
privilege of confidentiality to exist, the communication
must be to, from, or with a lawyer.
● Communications related to a lawsuit.
● Communications related to a contract.
● Services related to a contract dispute.
Restricted
Contractual
Non-Disclosure
Information, materials, data and records designated
confidential by by contract, including information obtained
by the University from third parties under non-disclosure
agreements or any other contract that designates third
party information as confidential.
Internal
Departmental
Administration
Budgetary, departmental. Non-public financial,
procurement, health/safety, audit, insurance, departmental
files, and claims information.
Internal
Financial
Information
Personal financial information held. Restricted
General Business
Information
Sales material, marketing videos, Images, WhitePaper
Press Release, Management Reports & Minutes
Internal
Payment Card
Information (“PCI”)
Information related to credit, debit, or other payment
cards. This data type is governed by the Payment Card
Industry (PCI) Data Security Standards. Payment card
information is defined as a credit card number (also
referred to as a primary account number or PAN) in
combination with one or more of the following data
elements:
○ Cardholder name
○ Credit/debit card account number
○ Credit/debit card expiration date
Restricted


○ Credit/debit card verification number (CVC2,
CVV2 or CID value)
○ Credit/debit card security code
○ Contents of a credit card’s magnetic stripe
Payment Card Information is generally governed by
organisations PCI DSS Policy and Guidelines.
Personally
Identifiable
Information
The following data, often used for the express purpose of
distinguishing individual identity, clearly classify as PII
under the definition used by the ​National Institute of
Standards and Technology​ (described in detail below):
○ National identification number
○ Passport number
○ Social security number
○ State-issued driver’s license number
○ State-issued identification card number
○ Financial account number in combination with a
security code, access code or password that
would permit access to the account
○ Medical and/or health insurance information
○ Home address
○ Email address (if private from an association/club
membership, etc.)
○ IP address (when linked, but not PII by itself in US)
○ Vehicle registration plate number
○ Driver's license number
○ Face, fingerprints, or handwriting
○ Credit card numbers
○ Digital identity
○ Date of birth
○ Birthplace
○ Genetic information
○ Telephone number
○ Login name, screen name, nickname, or handle
The following are less often used to distinguish individual
identity, because they are traits shared by many people.
However, they are potentially PII, because they may be
combined with other personal information to identify an
individual.
○ First or last name, if common
○ Country, state, postcode or city of residence
○ Age, especially if non-specific
○ Gender or race
○ Name of the school they attend or workplace
○ Grades, salary, or job position
○ Criminal record
○ Web cookie
Restricted
Proprietary
Intellectual
Property
Proprietary intellectual property in which the organisation
asserts ownership that is created by employees in
connection with their work.
Internal


Protected Health
Information ("PHI")
Protected Health Information (PHI) is defined by the Health
Insurance Portability and Accountability Act (HIPAA). PHI is
individually identifiable health information that relates to
the;
○ Past, present, or future physical or mental health
or condition of an individual.
○ Provision of health care to the individual by a
covered entity (for example, hospital or doctor).
○ Past, present, or future payment for the provision
of health care to the individual.
The following individually identifiable data elements, when
combined with health information about that person, make
such information protected health information (PHI):
○ Names
○ Telephone numbers
○ Fax numbers
○ Email addresses
○ Social Security numbers
○ Medical record numbers
○ Health plan beneficiary numbers
○ License plate numbers
○ URLs
○ Full-face photographic images
○ Any other unique identifying number,
characteristic, code, or combination that allows
identification of an individual
Restricted








