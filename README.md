### EX1 Creation of Employee, Weather dataset in WEKA Data Mining and Analysis Tool and perform Preprocessing
### DATE: 03-11-26
### AIM: 
  To Create Employee, Weather dataset in WEKA Data Mining and Analysis Tool and perform preprocessing
### PROCEDURE: 
1) Open Start -> Programs -> Accessories -> Notepad
2) Type the following training data set with the help of Notepad for Employee Table.

```
--------------
Employee Data
---------------
@relation employee
@attribute name {x,y,z,a,b}
@attribute id numeric
@attribute salary {low,medium,high}
@attribute exp numeric
@attribute gender {male,female}
@attribute phone numeric
@data
x,101,low,2,male,250311
y,102,high,3,female,251665
z,103,medium,1,male,240238
a,104,low,5,female,200200
b,105,high,2,male,240240

--------------
Weather Data
---------------
@relation weather
@attribute outlook {sunny,rainy,overcast}
@attribute temparature numeric
@attribute humidity numeric
@attribute windy {true,false}
@attribute play {yes,no}
@data
sunny,85.0,85.0,false,no
overcast,80.0,90.0,true,no
sunny,83.0,86.0,false,yes
rainy,70.0,86.0,false,yes
rainy,68.0,80.0,false,yes
rainy,65.0,70.0,true,no
overcast,64.0,65.0,false,yes
sunny,72.0,95.0,true,no
sunny,69.0,70.0,false,yes
rainy,75.0,80.0,false,yes
```
3) After that the file is saved with .arff file format.
4) Minimize the arff file and then open Start -> Programs -> weka-3-4.
5) Click on weka-3-4, then Weka dialog box is displayed on the screen.
6) In that dialog box there are four modes, click on explorer.
7) Explorer shows many options. In that click on ‘open file’ and select the arff file
8) Click on edit button which shows employee table on weka.

### OUTPUT:
#### EMPLOYEE DATA
<img width="1228" height="737" alt="image" src="https://github.com/user-attachments/assets/a1f61fae-7c37-44b9-aa5b-fc2b71afac19" />

#### WEATHER DATA
<img width="1231" height="743" alt="image" src="https://github.com/user-attachments/assets/3389333f-47da-4ee3-bff4-17f200752b4a" />




### PREPROCESSING
### Procedure:
#### 1) Add -> Pre-Processing Technique:
1) Start -> Programs -> Weka-3-4 -> Weka-3-4
2) Click on explorer.
3) Click on open file.
4) Select Weather.arff file and click on open.
5) Click on Choose button and select the Filters option.
6) In Filters, we have Supervised and Unsupervised data.
7) Click on Unsupervised data.
8) Select the attribute Add.
9) A new window is opened.
10) In that we enter attribute index, type, data format, nominal label values for Climate.
11) Click on OK.
12) Press the Apply button, then a new attribute is added to the Weather Table.
13) Save the file.
14) Click on the Edit button, it shows a new Weather Table on Weka.

### OUTPUT:
### EMPLOYEE DATA 
<img width="1233" height="746" alt="580548682-c6812a80-194b-49d2-b422-625f16a24332" src="https://github.com/user-attachments/assets/0af3210b-734b-45c2-899e-868a9cbe719f" />
### WEATHER DATA
<img width="1230" height="749" alt="580548756-6c27130a-c969-40f0-96f6-fcef77e878ce" src="https://github.com/user-attachments/assets/fab03b65-2767-4c5e-864d-750c78ee8e81" />


### 2) Remove -> Pre-Processing Technique:

1) Start -> Programs -> Weka-3-4 -> Weka-3-4
2) Click on explorer.
3) Click on open file.
4) Select Weather.arff file and click on open.
5) Click on Choose button and select the Filters option.
6) In Filters, we have Supervised and Unsupervised data.
7) Click on Unsupervised data.
8) Select the attribute Remove.
9) Select the attributes windy, play to Remove.
10) Click Remove button and then Save.
11) Click on the Edit button, it shows a new Weather Table on Weka.

### OUTPUT:
#### EMPLOYEE DATA
<img width="1234" height="742" alt="580548857-d700d2a5-c156-43e5-983d-f8a91e94ee46" src="https://github.com/user-attachments/assets/84d8dd7b-3051-4d5d-9078-59f390e7efbb" />
#### WEATHER DATA
<img width="1234" height="742" alt="580548897-9e955a1c-9c80-44ef-9cdf-6c4c6eb5133c" src="https://github.com/user-attachments/assets/05675ce7-57e8-4e99-9f5f-2e4fcf8bc98c" />


### Normalize -> Pre-Processing Technique:

1) Start -> Programs -> Weka-3-4 -> Weka-3-4
2) Click on explorer.
3) Click on open file.
4) Select Weather.arff file and click on open.
5) Click on Choose button and select the Filters option.
6) In Filters, we have Supervised and Unsupervised data.
7) Click on Unsupervised data.
8) Select the attribute Normalize.
9) Select the attributes temparature, humidity to Normalize.
10) Click on Apply button and then Save.
11) Click on the Edit button, it shows a new Weather Table with normalized values on Weka.

### OUTPUT:
### EMPLOYEE DATA
<img width="1234" height="742" alt="580548966-4c0fa438-5c23-403d-87ee-513ca1b487a5" src="https://github.com/user-attachments/assets/3a90d059-8d7e-4793-a23e-c39db897be96" />
### WEATHER DATA
<img width="1234" height="742" alt="580549095-3b554f59-3190-4fe3-822f-d4109fca58dc" src="https://github.com/user-attachments/assets/0a5e9e5b-8e29-4b06-97d9-201775832931" />


### RESULT: 
  Thus the program for generating employee and weather datasets has been developed, and preprocessing has been accomplished successfully.
