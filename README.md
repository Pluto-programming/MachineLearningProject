# Abstract

Cardiotocography (CTG) is a technique used for data collection in fetal health. It is employed to analyze the health of a
fetus during pregnancy and determine whether the fetus requires medical attention. CTG mainly yields two results fetal
health rate (FHR) and uterine contractions (UC). In total, there are 21 attributes in the measurement of FHR and UC on
CTG. These attributes can help obstreticians to clasify whether the fetus health is normal, suspected, or pathological.
This study implements six different algorithms: Artifical Neural Networks, ADABoost, XGBoost, LGBoost,Random
Forest and SVM in order to predict the health of a fetus and decide on a classification between Normal, Suspect, and
Pathological. The implementation includes a Multiclass classifier using those three classes and a Binary classifier
(Normal or not Normal) to demonstrate that a binary classifier can achieve a higher accuracy on this dataset and therefore
allow doctors to prioritize patients in need with more confidence. By employing three scenarios, this paper reports the
performance measurements among those algorithms. The study shows that 5 out of 6 algorithms perform very
well using SMOTE Technique (85-98% accurate) and not as well using Ensemble Technique (58-77%accurate).

Keywords: Cardiotocography; Fetal health; ANN; XGBoost; LightGBM; SVM; AdaBoost; Random Forest Classifier;
Multi-class Classifier; Binary-class Classifier, SMOTE, Ensemble
