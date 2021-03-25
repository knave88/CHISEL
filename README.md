# CHISEL
CHISEL (Computer-assisted Histopathological Image Segmentation and EvaLuation)

### Description
Software was developed during the project PRELUDIUM (Polish National Science Center, grant No 2013/11/N/ST7/02797) managed by Lukasz Roszkowiak in Nalecz Institute of Biocybernetics and Biomedical Engineering Polish Academy of Sciences (https://www.ibib.waw.pl/en/).

Project: https://www.ibib.waw.pl/en/scientific-activity/projects/167-umo-2013-11-n-st7-02797/233-umo-2013-11-n-st7-02797

It is a program for automatic localization and counting of the cells’ nuclei in digitalized tissue sampled stained using the indirect immunohistochemical (IHC) method. The primary dataset used during the development of the software consisted of samples with primary antibody against FOXP3 and final staining with 3,3’-diaminobenzidine (DAB) and then contra-stained with Haematoxylin. The chosen methods of image processing allows the software to swiftly and precisely localize (segmentation) and accurately label (classification) the cells’ nuclei in digitalized tissue images as well as WSI. 

Benefits of the CHISEL software are as follows:
*	Automatic extraction of nucleus in an image (image/TMA punch/WSI) without any human intervention
*	Considerable decrease in the amount of time needed for the sample evaluation (use of parallel computing and GPU computing)
*	Reduction of the errors in nuclei quantification
*	Automatic differentiation between positive and negative cells’ nuclei (in IHC)
*	The adjustable parameters allows the software to be robust with variety of applicable types of stained tissue samples 
*	The graphical user interface is user-friendly and easy to manage

### Publication
[Under review]

****
### Acknowledgement
We acknowledge the financial support of the Polish National Science Center grant, PRELUDIUM, 2013/11/N/ST7/02797. The funders had no role in study design, data collection and analysis, or preparation of the software.

### Liability
We do not take any responsibility and we are not liable for any damage caused through use of this software, be it indirect, special, incidental or consequential damages.
