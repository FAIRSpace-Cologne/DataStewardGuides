#RDM Repository Evaluation Checklist for Data Stewards

This checklist supports data stewards in selecting and evaluating **open-source Research Data Management (RDM) repositories**.  
Each criterion can be assigned a **weight** (importance) and **score** (performance), with optional notes or evidence.

| **Dimension** | **Sub-Criteria** | **Description / Measurement Guidance** | **Weight** | **Score (1–5)** | **Notes / Evidence** |
|----------------|------------------|-----------------------------------------|-------------|------------------|-----------------------|
| **1. Usability** | User documentation | Evaluate quality, completeness, and clarity of manuals, online guides, tutorials. | | | |
|  | System Usability Scale (SUS) (optional) | Conduct or review usability surveys with representative users (admin, researchers, data curators). | | | |
|  | User role support | Check support for key roles (data steward, depositor, reviewer, admin). | | | |
|  | Basic tasks support | Assess ease of performing typical repository tasks: deposit, publish, edit metadata, manage access. | | | |
| **2. Metadata Management** | Metadata enrichment support | Ability to define, extend, or enrich metadata schemas (e.g., custom templates). | | | |
|  | Custom metadata | Support for domain-specific or project-level metadata fields. | | | |
|  | Standardised vocabulary support | Integration with ontologies, controlled vocabularies, or taxonomies. | | | |
|  | Findability & metadata quality | Support for standards (e.g., Dublin Core, schema.org), DOI minting, metadata exposure via OAI-PMH. | | | |
| **3. Data Handling** | Data upload | Methods and limits for file upload; drag-and-drop, API upload, large file support. | | | |
|  | Searchability | Availability of full-text search, faceted search, advanced filters, indexing performance. | | | |
|  | Browsing | Ease of navigating collections, communities, or datasets. | | | |
|  | Versioning | Dataset and file version tracking and comparison capabilities. | | | |
|  | Linking | Support for linking related datasets, publications, grants, projects. | | | |
|  | Deletion | Soft delete, retention policies, and compliance with institutional policies. | | | |
|  | Publishing | Support for embargoes, DOI assignment, review workflow before publication. | | | |
|  | Access control | Granularity of access control (dataset-level, file-level, role-based). | | | |
| **4. Interoperability** | API support | Availability of REST, GraphQL, or SDKs for programmatic access and automation. | | | |
|  | Integration capabilities | Ease of integrating with CRIS systems, identity providers (ORCID, LDAP), or workflow tools. | | | |
|  | Standards compliance | Compliance with data exchange standards (OAI-PMH, SWORD, FAIR principles). | | | |
|  | Data import/export | Supported formats, batch import/export options, preservation formats. | | | |
| **5. Extensibility & Maintenance** | Installation complexity | Evaluate steps, documentation quality, and technical expertise required. | | | |
|  | Configuration | Flexibility and difficulty of configuring appearance, workflows, and metadata. | | | |
|  | Monitoring | Built-in or external monitoring/logging support for performance and errors. | | | |
|  | Documentation (technical) | Clarity and completeness of system administration and API documentation. | | | |
|  | Design flexibility | Modular architecture, ability to add or remove components. | | | |
|  | Developer friendliness | Ease of customization and code extensibility (framework, documentation, APIs). | | | |
|  | Extension/adaptation | Support for plugins, themes, modules, or custom workflows. | | | |
| **6. Governance & Compliance** | Version and provenance control | Provenance tracking for data and metadata changes. | | | |
|  | Auditing | Logging of user actions, administrative changes, and compliance events. | | | |
|  | Policy enforcement | Mechanisms to enforce retention, embargo, or sharing policies. | | | |
|  | FAIR reporting | Built-in tools or reports showing FAIR compliance metrics. | | | |
| **7. Adoption & Integration** | Institutional adoption | Evidence of adoption across research institutions or universities. | | | |
|  | Domain adoption | Number and diversity of scientific domains actively using the platform. | | | |
|  | Ease of domain adaptation | Ease of customizing platform for specific disciplines or data types. | | | |
|  | Community trust & maturity | Longevity, governance transparency, reputation within the RDM community. | | | |
| **8. Community & Sustainability** | Deployment model | Supported deployment types (cloud, on-premises, hybrid, containerized). | | | |
|  | Open-source licensing | License type, openness of development, IP restrictions. | | | |
|  | Active development | Release cycle, commit frequency, responsiveness to issues. | | | |
|  | Community support | Forum, mailing list, issue tracker activity, response rate. | | | |
|  | Sustainability & roadmap | Clarity of roadmap, funding model, long-term governance. | | | |

---

##How to Use This Checklist

1. **Assign Weight (1–5)**  
   Rate importance of each sub-criterion for your institution or use case (1 = low, 5 = critical).  

2. **Assign Score (1–5)**  
   Rate how well the evaluated repository meets the criterion (1 = poor, 5 = excellent).  

3. **Compute Weighted Score (optional)**  
   Multiply *Weight × Score* to compare across tools.

4. **Aggregate by Dimension**  
   Sum weighted scores to assess overall strengths and weaknesses by category.

5. **Document Evidence**  
   Record screenshots, URLs, or documentation references in the *Notes / Evidence* column.

---
**Version:** 1.0  
**Author:** [Hajira Jabeen]  
**License:** CC-BY 4.0
