# MISSION
[MISSION: Ultra Large-Scale Feature Selection using Count-Sketches](https://arxiv.org/abs/1806.04310)

An ICML 2018 paper by Amirali Aghazadeh\*, Ryan Spring\*, Daniel LeJeune, Gautam Dasarathy, Anshumali Shrivastava, Richard G. Baraniuk

\* These authors contributed equally and are listed alphabetically.

# Code Versions

1. Mission Logistic Regression
2. Mission Softmax Regression
3. Feature Hashing Softmax Regression

# Optimizations

* Mission streams in the dataset via Memory-Mapped I/O instead of loading everything directly into memory -\
Necessary for Tera-Scale Datasets
* AVX SIMD optimization for fast Softmax Regression
* The code is currently optimized for the Splice-Site and DNA Metagenomics datasets.

# Datasets
1. [KDD 2012](https://www.csie.ntu.edu.tw/~cjlin/libsvmtools/datasets/binary.html#kdd2012)
2. [RCV1](https://www.csie.ntu.edu.tw/~cjlin/libsvmtools/datasets/binary.html#rcv1.binary)
3. [Webspam - Trigram](https://www.csie.ntu.edu.tw/~cjlin/libsvmtools/datasets/binary.html#webspam)
5. [DNA Metagenomics](http://projects.cbio.mines-paristech.fr/largescalemetagenomics/)
6. [Criteo 1TB](https://www.csie.ntu.edu.tw/~cjlin/libsvmtools/datasets/binary.html#criteo_tb)
7. [Splice-Site 3.2TB](https://www.csie.ntu.edu.tw/~cjlin/libsvmtools/datasets/binary.html#splice-site)
