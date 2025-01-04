
# Welcome to my webpage!

## About me
An aspiring researcher and educator, want to flourish in data science and machine learning, and apply them to solve real-life problems in healthcare. I enjoy teaching and interacting with students, also enjoy learning from students about new things and their diverse interest. I am passionate about working with data, particularly clinical data, and uncovering patterns through meticulous analysis and processing. I thrive on solving complex problems by devising straightforward, effective solutions and applying them to address real-world challenges with meaningful societal impact.

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
### 1. “Exploiting the Similarity of Dissimilarities for Biomedical Applications and Enhanced Machine Learning”, Mohammad Neamul Kabir, Wang Li Rong, Wilson Wen Bin Goh, PLOS Computational Biology (in press), 2024
### 2. [“Ten quick tips for ensuring Machine Learning model validity”](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1012402), Wilson Wen Bin Goh, Mohammad Neamul Kabir, Sehwan Yoo, Limsoon Wong, PLOS Computational Biology 20, no. 9 (2024)
### 3. [“EnsembleFam: towards more accurate protein family prediction in the twilight zone”](https://link.springer.com/article/10.1186/s12859-022-04626-w), Mohammad Neamul Kabir, Limsoon Wong, BMC Bioinformatics 23, no. 1 (2022)
