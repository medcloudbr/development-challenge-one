# Development challenge

![logo medcloud-03 white copy](https://user-images.githubusercontent.com/46347123/158176045-de9fefb0-35e2-4515-83ff-c132608aa870.png)

About Medcloud:

We make exams and medical data management more flexible, secure and effective by accelerating the transition from clinics and hospitals to the cloud.
The RIS and PACS systems have been practically the same for the past 25 years. Interoperability problems, high costs and a lack of understanding about the patient's access to his medical records.

These points defined limits for the doctor-patient relationship and barriers to radiology workflows. We are revolutionizing this through a Care Coordination based solution that improves workflows for providers and integrates doctors and patients for a better experience.

Since our foundation, almost 10 years ago, we have prioritized excellence in the management of health data, structuring workflows of health professionals, clinics, laboratories and hospitals for assertive and quality diagnostics.

We understand that behind each medical record there is a patient seeking to improve his health and the hope of family members for his well being. After all, we are all patients, and Medcloud's mission is to help you live longer and better. #PatientFirst

Medcloud's challenge for the back-end developer positions.

## Problem
We need a simple Java program that saves a collection of patients  (Patient's name, birth date, email and address) in a database (MySQL, PostgreSQL, etc) and right after, perform a select on these data and save the results on a xml file. 

The patient address should be saved by entering the CEP of the patient and retrieving the full address by Correios Web Service. 

After saving the file in .xml, read this xml file again, obtain the patient's name from this file, and finally proceed with the replication of this data + the epoch timestamp in a 2nd database, different from the 1st transaction.
## What will be evaluated:

- Clean and organized code (naming, etc.)
- Knowledge of patterns (PSRs, design patterns, SOLID)
- Be consistent and know how to argue your choices
- Present solutions you master
- Data Modeling
- Code maintainability
- Error handling
- Architecture (structuring thought before writing)
- Affection in decoupling components (other layers, service, repository)

According to the above criteria, we will evaluate your test in order to proceed to the technical interview. If you have not acceptably achieved what we are proposing above, we will not proceed with the process.

## Delivery

You MUST fork this repository to your own account and push you code to it. 
When you finish it, you must send a email to cv@medcloud.com.br with your curriculum, fork and how many time you managed to complete the challenge.

Good luck! Any doubts, feel free to send an email to cv@medcloud.com.br.

## For the day of the technical interview and code review

On the date set by the recruiter, have your application running on your local machine to run the tests and to show us the points developed and possible questions. We will do a code review together with you as if you were already on our team, you will be able to explain what you thought, how you architected and how the project can evolve. Good luck!
