# t32grant-docs
Public docs for the private web app at t32grant.stanford.edu.

## Description
This site is to facilitate the application process for NIH's T32 grant. There's a public form to invite Stanford's graduated trainee to fill out. The Internet portion of the site pull data from multiple sources for Faculty's info, Faculty-trainees mapping, grants, publications, etc etc. The output are documents to submit to NIH. Shortern the application process from 2-3 months to 1-2 weeks.


## Tools
Laravel for backend. Vue with vuex for frontend. MySQL. Laravel tenancy to "clone" site for 10+ groups so far.


## Public trainee information collection form

![Info collection form](https://raw.githubusercontent.com/ahtle/t32grant-docs/main/images/input-form.png)


## Internal dashboard
Design to follow the 8 documents required by NIH so that user can ituitively pick it up.

Example of an automation: Map faculty/trainee to PubMed's publications.
![Dashboard](https://raw.githubusercontent.com/ahtle/t32grant-docs/main/images/publications.png)

Allow manual addition, editing, and deletion actions so the user can double check the data.
![Edit form](https://raw.githubusercontent.com/ahtle/t32grant-docs/main/images/edits.png)


## Output
Export PDFs that follow NIH's requirements.

![Output documents](https://raw.githubusercontent.com/ahtle/t32grant-docs/main/images/output.png)


## Conclusion
Greatly sped up the application process; saving time and efforts. Provide an easy way for user to look at past applications. The data from trainee info collection form can potentially be used in other grant applications. This project originally served just the Department of Medicine, it was then expended to other units. Project is take up by the School of Medicine to create a school-wide app.
