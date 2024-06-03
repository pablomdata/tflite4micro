# tflite4micro
Materials for a course in Tensorflow Lite for Microcontrollers


## Tentative syllabus

### Day 1
- Python basics.
- Pandas Quickstart for data manipulation. (`sensor_grid.csv`)
- Types of Machine Learning
- Machine Learning Methodology: Train/Test/Validation
- Example: Classification (`ford_train.tsv` and `ford_test.tsv`).

### Day 2
- Neural Network Classification/Regression. Other network architectures.
- Neural networks and deep learning (dense) / playground.tensorflow.org
- End to end example (Arduino).
- Case studies / Exercises

### Day 3
- Autoencoders.
- k Nearest Neighbours.
- Z-scores / K-Means.
- Model optimisation (Quantisation, pruning, clustering)

## Installation instructions
- Install virtualenv.
`pip install virtualenv`

- Create a virtual environment.
`virtualenv env`

- Activate the virtual environment.
`env\Scripts\activate`

- Install dependencies
`pip install matplotlib pandas jupyter scikit-learn tensorflow==2.15`


## References / Case Studies

### Anomaly Detection
https://github.com/ShawnHymel/tinyml-example-anomaly-detection/tree/master

### ToyADMOS
- https://github.com/Ekhao/ToyADMOSTinyAutoencoder/tree/main
- https://github.com/YumaKoizumi/ToyADMOS-dataset

### MIMII-Hitachi
- https://github.com/MIMII-hitachi/mimii_baseline/
- https://zenodo.org/records/3384388


