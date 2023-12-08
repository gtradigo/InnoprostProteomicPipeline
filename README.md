# InnoprostProteomicPipeline
This is a research prototype of a biological pipeline for the integration of clinical and proteomic data.

Proteomic-based analysis is used to identify biomarkers in blood samples and tissues. Data produced by devices such as mass spectrometry, requires platforms to identify and quantify proteins (or peptides). Clinical information can be related with mass spectrometry data to identify diseases at an early stage. Machine learning techniques can be used to support physicians and biologists for studying and classifying pathologies.

We present a pipeline using machine learning techniques being able to classify proteomics data enriched by means of clinical information. The pipeline allows users to relate established blood biomarkers with clinical parameters and proteomics data.

#![pipeline](/img/pipeline_small.png?raw=true "pipeline workflow")
![pipeline_small](https://github.com/gtradigo/InnoprostProteomicPipeline/assets/3709044/2c7b143c-8d35-43df-8e15-490caa1ff654)

The proposed pipeline entails three main phases:
1. feature selection
2. models training
3. models ensembling 

We tested the pipeline on prostate related clinical data. Models have been trained on a proprietary clinical datasets which results from the integration of clinical and mass spectrometry -based data. The pipeline receives as input data from blood analytes, tissue samples, proteomic information and urine biomarkers. It then trains different models for feature selection and classification. 

The pipeline has been used in two biological projects, which present results from a 2 years research project called INNOPROST (see [1-3]).

## References
[1] C. Gabriele, F. Aracri, L. E. Prestagiacomo, M. A. Rota, S. Alba, G. Tradigo, P. H. Guzzi, G. Cuda, R. Damiano, P. Veltri, et al., *Development of a predictive model to distinguish prostate cancer from benign prostatic hyperplasia by integrating serum glycoproteomics and clinical variables*, **Clinical Proteomics** 20 (1) (2023).

[2] L. Prestagiacomo, G. Tradigo, F. Aracri, C. Gabriele, M. A. Rota, S. Alba, G. Cuda, R. Damiano, P. Veltri, M. Gaspari, *Data-independent acquisition mass spectrometry of eps-urine coupled to machine learning: a predictive model for prostate cancer*, **ACS Omega** (2022).

[3] P. Vizza, L. Pascuzzi, F. Aracri, E. Tavolaro, P. Lambardi, M. Gaspari, P. H. Guzzi, G. Tradigo, P. Veltri, *Prostate cancer disease study by integrating peptides and clinical data*, in: **AAI4H@ ECAI**, pp. 45–48 (2020).
