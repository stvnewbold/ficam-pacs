---
layout: default
title: PIV and PIV-I Considerations
permalink: /pivandpivi/
---

PIV and PIV-Interoperable (PIV-I) credentials are based on smart card technology. Smart cards incorporate a small computer chip in a card (or other form factor).  The embedded chip provides the card with built-in tamper resistance, the ability to store large amounts of data securely, data processing capability, and the ability to interact intelligently with a smart card reader. Smart cards can be used online and across networks and deliver very high levels of security over the Internet.  They are also convenient and easy to use.
Smart card technology can provide an identity management system or physical access control system with strong information and privacy protection.  A smart card-based ID can guard personal information and individual privacy by implementing a personal firewall, releasing only required information and only when it is genuinely required.

The PIV and PIV-I credentials include a dual-interface chip that supports both contact (ISO/IEC 7816-compliant) and contactless (ISO/IEC 14443-compliant) operations.

## What Is the Difference between PIV and PIV-I?

The Federal Government has issued well over 5 million PIV cards to employees and contractors.  Federal agencies use the PIV card to authorize employee access to both physical and logical resources and to assign access privileges.  The success of the program is largely due to the development of goals, issuance policies, and technical specifications that all Federal agencies have agreed to follow.  A cross-certification policy establishes trust between agencies; employees from one agency can use their PIV credentials to access controlled resources when visiting other agencies.  A variety of suppliers offer products and systems that conform to the technical interoperability standards.

Interest in a common identity credential is growing among Non-Federal Issuers. PIV-I cards are already being issued by federal contractors to employees who need access to federal buildings and IT networks.  The PIV-I credential is technically interoperable with the government PIV systems (e.g., readers) and is issued in a way that allows government agencies to trust the card.  PIV-I credentials comply with Federal Bridge guidance on identity-proofing, registration, and issuance.  PIV-I credentials are cross-certified with the Federal Public Key Infrastructure (PKI) Bridge to allow contractor personnel, visitors, and personnel waiting for clearance to access authorized resources.  Table 4 compares the PIV and PIV-I cards.

Agency policy may dictate a background check before granting access to a PIV-I cardholder.

**Table 4. Comparison of PIV and PIV-I Cards**

| **Policy** |  **PIV** | **PIV-I** |
| :-------- | :------------ | :----------- |
| Breeder documents  | Follows FIPS 201 |  Follows FIPS 201  |
| Background checks  | National Agency check with investigation <!--Do we mean to say "National Agency Check with Inquiries (NACI)"?--> | None required |
| **Process** |   |   |
| Application, Adjudication,<br>Enrollment, Issuance,<br>Activation  | Follows FIPS 201: separation of<br>roles, strong biometric binding | Follows Federal Bridge cross-certification<br>certificate policies.<br>Follows NIST SP 800-63-1 <!--800-63-1 is a deprecated and shouldn't be referenced.-->for<br>Federal issuance.<br>Based on FIPS 201: separation<br>of roles, strong biometric binding. |  
| **Technology** |   |  |
| Card data mode  | Must follow SP 800-73 | Must follow SP 800-73  |
| Current primary credential number   | FASC-N (requires federal agency code) | UUID (no federal agency code required) |
| Object identifiers  | Federal Bridge | Federal Bridge  |
| **Federation Levels&nbsp;of Assurance** |   |  |
| Trustworthiness   | Trusted identity, credential, and suitability | Trusted basic identity and credential<br>but not suitability |
| Trust among organizations   | Federal Bridge | Clustered through Federal Bridge |
| **Origin** |  |  |
| Organization   | NIST Federal | CIO Council |
| Defining documents   | FIPS 201, FIPS 201-2, NIST SP 800-73 and other related NIST publications | Personal Identity Verification Interoperability for NFIs<br>FICAM PIV-I FAQ |
| Motivation | HSPD-12 | Interoperable credential for organizations doing business with the government and for first responders |
| **Markets** |   |  |
| Organizations that may issue and/or use the credential  | Federal agencies | Federal agencies<br>Federal contractors<br>Commercial organizations doing business with the Federal Government<br>State and local governments<br>Critical infrastructure providers<br>First responder organizations<br>Commercial organizations who are part of an industry initiative and require an interoperable, trusted credential |
| Use  | Credential can be used in a wide range of both employment-related and consumer-based transactions.<br>Examples include physical access, logical access, mass transit, and closed loop payments. | Same as for PIV  |

## Does PIV-I Affect Federal Agencies and Employees?

Federal contractors, as well as a variety of other organizations, including large corporations, consulting firms, first responders, and state and local governments, are all beginning to use PIV-I cards.  Federal agencies also issue PIV-I cards to some personnel, such as employees who are waiting for completion of background checks or on temporary assignment.  Certain common considerations drive PIV-I use.

- **Published credential standard.**  The credential is based on open published standards, making it easier to develop software applications that use the credential.
- **Interoperability.** The credential can be used across a variety of applications and devices.  For example, individuals can use one credential to access offices, the parking garage, and client locations and networks.
- **Economies of scale.**  As use of PIV and PIV-I credentials increases, multiple commercial sources become available for the card, the card reader, supporting middleware, and operating systems.  Increasing availability reduces the cost of implementation, speeds up deployment, and simplifies use.
- **Multiple form factors.**  A PIV-I credential can take a variety of forms, such as a plastic card, a USB token, or a smart phone.  PIV-I credentials can therefore be included in a variety of devices.
- **Fewer credentials.**  The ultimate goal is to reduce the number of identity credentials that individuals must carry or remember.
- **Identity assurance.**  Individuals with PIV-I credentials have been verified through an identity proofing process and enrollment system.  Entities can rely on a basic level of identity confirmation and privacy protection to secure web and messaging applications.   
- **Data protection.**  Use of the PIV-I credential supports the secure transfer and storage of data and messages, using encryption and digital signatures.   
- **Remote access.**  PIV-I credentials use smart card technology and provide strong authentication for remote and wireless access to enterprise networks.  

## What Is the Difference between PIV and PIV-I Readers?

The PIV-I credential is technically interoperable with Federal PIV systems, including card readers.  

The PIV and PIV-I technology and infrastructure are based on multiple standards governing components ranging from the physical token (the smart card) to the identity credential components to the PKI that enables interoperable trust.  Both PIV and PIV-I are based on FIPS 201-2 and accompanying special publications and reference other internationally recognized standards.  

The GSA validates and approves products that comply with FIPS 201-2 and publishes the results as a GSA FICAM Approved Products List (APL).  APL-certified smart card readers are capable of reading identifiers on both PIV cards (Federal Agency Smart Credential Number, FASC-N 64-bit identifier) and PIV-I cards (128 bit UUID, defined by RFC 4530).  PIV and PIV-I cards are interchangeable if the appropriate level of trust is established for the PIV-I card.

