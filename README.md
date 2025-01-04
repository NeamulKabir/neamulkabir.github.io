
# Welcome to *Mohammad Neamul Kabir*'s webpage!

## About me
An aspiring researcher and educator, want to flourish in data science and machine learning, and apply them to solve real-life problems in healthcare. I enjoy teaching and interacting with students, also enjoy learning from students about new things and their diverse interest. I am passionate about working with data, particularly clinical data, and uncovering patterns through meticulous analysis and processing. I thrive on solving complex problems by devising straightforward, effective solutions and applying them to address real-world challenges with meaningful societal impact.

## Current Position
At present, I am working as a **Research Fellow** at *Centre of AI in Medicine* at Lee Kong Chian School of Medicine in NTU. Here, I work with clinician scientists to analyze clinical data and build advanced machine learning models for different clinical prediction task such as early disease risk prediction, ICU mortality prediction, hospital re-admission prediction etc.

## Teaching
  
#### 1. (NUS) Basic AI Competency Course
* **Role:** Primary Instructor
* **Period:** June 2021 to July 2022
* **Participants:** NUS Staff
* **Responsibilities:**  Delivered lectures to NUS sta@ for seven iteration and to multiple groups in each iteration as primary instructor. Each iteration includes five lectures (weekly) along with assessments and presentation evaluation.

#### 2. (NUS) BT5151: Advanced Analytics and Machine Learning
* **Role:** Graduate Teaching Assistant
* **Period:** Sem 2 AY2021/22, Sem 2 AY 2020/21
* **Participants:** NUS Graduate students (mostly working professionals)
* **Respinsibilities:** Conducted tutorial class, assessed assignment, prepared material, evaluated presentations

#### 3. (NUS) CS3244: Introduction to Machine Learning
* **Role:** Graduate Teaching Assistant
* **Period:** Sem 1 AY2020/21, Sem 1 AY 2019/20, Sem 1 AY2018/19
* **Participants:** NUS Undergraduate students
* **Respinsibilities:** Prepared materials (jupyter notebook, tutorial question, assessment quiz) for flipped classroom, conducted tutorial classes, conducted coding help session, assisted in final exam invigilation.

#### 4. (NUS SCALE) Machine Learning
* **Role:** Graduate Teaching Assistant
* **Period:** January 2019
* **Participants:** High School students from China
* **Respinsibilities:** Conducted tutorial session on basic ML algorithms, helped students in building ML models using Azure platform.

#### 5. Lecturer at Ahsanullah University of Science and Technolohy (AUST), Bangladesh
* **Role:** Lecturer
* **Period:** Spring Sem 2017, Fall Sem 2017
* **Participants:** AUST Undergraduate Students
* **Theory Courses:** C programming, Python programming
* **Laboratory Courses:** Computer Graphics, Assemble Language, Digital System Design, Digital Logic Design



## Research Interest
* Digital health
* ML for healthcare
* Data science
* Computational Biology


## Research Projects

### Cancer-risk prediction for diabetic patients
Diabetic patients, particularly those with Type 2 diabetes have an elevated risk of developing certain types of cancer compared to individuals without diabetes. From past medical records of diabetic patients from Hong Kong hospitals, we analyze how cancer-risk can be predicted X years (e.g. 3 years) before cancer onset so that some preemptive measures can be taken. To predict cancer-risk from EHR data, we utilize Gated Recurrent Unit (GRU)-based autoencoders for feature representation of di@erent laboratory measurements. Later, these represented features from GRU network are incorporated along with demographic features into a second vanilla neural network which predicts risk of developing cancer in the coming X years. In this project, we are trying to tackle key challenges of clinical data like missing values, variable feature length for di@erent patients, variable measurement window, class imbalance etc. and also capture time sensitive patterns from di@erent laboratory measurements that contribute to cancer development. This is an ongoing project that I am leading, and we are currently in the model building phase.

### MiMic-king summary stat-based model in digital health
In recent years, ML models for clinical decision support system has become much more popular and a lot of models are being developed for di@erent prediction task such as ICU mortality risk prediction, re- hospitalization prediction, length of stay prediction etc. Large number of these models use summary statistics feature to develop ML models and provide state-of-the-art performance. But many of these models lack thorough evaluation of the outcome predicted and interpretations provided. Although using summary statistics makes it easier to develop model and tackle challenges pertaining to clinical data, it also over-simplifies the feature representation and loses crucial information such as longitudinality (i.e. time temporality), patterns of fluctuation, small or sharp changes that can be very important for clinical decision making. In this project, we try to mimic such models and do post-hoc analysis to show that in majority cases the added clinical utility is very small or non-existent. We have conducted extensive experiments using MIMIC-IV and eICU data for the ICU mortality risk prediction task and shown that summary statistics-based model cannot address some of the key issues pertaining to clinical data. To capture hidden patterns and to make mortality prediction more e@ectively, longitudinal data should be considered preserving time temporality, compared to over-simplified summary statistics features. I am also leading this project and we are currently drafting one manuscript for submission.

