# PCOS_diagnosis

## Abstract


Polycystic Ovary Syndrome (PCOS) is a medical condition which causes hormonal disorder in women in their childbearing years. 
The hormonal imbalance leads to a delayed or even absent menstrual cycle. Women with PCOS majorly suffer from excessive weight gain, facial hair growth, acne, hair loss, skin darkening and irregular periods leading to infertility in rare cases. The existing methodologies and treatments are insufficient for early-stage detection and prediction. 

To deal with this problem, we propose a system which can help in early detection and prediction of PCOS treatment from an optimal and minimal set of parameters. To detect whether a woman is suffering from PCOS, 5 different machine learning classifiers like Random Forest, SVM, Logistic Regression, Gaussian Naïve Bayes, K Neighbours have been used. Out of the 41 features from the dataset, top 30 features were identified using CHI SQUARE method and used in the feature vector. We also compared the results of each classifier and it has been observed that the accuracy of the Random Forest Classifier is the highest and the most reliable. 

The dataset used is available on KAGGLE and owned by Prasoon Kottarathil.

Dataset link: https://www.kaggle.com/prasoonkottarathil/polycystic-ovary-syndrome-pcos

Target:
PCOS (Y/N): Whether the person has diagnosed with PCOS.

Features:
1. Physical Parameters:
Age (yrs)  
Weight (Kg)  
Height(Cm)  
Blood Group  
Pulse rate(bpm)  
RR (breaths/min)  
Cycle(R/I)  
Cycle length(days)  
Marraige Status (Yrs)
Hip(inch)  
Waist(inch)  
Waist:Hip Ratio  
No. of abortions

2. Physical Symptoms:
Pregnant(Y/N)  
Weight gain(Y/N)  
hair growth(Y/N)  
Skin darkening (Y/N)  
Hair loss(Y/N)  
Pimples(Y/N)  
Fast food (Y/N)  
Reg.Exercise(Y/N).

3. Medical Parameters:
BMI: Body mass index (BMI) is a measure of body fat based on height and weight that applies to adult men and women.
Hb(g/dl): Hemoglobin(a protein in your red blood cells).
I beta-HCG(mIU/mL), II beta-HCG(mIU/mL): Human chorionic gonadotropin is a hormone for the maternal recognition of pregnancy.
FSH(mIU/mL): FSH helps manage the menstrual cycle and stimulates the ovaries to produce eggs.
LH(mIU/mL): LH helps control the menstrual cycle. It also triggers the release of an egg from the ovary.
FSH/LH: are gonadotropins because they stimulate the gonads - in males, the testes, and in females, the ovaries.
TSH(mIU/L): TSH stands for thyroid stimulating hormone. A TSH test is a blood test that measures this hormone.
AMH(ng/mL): Within the ovaries, AMH helps in the early development of follicles.
PRL(ng/mL): PRL or lactogenic hormone. Prolactin is mainly used to help women produce milk after childbirth.
Vit D3(ng/mL): Vitamin D.
PRG(ng/mL): Progesterone is an endogenous steroid and progestogen sex hormone involved in the menstrual cycle, pregnancy.
RBS(mg/dl): Random blood sugar (RBS) measures blood glucose regardless of when you last ate.
BP_Systolic (mmHg): Systolic pressure, the force of the blood against the artery walls as your heart beats.
BP_Diastolic (mmHg): Diastolic pressure, the blood pressure between heartbeats.
Follicle No. (L), Follicle No. (R): Ovarian follicles are small sacs filled with fluid that are found inside a woman's ovaries.
Endometrium (mm): The endometrium is the innermost lining layer of the uterus.
