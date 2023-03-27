# Data_Visualization-Challenge

In the following Challenge we are analyzing data from a study for potential drug treatments for squamous cell carinoma(type of skin cancer). The data provided was a study done on 249 mice with squamous cell carinoma. After looking deeper at the data one mouse had duplicate timepoints values and with no way to authenicate which timepoints were correct, this mice was drop from the dataset. The dataset only contains analyses of 248 mice findings.

Pandas, matplotlib and other data visualizations were used to further understand the outcome of the study. The following conclusions were made:

    1) There was an almost even distrubtion between male and female mice, with 51% male mice and 49% female mice.
    2)Capomulin and Ramicane drug regimen were the two most tested treatment types in the mice in this study
    3)After taking a closer look at four drug treatments: Capomulin, Ramicane, Infubinol, Ceftamin and there correlation with the mices Tumor Volume, the conclusion made was the data seemed accurate and not skewered. Furthermore, Capomulin and Ramicane seem to be a better drug treatment than Infubinol and Ceftamin. Capomulin and Ramicane have lower final tumor size volume.
    4)After looking closely at mouse (r554) who received Capomulin treatment, it seems this drug works and is a good choice in treating squamous cell carinoma. The tumor volume for r554 drastically decrease of the course of the 45 days. 
    5)There is a positive correlation between weight and tumor volume for mice that received Capomulin drug Treatment. The less the mouse weighed the smaller the tumor volume. 
