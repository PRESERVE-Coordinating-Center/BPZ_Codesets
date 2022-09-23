# BPZ_Codesets


Codesets utilized for cohort development and analyses for the PRESERVE Blood Pressure Z-Score Working Group

## Cohort Development

A series of inclusion and exclusion criteria were applied to the entire PEDSnet patient population to focus in on a cohort of generally healthy children.

### Medications

At least one exposure to any of the following medications disqualified a patient from the cohort:

  - [Angiotensin-converting enzyme (ACE) Inhibitors](codesets/drug/rx_ace_inhibitor.csv)
  - [Anti-hypertensive medications](codesets/drug/rx_antihtn.csv)
  - [Angiotentin II receptor blockers (ARBs)](codesets/drug/rx_arb.csv)
  - [Beta blockers](codesets/drug/rx_bb.csv)
  - [Calcium channel blockers](codesets/drug/rx_ccb.csv)
  - [Deflazacort (oral)](codesets/drug/rx_deflazacort.csv)
  - [Erythropoiesis-stimulating agents (EPO, DPO)](codesets/drug/rx_EpoetinAlfaDarbepoetin.csv)
  - [Fludrocortisone (oral)](codesets/drug/rx_fludrocortisone.csv)
  - [Loop diuretics](codesets/drug/rx_loop_diuretic.csv)
  - [Steroids](codesets/drug/rx_steroids.csv)
  - [Stimulants](codesets/drug/rx_stimulants.csv)
  - [Calcineurin inhibitors](codesets/drug/rx_tacrolimus_cyclosporine.csv)
  - [Thiazide diuretics](codesets/drug/rx_thiazide.csv)
  
Any blood pressure measurements within 30 days of an outpatient surgery with anesthesia were excluded from analyses. Anesthesia was identified using the following set of medication codes:  

  - [Anesthesia](codesets/drug/rx_anesthesia.csv)
  
  
### Conditions
  
Any patient with a diagnosis of hypertension was excluded from the cohort. Hypertension was defined using the following diagnosis codes:  

  - [Hypertension](codesets/condition/dx_hypertension.csv)
  
Patients with evidence of any chronic condition according to an ICD10 codeset developed for the Pediatric Medical Complexity Algorithm (PMCA) were excluded from the cohort. The PMCA codeset contains flags for the body system impacted and whether the condition is progressive. All patients with any of these diagnoses, regardless of body system or being progressive, were excluded from the cohort:

  - [PMCA Codes](codesets/condition/pmca_icd10.csv)
  
  
### Visits

Patients in the cohort were required to be seen primarily for general pediatric care in outpatient settings. General pedatric care was identified using the following specialty codes:  

  - [General Pediatrics](codesets/visit/spec_gen_peds.csv)
  
