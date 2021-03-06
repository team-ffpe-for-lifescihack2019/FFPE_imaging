# FFPE Seek - Tumor Evaluation
Life Science Tools

## Introduction
The right cancer treatment depends on the correct diagnosis. The current method of diagnosis uses FFPE (formalin fixed paraffin embedding) preservation of tumors, protecting the tumor in a wax block.  The FFPE block is cut into thin tissue slices, and is sent in parallel to separate labs for staining/microscopy and DNA sequencing. The problem that arises is the ambiguity between the healthy tissue and tumor tissue. The DNA sequencing relies heavily on the quantity of actual tumor DNA in the sample.

## How it works
FFPE Seek is a science app using a simple user interface with the power of computer vision deep learning integrating bayesian statistical methods behind it.

User logs into app -> Scans patient ID barcode or types in ID -> Retrieves data from patient information database -> User views patient file -> User uses handheld ultrasound device to scan FFPE block -> Interface outputs % Tumor and tumor location 3D image

FFPE Seek is used to save time and money by determining if the tumor yield is great enough to advance the sample to Pathology and Molecular Biology Labs within a Clinical Lab setting.  Typically, when a tumor is removed by a surgeon, the tumor is fixed in formalin and embedded in paraffin (FFPE) wax for long term storage (Figure. 1).  The FFPE block advances to the Clinical Lab where thin slices are sent in parallel to Pathology to undergo microscopic evaluation and to Molecular Biology where the DNA is extracted from the slices and the sample is sequenced.  The Pathology lab determined how much tumor and normal tissue are present.  Each institution has their own cutoff for acceptable tumor to normal tissue ration.  Too little tumor and a correct genetic diagnosis cannot be made.  Being able to determine if an FFPE block is viable to use before the expense and time of Pathology and Molecular Biology Labs allows for faster resampling, saving time, money, and lives.
Lab technicians can use a simple handheld ultrasound device to evaluate the amount of tumor is and FFPE sample (Figure 2).  In the Histology Lab, the FFPE block can be evaluate by a handheld ultrasound device, which penetrates the paraffin.  Five images are taken to create a 3D image of the tissue.

Computer vision deep learning integrating bayesian statistical methods was used to teach the app to differentiate between tumor and normal tissue.  The % tumor and 3D image reconstruction are outputted into the user interface.  This allows the lab technician to determine if there is enough tumor in the sample to advance the sample for further testing.  It also allows the lab technician to visualize the block in 3D to determine the optimum sample spot within the FFPE block.
Being able to determine if an FFPE block is viable to use before the expense and time of lab work allows for faster resampling; saving time, money, and lives.

## Figure 1. Typical Tumor Workflow

![](Figure1.jpg)

## Figure 2. Unique Solution

![](Figure2.jpg)

In Histology Lab the FFPE block can be evaluate by a handheld ultrasound device, which penetrates the paraffin.  Five images will be taken to create a 3D image of the tissue.

## Development

### Computer Learning Deep Vision
Natalia Villareal had to leave due to an unexpected medical emergency and wasn't able to get her submission to us in time.  This is a summary of what she was doing:

The algorithm used will require as many data points as possible of healthy tissue (databases used reference in Acknowledgements). This will be feed in and generate a new category which will be abnormal or normal. We will manually integrate by giving feedback to the system of any incorrect categorization.  This will be continued until the percentage of wrong classifications is within a tolerable threshold.


### UI Design
UI was designed by Michelle Sokoll
https://pr.to/HR69C6/

https://docs.google.com/document/d/1-Z8poETCXxZWrDEDsLyFYQ-9myh1AxPNn8_4ghZIWX0/edit?usp=sharing


## Marketing Opportunity
There are an estimated 1 billion FFPE samples worldwide!  In 2018, there were over 1,700,000 new cases of cancer diagnosed in the United States.  The number of FFPE tumor samples needing evaluation will continue to rise.  The FFPE Seek App allows for simple evaluation of FFPE samples to determine % tumor content.  Because DNA sequencing relies heavily on the quantity of actual tumor DNA in the sample, knowing the % content means knowing there is enough DNA to detect cancer mutations, and make a correct diagnosis and prognosis, which can predict best treatment.  Being able to determine if an FFPE block is viable to use before the expense and time of lab work allows for faster resampling; saving time, money, and lives.


## Acknowledgements
https://www.cancer.org/research/cancer-facts-statistics/

https://data.mendeley.com/datasets/wmy84gzngw/1

https://www.ultrasound-images.com/breast/

http://www.eng.usf.edu/cvprg/Mammography/Database.html

https://wiki.cancerimagingarchive.net/display/Public/ACRIN-FLT-Breast

Icons Used:
https://www.flaticon.com/home 
Michelle has a license


