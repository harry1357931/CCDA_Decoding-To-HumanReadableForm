CCD_Decoding-To-HumanReadableForm:
==================================
CCDA stands for Consolidated Clinical Document Architecture <br>
This repository contains program that decodes any given CCDA document to HRF(Human Readable form), 
In this assignment, HRF is referring to Text File which is outputted by the program.

Note: The program in this repository doesn't decode all sections of CCDA document.

About CCDA:
===========
The Consolidated CDA is based on components of two standard formats that were previously required for certified EHRs: 
the Continuity of Care Record (CCR) and the Continuity of Care Document (CCD). This format was chosen as the standard 
for communicating the summary of care since it can accommodate all data elements that CMS proposes providers give their 
patients after office visits. Health Level 7 (HL7), an accredited standards development organization, created a single 
implementation guide for the Consolidated CDA, which was released in December 2011 in an effort to reduce ambiguity and 
eliminate conflicts in documentation.
The Consolidated CDA solution encompasses a library of reusable CDA templates, setting the stage for streamlined 
development and quicker implementation. The templates allow for incremental interoperability and easier 
machine-to-machine communication, thereby facilitating the transfer and storage of more data.

Source Code File:
================= 
CCDA_Decode.java      &nbsp;&nbsp;&nbsp;   in 'src' folder

Examples of Input & Output File:
================================
BlueButtonPlusSample.txt --- Output File
BlueButtonPlusSample.xml --- Input File (CCDA Format)

For more Info.:
===============
Read comments in CCDA_Decode.java