### Exploiting similarity of dissimilarities to predict protein function in the twilight-zone
Predicting protein function from sequence information only is a di@icult task specially for the sequences where the similarity with reference sequence is very small, i.e., twilight-zone sequences. As these types of sequences are di@icult to annotate, the existing databases consist very little amount of them. As a result, di@erent computational method providing performance comparison on overall dataset, show very good performance only reflecting better performance for easy proteins. Hence, to annotate these di@icult proteins, we employed the concept of similarity of dissimilarities to account for sequences which share very less sequence similarity. The dissimilarity features are calculated by comparing sequences from one family with sequences from other families. Where the similarity values are higher they can readily be identified, but while the similarity scores are very low the dissimilarity values enhance the power of the ML models. Thus sequences in the twilight-zone can be identified better with this approach compared to the state-of-the-art methods. We employed this idea to predict protein function specially in the twilight- zone, to do enzyme classification where members share little similarity among them due to hierarchical classification, to identify proteins and predict their functions in multi-domain proteins. Overall, the aim of this project is to be able to get proteins from a genome and predict function for those. This was my PhD thesis subject and we have published one paper from it.


## Publications
### 1. [“Exploiting the Similarity of Dissimilarities for Biomedical Applications and Enhanced Machine Learning”](), Mohammad Neamul Kabir, Wang Li Rong, Wilson Wen Bin Goh, PLOS Computational Biology (in press), 2024
### 2. [“Ten quick tips for ensuring Machine Learning model validity”](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1012402), Wilson Wen Bin Goh, Mohammad Neamul Kabir, Sehwan Yoo, Limsoon Wong, PLOS Computational Biology 20, no. 9 (2024)
### 3. [“EnsembleFam: towards more accurate protein family prediction in the twilight zone”](https://link.springer.com/article/10.1186/s12859-022-04626-w), Mohammad Neamul Kabir, Limsoon Wong, BMC Bioinformatics 23, no. 1 (2022)


## Previous Work Experiences
  #### Research Fellow
  * **Instituition:** LKC School of Medicine, NTU, Singapore
  * **Period:** March'2023 to Present
    
  #### Research Assistant
  * **Instituition:** LKC School of Medicine, NTU, Singapore
  * **Period:** August'2022 to March'2023

  #### Lecturer
  * **Instituition:** Ahsanullah University of Science and Technology, Bangladesh
  * **Period:** May'2017 to December'2017

## Education
  ### Ph.D. in Computer Science
  * **Instituition:** School of Computing, National University of Singapore, Singapore
  * **Graduated:** February, 2023 (NUS Class of 2023)
  * **Thesis Title**: [Towards more accurate protein function prediction in the twilight-zone](https://www.proquest.com/openview/82c21dcad64a8df594c6034f2a89d22f/1?pq-origsite=gscholar&cbl=2026366&diss=y)
  * **Thesis Advisor:** [Porfessor Limsoon Wong](https://www.comp.nus.edu.sg/~wongls/)

  ### B.Sc. in Computer Science and Engineering
  * **Instituition:** Bangladesh University of Engineering and Technology, Bangldaseh
  * **Graduated:** March, 2017
  * **Undergraduate Thesis Title:** [Detection and correction of errors in genome in assemblies](https://drive.google.com/file/d/0B9aLIZr0gSIjckllRmhNcElVTkk/view?usp=sharing&resourcekey=0-o6Jv_BBA07xi9ptLf_LcoQ)
  * **Thesis Advisor:** [Assoc Professor Atif Hasan Rahman](https://cse.buet.ac.bd/web/faculty_list/detail/atif)

### Other activities
* Presented *EnsembleFam* at Young Researcher track in GIW'2023 conference, Singapore
* Conducted workshop on protein function prediction at GIW'2023 conference, Singapore
* Resident Assistant at NUS UTown Residence from June'2019 to Decemeber'2022
* Volunteered as translator for “A randomized open-label prophylaxis trial among migrant workers at high-risk of COVID-19 (DORM Trial)” in May'2020
