The dataset used here for testing is from the Institute of Marine Research inshore gill- and fyke-net survey conducted in 2025.

The material is from five Baited Remote Underwater Video (BRUV) stations, and was annotated in CVAT (by Gina Brøten) and exported in COCO 1.0 format. Frames for annotations were collected at a framerate of 65 images per hour. The BRUVs were deployed for 75 minutes.

The images are labelled with mutliple identifiers to make analysis later simpler. 
Ex. NO_2025_3007_GarnRuse_Lovund_LO3_RA1_L9_frame_9, is collected in Norway, in 2025 on the 30.07 on the Garn and Ruse Survey, the location name is Lovund, and is station number is LO3, and the BRUV-rig used is L9, and this is video number 9 from the left camera (L9), and is frame number 9. 

The annotations are made in a hierachical manner, where the minimum criteria for identifying an organism is species group, with 8 overall groups: decapods, sharks, gadines, labrids, flounders, pelagic gobies, benthic gobies
and lotids. When species identification was not possible, species were set to group level. Frames containing no target species to annotate were kept and included as empty annotations. For more details about the collection and preparation of this data read the attached thesis. 