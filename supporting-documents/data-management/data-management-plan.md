# Data Management Plan: Decolonial AI for K-12 Educational Equity

**Project Title**: The Right Path: Developing a Decolonial Framework for AI Integration in K-12 Education
**Principal Investigator**: Dr. Charles Martin, Ed.D.
**Funding Agency**: National Science Foundation (NSF)

---

## 1. Types of Data to be Generated

### 1.1 Qualitative Data

**Interview Data**
- Audio recordings: 150+ semi-structured interviews (60-90 min each)
- Transcripts: Verbatim transcriptions with speaker identification
- Interview protocols and field notes
- File formats: MP3 (audio), DOCX and PDF (transcripts)

**Observation Data**
- Video recordings: 1,200+ hours classroom observations
- Field notes: Detailed observational records using structured protocol
- Observation rubrics: The Right Path Pedagogical Rubric scoring
- File formats: MP4 (video), DOCX and PDF (field notes)

**Focus Group Data**
- Audio/video recordings: 40 focus groups (90 min each)
- Transcripts with participant codes
- Facilitator notes and debriefs
- File formats: MP4 (video), MP3 (audio), DOCX and PDF (transcripts)

**Documents and Artifacts**
- Curriculum materials (lesson plans, assessments)
- Student work samples (AI projects, reflections, portfolios)
- Policy documents (district policies, vendor contracts)
- Meeting minutes and community artifacts
- File formats: DOCX, PDF, XLSX, JPG/PNG (images)

### 1.2 Quantitative Data

**Survey Data**
- AI & Human Flourishing Readiness Index responses
- CS Identity & Belonging Scale responses
- Demographic data (de-identified)
- File formats: CSV, XLSX, SPSS/SAV

**Learning Analytics**
- Course enrollment and completion data
- Student performance metrics
- Engagement data (attendance, participation)
- File formats: CSV, XLSX

**Administrative Data**
- School-level demographics
- Budget and resource allocation data
- Professional development participation logs
- File formats: CSV, XLSX

### 1.3 Participatory Data (Community-Generated)

**Community Research Team (CRT) Data**
- Research protocols designed by CRTs
- Data collected by community researchers
- Community analysis notes and interpretations
- Data governance agreements and protocols
- File formats: Various (determined by CRTs)

**Youth Participatory Action Research (YPAR) Data**
- Student-designed research instruments
- Student-collected data (surveys, interviews)
- Student analysis artifacts
- File formats: Various (determined by YPAR teams)

### 1.4 Metadata

For all datasets:
- Data dictionaries (variable names, definitions, coding schemes)
- Codebooks for qualitative data
- README files explaining file structure and contents
- Version control logs
- File formats: TXT, PDF, DOCX

**Estimated Total Data Volume**: 5-10 TB over 3 years

---

## 2. Data and Metadata Standards

### 2.1 File Naming Conventions

**Structure**: `[ProjectID]_[DataType]_[Site]_[Date]_[Version].[ext]`

**Examples**:
- `TRPAI_Interview_Site03_20250215_v1.mp3`
- `TRPAI_Observation_Site15_20260420_v2.docx`
- `TRPAI_Survey_AllSites_20270131_v1.csv`

### 2.2 Metadata Standards

**Dublin Core**: For all data files (title, creator, date, description, format, identifier)

**DataCite Schema**: For datasets deposited in repositories (with DOIs)

**Domain-Specific Standards**:
- Education research: ICPSR metadata standards
- Qualitative data: DDI (Data Documentation Initiative) for interview/observation metadata

### 2.3 Data Documentation

**README Files**: Each dataset accompanied by README containing:
- Project overview and research questions
- Data collection methods and dates
- File structure and naming conventions
- Data dictionary (variable definitions)
- Usage restrictions and citation requirements
- Contact information for questions

**Codebooks**: For all coded qualitative data
- Code definitions and examples
- Inter-rater reliability statistics
- Coding decision logs

**Data Dictionaries**: For all quantitative datasets
- Variable names, labels, and descriptions
- Value codes and missing data codes
- Units of measurement
- Data sources

---

## 3. Policies for Access and Sharing

### 3.1 General Principles

**Commitment to Open Science**: Data will be shared to the maximum extent possible while protecting:
- Participant privacy and confidentiality
- Community data sovereignty
- Intellectual property rights of Indigenous and marginalized communities
- Federal regulations (FERPA, COPPA)

**Tiered Access Model**: Different data types have different sharing policies based on sensitivity

### 3.2 Access Tiers

**Tier 1: Fully Open (Immediate Public Access)**

Data types:
- De-identified survey data (aggregate and individual-level, with sensitive demographics removed)
- Published curriculum materials
- Professional development resources
- Public-facing project documentation

Access: Deposited in open repositories with CC BY 4.0 license

