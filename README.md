---
# MIOP terms
methodology_category: sample extraction and purification
project: Experiment comparing the efficacy of various filters in eDNA sampling. DNA extracted in a time series to evaluate potential DNA degredation over time and compare biodiversity
purpose: protocol optimization objective [OBI:0000186] 
analyses: DNA extraction [OBI:0000257]
geographic_location: # Atlantic Ocean [GAZ:00000344]
broad_scale_environmental_context: # marine biome [ENVO:00000447], marine photic zone [ENVO:00000209]
local_environmental_context: # marine biome [ENVO:00000447], marine photic zone [ENVO:00000209], coastal ocean water [ENVO:01001966]
environmental_medium: # sea water [ENVO:00002149], coastal ocean water [ENVO:01001966]
target: deoxyribonucleic acid (DNA) [NCIT:C449]
creator: # Emily Salonia
materials_required: # vortexer [OBI:0400118], centrifuge [OBI:0400106], pipettes [OBI:0002488], Qiagen DNeasy PowerWater Kit, Qubit dsDNA Quantification High Sensitivity Assay Kit, forceps, incubator [OBI:0000136], fluorometer [OBI:0400143]
skills_required: sterile technique, pipetting skills, standard molecular technique
time_required: # 120 minutes (integer)
personnel_required: 1
language: en
issued: # 2025-03-17
audience: scientists
publisher: # NOAA NMFS NEFSC Milford Laboratory
hasVersion: 1
license: CC0 1.0 Universal
maturity level: mature

# FAIRe terms
samp_vol_we_dna_ext: # 100
samp_vol_we_dna_ext_unit: # uL
nucl_acid_ext_lysis: # physical, chemical
nucl_acid_ext_sep: # centrifugation, spin column
nucl_acid_ext: # https://www.qiagen.com/us/resources/resourcedetail?id=58f43d7e-172a-4970-84f0-9cb335a8d262&lang=en
nucl_acid_ext_kit: # Qiagen DNeasy PowerWater Kit
nucl_acid_ext_modify: # not applicable
dna_cleanup_0_1: # not applicable
dna_cleanup_method: # not applicable
concentration: # not applicable
concentration_method: # Invitrogen Qubit Fluorometer, Invitrogen Qubit dsDNA High Sensitivity Assay Kit
ratioOfAbsorbance260_280: # not applicable
pool_dna_num: # not applicable
nucl_acid_ext_method_additional: # not applicable
---

# Protocol Template - DNA Extraction

## PROTOCOL INFORMATION

### Minimum Information about an Omics Protocol (MIOP)
### MIOP terms
-  methodology_category: sample extraction and purification
- project: Experiment comparing the efficacy of various filters in eDNA sampling. DNA extracted in a time series to evaluate potential DNA degredation over time and compare biodiversity
- purpose: protocol optimization objective [OBI:0000186] 
- analyses: DNA extraction [OBI:0000257]
- geographic_location: # Atlantic Ocean [GAZ:00000344]
- broad_scale_environmental_context: # marine biome [ENVO:00000447], marine photic zone [ENVO:00000209]
- local_environmental_context: # marine biome [ENVO:00000447], marine photic zone [ENVO:00000209], coastal ocean water [ENVO:01001966]
- environmental_medium: # sea water [ENVO:00002149], coastal ocean water [ENVO:01001966]
- target: deoxyribonucleic acid (DNA) [NCIT:C449]
- creator: # Emily Salonia
- materials_required: # vortexer [OBI:0400118], centrifuge [OBI:0400106], pipettes [OBI:0002488], Qiagen DNeasy PowerWater Kit, Qubit dsDNA Quantification High Sensitivity Assay Kit, forceps, incubator [OBI:0000136], fluorometer [OBI:0400143]
- skills_required: sterile technique, pipetting skills, standard molecular technique
- time_required: # 120 minutes (integer)
- personnel_required: 1
- language: en
- issued: # 2025-03-17
- audience: scientists
- publisher: # NOAA NMFS NEFSC Milford Laboratory
- hasVersion: 1
- license: CC0 1.0 Universal
- maturity level: mature
### Making eDNA FAIR (FAIRe)

