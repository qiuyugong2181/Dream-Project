# Dream-Project

Group member: 


CHENGJIN JIN;
CHENGXI CAI;
QIUYU GONG; 
XIN XIONG; 
YICHUN LUO;


2.1 Feature selection:
We select the features based on the differential expression analysis (DE).  The package we used is Limma in R. The data DREAM project provides comes from Microarray, and is already transformed.  Therefore, we do not need to do transformation again. We separate the data set to the groups based on their gestational age (GA). We define time point 1 (T1) if GA lower than 25, and time point 2 (T2) if GA higher than 25.  We only do DE analysis between control group versus PPROM and control group versus sPTD at T2 due to the reason that we think T2 is more close to delivery time, thus more representative. We selected top 100 genes for PPROM and sPTD with high fold changes and with p value lower than 0.05. 
