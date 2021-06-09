---
title: "Obtaining Data Approval"
author: "AnVIL"
description: "An overview of the approval process for submitting data to AnVIL."
---

# Step 1 - Obtain Approval

<hero>“Data should be made as widely and freely available as possible while safeguarding the privacy of participants, and protecting confidential and proprietary data”
[NIH - Data Sharing Guidance](https://grants.nih.gov/grants/policy/data_sharing/data_sharing_guidance.htm).</hero>

<hero>“The rights and privacy of human subjects who participate in NIH-sponsored research must be protected at all times.”
[NIH Data Sharing Policy and Implementation Guidance](https://grants.nih.gov/grants/policy/data_sharing/data_sharing_guidance.htm).</hero>

To deposit large-scale, individual-level data into AnVIL, data submitters must first obtain approval from:

1. The National Human Genome Research Institute (NHGRI)
1. The AnVIL ingestion committee

### General Data Requirements
Make sure your data conforms to these overall data requirements, or contact the AnVIL data team.

- All submitted genomic data should be based on Human reference genome assembly GRCh37 or GRCh38.

- Studies must be registered in dbGaP. You will need to populate the data elements `dbGaP_study_ID` (phsXXXXXX).

- All individual-level human genomic and phenotypic data must conform to the [NIH Genomic Data Sharing Policy](https://www.genome.gov/about-nhgri/Policies-Guidance/Genomic-Data-Sharing), including the expectation that participants [are/were] explicitly consented for data sharing.

### Access Control
Access control within the AnVIL is governed by three major groups - developer access, consortium access, and external researcher access (via dbGaP). For more information, see [Data Access Controls](/learn/accessing-data/data-access-controls).

### dbGaP Submission Requirements
Studies submitted to the AnVIL will still need to be registered with dbGaP, though there will be no requirement to submit source files or individual samples through the dbGaP portal. The dbGaP consent codes will be used to determine data access. Studies with multiple consent codes will be split into individual workspaces based on cohort and consent pairings. External researchers can use dbGaP to apply for access, and a completed and approved DAR will permit dbGaP to communicate this access grant to Terra.



## 1.1 - Obtain NHGRI Approval

### NHGRI program Officer Attestation
Submitters must obtain a written attestation from the NHGRI Program Officer stating the AnVIL team has permission to store, index, and access data on the AnVIL. This document must also include a list of people designated to speak and make decisions on behalf of the institution.

### Institutional Certification (NIH Data Sharing Policy)
Submitted data must be consistent with the requirements of the [NIH Genomic Data Sharing (GDS) Policy](https://www.genome.gov/about-nhgri/Policies-Guidance/Genomic-Data-Sharing). To ensure this, institutions will need to submit an Institutional Certification, which must include:

1. Confirmation that data conform to all applicable laws
2. Limitations for sharing, based on the informed consent of the research participants
3. The NHGRI Genomic Program Administrator who currently registers the study

The AnVIL team can provide an Institutional Certification template form.


## 1.2 - Obtain AnVIL Data Ingestion Committee Approval

The AnVIL data ingestion committee will evaluate ingestion applications to ensure data deposited into AnVIL meets the high quality of the [NIH Genomic Data Sharing (GDS) Policy](https://www.genome.gov/about-nhgri/Policies-Guidance/Genomic-Data-Sharing). The committee includes NHGRI program officers and AnVIL leadership team members.

After the AnVIL data ingestion committee approves datasets for ingestion, an approval notice will be sent via email to the applicant.

### Ethical Review

All scientific investigations should be undertaken with the highest priority given to the ethical requirements of such inquiries. AnVIL Program Directors and DIC will evaluate the ethical collection of both the data and of the submitting parties before approving for inclusion in the AnVIL.

### Data Retention

The committee will coordinate with the dataset stewards to determine a reasonable timeframe for retention of data within the AnVIL, as well as any other provisions around the long-term storage, archival, and availability of the data. This will happen during the initial discussions and vetting with the Data Ingestion Committee