- samp_vol_we_dna_ext: # 100
- samp_vol_we_dna_ext_unit: # uL
- nucl_acid_ext_lysis: # physical, chemical
- nucl_acid_ext_sep: # centrifugation, spin column
- nucl_acid_ext: # https://www.qiagen.com/us/resources/resourcedetail?id=58f43d7e-172a-4970-84f0-9cb335a8d262&lang=en
- nucl_acid_ext_kit: # Qiagen DNeasy PowerWater Kit
- nucl_acid_ext_modify: # not applicable
- dna_cleanup_0_1: # not applicable
- dna_cleanup_method: # not applicable
- concentration: # not applicable
- concentration_method: # Invitrogen Qubit Fluorometer, Invitrogen Qubit dsDNA High Sensitivity Assay Kit
- ratioOfAbsorbance260_280: # not applicable
- pool_dna_num: # not applicable
- nucl_acid_ext_method_additional: # not applicable
---

### Authors


| PREPARED BY  | AFFILIATION  | ORCID        | DATE       |
| ------------ | ------------ | ------------ | ---------- |
| Emily Salonia| NOAA Affiliate |0009-0007-0898-3776 | 2025-03-17 |


|

## BACKGROUND

This document describes the required protocol to conduct DNA extraction.

### Summary

This protocol is used to extract DNA from filtered coastal ocean water [ENVO:01001966]. 

### Method Description and Rationale

This DNA extraction method works by first using cell lysis through a lysing reagent and mechanical beating on the vortex to break cell walls and release the DNA. Then a reagent is added to remove inhibitors, and next a salt solution is added to help bind DNA to a spin column. Wash solutions are added to improve the purity of the DNA extract. An elution buffer is added and centrifugation occurs to release the DNA from the spin column.

This kit and procedure were selected because they were designed for use with filtered water samples. 

### Spatial Coverage and Environment(s) of Relevance
Coastal ocean water [ENVO:01001966]
Sea water [ENVO:00002149]
Marine photic zone [ENVO:00000209]
Marine Biome [ENVO:00000447]
Atlantic Ocean [GAZ:00000344]


## PERSONNEL REQUIRED

1


### Safety
Gloves are required for this procedure. This kit contains chemicals that are irritants. Safety goggles should be worn when diluting bleach or ethanol.  Chemical safety training is reccomended. 


### Training Requirements

General knowledge of molecular best practices is required for this procedure. Chemical safety training is reccomended. 

### Time Needed to Execute the Procedure

210 minutes

## EQUIPMENT




