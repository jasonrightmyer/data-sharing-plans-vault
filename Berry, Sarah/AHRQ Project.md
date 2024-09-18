___
# DATA MANAGEMENT AND SHARING PLAN

# Element 1: Data Type

**A.**    **Types and amount of scientific data expected to be generated in the project:**

The scientific data used in this study will be primary data collected as part of the study and secondary data obtained from other sources. The primary data for **Aim 1** will be obtained via a worker survey administered to a national sample of nursing home (NH) directors of nursing. Secondary data in Aim 1 will include the rate of NH worker turnover obtained from the Centers for Medicare & Medicaid Services (CMS)’s publically available turnover measure, a measure derived from the Payroll Based Journal (a national, auditable record of nurse and nursing assistant staffing hours and turnover of NH staff). The primary data for **Aim 2** will be obtained from qualitative interviews with directors of nursing, nurses and nursing assistants in 20 NHs (N=40 interviews). It will include staff descriptions of their experiences at work, the ways that the NHs where they are employed have engaged in strategies to increase the level of safety and well-being in the workplace, and rich details about workplace safety and well-being programs. Finally, data for **Aim 3** will be obtained as part of a pilot study of a Worker Care Model in 3 NHs. Primary data in Aim 3 will include a survey of worker experiences of psychological safety and burnout, and data from the intervention log with rich detail about a customized Worker Care Model in each NH (N=3) and challenges and facilitators to implementing the Worker Care Model. Secondary data in Aim 3 such as the rate that nurses and nursing assistants turnover in 3 NHs (obtained from CMS’s turnover measure, as above) and patient level data about the rates of psychotropic medication use and hospital transfers from restricted datasets that are provided by CMS and the electronic health records (EHR) from each of the 30 facilities in the trial. The LTC Data Cooperative data use agreements (DUAs) for the data never allow for the research team of the current study to assume control of the data.

**B.           Scientific data that will be preserved and shared, and the rationale for doing so:**

