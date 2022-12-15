# Projects

This page lists known community projects related to Clinical Quality Language. If you have a community project, feel free to add it here!

The projects are divided into two broad categories, tooling and content development:

* [Tooling](#tooling): Projects related to implementation of CQF projects (such as translators, engines, publication tooling, etc)
* [Content](#content): Projects that are using CQF-related standards to build content

## Tooling

### CQL-to-ELM Translator and Formatter

* <https://github.com/cqframework/clinical_quality_language>: CQL-to-ELM Translator

### JavaScript Execution Engine

* <https://github.com/cqframework/cql-execution>: Java-Script Execution Engine
* <https://github.com/cqframework/cql-exec-fhir>: A FHIR data source provider for the CQL Execution framework
* <https://github.com/cqframework/cql-exec-vsac>: A VSAC-enabled value set provider for the CQL Execution framework
* <https://github.com/cqframework/cql-exec-examples>: Simple examples demonstrating how to use cql-execution, cql-exec-fhir, and cql-exec-vasc

### CQL Translation Service

* <https://github.com/cqframework/cql-translation-service>: RESTful service for translating CQL to ELM

### Java Execution Engine

* <https://github.com/dbcg/cql_engine>

### CQL-based Capabilities

* <https://www.npmjs.com/package/encender>: JS implementation of $apply
* <https://github.com/dbcg/cql-evaluator>: Java implementation of $cql, $evaluate, $evaluate-measure, and $apply
* <https://github.com/google/android-fhir#workflow-library>: Android FHIR SDK support for $evaluate-measure and $apply

### CQL Execution Service

* <https://github.com/dbcg/cql_execution_service>
* <https://github.com/AHRQ-CDS/AHRQ-CDS-Connect-CQL-SERVICES>: Expose CQL via Custom-API or CDS Hooks interface (built on JavaScript CQL Execution Engine)

### CQL Authoring

* <https://github.com/Path-Check/cql-editor-app>: Android CQL compiler
* <https://github.com/DBCG/cql_runner>: Web-based CQL Authoring
* <https://github.com/cqframework/atom-cql-support>: Atom IDE plugin (deprecated, use the VS Code plugin instead)
* <https://github.com/cqframework/vscode-cql>: VS Code IDE plugin
* <https://sandbox.cqlab.io/>: Web-based CQL and clinical reasoning artifact authoring environment

### CDS Connect

* <https://cds.ahrq.gov/>: Repository of CDS including CQL-based artifacts
* <https://cds.ahrq.gov/authoring/>: CDS Authoring Tool capable of exporting FHIR-based CQL logic
* <https://github.com/AHRQ-CDS/AHRQ-CDS-Connect-Authoring-Tool>: CDS Authoring Tool Source Code

### CQL Testing

* <https://github.com/AHRQ-CDS/CQL-Testing-Framework>

### CQL Server-side Functionality

* <https://github.com/samply/blaze>: A FHIR® server with internal, fast CQL Evaluation Engine
* <https://github.com/dbcg/cqf-ruler>: HAPI FHIR server plugin to enable CQL evaluation and Clinical Reasoning functionality
* <https://github.com/PheMA/cql-on-omop>: Translates CQL (ELM) to OMOP for evaluation against an OHDSI repository
* <https://github.com/DBCG/spark-cql-fhir>: Demonstration of a Spark-CQL pipeline
* <https://github.com/IBM/FHIR>: An open source FHIR server implementation that includes CQL and Clinical Reasoning functionality

### CQL Tooling

* <https://github.com/cqframework/cqf-tooling>: Tooling to support CQL library tooling and other handy utilities related to CQL-based FHIR content
* <https://github.com/projecttacoma/fhir-patient-generator>: Tooling to generate FHIR patients for eCQM testing

## Content

The projects listed here provide a catalog of known CQF-related content development projects. The projects listed here are all independently funded and managed.

### CQF Common

* [CQF Common](http://github.com/cqframework/cqf) - Common CQF Assets (FHIRHelpers, FHIR-ModelInfo, etc) ([published](http://fhir.org/guides/cqf/common))

### Opioid Prescribing Guideline

* [Opioid Milligram Morphine Equivalent Calculator](https://github.com/cqframework/opioid-mme-r4) ([published](http://fhir.org/guides/cdc/opioid-mme-r4))
* [Opioid Prescribing Implementation Guide (STU3)](https://github.com/cqframework/opioid-cds)
* [Opioid Prescribing Implementation Guide (R4)](https://github.com/cqframework/opioid-cds-r4)

### Pain Management Summary

* [AHRQ CDS Connect Pain Management Summary](https://github.com/AHRQ-CDS/AHRQ-CDS-Connect-PAIN-MANAGEMENT-SUMMARY)

### Lung Cancer Screening

* [USPTF Lung Cancer Screening](https://github.com/cqframework/lcs-cds)

### CDS for Chronic Pain Management

* [CDS for Chronic Pain Management IG](https://github.com/cqframework/cds4cpm)
* [Pain Manager (fork of Pain Management Summary)](https://github.com/cqframework/AHRQ-CDS-Connect-PAIN-MANAGEMENT-SUMMARY)
* [MyPAIN Patient Engagement Application](https://github.com/cqframework/cds4cpm-mypain)

### WHO SMART Guidelines

* [WHO Core](https://github.com/WorldHealthOrganization/smart-core)
* [WHO Antenatal Care](https://github.com/WorldHealthOrganization/smart-anc)
* [WHO Family Planning](https://github.com/WorldHealthOrganization/smart-fp)
* [WHO Sexually Transmitted Infections](https://github.com/WorldHealthOrganization/smart-sti)

### Oregon Health Sciences University Hypertension Management

* [Hypertension Management Implementation Guide](https://github.com/OHSUCMP/htnu18ig)