Timeline: Within 1 year of data collection or upon publication

**Tier 2: Restricted Access (Qualified Researchers)**

Data types:
- De-identified interview transcripts (with identifiers removed)
- Observation field notes (with identifiers removed)
- Student work samples (with consent and de-identification)
- Institutional documents (with sensitive info redacted)

Access: Request-based access requiring:
- Data Use Agreement (DUA)
- IRB approval from researcher's institution
- Demonstrated research purpose aligned with ethical use
- Training in ethical use of qualitative data

Timeline: Within 2 years of data collection

Process: Managed through institutional data repository or ICPSR

**Tier 3: Community-Controlled (Tribal and Community Data)**

Data types:
- All data from tribal partner sites
- Community-specific artifacts and knowledge
- Culturally sensitive materials
- Any data deemed sensitive by Community Research Teams

Access: Governed by Community Research Teams and tribal data sovereignty protocols
- Each CRT establishes own data governance policy
- Tribal IRBs and data sovereignty agreements control tribal data
- Researchers must obtain explicit permission from communities
- Communities retain veto power over any data use or publication

Timeline: Determined by communities (may be embargoed indefinitely)

**Tier 4: Permanently Restricted (Never Shared)**

Data types:
- Audio/video recordings with identifiable participants (unless explicit consent for sharing obtained)
- Raw data containing personally identifiable information (PII)
- Data subject to FERPA protections (student education records)
- Data involving minors without parental consent for sharing

Access: Not shared publicly; retained for verification purposes only

---

## 4. Policies and Provisions for Re-Use, Re-Distribution, and Derivative Works

### 4.1 Licenses and Attribution

**Open Data (Tier 1)**: Creative Commons Attribution 4.0 International (CC BY 4.0)
- Users may share, adapt, remix data for any purpose
- Must provide attribution to original project and communities
- Citation format provided in README files

**Restricted Data (Tier 2)**: Data Use Agreement (DUA) required
- Specify permitted uses (e.g., research, not commercial)
- Require attribution and co-authorship consideration for community members
- Prohibit re-sharing without permission

**Community-Controlled Data (Tier 3)**: Community-Specific Agreements
- Each community defines terms of use
- May require benefit-sharing agreements
- May require community review of publications
- Traditional Knowledge (TK) Labels applied where appropriate (localcontexts.org)

### 4.2 Required Attribution

All data use must cite:
- Original research project and funding source (NSF grant number)
- Community Research Teams and partner communities
- Specific community members who contributed (if desired by community)

**Example Citation**:
> Martin, C., [Co-PIs], & Community Research Teams. (2027). *The Right Path: Decolonial AI for K-12 Education—Research Data* [Dataset]. [Repository]. https://doi.org/[DOI]. Supported by NSF Grant #[XXXXX]. Data collected in partnership with [Community Names].

### 4.3 Community Benefit-Sharing

**Principle**: Research data represents community knowledge and labor; communities deserve credit and benefit

**Mechanisms**:
- **Co-Authorship**: Community members invited as co-authors on publications using their data
- **Data Return**: Processed data returned to communities in accessible formats
- **Capacity Building**: Communities receive training in data analysis and use
- **Community Publications**: Communities supported in creating their own publications from data

---

## 5. Plans for Archiving and Preservation

### 5.1 Short-Term Storage (During Project)

**Primary Storage**: Secure cloud-based storage (Microsoft OneDrive for Business or Google Drive)
- Encrypted storage with role-based access controls
- Automatic versioning and backup
- Capacity: 10 TB storage allocation

**Backup Strategy**: 3-2-1 rule
- 3 copies of data
- 2 different storage media (cloud + external hard drive)
- 1 off-site backup

**Access Controls**: Role-based permissions
- PI, Co-PIs: Full access to all data (except Tier 3 without community permission)
- Research team: Access to assigned data only
- Community Research Teams: Full access to their site's data
- Graduate students: Access to de-identified data only

### 5.2 Long-Term Preservation (Post-Project)

**Repository Selection**: Based on data type and access tier

**Tier 1 (Open) Data Repositories**:
- **Primary**: Inter-university Consortium for Political and Social Research (ICPSR)
  - Specializes in social science data
  - Provides long-term curation and access
  - Assigns DOIs for citability
  - Ensures data persistence beyond project life

- **Secondary**: Open Science Framework (OSF)
  - Flexible, researcher-friendly platform
  - Integrated with pre-registration and publications
  - Long-term preservation commitment

- **Curriculum Materials**: GitHub + Zenodo
  - Version control for curriculum
  - Community contributions enabled
  - Zenodo provides DOIs and long-term archiving

**Tier 2 (Restricted) Data**: ICPSR Restricted Data Archive
- Secure access protocols
- Data Use Agreements managed by ICPSR
- Long-term preservation (50+ years)

