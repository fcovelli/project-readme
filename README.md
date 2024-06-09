---
type: "project" # DON'T TOUCH THIS ! :)
date: "2024-06-14" # Date you first upload your project.
# Title of your project 
title: "Detecting ADHD through fMRI signals using machine learning classification models"

# List the names of the collaborators within the [ ].
names: [Agustín, Ezequiel, Francisco]

# Your project GitHub repository URL
github_repo: https://github.com/AgustinNR/BrainHack-BsAs-Humai-Team1

# If you are working on a project that has website, indicate the full url including "https://" below or leave it empty.
website:

# List +- 4 keywords that best describe your project within []. Note that the project summary also involves a number of key words. Those are listed on top of the [github repository](https://github.com/PSY6983-2021/project_template), click `manage topics`.
# Please only lowercase letters
tags: [adhd, fmri, brainhack]

# Summarize your project in < ~75 words. This description will appear at the top of your page and on the list page with other projects..

summary: "."

# If you want to add a cover image (listpage and image in the right), add it to your directory and indicate the name
# below with the extension.
image: ""
---
<!-- This is an html comment and this won't appear in the rendered page. You are now editing the "content" area, the core of your description. Everything that you can do in markdown is allowed below. We added a couple of comments to guide your through documenting your progress. -->

# Detecting ADHD through fMRI signals using machine learning classification models
## Project definition

### Background

Attention-Deficit/Hyperactivity Disorder, or ADHD, is characterized by inattention, impulsivity and hyperactivity. Its prevalence in Argentina is 4% in children and adolescents. It is still diagnosed using subjective clinical criteria, which are often difficult to evaluate. However, artificial intelligence (AI) techniques hold potential for identifying neuroimaging biomarkers that could facilitate the diagnosis of ADHD. Our objective is to develop machine learning classification models to detect ADHD through the analysis of resting state functional MRI (rs-fMRI) signals.

According to previous studies (Stripada et al., 2014), ADHD brains at rest show altered connectivity between key nodes of the Ventral Attention Network (VAN) and the Default Mode Network (DMN), which are involved in lapses of attention. The DMN facilitates internally focused attention during tasks like recalling personal memories, planning for the future, and processing self-referential information. The VAN is crucial for monitoring the significance of external stimuli and for managing the switch between the DMN and task-oriented cognitive modes. Hence, we decided to study this regions of interest (ROIs) together with subcortical structures mentiones in the reviewed literature.

### Tools

Our project used the following tools:

* **Bash Terminal**: Employed for command-line operations and scripting.

* **Git and GitHub**: Managed version control, shared workspace, and repositories.

* **Jupyter Notebook**: Implemented the code within this interactive environment.

* **Python**:
  * **Nilearn**: to facilitate the processing and visualization of neuroimaging data.
  * **Matplotlib and Seaborn**: for data visualization.
  * **Numpy and Pandas**: for data manipulation and analysis.
  * **AAL atlas**: For brain parcellation.


### Data
CITAR EL REPO
The ADHD-200 Sample is a collaborative effort involving eight international imaging sites that have openly shared neuroimaging data from 362 children and adolescents diagnosed with ADHD, along with 585 typically developing controls. This collection includes 947 datasets containing both structural and resting-state fMRI data, as well as phenotypic information from the subjects.

In 2011, the ADHD-200 Consortium organized a competition aimed at identifying biomarkers of ADHD USING the ADHD-200 dataset. The Preprocessed Connectomes Project (PCP) emerged as an effort to broaden the competition's accessibility to a wider audience of researchers by preprocessing the data and openly sharing the outcomes. The data provided by this initiative has led to several publications.

Pierre Bellec, Carlton Chu, François Chouinard-Decorte, Yassine Benhajali, Daniel S. Margulies, R. Cameron Craddock (2017). The Neuro Bureau ADHD-200 Preprocessed repository. NeuroImage, 144, Part B, pp. 275 - 286. doi:10.1016/j.neuroimage.2016.06.034

### Deliverables