| DESCRIPTION                           | PRODUCT NAME AND MODEL                                                                                                                                  | MANUFACTURER                    | QUANTITY                                                                | REMARK                                                                                                                      |
| ------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------- | ----------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------- |
| **Durable equipment**                 |                                                                                                                                                         |                                 |                                                                         |                                                                                                                             |
| Forceps                               | Filter forceps, blunt end, stainless steel                                                                                                              | Millipore Sigma                 | 1                                                                       |                                                                                                                             |
| Tube Rack for 2 mL tubes              |                                                                                                                                                         |                                 | 1                                                                       |                                                                                                                             |
| Vortex                                | Vortex-Genie 2 Vortex                                                                                                                                   | Scientific Industries Inc       | 1                                                                       | Use with 5 mL tube adaptor                                                                                                  |
| 5 mL tube vortex adaptor              | Vortex Adapter for 6 (5 - 15 ml) tubes, 13000-V1-5                                                                                                      | Qiagen                          | 1                                                                       | Use on Vortex                                                                                                               |
| Mini vortex                           | Vornado BV101 Mini Vortex Mixer                                                                                                                         | Benchmark Scientific            | 1                                                                       |                                                                                                                             |
| 0.5 - 10 uL pipette                   | Research plus 0.5-10 uL pipette                                                                                                                         | Eppendorf                       | 1                                                                       | Sterilize Before Use                                                                                                        |
| 2-20 uL pipette                       | Research plus 2-20 uL pipette                                                                                                                           | Eppendorf                       | 1                                                                       | Sterilize Before Use                                                                                                        |
| 20-200 uL Pipette                     | Research plus 20-200 uL pipette                                                                                                                         | Eppendorf                       | 1                                                                       | Sterilize before use.                                                                                                       |
| 100-1000 uL Pipette                   | Research plus 100-1000 uL Pipette                                                                                                                       | Eppendorf                       | 1                                                                       | Sterilize before use.                                                                                                       |
| Pipette UV Sterilizer                 | nUVaClean UV Pipette Sterilizer                                                                                                                         | MTC Bio                         | 1                                                                       |                                                                                                                             |
| Centrifuge                            | Centrifuge 5430 R                                                                                                                                       | Eppendorf                       | 1                                                                       | Used with 2 mL tubes and spin columns                                                                                       |
| Centrifuge                            | accuSpin 8C Clinical Centrifuge                                                                                                                         | Fisher Scientific               | 1                                                                       | Used with 5 mL tubes                                                                                                        |
| Mini Centrifuge                       | MyFuge, Model C1012                                                                                                                                     | Benchmark Scientific            | 1                                                                       | For use centrigufing DNA extracts before performing quality control procedure                                               |
| Fluorometer                           | Qubit 3 Fluorometer                                                                                                                                     | Invitrogen                      | 1                                                                       | Used in Quality Control Procedure                                                                                           |
| Frozen tube rack for 2 mL tubes       |                                                                                                                                                         |                                 | 1                                                                       | Stored in -20C freezer before use                                                                                           |
| Incubator                             | Incu-Shaker Mini                                                                                                                                        | Benchmark Scientific            | 1                                                                       | Set at 55C to heat PW1 Solution before use.                                                                                 |
| **Consumable equipment**              |                                                                                                                                                         |                                 |                                                                         |                                                                                                                             |
| 1000 uL Pipette Tips                  | Fisher Sure One Sterile Filtered Pipette Tips, 1000 uL                                                                                                  | Fisher Scientific               | 9 tips per sample for Extraction plus 1 for  DNA Quantification         | Must be sterile                                                                                                             |
| 200 uL Pipette Tips                   | Fisher Sure One Sterile Filtered Pipette Tips, 200 uL                                                                                                   | Fisher Scientific               | 2 per sample for DNA Extraction, 1 tip per sampe for DNA Quantification | Must be sterile                                                                                                             |
| 20 uL Pipette Tips                    | Fisher Sure One Sterile Filtered Pipette Tips, 20 uL                                                                                                    | Fisher Scientific               | 3 tips                                                                  | Must be sterile                                                                                                             |
| 10 uL Pipette Tips                    | Fisher Sure One Sterile Filtered Pipette Tips, 10 uL                                                                                                    | Fisher Scientific               | 1 tip per sample                                                        | Must be sterile                                                                                                             |
| Delicate Task Wipes                   | Kimwipes                                                                                                                                                | KimTech, Kimberly-Clark         | 1 per sample                                                            |                                                                                                                             |
| 2 mL Collection Tubes                 | 2 mL collection tubes included in DNeasy PowerWater kit                                                                                                 | Qiagen                          | 5 tubes per sample                                                      |                                                                                                                             |
| Spin column                           | MB spin column, included in DNeasy PowerWater kit                                                                                                       | Qiagen                          | 1 per sample                                                            |                                                                                                                             |
| 5 mL tube with sterile beads          | PowerWater Bead Pro Tubes                                                                                                                               | Qiagen                          | 1 per sample                                                            |                                                                                                                             |
| 5.0 mL tubes                          | Eppendorf Tubes 5.0 mL                                                                                                                                  | Eppendorf                       | 1                                                                       |                                                                                                                             |
| 0.5 mL PCR tubes                      | PCR tubes, 0.5 mL, thin wall, clear, flat cap                                                                                                           | Axygen                          | 1 per sample                                                            | Used in DNA Quantification procedure                                                                                        |
| Qubit High Sensitivity Buffer         | Qubit™ dsDNA HS Assay Kit                                                                                                                               | Invitrogen                      | 200 uL per sample                                                       | Included in Qubit dsDNA Quantitation High Sensitivity Assay Kit                                                             |
| Qubit High Sensitivity Standard 1     | Qubit dsDNA HS Standard #1                                                                                                                              | Invitrogen                      | 10 uL                                                                   | Included in Qubit dsDNA Quantitation High Sensitivity Assay Kit                                                             |
| Qubit High Sensitivity Standard 2     | Qubit® dsDNA HS Standard #2                                                                                                                             | Invitrogen                      | 10 uL                                                                   | Included in Qubit dsDNA Quantitation High Sensitivity Assay Kit                                                             |
| Aluminum Foil                         | Foodservice Foil, Standard 12" x 1000'                                                                                                                  | Durable Packaging International | Dependent on user                                                       |                                                                                                                             |
| Nitrile Gloves                        | UltraSOFT 5000TM Nitrile Gloves, Powder-Free                                                                                                            | Alkali Scientific               | Dependent on number of samples and user                                 |                                                                                                                             |
| **Chemicals**                         |                                                                                                                                                         |                                 |                                                                         |                                                                                                                             |
| Solution PW1                          | Guanidinium thiocyanate solution, Less than 10% concentration (exact concentration not disclosed  by manufacturer)                                      | Qiagen                          | 1 mL per sample                                                         | Hazards: H315 Causes skin irritation, H319 Causes serious eye irritation                                                    |
| Solution PW3                          | 30-50% guanidinium thiocyanate (exact concentration not disclosed by manufacturer), 30-50% ethanol  (exact concentration not disclosed by manufacturer) | Qiagen                          | 650 uL per sample                                                       | Hazards: H225 Highly flammable liquid and vapor, H302 Harmful if swallowed, H314 Causes severe skin burns and eye damage    |
| Solution PW4                          | 50-70% isopropanol (exact concentration not disclosed by manufacturer)                                                                                  | Qiagen                          | 650 uL per sample                                                       | Hazards: H225 Highly flammable liquid and vapor, H319 Causes serious eye irritation, H336 May cause drowsiness or dizziness |
| Solution EB                           | Elution Buffer (exact composition not disclosed by manufacturer)                                                                                        | Qiagen                          | 100 uL per sample                                                       | Not a hazardous substance                                                                                                   |
| Solution IRS                          | Less than 10% AAS-12, (exact concentration not disclosed by manufacturer)                                                                               | Qiagen                          | 200 uL per sample                                                       | Not a hazardous substance                                                                                                   |
| Qubit Dye for High Sensitivity  Assay | Qubit dsDNA HS  Reagent, 200X concentrate in dimethylsulfoxide                                                                                          | Invitrogen                      | 1 uL per sampe                                                          | Hazards: Flammable liquid                                                                                                   |
| Ethanol                               | 90-100% ethanol (exact concentration not disclosed by manufacturer)                                                                                     | Qiagen                          | 650 uL per sample                                                       | Used in extraction protocol,  Hazards:  H225 Hiughly flammable liquid and vapor, H319 Causes serious eye irritation         |
| Ethanol                               | EtOH                                                                                                                                                    | 70%                             | Dependant on user                                                       | Used for sterilization procedure, Hazards: H225 Hiughly flammable liquid and vapor, H319 Causes serious eye irritation      |
| Bleach                                | Sodium Hypochlorite Solution                                                                                                                            | 0.6%                            | Dependent on user and number of samples                                 | Used for sterilization procedure                                                                                            |

