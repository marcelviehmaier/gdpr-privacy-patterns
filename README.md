# GDPR Privacy Patterns in Amazon Web Services (AWS)
This project is part of my master thesis with the title: Privacy Aware Cloud Services.

## Purpose
The purpose of this project is to provide reference implementations for the requirements od the GDPR. So far, the "Right to be forgotten" and the "Purpose Limitation" are implementes using the services of AWS. If you need further information about this project, feel free to contact me. Then I can provide you futher information about the architecture.

## Documentation
In this section you can find a documentation of the existing projects. The Purpose Limitation is Art. 5 (1e) GDPR an has the goal to only process data with a specific prupose. Without this purpose, its not allowed to process the data. There are several ideas how to implement this, in this project I porvide 3 architectures. First of all, there is a microservice that can be expanded for futher implementations. The second project implements the purpose limitation with the IAM service of AWS. The last project implements this requirement with an specific algorithm.
The Right to be Forgotten (Art. 17 GDPR) gives data subjects the right to reqeuest the deletion of their account or data. The architecture is based on a metadata store, that stores metadata about the location of the saved data.
