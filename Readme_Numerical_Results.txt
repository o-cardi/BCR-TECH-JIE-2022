Data and Replication Codes for 'Labor Market Effects of Technology Shocks Biased Toward the Traded Sector' by
Luis Bertinelli,  Olivier Cardi and Romain Restout, June 2022

The Folder 'NUMERICAL RESULTS' comprises three folders: 

1) the folder 'TABLE-NUMERICAL RESULTS' contains all Matlab codes (plus 'calibration-file.xlsx' that contains the shock process) 
to generate the Table in the main text (Table 1). To generate the table in the main text, run 'TABLE.m' file

CAC: Capital adjustment costs; 
TOT: Terms of trade; 
IML: Imperfect mobility of labor; 
PML: Perfect mobility of labor
CES: Constant elasticity of substitution production functions; 
CD: Cobb-Douglas production functions; 
FBTC: Factor-biased technological change
HNTC: Hicks neutral technological change

IML_CAC_TOT_CES_BIAS_NORM: Baseline model with CES production functions, CAC, IML, endogenous TOT and FBTC. The CES eocnomy is normalized by 
using the Cobb-Douglas eocnomy as the normalization point. 
IML_CAC_TOT_CD: Model with Cobb-Douglas production functions which generates the initial steeady-state which is 
considered as the reference point for the CES eocnomy (i.e., ensures that ratios are unchanged when we modify the 
elasticity of substitution between capital and labor)
IML_CAC_TOT_CES_NORM; Model with CES production functions, CAC, IML, endogenous TOT and HNTC
IML_CAC_TOT_CES_NORM_OPEN; Model with CES production functions and Hicks neutral technological change and higher phi=1.2 (instead of 0.44)
IML_CAC;  Baseline model with CD production functions, CAC, IML, exogenous TOT
PML_CAC_TOT_CES_BIAS_NORM; Baseline model with CES production functions, CAC, IML, endogenous TOT and FBTC.
PML_CAC_TOT_CES_NORM; Baseline model with CES production functions, CAC, PML, endogenous TOT and FBTC.
PML_CAC_TOT; Baseline model with CD production functions, CAC, PML, endogenous TOT
PML_CAC; Baseline model with CD production functions, CAC, PML, exogenous TOT

All extensions of Matlab codes '_CD' include models with Cobb-douglas production functions which are used for the normalization only of the CES economy. 


2) the folder 'THEORETICAL vs. EMPIRICAL IRF' contains all Matlab codes (plus 'calibration-file.xlsx' that contains the shock process) 
and excel files which contain the empirical responses generated from the SVAR. Just run 'IRF_FINAL_FIGURE7". 

3) the folder 'CROSS-COUNTRY' contains Matlab codes to generate numerical results from which we construct Figure8. 
More speicifically, the folder 'Calibration_CES_NORM' comprises the Matlab code for each country of the sample 'name of the country_CES.m'; when you run this file, 
the CES economy will be normalized as it runs a second matlab file 'name of the country_CD.m' which generates the initial steady-state with Cobb-Douglas production 
functions that we use as the normalization point for the corresponding country. The tab 'GRAPHS' of the excel file 'Figure8a&8b-Cross-Country' contains the 
data to generate Figure 8a and Figure 8b of the paper. The tab 'GRAPHS' of the excel file 'Figure8c-Cross-Country' contains the data to generate Figure 8c. 