At the end of this project, the following files will be made available:
* The current markdown document.
* Python scripts in a jupyter notebook.
* Figures of our results: Connectivity matrix, graphs for statistical analysis, visualizations
* A repository on GitHub to share our work and methods.


## Results

### Progress overview
.

### Tools I learned during this project

* Project management
* Git and Github workflow
* Python for data analysis
* Machine learning basics
* Introduction to deep learning
* Functional connectivity in fMRI
 

### Results

#### Deliverable 1: 

#### Deliverable 2: 

#####


## Conclusion and acknowledgement
![HUMAI LOGO](https://github.com/fcovelli/project-readme/assets/169564890/ffca62e3-ac11-4409-a444-0210ef44e80a)
![brainhack-800x450](https://github.com/fcovelli/project-readme/assets/169564890/ad83bf31-f1f4-49d5-ac2a-eb30b1cf39a3)

## References
Zhu CZ, Zang YF, Cao QJ, Yan CG, He Y, Jiang TZ, Sui MQ, Wang YF. Fisher discriminative analysis of resting-state brain function for attention-deficit/hyperactivity disorder. Neuroimage. 2008 Mar 1;40(1):110-20. doi: 10.1016/j.neuroimage.2007.11.029. Epub 2007 Dec 3. PMID: 18191584.

Buckner RL, Andrews-Hanna JR, Schacter DL. The brain's default network: anatomy, function, and relevance to disease. Ann N Y Acad Sci. 2008 Mar;1124:1-38. doi: 10.1196/annals.1440.011. PMID: 18400922.

Yeo BT, Krienen FM, Sepulcre J, Sabuncu MR, Lashkari D, Hollinshead M, Roffman JL, Smoller JW, Zöllei L, Polimeni JR, Fischl B, Liu H, Buckner RL. The organization of the human cerebral cortex estimated by intrinsic functional connectivity. J Neurophysiol. 2011 Sep;106(3):1125-65. doi: 10.1152/jn.00338.2011. Epub 2011 Jun 8. PMID: 21653723; PMCID: PMC3174820.

Cortese S, Castellanos FX. Neuroimaging of attention-deficit/hyperactivity disorder: current neuroscience-informed perspectives for clinicians. Curr Psychiatry Rep. 2012 Oct;14(5):568-78. doi: 10.1007/s11920-012-0310-y. PMID: 22851201; PMCID: PMC3876939.

Sripada C, Kessler D, Fang Y, Welsh RC, Prem Kumar K, Angstadt M. Disrupted network architecture of the resting brain in attention-deficit/hyperactivity disorder. Hum Brain Mapp. 2014 Sep;35(9):4693-705. doi: 10.1002/hbm.22504. Epub 2014 Mar 25. PMID: 24668728; PMCID: PMC6869736.

Bellec P, Chu C, Chouinard-Decorte F, Benhajali Y, Margulies DS, Craddock RC. The Neuro Bureau ADHD-200 Preprocessed repository. Neuroimage. 2017 Jan;144(Pt B):275-286. doi: 10.1016/j.neuroimage.2016.06.034. Epub 2016 Jul 15. PMID: 27423255.

Damiani S, Tarchi L, Scalabrini A, Marini S, Provenzani U, Rocchetti M, Oliva F, Politi P. Beneath the surface: hyper-connectivity between caudate and salience regions in ADHD fMRI at rest. Eur Child Adolesc Psychiatry. 2021 Apr;30(4):619-631. doi: 10.1007/s00787-020-01545-0. Epub 2020 May 8. PMID: 32385695.

Hroncich, Camila. “¿Qué sabemos de TDAH?” CONICET, 12 January 2023, https://www.conicet.gov.ar/que-sabemos-de-tdah/. 

Wang, Z., Zhou, X., Gui, Y. et al. Multiple measurement analysis of resting-state fMRI for ADHD classification in adolescent brain from the ABCD study. Transl Psychiatry 13, 45 (2023). https://doi.org/10.1038/s41398-023-02309-5