The secondary data in this application are already available through publicly available websites (NH Compare) and the LTC Data Cooperative. First, the CMS measure of worker turnover can be accessed through their publicly available website: [Finding a Nursing Home | CMS](https://www.cms.gov/about-cms/what-we-do/nursing-homes/patients-caregivers/finding-nursing-home).  Second, the LTC Data Cooperative data can be only accessed through formal request processes established by CMS and the LTC Data Cooperative according to their DUAs. See letter of support from the LTCDC. The qualitative data in **Aim 2** cannot be shared because the rich contextual detail in the data cannot be de-identified to protect the confidentiality of study participants. Scientific data that will be preserved and shared will include the following: 1) the de-identified worker survey data from **Aim 1** can shared without compromising the confidentiality of the study participants; 2) the primary data in **Aim 3**, because it is from only three NHs can only be shared in aggregate by facility; the rationale for sharing Aim 3 data in aggregate only is to protect the confidentiality of study participants. Any researcher or individual can use the data request processes and access the data to fully replicate all analyses that will be conducted in the current proposed application.

**C.        Metadata, other relevant data, and associated documentation:**

The study protocols and statistical analysis plans will be made available to facilitate interpretation, including  a record of changes made and the accompanying rationale.

# Element 2: Related Tools, Software and/or Code:

Datasets will be provided in common data formats including .sas7bdat data storage or transport format (XPORT) files for SAS (SAS Institute, Cary, NC) and comma-delimited datasets. While SAS is not open-source software, there are several freely available software packages for reading .sas7bdat datasets into other statistical programs, including the _haven_ package1 for the R Statistical Computing Environment.2 Due to the nature of the datasets we will analyze, data management is performed in SAS, which is able to more effectively handle data management tasks that must be completed to make the data analysis-ready. Once analysis-ready, statistical analyses and data visualization may be conducted using R software.

# Element 3: Standards:

The data for Aims 1 and the worker survey data in Aim 3 will be held in secure computing environments located at Marcus Institute for Aging Research. The qualitative data for Aim 2 will be stored at the University of North Carolina, Chapel Hill. The data will be formatted using standardized data dictionaries and procedures. Any data management work to conduct reformats will be carefully documented in the software code. In addition, any variable renaming will follow relevant conventions (e.g., consistent maximum number characters, all uppercase letters or numbers, always starting with a letter). Similar standardized conventions will be applied to the naming of all analytic datasets produced through management of the existing secondary data. In general, measurements of time will be converted to a relative measure of the number of days (or months) since the start of follow-up. A data dictionary will be generated. See environment and resources for additional description of computing and storage standards.

# Element 4: Data Preservation, Access, and Associated Timelines

**A.**    **Repository where scientific data and metadata will be archived:**

All of the primary survey data is controlled by Marcus Institute, whereas the patient level data is controlled by the LTCDC, and cannot be shared. For primary survey data that will be shared, we will archive metadata in ???Github or other repository.

# B.    How scientific data will be findable and identifiable:

Some of the data for the proposal is already available on CMS’s public website, NH Compare. Data are thus easily findable for the research community through systems that have existed for many years before this application for funding. To make data even more readily identifiable, our research team will provide detailed protocol and analytic plans on public facing websites (clinicaltrials.gov). Data for Aim 3 worker surveys will be shared in aggregate given the very small number of facilities (n=3) to protect worker confidentiality.

# C.    When and how long the scientific data will be made available:

Researchers and other individuals can request access to the datasets at any time. While the DUAs of CMS and AHCA do not allow for data to be made publicly and unrestrictedly available, anyone can access the datasets upon reasonable request from each of those data controllers, which decide whether to grant access in response to each request. The standard duration of access is determined by the DUAs. Each of those data controllers has maintained the long-term control of the datasets.

# Element 5: Access, Distribution, or Reuse Considerations

**A.**    **Factors affecting subsequent access, distribution, or reuse of scientific data:**

Data will be available for investigators providing an Institutional Review Board (IRB)/Ethics approval or certification of exemption, and agreeing to the terms and conditions of the DUAs with each of the data controllers. Data will be available unless prohibited by the informed consent process or the data controllers. Standard terms of the DUAs for each of the datasets prevents redistribution and re-identification of individuals.

# B.    Whether access to scientific data will be controlled:

Access to the primary survey data will be controlled by Marcus Institute for Aging Research. To request access to the data, researchers will be required to use the standard data access processes that have been established by each data controller.

# C.    Protections for privacy, rights, and confidentiality of human research participants:

We will utilize procedures required by the data controllers to ensure compliance with the Health Insurance Portability and Accountability Act (HIPAA) and other privacy measures. For Aim 1 survey data, each participant will be provided with a masked study identifier that will be used subsequently to link with study data in shared datasets. All measurements of time will be converted to a relative measure of the number of days (or months) since the start of follow-up whenever possible. Data will be obscured so that extreme values for any particular variable (such as centenarian participants) are aggregated so as not to be identifiable. No cell containing a value of between 1 and 10 will be reported directly. For Aim 3 we will take the additional precaution of aggregating the worker survey data at the facility level (n=3). Given the very low risk of this study aimed to improve the well-being of nursing home workers, we will seek waivers of written informed consent for workers and waivers of informed consent for patients.

# Element 6: Oversight of Data Management and Sharing:

All responsibilities will be shared with the MPIs, Drs. Sarah Berry, Mark Toles and co-I Alyssa Dufour. We have budgeted salary support to ensure that technical staff are appropriately supported to create software code, documentation, and other resources for the research community. We have additionally budgeted for Dr. Dufour’s time, to oversee and manage the Data Management and Sharing Plan.

**REFERENCES**

[^1] Wickham H, Miller E, Smith D (2022). _haven: Import and Export 'SPSS', 'Stata' and 'SAS' Files_. https://haven.tidyverse.org, https://github.com/tidyverse/haven, [https://github.com/WizardMac/ReadStat](https://github.com/WizardMac/ReadStat).

[^2] R Core Team (2021). R: A language and environment for statistical computing. R Foundation for Statistical Computing, Vienna, Austria. URL [https://www.R-project.org/](https://www.R-project.org/).