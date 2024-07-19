# Atomic-Orbital-Contributions-ADF

* sometimes it's important to highlight the AO contributions on the molecular orbital diagrams in order to provide more context and clarity for the topic. That is what Atomic-Orbital-Contributions-ADF is here to accomplish!
* the script is divided into three sections,

**_1. Section I: Extracting the atomic orbital contributions from ADF file_**
* the primary goal of this part will be to extract data from the calculated molecule regarding the most important SFO gross populations across all MOs.
* the name of the ADF output file is all that is needed for this section.
* this will eventually produce a _.text _file that you will need to use in **_Section II_**.
    
**_2. Section II: Trim the output_**
* use Excel to access the _.text_ file after Section I and extract the data we need.
* in order to generate the _.csv_ required in this step, utilize the _**atomic_orbital_contributor.xlsx**_ Excel file (A copy of the document is available here)!
* using the .csv file in this section, you can accurately trim it and use it for the last section 😀.

**_Section III: Atomic orbital contribution plot_**
* using the data obtained from earlier sections, we will create the atomic orbital contribution plot ⚛️📈 in this section.
* the _final.csv_ file is the only crucial document in this section.
* it's important to remember that, based on the results, you might need to make a few changes in this section (such as changing the arrow direction from one orbital to the next).

* finally, you will get the figure,
  
![aoc(383nm)-diadm-b3lyp-dz-dcm-stddft](https://github.com/user-attachments/assets/a844343a-7ee1-4497-929b-14f22bc7e560)
