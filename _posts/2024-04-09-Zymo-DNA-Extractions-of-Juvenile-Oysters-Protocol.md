---
layout: post
title: Zymo RNA Extractions of Juvenile Oysters Protocol
date: '2024-04-05'
categories: Processing, Protocols
tags: [Crassostrea virginica, oyster, juveniles, RNA, Extractions]
projects: [ASMFC-EOBC]
---

Using [Zymo *Quick*-RNA Miniprep Plus Kit](https://www.zymoresearch.com/products/quick-rna-miniprep-plus-kit)

Extracting RNA from juvenile oyster samples from multi-stressor exposure experiment.

Juveniles were collected individually in 1.5ml tubes, preserved with liquid nitrogen, and stored in -80 freezer until processing. 

This is the general protocol I followed for RNA Extractions adapted from [dual DNA/RNA extraction protcol](https://mguid73.github.io/MEGPuritz_Lab_Notebook/Zymo-DNA_RNA-Extractions-of-Juvenile-Oysters-Protocol/). I typically processed 10-12 samples at a time. 

**Time to Completion: 5-6 hours (includes QC)**

### Prep tubes
Prep and label all tubes for extraction protocol (for each tube type, multiply by number of samples being processed)

|tube                                         |purpose                      |number           |
|---------------------------------------------|-----------------------------|-----------------|
|1.5 mL                                       |homogenization/digest tube   | * (# of samples)|
|1.5 mL                                       |intmed. DNA steps            | * (# of samples)|
|1.5 mL                                       |intmed. RNA steps            | * (# of samples)|
|Yellow spin-column & collection tubes        |Spin-away DNA                | * (# of samples)|
|Green or white spin-column & collection tubes|RNA purification             | * (# of samples)|
|1.5 mL                                       |final RNA sample             | * (# of samples)|

### Homogenization 
- Turn on thermomixer and set to 55 degrees C, speed 1000 rpm
- Pull ***Proteinase K*** out of -20 freezer to warm to room temperature 
- Pull ***DNAse I*** out of -20 freezer to thaw on ice
- In homogenization/digest tubes, add 300 μL of DNA/RNA Shield
- Pull samples out of -80 freezer and put on ice
- Sterilize forceps with 100% EtOH, Type II DI Water, RNAse Zap, and RNAse-free Water
- Sterilize forceps between each sample
- Using forceps, transfer juvenile to 1.5 mL tube with DNA/RNA Shield
- Sterilize cone-shaped dremmel bit with 100% EtOH, Type II DI Water, RNAse Zap, and RNAse-free Water
- Sterilize the dremmel bit between each sample
- Insert dremmel bit into 1.5 mL tube with juvenile and grind up juvenile for ~10 seconds at speed 5
- Add **30 μL** ***PK Digestion Buffer*** to each tube
- Add **15 μL** ***Proteinase K***
- Vortex and spin down
- Incubate in thermomixer at 55 degrees C and 1000 rpm for 30 minutes
- Halfway through incubation, spin down tubes in tabletop centrifuge for 1 minute at 13000 rpm

**During incubation period:**
- *Pull Biotium RNA kit out of fridge/freezer and put in drawer (light sensitive) to warm to room temperature*
- Prep RNAse-free Water for thermomixer
    - 50 μL x # of samples (plus error) in 1.5 mL tubes
    - Put in thermomixer set to 70 degrees C
- Make DNAse reaction mix:
    - DNA Digestion Buffer: 75 μL x # of samples
    - DNAse I: 5 μL x # of samples

**After incubation:**
- Spin down tubes at max speed for 2 minutes in tabletop centrifuge
- Without disturbing the debris pellet, gently transfer all supernatant (~350 μL) to *new 1.5 mL tube for DNA removal* (intmed. DNA steps)
- Save debris pellet and store in -20 freezer (can check for incomplete digestion later on if necessary)
- Add equal volume (300 μL) of ***RNA Lysis Buffer (kit)*** to each tube
- Finger flick to mix
- Transfer all supernatant (~600 μL) to *yellow spin-column*
- Centrigue at 16000 rpm for 30 seconds
- SAVE flow-through in *new 1.5 mL tube for RNA*


#### RNA Purification
- Add equal volume (**600 μL**) ***100% EtOH*** to each *1.5 mL tube for RNA* 
- Transfer **600 μL** of supernatant to *white spin-column* 
- Centrifuge at 16000 rpm for 30 seconds; discard flow-through
- Repeat until all supernatant is filtered (2 times total)
- Add **400 μL** of ***RNA Wash Buffer (kit)*** to *white spin-column*
- Centrifuge at 16000 rpm for 30 seconds; discard flow-through
- Add **80 μL** of ***DNAse reaction mix*** to each column (I add directly onto filter)
- *Incubate at room temperature for 30 minutes* 
- *NOW IS A GOOD TIME TO PULL OUT RNA QUBIT STANDARD AND TAPESTATION SUPPLIES*
- Add **400 μL** of ***RNA Prep Buffer (kit)*** to *white spin-column* 
- Centrifuge at 16000 rpm for 30 seconds; discard flow-through
- Add **700 μL** of ***RNA Wash Buffer (kit)*** 
- Centrifuge at 16000 rpm for 30 seconds; discard flow-through
- Add **400 μL** of ***RNA Wash Buffer (kit)*** 
- Centrifuge at 16000 rpm for **2 minutes**; discard flow-through
- Transfer spin-column to *final RNA 1.5 mL tube*
- Carefully drip **50 μL** of ***warmed RNAse-free Water*** directly onto filter 
- *Incubate at room temperature for 5 minutes*
- Centrifuge at 16000 rpm for 30 seconds and discard spin column
    - KEEP FLOW-THROUGH
- ***Should have 50 μL of RNA***

#### Quality Control Check 

**Qubit**
- RNA concentrations are checked using the Biotium [RNA Broad Range](https://biotium.com/wp-content/uploads/2018/06/PI-31073.pdf) quantitation kits 
- use 1 μL of sample for each of the assays (unless you need to use more)
- Final RNA concentrations (ng/μL) can be accessed [here]()

**TapeStation**
- RNA quality is checked using the [RNA ScreenTape Assay](https://www.agilent.com/cs/library/usermanuals/public/RNA_QuickGuide.pdf)
- Sample TapeStation report can be accessed [here]()