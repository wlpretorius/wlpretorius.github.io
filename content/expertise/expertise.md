+++
title = "Expertise"
description = ""
date = "2019-02-28"
aliases = ["expertise"]
author = "Willem Pretorius"
+++

## Advanced-IRB Loss Given Default (LGD)

I focused on the full model development lifecycle (this includes writing code in Python) for Mortgages (Residential) and Corporate (Rural/Agricultural) portfolios as well as updating internal model procedures (Rabobank LGD Model Development Procedure). Further, I obtained experience in both the modelling and calibration of Structural (component-based) and Non-Structural (singular-regression) models, including:

- **Model Design**: 
In the one portfolio a significant focus was on Structural components such as Cure, Loss Given Cure (LGC), and LGL (Loss Given Liquidation) while each individual component had their own risk drivers and estimates. The Cure model was a logistic regression model with its own Single-Factor Analysis (SFA) and Multi-Factor Analysis (MFA). The Loss Given Cure was a linear regression model with its own SFA and MFA. The Loss Given Liquidation was itself a component based model using the information from recoveries and costs (cashflows) stemming from different sources. In the other portfolio, a Non-Structural approach was used to obtain a direct estimate of the LGD. In both portfolios a performing and in-default (and ELBE - Expected Loss Best Estimate) model was built.

- **Single-Factor Analysis (SFA)**: 
This includes univariate and bivariate analysis for each individual risk driver (independent variables used). 

- **Multi-Factor Analysis (MFA)**: 
This includes risk driver selection as well as model selection. Additional assessment was done on the model assumptions and statistical assumptions and if they have been met.

- **Reference Dates Analysis for In-Default**: 
As per requirement of EBA GL PD, LGD Estimation Par. 172, an analysis was done on the appropriate reference dates to be used for the in-default model. The analysis consisted of an investigation of the recovery patterns. 

- **Maximum Recovery Period (MRP)**: 
As per requirement of EBA GL PD, LGD Estimation Par. 156, an analysis was done on the appropriate maximum recovery period (maximum time-to-workout). The analysis consisted of an investigation on the recovery patterns of both complete (Resolved) and incomplete recovery processes (Unresolved cases - the LRA LGD calculation should include both Resolved and Unresolved cases, where incomplete recoveries beyond or longer in-default than the MRP is considered Resolved). This was also directly connected with the Downturn Quantification analysis (which was not done previously in Rabobank but is a requirement from the ECB - where banks should assess the sensitivity of the MRP towards the Downturn estimates given that only closed cases should be taken into account for Downturn Quantification). 

- **Unresolved or Incomplete Recovery Processes**:
As per requirement of EBA GL PD, LGD Estimation Par. 159, for the calculation of LGD LRA, both resolved and unresolved cases should be included. Including unresolved cases without analysis on the expected future recoveries could create a bias towards higher loss rates if unresolved LGDs are directly used. Banks typically avoid this bias by estimating the future recoveries with a model. An investigation was done on the use of an appropriate model (typically the in-default or ELBE model). The 'imputation' or extension of incomplete recoveries were done on component level for the structural models. 

- **LGD In-Default and ELBE model**:
For each model component there was a respective performing and in-default model developed separately. CRR article 181(1) requires that for in-default facilities estimates need to be calculated considering current economic circumstances. Typically, banks use their in-default models directly and show that there is sensitivity of risk drivers to the current economy or they develop an ELBE model (with macroeconomic variable as a risk driver to estimate LGD) and then estimate in-default LGD as an add-on (including unexpected losses) to ELBE. The first approach is usually chosen, and EBA GL PD, LGD Estimation Par. 184 needs to be followed. If the in-default model is sensitive to economic conditions (some of the risk drivers have correlation with some macroeconomic variable) then no further ELBE adjustment is needed. ELBE then is the in-default estimates (before adding the relevant in-default downturn estimate and margin of conservatism (MoC)).  

- **Long-run Average (LRA) Calibration for Performing and In-Default Models**:
This includes an analysis of the calibration functions used for the LRA on Performing and In-default (at each reference date) models. 