**Tier 3 (Community-Controlled) Data**: Community-Designated Repositories
- Tribal archives or community-selected platforms
- May include: Mukurtu (Indigenous cultural heritage platform)
- Long-term stewardship by communities

**Tier 4 (Permanently Restricted)**: Institutional Research Data Repository
- Secure, access-restricted storage
- Retained for 7 years post-project (NSF requirement)
- Destroyed after retention period or transferred to communities

### 5.3 Data Formats for Long-Term Preservation

**Preferred Formats** (open, non-proprietary, widely adopted):
- Text: TXT, PDF/A, HTML
- Spreadsheets: CSV, TSV
- Databases: SQL, XML
- Audio: WAV, FLAC
- Video: MP4 (H.264 codec)
- Images: TIFF, PNG, JPEG2000
- Statistical data: CSV with SAS/SPSS syntax files

**Migration Plan**: Convert proprietary formats (DOCX, XLSX) to preservation formats within 1 year of data collection

### 5.4 Timeline for Deposit

| Data Type | Deposit Timeline |
|-----------|------------------|
| Curriculum materials | Rolling basis as developed; final deposit Year 3 |
| Survey data (de-identified) | Within 1 year of collection or upon publication |
| Interview/observation (de-identified) | Within 2 years of collection |
| Community-controlled data | Per community timeline |
| Final integrated datasets | Within 6 months of project completion |

---

## 6. Data Security and Confidentiality

### 6.1 Human Subjects Protection

**IRB Approval**: All data collection protocols approved by:
- PI institution's IRB
- Partner school districts' research review boards (where required)
- Tribal IRBs (for tribal partner sites)

**Informed Consent**: All participants provide informed consent/assent including:
- Explanation of data use and sharing
- Options for participation without data sharing
- Right to withdraw data at any time
- Community data sovereignty explained

**FERPA Compliance**: Student education records protected per Family Educational Rights and Privacy Act
- De-identification of all student-level data prior to sharing
- Aggregation where n<10 to prevent re-identification
- Data Use Agreements require FERPA compliance

**COPPA Compliance**: For participants under 13, Children's Online Privacy Protection Act requirements met
- Parental consent obtained
- Minimal data collection from minors
- No commercial use of children's data

### 6.2 De-Identification Procedures

**Direct Identifiers Removed**:
- Names, addresses, phone numbers, email addresses
- Social Security numbers, student IDs
- Photos or videos showing faces (unless consent for sharing obtained)
- Specific geographic locations smaller than county level
- Dates narrowed to month and year (not exact dates)

**Indirect Identifiers**:
- Demographic combinations that could enable re-identification
- Unusual characteristics or quotes that could identify individuals
- Small cell sizes (<10) aggregated

**De-Identification Review**: Two-person team reviews all data before sharing; additional review by external data security expert

### 6.3 Data Security Measures

**During Collection and Analysis**:
- Encrypted devices (laptops, tablets, audio recorders)
- Secure file transfer (SFTP, encrypted email)
- Password-protected files
- Limited access (role-based permissions)
- Virtual Private Network (VPN) for remote access
- Two-factor authentication for cloud storage

**Physical Security**:
- Locked file cabinets for paper materials
- Secure server room for physical data storage
- Limited key/access card distribution

**Cybersecurity**:
- Institutional IT security protocols
- Regular security audits
- Antivirus and anti-malware software
- Firewall protections
- Intrusion detection systems

**Data Breach Protocol**: In event of breach:
1. Immediate notification to IRB, NSF, affected communities
2. Assessment of compromised data
3. Notification to affected individuals (if identifiable)
4. Remediation and enhanced security measures
5. Incident report and lessons learned

---

## 7. Roles and Responsibilities

### 7.1 Data Management Team

**Principal Investigator (Dr. Charles Martin)**:
- Overall responsibility for data management plan implementation
- Ensures compliance with NSF, IRB, FERPA requirements
- Final authority on data sharing decisions (in consultation with communities)

**Research Director**:
- Day-to-day oversight of data collection and storage
- Trains research team on data management protocols
- Monitors data security and quality
- Coordinates de-identification and archiving

**Data Analyst**:
- Manages quantitative datasets
- Creates data dictionaries and documentation
- Prepares datasets for deposit
- Ensures data quality and integrity

**Community Research Teams**:
- Control data from their sites (Tier 3)
- Participate in data governance decisions
- Review and approve any data sharing from their communities

### 7.2 Institutional Support

**Grants Office**: Budget management, compliance oversight

**IRB Office**: Human subjects protection, protocol approval

**IT Services**: Data security, storage infrastructure

**Library**: Data repository selection, metadata support, long-term preservation

---

## 8. Budget for Data Management