## STANDARD OPERATING PROCEDURE


### Preparation

1. First set the incubator to 55&deg;C.
    a. Incu-Shaker Mini is used for this step.
2. Wipe down pipettes with ethanol using a kimwipe.
3. Put pipettes in the UV sterilizer and turn on the UV sterilizer to sterilize the pipettes.
    a. nUVaClean UV Pipette Sterilizer is used for this step. 
4. Spray benchtop with bleach solution, let sit for 3 minutes, and then wipe the benchtop dry with a paper towel.
5. Sterilize forceps with bleach solution and wipe clean. 
6. Wait 5 minutes and then spray the benchtop with 70% ethanol. Wipe down the benchtop with a paper towel.
7. Once the incubator reaches 55&deg;C, place the PW1 solution into the incubator and allow it to heat at 55&deg;C for 5-10 minutes. 
8. Check to see if Solution PW3 has precipitated. If PW3 has precipitated place it in the incubator set at 55&deg;C for 5-10 minutes.
9. Prelabel the collection tubes with sample IDS prior to extraction for convenience during the extraction procedure. 

### Extraction
The following procedure is a modified version of the Qiagen DNeasy PowerWater Kit (Qiagen, 2022) extraction protocol. 

1. Put on clean gloves, sterilize the forceps with bleach, and then wipe the forceps with ethanol. 
2. Put on clean gloves and using the sterile forceps remove a filter from its filter housing. Loosely role the filter and place the filter inside a correspondingly labeled PowerWater Bead Pro Tube. Repeat this process sterilizing the forceps between each use or getting a new pair of sterilized forceps for each sample. Change gloves before handling each filter. 
3. Add 1 mL of warmed Solution PW1 to each PowerWater Bead Pro Tube.
4. Secure the tube horizontally to a vortex with an adaptor for 5 mL tubes.
    a. Vortex-Genie 2 vortex is used for this step.
5. Vortex at maximum speed for 5 minutes.
6. Centrifuge the tubes at a speed of less than or equal to 4,000 xg for 1 minute.
    a. accuSpin 8C Clinical Centrifuge is used for this step 
7. Transfer the supernatant to a clean 2 mL collection tube. Draw up the the supernatant using a 100-1000 uL pipette by placing the pipette down into the beads. 
   a. Placing the pipette down into the beads is necessary to recover all the supernatant. 
