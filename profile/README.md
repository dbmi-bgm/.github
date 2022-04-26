

# Clinical Genomics Analysis Platform

The [Clinical Genomics Analysis Platform (CGAP)](https://cgap.hms.harvard.edu) is an open-source platform developed primarily by Harvard's Department of Biomedical Informatics. CGAP consists of multiple repositories - the codebase of the portal itself, as well as repositories containing code which runs and defines the genomics pipelines, monitoring, and various utilities.

## Repositories


### Pipelines & Analysis


- **[cgap-pipeline-main](https://github.com/dbmi-bgm/cgap-pipeline-main)** - Main repository for bioinformatics pipelines and the relevant documentation.
- **[tibanna](https://github.com/4dn-dcic/tibanna)** - Software package that runs pipelines on Amazon Web Services (AWS).
- **[magma](https://github.com/dbmi-bgm/magma)** - Software package to manage meta-workflows automation and execution.

### Portal Infrastructure

- **[CGAP Portal](https://github.com/dbmi-bgm/cgap-portal)** - The primary codebase of the portal.
- [SubmitCGAP](https://github.com/dbmi-bgm/SubmitCGAP) - Command-line tools for submitting and uploading files to CGAP.
- [utils](https://github.com/4dn-dcic/utils) - A set of utility functions & scripts which are used in CGAP Portal and others.
- [snovault](https://github.com/4dn-dcic/snovault) - Contains abstractions for communicating with our databases, including PostgreSQL and ElasticSearch. A major dependency of CGAP Portal. Originally this was forked from ENCODE Project in ~2015.
- [react-workflow-viz](https://github.com/4dn-dcic/react-workflow-viz) - A React component/library for visualizing workflow runs.


