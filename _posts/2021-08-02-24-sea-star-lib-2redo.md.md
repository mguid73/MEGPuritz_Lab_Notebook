---
layout: post
title: "22 Sea Star WGS Library Preps and 2 Redos"
tags: [ DNA, Sea Stars ]
---

# DNA Library Prep on 24 Sea Stars (2 Redos) With 2.5 Min Sonication with 500ng, 100ng Going into DNA Prep

*Copied from Maggie Schedl's Notebook* [Link to Original](https://meschedl.github.io/MES_Puritz_Lab_Notebook/2021-08-02/24-sea-star-lib-2redo)
**Using 1/4th reactions of the [KAPA HyperPrep DNA Library Prep Kit](https://sequencing.roche.com/en-us/products-solutions/by-category/library-preparation/dna-library-preparation/kapa-hyperprep.html)**

### Sonication

- Prepared 500ng of each sample in 80ul of 10mM tris HCL
- **Only 22 samples for sonication, libraries 29 and 43 were either already sonicated or already prepped**

| Sample    | Library Number | 500ng | ul 10mM Tris HCl to 80ul |
|-----------|----------------|-------|--------------------------|
| CPDB 004  | 25             | 14.2  | 65.8                     |
| CPAB2 010 | 26             | 19.8  | 60.2                     |
| CHSB 008  | 27             | 18.1  | 61.9                     |
| CPBP-008  | 28             | 17.7  | 62.3                     |
| CPBO 007  | 30             | 21.8  | 58.2                     |
| CHSY-007  | 31             | 26.3  | 53.7                     |
| CHSB 002  | 32             | 11.0  | 69.0                     |
| CHSY 004  | 33             | 12.5  | 67.5                     |
| CHSB 010  | 34             | 33.3  | 46.7                     |
| CHSY 005  | 35             | 24.3  | 55.7                     |
| CPAB 007  | 36             | 14.7  | 65.3                     |
| CHSB 007  | 37             | 23.8  | 56.2                     |
| CPBP 005  | 38             | 12.5  | 67.5                     |
| CPBO 002  | 39             | 20.1  | 59.9                     |
| CPBP 003  | 40             | 16.8  | 63.2                     |
| CHSB 005  | 41             | 33.1  | 46.9                     |
| CPDB 006  | 42             | 16.9  | 63.1                     |
| CPOI 001  | 44             | 18.7  | 61.3                     |
| CHSB 006  | 45             | 23.7  | 56.3                     |
| CHSY 001  | 46             | 27.6  | 52.4                     |
| CPDB-008  | 47             | 31.8  | 48.2                     |
| CPAB 010  | 48             | 18.7  | 61.3                     |

- Ran sonicator for 2.5 minutes at 25% amplitude, 15 seconds on 15 seconds off. Samples were spun down after 1.25 minutes ([general sonicator protocol](https://github.com/meschedl/PPP-Lab-Resources/blob/master/Protocols_and_Lab_Resources/QSonica-General-Protocol.md))
- 1X bead clean after sonication, followed [protocol](https://github.com/meschedl/PPP-Lab-Resources/blob/master/Protocols_and_Lab_Resources/Bead-cleanup-1-1.8X.md)
- Samples were re-suspended in 62.5ul 10mM tris HCl, this is 5*12.5, which is the input volume to the kit. I was then able to take 12.5ul from each sonicated sample and that should be ~100ng

**Samples 14 and 43 are Redos and have already been sonicated**

### End Repair and A-tailing

- Prepared end repair and a-tailing master mix on ice:
  - ERAT buffer 1.75μl * 25 = 43.75μl
  - ERAT enzyme 0.75μl * 25 = 18.75μl
- Made 24 PCR strip tubes each with 12.5μl of 100ng sheared DNA
- Added 2.5μl of ERAT master mix to each sample
- Vortexed and spun down
- Placed samples in thermocyler A-tailing program in JONP login (~ 1 hour)

### Adapter Ligation

- Prepared ligation master mix on ice (**no vortexing of the ligase**):
  - ligation buffer 7.5μl * 25 = 187.5μl
  - DNA ligase 2.5μl * 25 = 62.5μl
  - nuclease free water 1.25μl * 25 = 31.25μl
- Added 11.25ul ligation master mix to each sample.  
- Added 1.25ul of planned adapter to each sample (see below). Adapters were added last to minimize adapter-adapter ligation
- **Note here that library 30 got adapter 5, when it was supposed to get 6. Library 29 also has adapter 5. This was noticed and library 30 was given a different index pair**

| Sample    | Library Number | Adapter Number |
|-----------|----------------|----------------|
| CPDB 004  | 25             | 1              |
| CPAB2 010 | 26             | 2              |
| CHSB 008  | 27             | 3              |
| CPBP-008  | 28             | 4              |
| CPBO 007  | 30             | 5              |
| CHSY-007  | 31             | 6              |
| CHSB 002  | 32             | 8              |
| CHSY 004  | 33             | 9              |
| CHSB 010  | 34             | 10             |
| CHSY 005  | 35             | 11             |
| CPAB 007  | 36             | 12             |
| CHSB 007  | 37             | 1              |
| CPBP 005  | 38             | 2              |
| CPBO 002  | 39             | 3              |
| CPBP 003  | 40             | 4              |
| CHSB 005  | 41             | 5              |
| CPDB 006  | 42             | 6              |
| CPOI 001  | 44             | 8              |
| CHSB 006  | 45             | 9              |
| CHSY 001  | 46             | 10             |
| CPDB-008  | 47             | 11             |
| CPAB 010  | 48             | 12             |
| CPBO 008  | 14             | 2              |
| CPBP 009  | 43             | 7              |

- Pipetted all samples up and down with the multichannel and spun down
- Incubated on the shaker at room temp for 1-2 hours at 200rpm

### 0.8X Cleanup

- Made fresh 80% EtOH
- Took KAPA Pure Beads out of fridge beforehand to warm to room temp
- After incubation at RT, added 22μl of KAPA pure beads to each sample and pipetted up and down at least 10 times to mix beads careful to avoid bubbles
- Placed tubes on shaker at room temp for 15 minutes
- Placed tubes on magnet plate and removed supernatant from tubes when it was fully clear not disturbing the beads
- Added 200μl of 80% EtOH to each tube while still the magnet not disturbing the beads
- Removed supernatant from each tube on the magnet plate without disturbing the beads
- Added 200μl of 80% EtOH to each tube while still the magnet not disturbing the beads
- Removed ALL the supernatant from each tube on the magnet plate without disturbing the beads. Extra EtOH blobs were removed with p20 pipette tips
- Resuspended beads in 6μl 10mM Tris HCl pH 8 and incubated tubes on shaker for 5 minutes
- Placed tubes back onto the magnet stand and removed 5ul supernatant when clear to new labeled PCR strip tubes

### Library Amplification

- Made 2 master mixes for the two sets of index pairs
- MM 4, library numbers 25-36 **but not 30**
  - 6.25 KAPA HiFi * 13 = 81.25ul
  - 0.75ul 502 20uM primer * 13 = 9.75ul
  - 0,75ul 702 20uM primer * 13 = 9.75ul
- MM 5, library numbers 37-48, **including redo 43**
  - 6.25 KAPA HiFi * 13 = 81.25ul
  - 0.75ul 503 20uM primer * 13 = 9.75ul
  - 0,75ul 703 20uM primer * 13 = 9.75ul
- Vortexed and spun down mixes and kept on ice
- Added 7.5ul of the appropriate mix to the strip tubes with the 5ul sample
- Added 6.25ul KAPA HiFi to libraries 14 and 30
- Added 0.75ul 503 and 0.75ul 703 to 14
- Added 0.75ul 512 and 0.75ul 712 to 30
- Vortexed and spun down samples
- Placed in the thermocyler Genomic PCR 6 program

### 2 1X Cleanups

- After PCR, added 12.5μl of KAPA pure beads to each sample and pipetted up and down at least 10 times to mix beads careful to avoid bubbles
- Placed tubes on shaker at room temp for 15 minutes
- Placed tubes on magnet plate and removed supernatant from tubes when it was fully clear not disturbing the beads
- Added 200μl of 80% EtOH to each tube while still the magnet not disturbing the beads
- Removed supernatant from each tube on the magnet plate without disturbing the beads
- Added 200μl of 80% EtOH to each tube while still the magnet not disturbing the beads
- Removed ALL the supernatant from each tube on the magnet plate without disturbing the beads. Extra EtOH blobs were removed with p20 pipette tips
- Resuspended beads in 13μl 10mM Tris HCl pH 8 and incubated tubes on shaker for 5 minutes
- Placed tubes back onto the magnet stand and removed 12.5ul supernatant when clear to new labeled PCR strip tubes
- Added 12.5μl of KAPA pure beads to each sample and pipetted up and down at least 10 times to mix beads careful to avoid bubbles
- Placed tubes on shaker at room temp for 15 minutes
- Placed tubes on magnet plate and removed supernatant from tubes when it was fully clear not disturbing the beads
- Added 200μl of 80% EtOH to each tube while still the magnet not disturbing the beads
- Removed supernatant from each tube on the magnet plate without disturbing the beads
- Added 200μl of 80% EtOH to each tube while still the magnet not disturbing the beads
- Removed ALL the supernatant from each tube on the magnet plate without disturbing the beads. Extra EtOH blobs were removed with p20 pipette tips
- Resuspended beads in 16μl 10mM Tris HCl pH 8 and incubated tubes on shaker for 5 minutes
- Placed tubes back onto the magnet stand and removed 15ul supernatant when clear to new labeled PCR strip tubes

### QC

- Followed [Qubit protocol for BR DNA](https://meschedl.github.io/MESPutnam_Open_Lab_Notebook/Qubit-Protocol/)

| Sample    | Library Number | Library concentration ng/ul |
|-----------|----------------|-----------------------------|
| CPDB 004  | 25             | 30.6                        |
| CPAB2 010 | 26             | 45.8                        |
| CHSB 008  | 27             | 34.8                        |
| CPBP-008  | 28             | 42.4                        |
| CPBO 007  | 30             | 35.4                        |
| CHSY-007  | 31             | 43.6                        |
| CHSB 002  | 32             | 37                          |
| CHSY 004  | 33             | 20.8                        |
| CHSB 010  | 34             | 10.9                        |
| CHSY 005  | 35             | 35.6                        |
| CPAB 007  | 36             | 32.6                        |
| CHSB 007  | 37             | 18.1                        |
| CPBP 005  | 38             | 40.4                        |
| CPBO 002  | 39             | 41.6                        |
| CPBP 003  | 40             | 31.2                        |
| CHSB 005  | 41             | 38.4                        |
| CPDB 006  | 42             | 24.8                        |
| CPOI 001  | 44             | 27                          |
| CHSB 006  | 45             | 11.4                        |
| CHSY 001  | 46             | 33.8                        |
| CPDB-008  | 47             | 42                          |
| CPAB 010  | 48             | 36                          |
| CPBO 008  | 14             | 2.4                         |
| CPBP 009  | 43             | 39.8                        |

- D1000 TapeStation, 11 samples, also tapestationing libraries 2 and 50, after their second cleanup to see if the small peak at ~160bp went away
  - See [report here](https://github.com/meschedl/MES_Puritz_Lab_Notebook/blob/master/tapetstations/2021-08-02%20-%2018.02.36.pdf)
  - Looks like after 2 bead cleanups at the end, there is no more peak at ~160
  - Looks like 34, 37, and 45 need to be re-done