8. Centrifuge at 13,000 xg for 1 minute using centrifuge 5430 R. 
9. Transfer the supernatant to a clean 2 mL collection tube. Be careful to avoid the pellet.
10. Add 200 uL of Solution IRS to each tube with supernatant.
11. Vortex briefly using a mini vortex.
12. Incubate at 2-8&deg;C for 5 minutes.
13. Centrifuge the tubes at 13,000 xg for 1 minute using centrifuge 5430 R. 
14. Transfer the supernatant to a clean 2 mL collection tube. Be careful to avoid the pellet.
15. Add 650 uL of Solution PW3 to each tube with supernatant.
16. Vortex briefly using a mini vortex.
17. Load 650 uL of the supernatant and Solution PW3 mix onto a spin column. Centrifuge at 13,000 xg for 1 minute using centrifuge 5430 R. Discard the flow through. 
   a. repeat until all supernatant has been processed 
18. Place the spin column into a clean 2 mL collection tube
19. Add 650 uL of Solution PW4 to each spin column.
    a. Shake solution PW4 before use.
20. Centrifuge at 13,000 xg for 1 minute using centrifuge 5430 R. Then discard the flow through.
22. Add 650 uL of ethanonl to each spin column.
23. Centrifuge at 13,000 xg for 1 minute using centrifuge 5430 R. Then discard the flow through.
25. Centrifuge at 13,000 xg for 2 minutes using centrifuge 5430 R. Then discard the flow through. 
26. Place the spin column into a clean 2 mL collection tube.
27. Add 100 uL of Solution EB to the center of the white filter membrane.
28. Centrifuge at 13,000 xg for 1 minute using centrifuge 5430 R. 
29. Discard the spin column.
30. Store DNA extract at -20&deg;C.

### Quality Control
DNA quantification is performed using a Qubit fluorometer (Invitrogen) to measure the quantity of DNA in a sample after extraction. This will confirm that there is measurable DNA in the sample. This procedure is based on the Qubit dsDNA Quantification High Sensitivity Assay Kit. 

1. First spray the benchtop with bleach solution. Wait 3 minutes and then wipe away the bleach. 
2. Wait 5 minutes, spray the benchtop with 70% ethanol, and then wipe away the ethanol.
3. Wipe pipettes with ethanol.  Place the pipettes in the UV sterilizer and begin the UV sterilization process.
4. Prelabel the lids of 0.5 mL PCR tubes with sample IDs.
5.  Wrap foil around a 5 mL tube so the buffer-dye mix may be prepared in a tube that is protected from light. 
6.  In the foil wrapped 5 mL tube add [(n+3)x 200] uL of high sensitivity buffer solution, where n is equal to the number of samples. 
7.  In the foil wrapped tube add (n+3) uL of high sensitity dye, where n is equal to the number of samples.
8.  Vortex the buffer-dye mix to using the vortex-genie 2.
9. Flick the tubes containing the DNA extracts to mix and then centrifuge the DNA extracts, using the mini centrifuge.
10.  Place the DNA extracts on a frozen tube rack to keep them cold.
11.  Pipette 10 uL of high sensitivity standard 1 into a 0.5 mL PCR tube using a 2-20 uL pippette. 
12.  Pipette 10 uL of high sensitivity standard 2 to a 0.5 mL PCR tube using a 2-20 uL pipette.
13.  Pipette 2 uL of DNA extract to its corresponding 0.5 uL PCR tube using a 0.5-10 uL pipette. Repeat for all extracts and change pipette tips between every extract.
14.  Pipette 190 uL of buffer-dye mix into the PCR tube with standard 1 using a 20-200 uL pipette. Change pipette tip and repeat for the PCR tube containing standard 2.
15.  Pipette 198 uL of buffer-dye mix into the PCR tubes containing the DNA extract. Repeat for all tubes with DNA extract, and change pipette tips each time. 
16.  Place the tubes in a dark location for 2 minutes. 
17.  While the tubes are in the dark, return the DNA extracts back to the -20&deg;C freezer for storage. 
18.  Measure the DNA concentrations with the Qubit 3 Fluorometer. First read  the standards before reading sample concentration. 
19.  After reading the standards confirm that the original sample volume reads 2 uL, then read the sample concentrations. 
20.  Use a flash drive to transfer the data files from the Qubit Fluorometer to a computer. 
21.  Transfer the  DNA concentrations from the Qubit file into a data sheet. 


### Basic Troubleshooting Guide

- The volume of Solution EB added can be reduced for a more concentrated DNA extract. 

## REFERENCES
Qiagen (2022). DNeasy PowerWater Kit Handbook. 

Invitrogen. Qubit dsDNA HS Assay Kit User Guide. https://assets.thermofisher.com/TFS-Assets/LSG/manuals/Qubit_dsDNA_HS_Assay_UG.pdf