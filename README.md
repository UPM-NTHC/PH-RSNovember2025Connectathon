 # Philippine Road Safety FHIR® Connectathon – November 2025, Quezon City, Philippines

![Placeholder PH RS Connectathon Graphic](<graphics/PH Road Safety Connectathon Graphic.png>)

The PH Road Safety Connectathon (17-21 November 2025, Metro Manila) is the final milestone of the SIL-PH project with the Department of Health. This Connectathon is co-organised by DOH and UP NTHC.

Around 60 participants from government, hospitals, EMS, EMR vendors, and partners will test the first Road Safety Minimum Data Set (MDS) and draft FHIR Implementation Guide through scenario-based simulations. 

Output is envisioned to strengthen Universal Health Care and the Philippine Road Safety Action Plan 2023–2028, advancing the DOH 8-Point Action Agenda.

The general objective of this activity is to strengthen capacity for digital health interoperability by combining structured training and a multi-day Connectathon focused on road safety workflows as a proof-of-concept use case.

## Important Information

- [PH Road Safety Connectathon Program (November 17-21, 2025)](insertlinkhere)
- [PH Road Safety Connectathon Logistic Note](insertlinkhere)
- [Draft PH Road Safety FHIR Implementation Guide (IG)](https://build.fhir.org/ig/UPM-NTHC/PH-RoadSafetyIG/)
- [PH Core FHIR Implementation Guide (IG)](https://build.fhir.org/ig/UP-Manila-SILab/ph-core/index.html) 

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
![Use Cases Graphic](<graphics/Use Cases.png>)

| **USE CASE**| **STATION** | **END USER** |
|-----------------|-----------------|----------|
| UC1: Submit Run Report Form to National Health Data Repository (NHDR)/Shared Health Record (SHR) **(POST)** | Transport | EMS |
| UC2: Retrieve data from NHDR/SHR **(GET)** | Facility | Hospital |
| UC3&4: Update & submit data to ONEISS & NHDR/SHR **(PUT & POST)** | Facility | Hospital
| UC5: Retrieve relevant data from NHDR/SHR for agency reports **(GET)** | Post-crash investigation | DPWH/DOTr
| UC6: Retrieve data from NHDR/SHR at patient follow-up **(GET)**| Post-crash investigation | Health centers

## Tracks and Sample Data

- [Use Case #1](use-case-1.md)
- [Use Case #2](use-case-2.md)
- [Use Case #3 and #4](use-case-3-4.md)
- [Use Case #5 and #6](use-case-5-6.md)
- [Postman Collection and Environment](postman-collection)

## FHIR Server available for testing during the Connectathon

 Version | Server | Endpoint
|-------------|---------|-------------|
FHIR R4 | FHIRLab |https://cdr.fhirlab.net/fhir 


Note: FHIR® is a registered trademark of Health Level Seven International.  

For questions and queries regarding the connectathon, please contact amongkeko@up.edu.ph.

