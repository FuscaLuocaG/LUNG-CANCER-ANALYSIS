# LUNG-CANCER-ANALYSIS

- End-to-End Clinical Risk Pipeline & Synthetic Data Fidelity Audit.

What about if we can make an estimation of survival of one of the most criticals fields in medicine of nowadays; "Lung Cancer", with the sample of 890,000 patients (Synthetic Data) and the power of the Machine Learning we can use years of records process them and get valuable insights. Thankfully to the history and the math, we can develop a system which checks for patterns that could be lost by human-eyes due to the amount of information, and get important hallmarks and behaviors of one of the most dangerous cancers in human-history, also one of the most common. So like this, we can act quick and save another life.

Dealing with thousands of hundreds of records is not an easy task. That is why the data processing is one of the most criticals steps on this project. The data has been divided by 3 data sets (Training set 70%, Testing set 15% and Validation set 15%);

- Training set: 623k of samples exclusively for the training-model stage only.
- Validation set: 133k of samples for the tuning any parameter and measure model-performance.
- Testing set: 133k of Data fully new for setting model up for production and for showing the model-performance for stakeholders.

By spliting the data set at the very beginning of the project into these 3 blocks we make sure there is not Data-Leakeage in the model or even humans in the modeling phase.


