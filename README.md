# Welcome to the EU Business Wallet Initiative

## Background

Within the recent launch of the [Competitiveness Compass for the EU](https://commission.europa.eu/document/download/10017eb1-4722-4333-add2-e0ed18105a34_en) the [European Commission](https://commission.europa.eu/index_en) 
announced its plan to augment the existing legislation around digital identity and trust, as laid 
down in the eIDAS-regulation [(EU) No 910/2014](https://eID.AS) for example, by introducing the 
**European Business Wallet (EUBW)**, which is envisioned to complement initiatives around 
the [European Digital Identity Wallet (EUDIW)](https://ec.europa.eu/digital-building-blocks/sites/display/EUDIGITALIDENTITYWALLET/EU+Digital+Identity+Wallet+Home) and become the cornerstone of doing business simply 
and digitally in the EU, providing a seamless environment for companies to interact with all 
public administrations. 

## EU Business Wallet System Architecture

As outlined in the following figure and explained in a first [discussion paper](https://dl.gi.de/items/c1d7ff4a-374a-4c11-a81e-64c5cc607e04), 
the *EU Business Wallet* is embedded in a system architecture, with an overarching *Trust Framework* defined by the eIDAS-regulation 
[(EU) No 910/2014](https://eID.AS) and optionally additional *Verifiable Data Registries* as defined 
in pertinent standards created by [W3C](https://www.w3.org). 

![EUBW Architecture](/img/eubw.svg)

The EU Business Wallet is interacting 
* with [European Digital Identity Wallets (EUDIWs)](https://ec.europa.eu/digital-building-blocks/sites/display/EUDIGITALIDENTITYWALLET/EU+Digital+Identity+Wallet+Home) for Business-to-Consumer (B2C) processes, 
* with EU Government Wallets (EUGW) for Business-to-Government (B2G) processes, 
* with other EU Business Wallets in Business-to-Business (B2B) processes,
* with embedded devices and machines in Business-to-Machine (B2M) processes,
* with employees in Business-to-Employee (B2E) processes and 
* it is integrated with existing services and data repositories. 

The EU Business Wallet is envisioned to play an important role within 
[Dataspaces](https://eclipse-dataspace-protocol-base.github.io/DataspaceProtocol/2025-1-RC1/), which are emerging within different domains and hence it has a *Data Plane* and a *Control Plane* 
in which there may be a variety of different protocols. Furthermore, the EU Business Wallet has a *Trust Plane*, which interacts with the different
providers, repositories and catalogues within the *Trust Framework*.

## Use Cases for the EU Business Wallet

The EUBW is expected to complement the EUDIW in order to support a large variety of use cases as outlined in the following.
Please do not hesitate to [suggest](https://github.com/eu-business-wallet/eu-business-wallet/issues)
additional use cases or priorities and [join us](#contact) for designing, standardizing and implementing 
the necessary protocols and data formats.   

![EUBW_Use_Cases](/img/use-cases.svg)

### Core Functionality of the EUBW

The Core Functionality of the EUBW comprises 
- Identification 
- Authentication 
- Authorization
- Creation and Validation of Electronic Signatures and Seals
- Requesting, Storing, Issuing, Presenting and Validating Electronic Attestations
- Preserving and Archiving of Electronic Signatures, Seals, Time Stamps, Electronic Attestations and Documents

### Cross-Sector Use Cases of the EUBW
 
- Establishment of a Company
- European Company Certificate
- Power of Attorney and Mandates
- Public Permits and Licences
- Onboarding of Business Partners and Master Data Management
- Electronic Invoicing
- Electronic Contracts
- Reporting of non-financial and diversity information

### Sector-specific Use Cases of the EUBW

#### Use Cases related to Finance
- Strong Customer Authentication  
- Identification of Payment Service Providers
- Identification and verification of the Identity of customers and beneficial owners
- Identification, authentication and business processes with agents
- SEPA Direct Debit Mandates
- Attestation of Financial Data and Statements
- Financial Data Access

#### Use Cases related to Industry

- Data Exchange and Dataspaces
- Digital Product Passport
- Digital Twins and Industrial Asset Management 
- Supply Chain Management and Trade Transparency
- Registration in the European Product Registry for Energy Labelling 
- Fulfilling the obligations of the Data Act
- Secure Processing Environments according to the Data Governance Act
- Reporting of Environmental Data from Industrial Installations
- Attestations for Accreditation, Certificates and Conformity Assessment   

#### Use Cases related to Logistics

- Electronic Freight Transport Information
- Electronic Consignment Notes (eCMR)
- Reporting within the European Maritime Single Window Environment
- Reporting of Carbon Dioxide Emmissions from Maritime Transport

#### Use Cases related to Mobility, Travel and Tourism
- Electronic Travel Documents
- Electronic Transportation Tickets  
- Mobile Driver's License
- Registration of Motor Vehicles
- Roadworthiness Certificates
- Attestations for Aviation Security 
- Data collection and sharing relating to short-term accommodation rental services

#### Use Cases related to Health
- Health Data Access and Exchange within the European Health Data Space
- Organ Donor Card  
- Reporting of suspected incidents related to Medical Devices
- Use Cases within national and regional electronic health systems

#### Use Cases related to Government

- Life events supported by the Single Digital Gateway 
- Use Cases within national and regional Electronic Government Initiatives
- Uses Cases related to democratic processes and electronic voting

#### Use Cases related to Education

- Application for Admission to Educational Institutions 
- Application and Approval of Educational Grants and Loans
- Attestations of Learning Achievements, Studies, School Certificates and University Diplomas
- Attestations of Professional Qualifications, Titles and Licences

#### Use Cases related to Social Security

- Registering of Employer or Employees within the Social Security System 
- Application for Health Insurance Membership 
- Application for and Approval of Health Related Services
- Attestation of Social Security Insurance Status
- European Health Insurance Card

#### Use Cases related to Justice

- Judical Cooperation and Cross-Border Access to Justice
- e-CODEX system
- Proceedings related to the Digital Markets Act

## Goal of the EU Business Wallet Initiative

To facilitate the trustworthy and interoperable implementation of the forthcoming European Business Wallet, 
the [go.eIDAS Association](https://go.eid.as/) has initiated the present initiative to pave the way for the European 
Business Wallet by preparing technical documents, which are planned to be provided as input for 
suitable standardisation bodies, such as [CEN](https://www.cencenelec.eu/), [ETSI](https://www.etsi.org/), [ISO](https://www.iso.org/), 
[IETF](https://www.ietf.org/)  and [W3C](https://www.w3.org/) for example. 

## Contributing

Please read the [CONTRIBUTING](CONTRIBUTING.md) file for details on how to contribute to the 
EU Business Wallet Initiative. 

## Versioning

We will use [SemVer](http://semver.org/) for versioning of our deliverables. 

## Licence

See the [LICENCE](LICENCE.md) file for details with respect to licensing.

## Contact

Please get in contact with us by either 
* opening an issue here, 
* visiting us at <https://go.eID.AS> or at <https://www.linkedin.com/company/68796097/> or
* by simply writing an email to [EUBW@eID.AS](mailto:EUBW@eID.AS).
