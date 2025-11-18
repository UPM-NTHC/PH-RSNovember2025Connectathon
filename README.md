 # Philippine Road Safety FHIR® Connectathon – November 2025, Quezon City, Philippines

![PH RS Connectathon Graphic](<graphics/ph-road-safety-connectathon-graphic.png>)

The PH Road Safety Connectathon (17-21 November 2025, Metro Manila) is the final milestone of the SIL-PH project with the Department of Health. This Connectathon is co-organized by DOH and UP NTHC.

Around 60 participants from government, hospitals, EMS, EMR vendors, and partners will test the first Road Safety Minimum Data Set (MDS) and draft FHIR Implementation Guide through scenario-based simulations. 
 
Output is envisioned to strengthen Universal Health Care and the Philippine Road Safety Action Plan 2023–2028, advancing the DOH 8-Point Action Agenda.

The general objective of this activity is to strengthen capacity for digital health interoperability by combining structured training and a multi-day Connectathon focused on road safety workflows as a proof-of-concept use case.

## Important Information

- [PH Road Safety Connectathon Program (November 17-21, 2025)](https://docs.google.com/document/d/17hV5Y1cuO2oAOhNZXDmwagq6KVonraf5uqqKZ0h4brU/)
- [PH Road Safety Connectathon Logistic Note](https://docs.google.com/document/d/1lOSJ5Jv6hQK56KHZS7bSjEpVGTeYu5JI3vCzxdb-bdc/)
- [Draft PH Road Safety FHIR Implementation Guide (IG)](https://build.fhir.org/ig/UPM-NTHC/PH-RoadSafetyIG/)
- [Draft PH Core FHIR Implementation Guide (IG)](https://build.fhir.org/ig/UP-Manila-SILab/ph-core/index.html) 

## Specific Objectives 

*Capacity building*

1. Equip IT professionals, decision-makers, and healthcare teams with foundational knowledge of interoperability standards and road safety workflows;
2. Validate training and learning materials (developed by UPCM MIU);

*Interoperability*

3. Test interoperability of systems using the Road Safety MDS across Scene, Transport, Facility, and Post-Crash phases;
4. Validate FHIR profiles, terminology mappings, and workflow simulations in line with WHO SMART Guidelines;
5. Capture and document technical issues, troubleshooting approaches, and lessons learned during hands-on Connectathon tracks;


*Governance*

6. Engage national agencies (DOH, DILG, LTO), hospitals, LGUs, and EMR vendors in governance discussions to generate policy recommendations for national scale-up; and
7. Conduct a formal handover of outputs (e.g., draft FHIR IG) to DOH for long-term adoption.

  
## Use Case Summary (Tracks)
![Use Cases Graphic](<graphics/use-cases-graphic.png>)

| **USE CASE**| **STATION** | **END USER** |
|-----------------|-----------------|----------|
| UC1: Users will submit *RS Case* bundle to Shared Health Record (SHR). **(POST)**  | Transport | EMS |
| 👉 [Click for track details of Use Case #1](use-case-1.md) | |
| UC2: Users will retrieve data bundle from SHR. **(GET)** | Facility | Hospital |
| 👉 [Click for track details of Use Case #2](use-case-2.md) | |
| UC3: Users will submit *RS Case* bundle to SHR. **(POST)** | Facility | Hospital |
| 👉 [Click for track details of Use Case #3](use-case-3.md) | |
| UC4: Users will retrieve relevant data from SHR for agency reports. **(GET)** | Post-incident investigation | Government agency
| 👉 [Click for track details of Use Case #4](use-case-4.md) | |
| UC5: Users will retrieve data for follow up and submit to SHR. **(GET & POST)** | Post-incident investigation | Health center
| 👉 [Click for track details of Use Case #5](use-case-5.md) | |

## Postman Collection and Environment

To help participants get started, we have prepared a Postman collection, environment, and example data for each use case. These include:

- Expanding valuesets
- Validating resources
- Submitting transaction bundles
- Retrieving resources

👉 [Click for the link to the Postman Collection and Environment](./postman/) 

## FHIR Server available for testing during the Connectathon

 Version | Server | Endpoint
|-------------|---------|-------------|
FHIR R4 | FHIRLab |https://cdr.fhirlab.net/fhir 

## Supplementary information
### International semantic and sytactic standards
- [OpenHIE Architecture](https://ohie.org/architecture-specification/)
- [HL7 FHIR](https://www.fhir.org/)
    - How to submit basic FHIR resources
    - How to submit FHIR resources with Profiles from a FHIR Implementation Guide
    - How to retrieve and $expand ValueSets
    > Note: FHIR R4 will be used in alignment with national digital health initiatives.
- [SNOMED CT](https://www.snomed.org/what-is-snomed-ct)
- [ICD-10](https://icd.who.int/browse10/2019/en)
- [LOINC](https://loinc.org/)

### FHIRLab (https://fhirlab.net) 
- [FHIR Server - `Hapi FHIR Endpoint`](https://cdr.fhirlab.net/fhir)
- [Terminology Server - `Ontoserver Endpoint`](https://tx.fhirlab.net/fhir)
- [Terminology Server - `Ontoserver w/ Shrimp as viewer`](https://ontoserver.csiro.au/shrimp/)

> Note: FHIR® Lab is part of The Strengthening Standards Capability Project (SSCP), co-funded by CSIRO Australia and Australian Government, Department of Foreign Affairs and Trade. 

---

FHIR® is a registered trademark of Health Level Seven International. 

For questions and queries regarding the connectathon, please contact nih-nthc.upmanila@up.edu.ph.

