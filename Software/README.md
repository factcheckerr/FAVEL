# Structure
- [**ContainerService**](ContainerService) : This module contains fact validations approaches that can be used with this software. The module includes Dockerfile to run them. The module is able to start and stopping containers automatically.
    - [**adamic_adar**](ContainerService/adamic_adar)
    - [**copaal**](ContainerService/copaal)
    - [**degree_product**](ContainerService/degree_product)
    - [**jaccard**](ContainerService/jaccard)
    - [**katz**](ContainerService/katz)
    - [**klinker**](ContainerService/klinker)
    - [**knowledgestream**](ContainerService/knowledgestream)
    - [**pathent**](ContainerService/pathent)
    - [**pra**](ContainerService/pra)
    - [**predpath**](ContainerService/predpath)
    - [**relklinker**](ContainerService/relklinker)
    - [**simrank**](ContainerService/simrank)
- [**controller**](controller): The controller of the application.
- [**datastructures**](datastructures): Data structures and custom exceptions
    - [**exceptions**](datastructures/exceptions): Custom exceptions
- [**FactValidationService**](FactValidationService): Module containing the fact validation services responsible for validating assertions on multiple fact validation approaches. Sends assertions to the fact validation approaches, gets the response, and caches if specified.
    - [**Interface_documentation**](FactValidationService/Interface_documentation) Documentation of the communication between the fact validation service and the fact validation approaches
- [**InputService**](InputService): The input service, reads the input dataset.
- [**ML Service**](MLService): The Machine learning service. Responsible for training and testing a supervised machine learning model.
- [**Output Service**](OutputService): Write the results.
- [**test**](test): Unittests