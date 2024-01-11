
PROBLEM STATEMENT

Many colleges around the country require apllicants to submit ACT and SAT scores as criteria for admission. States have different participation rates in each of the exams i.e. most states require most of its 11th and 12th graders take one or the other exam. Most states tend to favor one exam over the other. A minority of states either use both approximately equally or have only a small number of its 11th and 12th grades students take one of the exams.

The Deparment of Education has hired me to look into whether states that opt for one exam over the other have different college outcomes.



DATA DICTIONARY

|Feature|Type|Dataset|Description|
|---|---|---|---|
|state|object|sat_act_2019|State names| 
|participation_sat|float|sat_act_2019|Participation rate in the SAT| 
|ebrw|int|sat_act_2019|EBRW score on SAT| 
|math|int|sat_act_2019|Math score on SAT| 
|total|int|sat_act_2019|Total SAT score| 
|participation_act|float|sat_act_2019|Participation rate in the ACT| 
|composite|float|sat_act_2019|Composite ACT score| 

|Feature|Type|Dataset|Description|
|---|---|---|---|
|school|object|colleges|University name| 
|applies_to_class_year(s)|object|colleges|Year that test-optional policy applies| 
|policy_details|object|colleges|Policy details concerning test-optional policy| 
|number_of_applicants|int|colleges|NUmber of applicants to university| 
|accept_rate|float|colleges|University acceptance rate| 
|state_abbrev|object|colleges|State abbreviation| 
|state|object|colleges|Stat in which school is located| 
|sat_total_25th_percentile|int|colleges|25th percentile scored by applicants on SAT| 
|sat_total_75th_percentile|int|colleges|75th percentile scored by applicants on SAT| 
|act_total_25th_percentile|float|colleges|25th percentile scored by applicants on ACT| 
|act_total_75th_percentile|float|colleges|75th percentile scored by applicants on SAT| 
|test_optional_no|int|colleges|Binary denoting whether school is test-optional. 1 in this column means school requires test| 
|test_optional_yes|int|colleges|Binary denoting whether school is test-optional. 1 in this column means school does not require test| 
|permanent_test_opt|int|colleges|Binary denoting whether school has a permanent test-optional policy. 1 in this column means school has a permanent test optional policy|
|temporary_test_opt|int|colleges|Binary denoting whether school has a temporary test-optional policy. 1 in this column means school has a temporary test optional policy|

ANALYSIS
I explored three datasets, two (act_2019.csv and sat_2019.csv) containing information about state participation rate and scores on ACT and SAT for the year 2019, and another containing data on college admissions rates and scores on the SAT and ACT by applicants to those schools. 

I created an attribute correlation heatmap, histograms, boxplots, and various scatter plots. In them I compared trends and tendencies regarding university admissions rates with participation in the SAT and ACT. I aslo looked into whether any correlations existed between test scores and other attributes like whether most colleges in a state had a test-optional policies in place, or wheteher most colleges in a state had permanent test-optional policies.



RECOMMENDATIONS
My recommendation would be to look into factors that might be causing this tendency. Is this simply a coincidence? Could it be caused by socioeconomic or cultural factors? Could it be caused by education policy in each state? 
It is possible that on average states that use the SAT more widely than the ACT have more exclusive universities, thus a lower acceptance rate overall?
Resources should be allocated to carry out research into these questions and to identify and explore other datasets that might shed more light on the matter. 