<h2>CPSC-4310 Machine Learning Data Analysis Project - Assignment 2</h2><br>
Team Members:<br>
Marco Rodriguez, 
Shaun Lee, 
Zachary Chandler 
<br>
<h1> New York Times Coronavirus (COVID-19) Data in the United States (Dataset #1) </h1><br>
Description: This dataset has the cumulative counts of coronavirus cases in the United States, at the state and county level, over time. This data is taken from state and local governments and health departments in order to provide a complete record of the outbreak in the United States.<br>
<br>
Size of dataset: <br>
Instances (Rows): 3549<br>
Attributes (Columns): 7<br>
<br>
<h3>Data Samples:</h3><br>
First five datasamples:<br>

|date   |state   |cases   |deaths   | cases_per_capita |deaths_per_capita |state_population
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
|2020-01-21|	Washington|	1|	0|	0.0| 0.0| 7614893
|2020-01-21|	Washington|	1|	0|	0.0| 0.0| 7614893
|2020-01-21|	Washington|	1|	0|	0.0| 0.0| 7614893
|2020-01-21|	Washington|	1|	0|	0.0| 0.0| 7614893
|2020-01-21|	Washington|	1|	0|	0.0| 0.0| 7614893

Last five datasamples (as of 4/26/20): <br>

|date   |state   |fips   |cases   |deaths   |
|:-:|:-:|:-:|:-:|:-:|
|2020-04-26	|Virginia	|51	|12970	|448|
|2020-04-26	|Washington	|53	|13663	|757|
|2020-04-26	|West Virginia	|54	|1053	|34|
|2020-04-26	|Wisconsin	|55	|5911	|274|
|2020-04-26	|Wyoming	|56	|371	|7|

<h3>Attributes:</h3>
Date: date of confirmed cases and deaths

State: US State of confirmed cases and deaths

FIPS: a FIPS code, a standard geographic identifier to make it easier for an analyst to combine this data with other data sets like a map file or population data.

Cases: Cumulative cases of COVID-19 to date.

Deaths: Cumulative deaths from COVID-19 to date.

<h3>Appropriate measures of the central tendency and dispersion for attributes:</h3>


<h1> State Action on Coronavirus (Dataset #2) </h1><br>
Description: This dataset showcases state legislative action towards containing the COVID-19 outbreak. <br>
<br>
Size of dataset:<br>
Instances (Rows): 579<br>
Attributes (Columns): 3<br>
<br>
<h3>Data Samples:</h3><br>
First five datasamples:<br>

|State   |Bill Summary   |Date of Enactment   |
|:-:|:-:|:-:|
|Alabama |SJR 40  Urges individuals to fist bump rather than shake hands. Enacted|2020-04-02|
|Alabama |SR 49  Urges Congress to fund additional rental assistance due to coronavirus. Adopted.|2020-03-12|
|Alabama |HR 107  Urges the promotion, sharing and posting of practices to reduce the spread of infectious diseases. Pending.| - |
|Alabama |HJR 121/HJR 122  Urges the Governor to expand Medicaid coverage for new mothers in response to the current COVID-19 pandemic. Pending. | - |
|Alabama |HB 186  Makes supplemental appropriations; includes an appropriation of $5,000,000 from the general fund to the Department of Public Health to be used for coronavirus preparedness and response activities. Enacted. | 2020-04-12|

Last five datasamples (as of 4/26/20): <br>

|State|Bill Summary|Date of Enactment|
|:-:|:-:|:-:|
|Washington|SB 6189  Clarifies eligibility for School Employees' Benefits Board coverage of substitute teachers; and of school employees during quarantine or school closures due to COVID-19. Enacted.|2020-03-17|
|Wisconsin|SR 7  Acknowledges that the Communist Party of China deliberately and intentionally misled the world on the Wuhan Coronavirus; stands in solidarity with the Chinese people to condemn the actions of the Communist Party of China. Failed.|-|
|Wisconsin|SB 927  Exempts pharmaceutical, treatment, and other medical supplies used for treating coronavirus from the Unfair Sales Act, also called the minimum markup law, during the public health emergency due to coronavirus. Failed.|-|
|Wisconsin|AB 1035  Exempts pharmaceutical, treatment, and other medical supplies used for treating COVID-19 from the Unfair Sales Act, also called the minimum markup law, during the public health emergency declared on March 12, 2020. Failed. |-|
|Wisconsin|AB 1038  Relates to the state government response to the coronavirus pandemic; authorizes limited autopsies for the death of an inmate due to COVID-19; establishes a civil liability exemption for persons who manufacture, distribute or sell emergency medical supplies to respond to the public health emergency. Enacted.|2020-04-15|
<h3>Attributes:</h3>
State: US State where the bill is proposed.

Bill Summary: A brief summary of the proposed bill.

Date of Enactment:  Date of when the bill was passed.

<h3>Appropriate measures of the central tendency and dispersion for attributes:</h3>
