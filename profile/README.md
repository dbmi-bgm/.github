<img src="https://github.com/dbmi-bgm/cgap-pipeline/blob/master/docs/images/cgap_logo.png" width="200" align="right">

# Clinical Genome Analysis Platform

The [Clinical Genome Analysis Platform (CGAP)](https://cgap.hms.harvard.edu) is an open-source platform developed primarily by Harvard's Department of Biomedical Informatics. CGAP consists of multiple repositories - the codebase of the portal itself, as well as repositories containing code which runs and defines the genomics pipelines, monitoring, and various utilities. Want to contribute to our open source community efforts? Contact us at cgap-support@hms-dbmi.atlassian.net.

## Repositories


### Pipelines & Analysis


- **[cgap-pipeline-main](https://github.com/dbmi-bgm/cgap-pipeline-main)** - Main repository for bioinformatics pipelines and the relevant documentation.
- **[granite](https://github.com/dbmi-bgm/granite)** - Software package to work with genomic variants. The package provides inheritance mode callers and utilities to filter and refine variants called by other methods in VCF format.
- **[tibanna](https://github.com/4dn-dcic/tibanna)** - Software package that runs pipelines on Amazon Web Services (AWS).
- **[magma](https://github.com/dbmi-bgm/magma)** - Software package to manage meta-workflows automation and execution.

### Portal Infrastructure

- **[CGAP Portal](https://github.com/dbmi-bgm/cgap-portal)** - The primary codebase of the portal.
- [utils](https://github.com/4dn-dcic/utils) - A set of utility functions & scripts which are used in CGAP Portal and others.
- [snovault](https://github.com/4dn-dcic/snovault) - Contains abstractions for communicating with our databases, including PostgreSQL and ElasticSearch. A major dependency of CGAP Portal. Originally this was forked from ENCODE Project in ~2015.
- [react-workflow-viz](https://github.com/4dn-dcic/react-workflow-viz) - A React component/library for visualizing workflow runs.

### Visualization

- [higlass-sv](https://github.com/dbmi-bgm/higlass-sv) - HiGlass plugin track to visualize structural variants.
- [higlass-general-vcf](https://github.com/dbmi-bgm/higlass-general-vcf) - HiGlass plugin track that can visualize general VCF files.
- [higlass-cohort](https://github.com/dbmi-bgm/higlass-cohort) - HiGlass plugin track that visualizes cohort data.
- [cgap-higlass-server](https://github.com/dbmi-bgm/cgap-higlass-server) - Server component for HiGlass that manages and serves tiled data.

### Applications
- [SubmitCGAP](https://github.com/dbmi-bgm/SubmitCGAP) - Command-line tools for submitting and uploading files to CGAP.

----

[Legal Notices](https://cgap.hms.harvard.edu/legal)
