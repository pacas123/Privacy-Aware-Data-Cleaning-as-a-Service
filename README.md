# Privacy-Aware-Data-Cleaning-as-a-Service


## Datasets

### Clinical Trails Dataset
This dataset is from [source](https://old.datahub.io/dataset/linkedct), which describes patient demographics, diagnosis, prescribed drugs, symptoms, and treatment.

**Attribute Details**   
```
id,facility_address_country,download_date,org_study_id,nct_id,brief_title,acronym,official_title,lead_sponsor_agency,source,overall_status,why_stopped,phase,study_type,study_design,number_of_arms,diagnosis,enrollment,biospec_retention,eligibility_sampling_method,eligibility_gender,eligibility_minimum_age,eligibility_maximum_age,eligibility_healthy_volunteers,condition,measure,time_frame,safety_issue,drug_name
```                                                                                                                                                                                                                             
### Census Dataset 
The dataset contains 300K records with 40 attributes from the U.S. Census Bureau. This dataset can be found [here](https://archive.ics.uci.edu/ml/machine-learning-databases/census-income-mld/census-income.html), containing population data.

**Attribute Details**   
```
age AAGE
class of worker ACLSWKR
industry code ADTIND
occupation ADTOCC
adjusted gross income AGI
education AHGA
education-num
wage per hour AHRSPAY
enrolled in edu inst last wk AHSCOL
marital status AMARITL
major industry code AMJIND
major occupation code AMJOCC
race ARACE
hispanic Origin AREORGN
sex ASEX
member of a labor union AUNMEM
reason for unemployment AUNTYPE
full or part time employment stat AWKSTAT
capital gains CAPGAIN
capital losses CAPLOSS
divdends from stocks DIVVAL
federal income tax liability FEDTAX
tax filer status FILESTAT
region of previous residence GRINREG
state of previous residence GRINST
detailed household and family stat HHDFMX
detailed household summary in household HHDREL
instance weight MARSUPWT
migration code-change in msa MIGMTR1
migration code-change in reg MIGMTR3
migration code-move within reg MIGMTR4
live in this house 1 year ago MIGSAME
migration prev res in sunbelt MIGSUN
num persons worked for employer NOEMP
family members under 18 PARENT
total person earnings PEARNVAL
country of birth father PEFNTVTY
country of birth mother PEMNTVTY
country of birth self PENATVTY
citizenship PRCITSHP
total person income PTOTVAL
own business or self employed SEOTR
taxable income amount TAXINC
fill inc questionnaire for veteran's admin VETQVA
veterans benefits VETYN
weeks worked in year WKSWORK
```


### Food Inspection
This dataset is from NYU open data [source](https://opendata.cityofnewyork.us/), which contains violation citations of inspected restaurants in New York City describing the address, borough, zipcode, violation code, violation description, inspection type, score, grade.

**Attribute Details**

```
borough, address, violation code, violation description, zipcode, cuisine
description, action, inspection type, critical flag, score, grade
```

## Source Code
The source code is available [here](https://github.com/PrivacyPreversingDataCleaning/Privacy-Aware-Data-Cleaning-as-a-Service).
