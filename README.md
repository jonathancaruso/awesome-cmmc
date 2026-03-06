# Awesome CMMC [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of tools, resources, templates, and guides for CMMC (Cybersecurity Maturity Model Certification) and NIST SP 800-171 compliance.

Whether you're a defense contractor preparing for a CMMC Level 2 assessment, an MSP supporting DIB clients, or a C3PAO assessor, this list has something for you.

## Contents

- [Official Resources](#official-resources)
- [Frameworks & Standards](#frameworks--standards)
- [DFARS Clauses](#dfars-clauses)
- [Assessment & Certification](#assessment--certification)
- [Tools - Open Source](#tools---open-source)
- [Tools - Commercial](#tools---commercial)
- [Templates & Documentation](#templates--documentation)
- [Training & Certification](#training--certification)
- [Books](#books)
- [Podcasts & Video](#podcasts--video)
- [Community](#community)
- [News & Legal Analysis](#news--legal-analysis)
- [Cloud & Infrastructure](#cloud--infrastructure)
- [Contributing](#contributing)

---

## Official Resources

- [DoD CIO CMMC Homepage](https://dodcio.defense.gov/CMMC/) - The official DoD CMMC program page.
- [CMMC Model Documentation](https://dodcio.defense.gov/CMMC/Documentation/) - Official model overview, assessment guides, and scoping guidance.
- [CMMC Resources & Downloads](https://dodcio.defense.gov/cmmc/Resources-Documentation/) - Downloadable resources including assessment guides, scoping guides, and the CMMC model itself.
- [About CMMC](https://dodcio.defense.gov/cmmc/About/) - Overview of the CMMC program and its goals.
- [Office of Industrial Base Policy - CMMC 2.0](https://business.defense.gov/Programs/Cyber-Security-Resources/CMMC-20/) - CMMC 2.0 details from the Office of Industrial Base Policy.
- [The Cyber AB](https://cyberab.org/) - The official CMMC accreditation body (formerly CMMC-AB). Authorizes C3PAOs and certifies assessors.
- [NIST SP 800-171 Rev 2](https://csrc.nist.gov/pubs/sp/800/171/r2/upd1/final) - Protecting Controlled Unclassified Information in Nonfederal Systems and Organizations.
- [NIST SP 800-171 Rev 3](https://csrc.nist.gov/pubs/sp/800/171/r3/final) - Updated CUI protection requirements (February 2024).
- [NIST SP 800-171A](https://csrc.nist.gov/pubs/sp/800/171a/final) - Assessing Security Requirements for CUI. The 320 assessment objectives that define CMMC Level 2.
- [NIST SP 800-172](https://csrc.nist.gov/pubs/sp/800/172/final) - Enhanced security requirements for CUI (CMMC Level 3).
- [OSCAL (Open Security Controls Assessment Language)](https://pages.nist.gov/OSCAL/) - NIST's standardized format for machine-readable compliance data.
- [CMMC Final Rule (32 CFR Part 170)](https://www.federalregister.gov/documents/2024/10/15/2024-22905/cybersecurity-maturity-model-certification-cmmc-program) - The CMMC program final rule published October 2024.
- [NIST Cybersecurity Framework (CSF)](https://www.nist.gov/cyberframework) - Complementary framework often mapped alongside 800-171.

## Frameworks & Standards

- [NIST SP 800-53 Rev 5](https://csrc.nist.gov/pubs/sp/800/53/r5/upd1/final) - Security and Privacy Controls (parent framework for 800-171).
- [NIST SP 800-53B](https://csrc.nist.gov/pubs/sp/800/53b/upd1/final) - Control Baselines for Information Systems and Organizations.
- [CUI Registry](https://www.archives.gov/cui) - National Archives CUI Registry defining CUI categories and markings.
- [FedRAMP](https://www.fedramp.gov/) - Federal Risk and Authorization Management Program for cloud services. CMMC accepts FedRAMP Moderate (or equivalent) for cloud components.
- [CISA Cybersecurity Resources](https://www.cisa.gov/cybersecurity) - Free tools and guidance from CISA applicable to CMMC controls.

## DFARS Clauses

Key Defense Federal Acquisition Regulation Supplement clauses that drive CMMC:

- [DFARS 252.204-7012](https://www.acquisition.gov/dfars/252.204-7012-safeguarding-covered-defense-information-and-cyber-incident-reporting) - Safeguarding Covered Defense Information and Cyber Incident Reporting. The foundational clause requiring NIST 800-171 compliance.
- [DFARS 252.204-7019](https://www.acquisition.gov/dfars/252.204-7019-notice-nist-sp-800-171-dod-assessment-requirements) - Notice of NIST SP 800-171 DoD Assessment Requirements. Requires self-assessment scores in SPRS.
- [DFARS 252.204-7020](https://www.acquisition.gov/dfars/252.204-7020-nist-sp-800-171-dod-assessment-requirements) - NIST SP 800-171 DoD Assessment Requirements. Governs Medium and High assessments by DIBCAC.
- [DFARS 252.204-7021](https://www.acquisition.gov/dfars/252.204-7021-cybersecurity-maturity-model-certification-requirements) - Cybersecurity Maturity Model Certification Requirements. The CMMC clause itself.
- [SPRS (Supplier Performance Risk System)](https://www.sprs.csd.disa.mil/) - Where contractors submit their NIST 800-171 self-assessment scores.

## Assessment & Certification

- [Cyber AB Marketplace](https://cyberab.org/Marketplace) - Find authorized C3PAOs, Registered Practitioners (RPs), and training providers.
- [DIBCAC (Defense Industrial Base Cybersecurity Assessment Center)](https://www.dcma.mil/DIBCAC/) - Conducts Medium and High assessments of contractor cybersecurity.
- [CMMC Assessment Guide (Level 2)](https://dodcio.defense.gov/CMMC/Documentation/) - Official assessment procedures for Level 2.
- [DoD Assessment Methodology](https://www.acq.osd.mil/asda/dpc/cp/cyber/docs/safeguarding/NIST-SP-800-171-Assessment-Methodology-Version-1.2.1-6.24.2020.pdf) - Scoring methodology for NIST 800-171 self-assessments (Basic, Medium, High).

## Tools - Open Source

- [cmmc-tracker](https://github.com/jonathancaruso/cmmc-tracker) - Self-hosted CMMC Level 2 compliance tracker with artifact management, POA&M generator, audit trail, and PDF reports. Flask + SQLite, Docker-ready. (MIT)
- [CMMC-Bagel](https://github.com/SecurityBagel/CMMC-Bagel) - Compliance assessment and POA&M management for CMMC/NIST 800-171A.
- [JAKTOOL/cmmc](https://github.com/JAKTOOL/cmmc) - NIST SP 800-171 Rev 2 and Rev 3 compliance manager with local data storage and compliance summaries.
- [NIST OSCAL](https://github.com/usnistgov/OSCAL) - Official NIST OSCAL repository with schemas, examples, and the 800-53 catalog in machine-readable format.
- [OSCAL CLI](https://github.com/usnistgov/oscal-cli) - Command-line tool for common OSCAL operations (validate, convert, resolve).
- [Compliance Trestle](https://github.com/oscal-compass/compliance-trestle) - Opinionated tooling platform for managing compliance as code using OSCAL. Python/pip installable.
- [OpenSCAP](https://www.open-scap.org/) - Open source security compliance solution implementing SCAP standards. Useful for automated technical checks.
- [Awesome OSCAL](https://github.com/oscal-club/awesome-oscal) - Curated list of OSCAL tools, libraries, and resources.
- [Awesome Compliance](https://github.com/theopenlane/awesome-compliance) - Broader compliance resource list covering multiple frameworks.

## Tools - Commercial

- [RegScale](https://regscale.com/) - Continuous compliance automation platform with CMMC and 800-171 support.
- [Drata](https://drata.com/) - Compliance automation for SOC 2, CMMC, NIST 800-171, and other frameworks.
- [Coalfire](https://www.coalfire.com/) - Cybersecurity advisory and assessment firm, authorized C3PAO.
- [Schellman](https://www.schellman.com/) - Assessment firm offering CMMC, FedRAMP, and SOC services.
- [Fortra (Tripwire)](https://www.fortra.com/) - Security and compliance tools including configuration assessment and file integrity monitoring.
- [Totem Technologies](https://www.totem.tech/) - CMMC-focused compliance platform designed for small DIB contractors.
- [PreVeil](https://www.preveil.com/) - End-to-end encrypted email and file sharing purpose-built for CMMC/CUI compliance.
- [Summit 7](https://www.summit7.us/) - Microsoft GCC High and CMMC compliance services.
- [ComplianceForge](https://complianceforge.com/) - Editable CMMC/NIST 800-171 policy and documentation templates.

## Templates & Documentation

- [NIST CUI SSP Template](https://csrc.nist.gov/files/pubs/sp/800/171/r2/upd1/final/docs/cui-ssp-template-final.docx) - Official NIST System Security Plan template for 800-171 (Word doc).
- [Peak InfoSec Free Templates](https://peakinfosec.com/resources/nist-sp-800-171-and-cmmc-templates/) - Free SSP, POA&M, and policy templates for the DIB from a former DIBCAC assessor.
- [CMMCAudit.org Templates](https://www.cmmcaudit.org/policy-templates-and-tools-for-cmmc-and-800-171/) - Curated list of free and paid policy template sources.
- [NIST 800-171 Control Family Mapping](https://csrc.nist.gov/pubs/sp/800/171/r2/upd1/final) - Appendix D maps 800-171 controls to 800-53 for organizations needing both.

## Training & Certification

### Certification Levels (The Cyber AB)

- **CCP (Certified CMMC Professional)** - Entry-level certification for individuals supporting CMMC.
- **CCA (Certified CMMC Assessor)** - Authorized to conduct CMMC Level 2 assessments as part of a C3PAO team.
- **C3PAO (CMMC Third-Party Assessment Organization)** - Organizations authorized to conduct official CMMC assessments.
- **RP (Registered Practitioner)** - Individuals registered with The Cyber AB to provide CMMC consulting.
- **RPO (Registered Provider Organization)** - Organizations registered to deliver CMMC consulting services.

### Training Providers

- [Cyber AB Marketplace - Training](https://cyberab.org/Marketplace) - Official list of Licensed Training Providers (LTPs) and Licensed Partner Publishers (LPPs).
- [CyberSecInvestments CMMC Training Videos](https://cybersecinvestments.com/cmmc-video-training/) - Free video training covering CMMC assessment preparation.

## Books

- *NIST SP 800-171 Compliance: A Practitioner's Guide* - Practical implementation guidance for each control family.
- *CMMC for Small Business: A DIY Guide to Cybersecurity Compliance* - Aimed at small contractors navigating CMMC without large budgets.

## Podcasts & Video

- [CMMC Compliance Guide Podcast](https://podcasts.apple.com/us/podcast/cmmc-compliance-guide/id1781941210) - Hosted by Brooke and Austin Justice, covering practical CMMC compliance topics with industry guests.
- [Mission Compliance Podcast](https://www.youtube.com/playlist?list=PLstjectj9BFgDQvMlPdoJCB6hpzMHlBQH) - YouTube series for defense contractors navigating CMMC.
- [As the CMMC Churns](https://peakinfosec.com/) - Video series from Peak InfoSec covering SSP development and assessment preparation.

## Community

- [r/CMMC](https://www.reddit.com/r/CMMC/) - Active Reddit community discussing CMMC implementation, tools, and assessment experiences.
- [r/NISTControls](https://www.reddit.com/r/NISTControls/) - Reddit community focused on NIST 800-171 and related security controls.
- [NDIA (National Defense Industrial Association)](https://www.ndia.org/) - Industry association representing defense contractors, active in CMMC policy discussions.
- [PSC (Professional Services Council)](https://www.pscouncil.org/) - Advocacy organization for government services contractors.
- [The Cyber AB Town Halls](https://cyberab.org/) - Periodic public meetings and updates from the accreditation body.

## News & Legal Analysis

- [Husch Blackwell - CMMC Updates](https://www.huschblackwell.com/) - Law firm with regular CMMC rulemaking analysis.
- [Crowell & Moring - Government Contracts Blog](https://www.crowell.com/en/insights?topic=Government+Contracts) - Legal analysis of DFARS and CMMC developments.
- [PreVeil Blog](https://www.preveil.com/blog/) - Regular CMMC compliance articles and implementation guides.
- [CyberSecInvestments](https://cybersecinvestments.com/) - CMMC news, analysis, and compliance resources.
- [Federal News Network](https://federalnewsnetwork.com/) - Covers federal cybersecurity policy including CMMC updates.

## Cloud & Infrastructure

CMMC Level 2 requires that cloud services processing, storing, or transmitting CUI meet FedRAMP Moderate (or equivalent):

- [Microsoft GCC High](https://learn.microsoft.com/en-us/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/gcc-high-and-dod) - Microsoft 365 and Azure for CUI/ITAR workloads. Most popular choice for DIB.
- [Azure Government](https://azure.microsoft.com/en-us/explore/global-infrastructure/government) - Azure regions with FedRAMP High authorization.
- [AWS GovCloud](https://aws.amazon.com/govcloud-us/) - Isolated AWS regions designed for sensitive government workloads.
- [Google Cloud for Government](https://cloud.google.com/solutions/government) - Google's government cloud offerings with FedRAMP authorization.
- [PreVeil](https://www.preveil.com/) - End-to-end encrypted email/files that meets CMMC requirements without requiring GCC High migration.

---

## Contributing

Contributions welcome! Please read the [contributing guidelines](CONTRIBUTING.md) first.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

This list is dedicated to the public domain under CC0 1.0 Universal.