| Item | Cost | Justification |
|------|------|---------------|
| Cloud storage (10 TB, 3 years) | $4,500 | Secure data storage during project |
| Transcription services | $6,000 | Professional transcription of interviews/focus groups |
| Data security audit | $2,000 | Annual external security review |
| Repository deposit fees | $3,000 | ICPSR data deposit and curation |
| Data management software (NVivo, Dedoose) | $3,500 | Qualitative analysis and collaborative coding |
| External hard drives (backup) | $1,000 | Physical backup storage |
| **Total** | **$20,000** | 2.7% of total project budget |

**Note**: Data management costs embedded in "Other Direct Costs" budget category

---

## 9. Indigenous Data Sovereignty and Community Data Governance

### 9.1 Principles

This project centers **Indigenous Data Sovereignty** (Kukutai & Taylor, 2016; Walter & Suina, 2019):
- Indigenous peoples have rights to control data about their communities
- Data governance is an expression of tribal sovereignty
- Data should benefit Indigenous communities
- Traditional knowledge has distinct protections

**CARE Principles** for Indigenous Data Governance (GIDA, 2019):
- **Collective Benefit**: Data should benefit Indigenous communities
- **Authority to Control**: Indigenous peoples' rights to control data
- **Responsibility**: Researchers accountable to Indigenous communities
- **Ethics**: Respect for Indigenous values and wellbeing

### 9.2 Tribal Data Sovereignty Protocols

**For Tribal Partner Sites**:
1. **Tribal Research Agreements**: MOUs with each tribal nation defining:
   - Data ownership (retained by tribe)
   - Data access and use permissions
   - Publication review and approval process
   - Intellectual property rights
   - Benefit-sharing arrangements

2. **Tribal IRB Review**: All research protocols reviewed and approved by tribal IRBs

3. **Traditional Knowledge Labels**: Use of TK Labels (localcontexts.org) to communicate cultural protocols

4. **Data Return**: All data collected from tribal communities returned in accessible formats with tribal ownership

5. **Community Veto**: Tribes retain right to:
   - Withdraw data at any time
   - Veto publications or presentations
   - Define data sharing restrictions
   - Determine long-term data stewardship

### 9.3 Community Data Governance for Non-Tribal Sites

**Community Research Teams** at all sites (tribal and non-tribal) establish data governance protocols addressing:
- What data can be collected
- Who has access to data
- How data is analyzed and interpreted
- What can be published or shared
- Community ownership and credit
- Community benefit from research

**Participatory Data Analysis**: Communities involved in interpreting findings; community knowledge integrated into analysis

---

## 10. Monitoring and Compliance

### 10.1 Data Management Monitoring

**Annual Data Audit**: Research Director conducts annual review:
- Data security compliance
- Storage and backup integrity
- Documentation completeness
- Progress toward archiving

**Advisory Board Review**: External Advisory Board reviews data management at bi-annual meetings

### 10.2 Compliance Reporting

**NSF Annual Reports**: Data management progress reported in annual project reports to NSF

**IRB Continuing Review**: Data management practices reviewed during IRB continuing review (annually or as required)

**Community Reporting**: Annual data governance reports to Community Research Teams and tribal partners

---

## 11. Contingency Plans

**PI Departure**: Co-PI assumes data stewardship; documented succession plan

**Institutional Changes**: Data transferred to alternative repository if institutional support changes

**Technology Obsolescence**: Data migrated to current formats every 5 years

**Funding Interruption**: Critical data preservation funded through institutional cost-share if NSF funding interrupted

---

## Summary

This Data Management Plan balances:
- **Open Science**: Maximizing data sharing to advance knowledge
- **Participant Protection**: Ensuring confidentiality and informed consent
- **Community Sovereignty**: Centering Indigenous and marginalized communities' rights to control data about themselves
- **Ethical Research**: Conducting research that benefits—not extracts from—communities

The plan operationalizes decolonial principles in data management, recognizing that how we manage data is as important as what data we collect.

---

**References**:

Global Indigenous Data Alliance (GIDA). (2019). CARE Principles for Indigenous Data Governance. https://www.gida-global.org/care

Kukutai, T., & Taylor, J. (Eds.). (2016). *Indigenous data sovereignty: Toward an agenda*. ANU Press.

Walter, M., & Suina, M. (2019). Indigenous data, Indigenous methodologies and Indigenous data sovereignty. *International Journal of Social Research Methodology*, 22(3), 233-243.

---

**Word Count**: 3,124 (Target: 2,000-3,000 for NSF Data Management Plan)

**Approval**:
- [ ] PI Review
- [ ] IRB Review
- [ ] Institutional Grants Office Review
- [ ] Community Research Team Review (template shared for feedback)
- [ ] Tribal Partners Review (for tribal-specific protocols)