- **Downturn (DT) Calibration for Performing and In-Default Models**:
I spent a large portion of my time in Rabobank on compliant Downturn Identification and Quantification for both performing and in-default models. This is arguably the most important part for the LGD RWA Capital calculation and contains multiple complex steps. For the identification part, the Final Draft Regulatory Technical Standards on the
specification of the nature, severity and duration of an economic downturn in accordance with Articles 181(3)(a) and 182(4)(a) of Regulation (EU) No 575/2013 was followed as well as COMMISSION DELEGATED REGULATION (EU) 2021/930 supplementing Regulation (EU) No 575/2013 of the European Parliament and of the Council with regard to regulatory
technical standards specifying the nature, severity and duration of an economic downturn referred to in Article 181(1), point (b), and Article 182(1), point (b), of that
Regulation. These identified periods were used in the LGD DT quantification process, in the EAD DT quantification process, and also in the representativity analysis for the portfolios as part of the likely range of variability investigation and current and future market conditions. For the quantification part, the EBA/GL/2019/03 Final Report - Guidelines for the estimation of LGD appropriate for an economic downturn (‘Downturn LGD estimation’) was followed. This includes a deep investigation of appropriate macroeconomic indicators to use for the specific portfolio, investigation of multiple downturn periods, and investigation of type 1, 2, 3, and reference value approaches for specific portfolio segments. Thereafter, additional assessment on the DT MoC for both performing and in-default models were assessed. Additional assessments includes the sensitivity of downturn estimates to risk factors as well as the MRP. 

- **Business, Risk Experts and Validation Sessions**: 
This includes expert sessions with the Business and Risk Management (I led multiple sessions at Rabobank over 5 countries namely Australia, New-Zealand, Chile, Brazil and USA) after each of the above phases as well as a period of model validation investigations and model validation findings investigations. I also directly collaborated with economists withing Rabobank while preparing for the downturn identification and likely range of variability analysis. 

- **Documentation**: 
Created high quality model development code and documentation where I automated the documentation process in Rabobank through a Python program with the use of JupyterBooks and Markdown. This saved significant time in the development phase and preparation for the model validation phase and IMI. Additionally, created an independent compliant Downturn identification memo that can be used throughout the bank. 

- **Model Development Procedures**: 
Contributed to the development procedures for LGD modelling methodologies as well as incorporating external and internal business and regulatory requirements into the LGD modelling framework of Rabobank with a specific focus on Downturn identification and quantification. 
Translated regulations (and COVID-19 policies) into quantitative & qualitative procedures that are used by modellers throughout the bank. These procedures are used as guidelines in future model (re)-development at Rabobank. 
Additionally, directly consulted to modellers regarding A-IRB regulation and assisted with on-site IMIs from the ECB (Rabobank IPRE portfolio). As part of the internal model development procedure updates, I conducted an investigation on the downturn identification and quantification procedures in Rabobank. I designed a compliant downturn identification and quantification method that can be used throughout Rabobank.

- **What I would like to additionally work on in the future**: 
Simplifying the estimation of incomplete recovery process. A deeper investigation on Example 4 of pg. 23 in the EBA/GL/2019/03 Final Report - Guidelines for the estimation of LGD appropriate for an economic downturn (‘Downturn LGD estimation’), since this is rarely done in banks and rarely commented on in IMIs (from my experience at Rabobank). Survival or Machine Learning models for LGD estimation.  

## Advanced-IRB Probability of Default (PD)

I focused on the full model development lifecycle (this includes writing code in Python) for Mortgages (Residential) and Corporate (Rural/Agricultural) portfolios as well as updating internal model procedures (Rabobank PD Model Development Procedure and Rabobank Expert Review Procedure), including:

- **Definition of Default (DoD) and Observed Default Rate (ODR) calculation**: 
This includes an investigation on the triggers for DoD and changes over the historical period, on the received modelling and application dataset. Additionally, for the 
ODR calculation a cohorting (EBA GL PD, LGD Estimation Par. 80) method was designed and tested.

- **Single-Factor Analysis (SFA)**: 
This includes univariate and bivariate analysis for each individual risk driver (independent variables used in the PD model). 

- **Multi-Factor Analysis (MFA)**: 
This includes risk driver selection as well as model selection. Typically this is a stagewise logistic regression model that is standard across Europe. Additional assessment was done on the model assumptions and statistical assumptions and if they have been met.

- **Calibration**:
This includes a deep analysis of the calibration function (typically a bayesian scalar adjustment) used for the Long-run Average (LRA) and Masterscale mapping. Additionally, a deep investigation on the likely range of variability (as part of a representativity analysis - and the linkage with LGD economic downturn) of the ODRs which includes the assessment of the good and bad years as required by Paragraph 82 to 86 in the EBA PD, LGD Estimation guidelines (this has been highly scrutinized in the past IMIs, which are investigations by the ECB, at Rabobank and different banks in the Netherlands). Calibration on segment level and a specific analysis per segment was done (at country level for the Corporate portfolio and for Mortgages this was split in an Interest Only and Non-Interest Only segments). 

