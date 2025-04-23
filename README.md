## Pyruvate and Related Energetic Metabolites Modulate Resilience Against High Genetic Risk for Glaucoma

This code was used to generate the results of our [publication](https://elifesciences.org/reviewed-preprints/105576). 

### REFERENCE
If you use code or parts of this code in your work, please cite our publication:

Li Keva, Tolman Nicholas, Segrè Ayellet V, Stuart Kelsey V, Zeleznik Oana A, Vallabh Neeru A, Hu Kuang, Zebardast Nazlee, Hanyuda Akiko, Raita Yoshihiko, Montgomery Christa, Zhang Chi, Hysi Pirro G, Do Ron, Khawaja Anthony P, Wiggs Janey L, Kang Jae H, John Simon WM, Pasquale Louis R, UK Biobank Eye and Vision Consortium  (2025) Pyruvate and Related Energetic Metabolites Modulate Resilience Against High Genetic Risk for Glaucoma eLife 14:RP105576

[eLife](https://elifesciences.org/reviewed-preprints/105576). eLife14:RP105576

### ABSTRACT

A glaucoma polygenic risk score (PRS) can effectively identify disease risk, but some
individuals with high PRS do not develop glaucoma. Factors contributing to this resilience
remain unclear. Using 4,658 glaucoma cases and 113,040 controls in a cross-sectional study of
the UK Biobank, we investigated whether plasma metabolites enhanced glaucoma prediction and
if a metabolomic signature of resilience in high-genetic-risk individuals existed. Logistic
regression models incorporating 168 NMR-based metabolites into PRS-based glaucoma
assessments were developed, with multiple comparison corrections applied. While metabolites
weakly predicted glaucoma (Area Under the Curve=0.579), they offered marginal prediction
improvement in PRS-only-based models (P=0.004). We identified a metabolomic signature
associated with resilience in the top glaucoma PRS decile, with elevated glycolysis-related
metabolites—lactate (P=8.8E-12), pyruvate (P=1.9E-10), and citrate (P=0.02)—linked to
reduced glaucoma prevalence. These metabolites combined significantly modified the PRS-
glaucoma relationship (P interaction =0.011). Higher total resilience metabolite levels within the
highest PRS quartile corresponded to lower glaucoma prevalence (Odds Ratio highest vs. lowest total resilience
metabolite quartile =0.71, 95% Confidence Interval=0.64–0.80). As pyruvate is a foundational metabolite
linking glycolysis to tricarboxylic acid cycle metabolism and ATP generation, we pursued
experimental validation for this putative resilience biomarker in a human-relevant Mus musculus
glaucoma model. Dietary pyruvate mitigated elevated intraocular pressure (P=0.002) and optic
nerve damage (P&lt;0.0003) in Lmx1b V265D mice. These findings highlight the protective role of
pyruvate-related metabolism against glaucoma and suggest potential avenues for therapeutic
intervention.

## Setup

The data folder includes an example dataset that can be used to run the code. 
The R code is stored in the “src” folder. 

### System requirements

The code was tested using R (version 4.2.1: https://cran.rstudio.com/) and 
RStudio (https://posit.co/downloads/) for Mac. 

### Installation guide

All R code is available in the “src” folders. The whole analysis workflow is provided in 
src/main.R. The code can be run by following the instructions in the src/main.R file. 
Make sure to set the path to your study folder in main.R (main.dir = “my_folder/Cohorts/” 
or main.dir = “my_folder/UKBiobank/”)

Typical installation time, including all required packages, is around 1 hour on a typical 
desktop computer.

### Demo

As data can not be shared due to privacy protocols in place, the authors provide example 
datasets. The code will run on any other data formatted in 
the same way as the example data. Details on the format of the example data are provided 
in /src/main.R. 

### Instructions for use

The code will run with any data stored in the same format as the example data provided here. All R code is available in the “src”.

## Disclaimer

The code and data of this repository are provided to promote reproducible research. They are not intended for clinical care or commercial use.

The software is provided "as is", without warranty of any kind, express or implied, including but not limited to the warranties of merchantability, fitness for a particular purpose and noninfringement. In no event shall the authors or copyright holders be liable for any claim, damages or other liability, whether in an action of contract, tort or otherwise, arising from, out of or in connection with the software or the use or other dealings in the software.
