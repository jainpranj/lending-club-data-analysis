# Lending Club Data Analysis

## Steps to run the code

```
docker pull jainpranj/lending-club-data-analysis .
```

```
docker run -ti lending-club-analysis --module upload_to_S3 UploadDataToS3 --workers 4 --local-scheduler --EMAIL <your-lending-club-login-email> --PASSWORD <your-lending-club-password> --aws-access-key-id <your-aws-access-key-id> --aws-secret-access-key <your-aws-secret-access-key>
```


## Notebooks to look at :
All py files inside code/luigi/tasks/
Summarization of lending dataset
Data-Analysis.ipynb
Summarization-Lending-Club-Data-Set.pdf
Lending_Club_Analysis_Report1.docx

## References:

[1] [hickford/MechanicalSoup : A Python library for automating interaction with websites](https://github.com/hickford/MechanicalSoup) 

[2] [pysysops/docker-luigi-taskrunner: Docker container to make running Luigi tasks real easy.]( https://github.com/pysysops/docker-luigi-taskrunner)

[3] [Dervied Columns Links revolving utilization](http://blog.credit.com/2013/04/what-is-revolving-utilization-65530/)

[4] [Credit Age](https://www.nerdwallet.com/blog/finance/credit-age-length-of-credit-history/earliest_cr_line and last_credit_pull_d date)

[5] [Declined loans, Risk Score, How to get estimate credit score] (Grade http://investorhelp.upstart.com/114489-what-do-the-loan-grades-mean)

[6] [Power BI Dashboard Link](https://app.powerbi.com/viewr=eyJrIjoiNmMzZmY3ZTAtMTRiNy00NzAyLTgzZTgtM2NiNjMyZmQzZGVjIiwidCI6IjZhYmZjNzNmLWRhNjQtNDEzNy05ZjlmLTE1ZmFhZTU2ZjY4NSIsImMiOjN9)

[7][lendingclub-review-borrowers-insiders-reveal](http://www.magnifymoney.com/blog/personal-loans/lendingclub-review-borrowers-insiders-reveal578301843)

[8][FICO-booklet](https://www.credco.com/assets/pdfs/datasheets/FICO-booklet.pdf)
