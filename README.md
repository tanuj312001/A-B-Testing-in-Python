# A-B-Testing-in-Python

![image](https://github.com/tanuj312001/A-B-Testing-in-Python/assets/60888384/ffc1f6f2-3adc-4cac-8426-702e030420e8)


As a product manager for an e-commerce platform, which key metrics would you use to gauge the effectiveness of a new promotional banner? Dive into the details into the python notebook above.

In this repository, we focus on:

- Essential metrics to track for A/B testing.
- Analyzing potential changes in user behavior (Click Through Rate, Time on Page, Revenue, etc.) due to the promotional banner.

# Understanding the Dataset
Our dataset (data.csv) originates from an A/B testing scenario where a promotional banner was displayed to a subset of users. Each entry represents user interaction within a specific period. The dataset columns include:

- duration_seconds: Time spent by the user on the page (in seconds).
- start_time, end_time: Timestamps showing the start and end of the interaction.
- CTR: Click-Through Rate, indicating if a user clicked on the promotional banner.
- rev_user: Revenue generated from the user during the session.
- user_type: Specifies if the user was part of the treatment group (saw the banner) or the control group.

# Some distributions of Treatment and Control group 

![download (1)](https://github.com/tanuj312001/A-B-Testing-in-Python/assets/60888384/16c80c17-c32b-461d-828f-3788606fa8b0)
