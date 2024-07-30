
**Element 1: Data Type**

**A.**    **Types and amount of scientific data expected to be generated in the project:**

Demographic, cognitive, motor, clinical, gait kinematics, free-living accelerometry, functional near infrared spectroscopy (fNIRS), MRI, resting-state functional MRI (rs-fMRI), and trial compliance and safety data will be acquired from 128 men and women aged 65-90 years.

**B.**    **Scientific data that will be preserved and shared, and the rationale for doing so:**

A de-identified dataset including all raw data, processed data, and metadata mentioned in Element 1.A. will be preserved and shared. Our rationale for sharing this data is to maximize rigor and transparency, enable verification of results, encourage collaboration, and afford other researchers with the opportunity to analyze the data for additional hypothesis generation and/or testing.

**C.**    **Metadata, other relevant data, and associated documentation:**

Documentation to be made publicly available will include the study protocol, sample informed consent, case report forms, MRI sequence information, and data dictionary. Each variable in the data dictionary will include the variable name, a brief description of the variable, the question number and question text from the questionnaire when appropriate, the variable label, value labels, and standard codes for missing values, including codes for non-applicable, “don’t know,” and refusal. This documentation will be provided in portable document format (PDF) or related content-types as appropriate to facilitate interoperability (e.g. Excel, CSV, etc.). We aim to make the study methods, results, and analyses reproducible.

**Element 2: Related Tools, Software and/or Code:**

We will utilize the REDCap system to facilitate data management operations. REDCap is a full-featured clinical trials data management system (DMS) accessible to data entry and data analysis workstations using secure Web technologies. Hebrew SeniorLife (HSL) hosts and maintains a dedicated instance of REDCap for use across our research enterprise. Each research study is provided separate project workspace in which all of the study data are stored in a MySQL relational database on the private corporate network behind several firewalls and located physically within the HSL data center.

Laboratory-based assessments of gait will be captured, processed, and analyzed using the commercially-available Mobility Lab™ motion capture system and accompanying analytic software. Functional near-infrared spectroscopy (fNIRS) will be used to acquire measures of brain activation during the gait assessment. These data will be captured using the commercially-available PortaLite® system (Artinis Medical Systems, The Netherlands) and analyzed with commercially-available MATLAB software. Feel-living accelerometry and home-based gait kinematic data will also be processed and analyzed with MATLAB software.

MRI and rs-fMRI data will be processed and analyzed with commercially-available MATLAB software. The resulting aggregate level statistics will be made available through tab delimited csv files and will not require the use of specialized tools to be accessed. The voxel-level associations data will be additionally shared in NIfTI file format. _3D Slicer_ is a free and open-source tool which can be used to visualize the voxel level neuroimage association maps. Additionally, the code used for the data preprocessing, feature extraction and data analysis will be shared via GitHub repository to support replication of the analyses and reuse of the implemented methods. A singularity image with the used Linux environment and installed software will be also shared for replication. A detailed explanation on how to run this code will be shared in the GitHub repository.

**Element 3: Standards:**

Participant age, sex, ethnicity, height, weight, socioeconomic status, and medical history will be collected using forms to be shared as described in Element 1.C. above. Trial safety data and participant medication usage (name, dosage, and timing) will be captured and coded according to current Medical Dictionary for Regulatory Activities (MedDRA) guidelines. Laboratory-based measures of gait, accompanying fNIRS data, cognitive testing, and questionnaires will be obtained using published procedural recommendations. To facilitate the efficient use of our MRI data, the resulting aggregate neuroimaging statistical data will be structured and described using the following standards: Data will be stored in tab delimited csv file with MNI coordinates, brain region names based on Desikan-Killiany atlas, regression betas, Z-stats, associated p-values, and clusters surviving to multiple comparisons. Additionally, for an easier visualization of the results this will be also stored in NIfTI format, which has been widely adopted to store neuroimage data in the community. This neuroimage statistical maps will be projected to MNI152 standard template.

**Element 4: Data Preservation, Access, and Associated Timelines**

**A.**    **Repository where scientific data and metadata will be archived:**

De-identified data and all metadata will be archived within the Marcus Institute Data Archiving Service (MIDAS), a publicly accessible website built on the CKAN (Comprehensive Knowledge Archive Network) open-source data management platform. The MIDAS system is maintained and hosted by HSL. 

**B.**    **How scientific data will be findable and identifiable:**

The MIDAS repository supports standard search and metadata query features through the CKAN platform interface.  Furthermore, the repository is linked to the Marcus Institute and HSL websites and indexed by several public search engines. Each dataset will be issued a persistent unique identifier and will be organized by publication; however, access to a given dataset will not require publication association.

**C. When and how long the scientific data will be made available:**

Sharing of clinical trial data (participant level and summary level data, raw and processed) is expected at the time of publication of the primary results or within 9 months of database lock, whichever comes first. At minimum, per HSL’s Record Management, Retention, Disposition and Destruction Policy, all data will be retained for at least seven years after project completion or the sponsored award agreement end date as stipulated in its terms and conditions. 
  
**Element 5: Access, Distribution, or Reuse Considerations**

**_A._**    **Factors affecting subsequent access, distribution, or reuse of scientific data:**

All participants will be consented for broad data sharing of de-identified data as described in this document.

**B.**    **Whether access to scientific data will be controlled:**

Access to scientific data will be controlled prior to publication of the primary results or for 9 months following database lock, whichever comes first. During this period, the project PI will maintain and chair a standing subcommittee of the project investigators which will review each request. Upon majority approval of a request, access to the data may be granted in secure fashion. After this period, archived data will be accessible by investigators without need of approval by the study team. Moreover, investigators who wish to access data will not need to be affiliated with HSL. Data containing patient identifiers or related sensitive fields will be archived on HSL private servers and will not be publicly accessible. Limited or identifiable data sets will be shared only under HSL data use agreement (DUA) terms and conditions.

**C.  Protections for privacy, rights, and confidentiality of human research participants:**

Only those individuals listed on the approved IRB protocol will have access to personally identifiable information. Identifying information will not be used during discussion, presentation, or research publication. All data collected for analysis will be de-identified and assigned a unique study identification (ID) number. Paper-based data collection forms and ID code information will be kept in a locked file cabinet within dedicated and locked office space at each study site. REDCap data will be entered and stored electronically on a secure server hosted in the HSL Data Center. MRI and laboratory gait measures will be archived and processed electronically on a secure file server at HSL. The to-be-shared data described in Element 1 of this document will be completely stripped of identifiers.

**Element 6: Oversight of Data Management and Sharing:**

Monitoring and compliance with the Data Management and Sharing Plan will occur at a minimum of every six months and will be the responsibility of the project’s Principal Investigators (Dr. Manor and Dr. Hausdorff). The plan will be implemented and managed by professional staff working under the direction of the PIs.

---

 [[BM1]](#_msoanchor_1)This is the word-for-word sentence that the NIA asked us to include.  Are you suggesting we tweak the wording to something like “Sharing of clinical trial data accompanying each publication of primary results...” in order to not promise archiving the entire study dataset??