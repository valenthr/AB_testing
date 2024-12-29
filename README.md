# A/B testing
## Tools
Python libraries:
* Pandas;
* Scipy;
* Statsmodels;
* Matplotlib;
* Seaborn.
## Purpose
Make the right decision whether to apply a new design or not based on the results of an A/B test.
## Context of A/B test
In our mobile application, after onboarding, the user is offered to buy a weekly subscription for $4.99, which gives access to premium features.
### Groups
1. A - control group - old design with offer for the weekly subscription for $4.99.
2. B - test group - new design also with the same price, but we say it's actually a 50% off price.
## Data
All data is in table 'ab_test_data':
* user_id - unique id of each user;
* timestamp - time of displaying an offer of subscription;
* test_group - a or b;
* conversion - 0 if user rejected the offer and 1 if user buy the weekly subscription
## Analysis and final report
* Analysis with explanations - [there](https://drive.google.com/file/d/1mu6lFVQdXFCosVup2xnQWbOEEHVt6cTc/view?usp=sharing).
* Final report with conclusion - [there](https://docs.google.com/presentation/d/14YqG0EmGnjJcl9SFT2Cp-fn7fT1tkmSx/edit?usp=sharing&ouid=110123972342957476617&rtpof=true&sd=true).