- **Appropriate Adjustments (AAs) and Margin of Conservatism (MoCs)**:
Adding any AAs and MoCs to the ODRs and LRA (the analysis in the likely range of variability assesses the AA that needs top be added to the LRA for a conservative manner to include all appropriate good and bad years in the historical observation period). 

- **Testing**: 
This includes model performance and accuracy (differentiation and quantification), segmentation and sensitivity testing. 

- **Business, Risk Experts and Validation Sessions**: 
This includes expert sessions with the Business and Risk Management (I led multiple sessions at Rabobank over 5 countries namely Australia, New-Zealand, Chile, Brazil and USA) after each of the above phases as well as a period of model validation investigations and model validation findings investigations.

- **Documentation**: 
Created high quality model development code and documentation where I automated the documentation process in Rabobank through a Python program with the use of JupyterBooks and Markdown. This saved significant time in the development phase and preparation for the model validation phase and IMI.  

- **Model Development Procedures**: 
Contributed to the development procedures for PD modelling methodologies as well as incorporating external and internal business and regulatory requirements into the PD modelling framework of Rabobank. 
Translated regulations (and COVID-19 policies) into quantitative & qualitative procedures that are used by modellers throughout the bank. These procedures are used as guidelines in future model (re)-development at Rabobank. 
Additionally, directly consulted to modellers regarding A-IRB regulation and assisted with on-site IMIs from the ECB (Rabobank IPRE portfolio). As part of the internal model development procedure updates, I conducted an investigation on the Gini coefficient as a discriminatory power statistic for risk differentiation in Rabobank.
I designed a confidence interval framework with a traffic lights system around the Gini Coefficient taking into consideration type 1 and 2 errors using Bootstrapping that could assist business decisions on model selection and performance. The findings and method were added in the Rabobank credit monitoring python library and procedures.

- **What I would like to additionally work on in the future**: 
Obligor (and joint-obligor) definition and construction. Machine learning challenger models in the MFA phase. Further enhancement of Interest Only Mortgages (IOM).

## Advanced-IRB Exposure at Default (EAD)

I focused on the parts model development lifecycle (this includes writing code in Python) for the Corporate (Rural/Agricultural) portfolio as well as updating internal model procedures (Rabobank EAD Model Development Procedure), including:

- **Downturn (DT) Calibration for Performing and In-Default Models**:
 The analysis done in the LGD counterpart was replicated for EAD/CCF DT calibration and included type 1 and type 2 approaches. 

- **What I would like to additionally work on in the future**: 
The full model development lifecycle after future expected updates on guidelines from the ECB on CCF modelling.

## Representativity Analysis for Advanced-IRB Models
This includes analysis for risk differentiation and quantification, including scope of application, DoD, distribution of relevant risk drivers, changes in lending standards and recovery policies, and current and foreseeable economic and market conditions (downturn investigation and likely range of variability analysis).   

## Internal Procedures updated and worked on at Rabobank:
This includes: Stress Testing monitoring procedure. Early Warning Signal models monitoring procedure based on Machine Learning models. Acceptance models monitoring procedure based on a Machine Learning model. PD, LGD, and EAD model development procedure. Expert Review (Human Judgement) procedure. IFRS9 model monitoring procedure. 

## Automated Valuation Model (AVM) Development at NIBC Bank:
Automated Valuation Model (AVM) development for Residential Real Estate (Mortgages) portfolio of NIBC Bank. Developed an in-house AVM for NIBC predicting current market prices of collateral (properties) to comply with the new Europe CRR3. Contributed to the full model development cycle (for Owner Occupied mortgages as well as Buy-to-let mortgages) including SFA, MFA, and Calibration while benchmarking and backtesting against Calcasa (Calcasa is currently the market leader in The Netherlands in providing data related to the market value of the property, but their model is a universal Dutch model not based on the own data of the bank - the majority of banks in the NLs use their service). Developed a dashboard that provides updated market values given location and property characteristics of the property. Additionally, designed an algorithm to provide an estimated collateral value if the property characteristics are not available. 

## Enquiries

If you think my experience can benefit your organization, please contact me.

