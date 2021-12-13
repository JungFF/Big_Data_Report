# CS-GY 6513 Big Data Project

## Group Members

* Xiaozhe Wang
* Guanliang Yao
* Jingxuan Feng

## Project Introduction

With the rapid development of information technology, more and more types of data begin to appear in people’s lives, which means more and more difficult data problems occur, which can cause a significant obstacle to the work of data analysts. Diverse data cleaning and data profiling techniques are essential for improving data processing efficiency. In this project, we start by processing different types of data in a typical dataset, analyze their data structures, and derive a more efficient data processing strategy, then evaluate and improve the efficiency of this strategy by processing data in other highly similar datasets and finally obtain a generalized data processing strategy.

This project implements and demonstrates more efficient and diverse data cleaning techniques. In this project, we use the DOB Job Application Filings dataset as our typical dataset and use the similarity query to get the dataset with high similarity and complete the analysis.

## Ways to Reproduce

We mainly used jupyter notebook to perform data profiling, cleaning and visualisation in the experiment.

Below were the tools and packages used by us, please download them before reproducing the experiment.

1. openclean(version: 0.2.1)  https://pypi.org/project/openclean/
2. pandas(version: 1.3.4) https://pypi.org/project/pandas/1.3.4/
3. numpy(version: 1.20.3) https://pypi.org/project/numpy/1.20.3/
4. Python(version: 3.9.7) https://www.python.org/downloads/release/python-397/
5. matplotlib(version: 3.5.0)  https://pypi.org/project/matplotlib/3.5.0/

To generate a reproducable report, you will need the datasets below:

* [DOB NOW: Build – Approved Permits](https://data.cityofnewyork.us/Housing-Development/DOB-NOW-Build-Approved-Permits/rbx6-tga4)
* [DOB Complaints Received](https://data.cityofnewyork.us/Housing-Development/DOB-Complaints-Received/eabe-havv)
* [DOB Violations](https://data.cityofnewyork.us/Housing-Development/DOB-Violations/3h2n-5cm9)
* [Local Law 8 of 2020 – Complaints of Illegal Parking of Vehicles Operated on Behalf of the City](https://data.cityofnewyork.us/City-Government/Local-Law-8-of-2020-Complaints-of-Illegal-Parking-/cwy2-px8b)
* [DOB Cellular Antenna Filings](https://data.cityofnewyork.us/Housing-Development/DOB-Cellular-Antenna-Filings/iz2q-9x8d)
* [DOB NOW: Electrical Permit Applications](https://data.cityofnewyork.us/City-Government/DOB-NOW-Electrical-Permit-Applications/dm9a-ab7w)
* [DOB_Certificate_Of_Occupancy](https://data.cityofnewyork.us/Housing-Development/DOB-Certificate-Of-Occupancy/bs8b-p36w)
* [DOB Stalled Construction Sites](https://data.cityofnewyork.us/Housing-Development/DOB-Stalled-Construction-Sites/i296-73x5)
* [Interagency Coordination and Construction Permits Data (MOSYS)](https://data.cityofnewyork.us/City-Government/Interagency-Coordination-and-Construction-Permits-/wye7-nyek)
* [Active_Projects_Under_Construction](https://data.cityofnewyork.us/Housing-Development/Active-Projects-Under-Construction/8586-3zfm)
* [FY19 BID Trends Report Data](https://data.cityofnewyork.us/City-Government/FY19-BID-Trends-Report-Data/gt6r-wh7c)
* [DOB NOW: Safety – Facades Compliance Filings](https://data.cityofnewyork.us/Housing-Development/DOB-NOW-Safety-Facades-Compliance-Filings/xubg-57si)
* [DOB Sign Application Filings](https://data.cityofnewyork.us/Housing-Development/DOB-Sign-Application-Filings/nyis-y4yr)

Please download all the datasets above and save them into Dataset folder and please **do not** change their names.

All the referenced data and the result data will be stored into Reference Data folder and Resultset folder respectively after running all jupter notebooks.

## Deliverables

You could find our report and thorough explanation of our algorigthm in Report folder. 

