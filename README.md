# UCSF-MIM Dose Composite Workflow

MIM workflows simplify physical and EQD2 dose composites and reporting are **provided without any support from Evan Porter, UCSF, or MIM Software**. The provided MIM workflows are intended solely as references for workflow design and are not designed for widespread clinical use. Users are fully responsible for testing all functionality prior to clinical implementation. 

Disclaimers:

* These workflows are provided "as is" without any warranties, expressed or implied, including but not limited to the implied warranties of merchantability and fitness for a particular purpose. 	
  
* Neither the creator nor any associated parties are liable for any damages resulting from the use or misuse of the workflows. 	
  
* Users must comply with all applicable laws, regulations, and professional guidelines when utilizing these workflows. 	
  
* Any modifications made by users are their responsibility and may void any implied assurances. 	
    
* By using these workflows, users agree to indemnify and hold harmless the creators from any claims arising from their use or misuse.

# Configuration

## UCSF Dose Composite & EQD2
1. In "UCSF Dose Composite & EQD2" Line 91, Open "Z-Launch Treatment Eval: Registration Loop Optional"
2. In "Z-Launch Treatment Eval: Registration Loop Optional" Line 22, Configure working directory used for EQD2 creation

## UCSF Composite Report ONLY
1. No clinic specific configuration required

# Workflow Optimization
Recommended MIM Software settings to improve performance: 
* Enable Plan Review: **OFF**
* Automatically Generate VMAT DRRs with plan review: **OFF**
  
