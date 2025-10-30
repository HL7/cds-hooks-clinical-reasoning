### Introduction

This implementation guide provides conformance criteria and guidance for using CDS Hooks with FHIR. The IG describes logical models for representing CDS Hooks constructs, mappings from those constructs to FHIR resources, as well as how CDS Hooks can be used to surface FHIR Clinical Reasoning services.

The content in this implementation guide was originally published in the Decision Support Services topic of the FHIR Clinical Reasoning module. It has been moved to this implementation guide to allow focused definition of and guidance for the use of CDS Hooks with FHIR generally, as well as the use of FHIR Clinical Reasoning services with CDS Hooks.

### Scope of Use

CDS Hooks is an open source specification focused on user-facing remote clinical decision support. CDS Hooks uses FHIR to represent patient information and recommendations, but is architecturally an independent specification. This implementation guide provides resources for using CDS Hooks with FHIR Clinical Reasoning, including:

* Logical models representing CDS Hooks specification constructions (including request, response, and discovery)
* FHIR Profiles for using GuidanceResponse, RequestOrchestration, and PlanDefinition resources with CDS Hooks
* Guidance on how to use CDS Hooks with FHIR generally
* Guidance on how to expose FHIR Clinical Reasoning services using CDS Hooks
* Guidance on how to make use of FHIR within agentic AI workflows

TODO:

https://build.fhir.org/clinicalreasoning-cds-on-fhir.html (including profiles referenced on this page)
https://build.fhir.org/ig/FHIR/fhir-tools-ig/artifacts.html#1

### How to Read This Guide

This Guide is divided into several pages which are listed at the top of each page in the menu bar:

* **[Home](index.html)**
* **[Background](background.html)**
* **[Specification](specification.html)**
* **[FHIR Artifacts](artifacts.html)**
* **[Examples](examples.html)**
* **Support**
  * **[Downloads](downloads.html)**
  * **[License](license.html)**
* **[Changes](changes.html)**

### Roadmap

This implementation guide is intended to be balloted in the May 2026 (the content will need to be removed from the base FHIR specification ahead of the November 1st 2025 deadline, so we expect at least draft content to be available alongside the January 2026 FHIR ballot). In addition, we will reference this implementation guide from the Clinical Reasoning CDS topic

### Dependencies

{% lang-fragment dependency-table-short.xhtml %}

### Cross Version Analysis

{% lang-fragment cross-version-analysis.xhtml %}

### Global Profiles

{% lang-fragment globals-table.xhtml %}

### IP Statements

{% lang-fragment ip-statements.xhtml %}