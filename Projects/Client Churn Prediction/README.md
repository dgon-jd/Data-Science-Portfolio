## Analysis of customer outflow [ENG]

**Target** - Build and train a model that will predict customer outflow. Target metric - **ROC-AUC** not less 0.88

The operator provides two main types of services:

- Stationary telephone communication. It is possible to connect a telephone to several lines at the same time.

- Internet.Connection can be of two types: via the telephone line DSL or fiber optic.

Such services are also available.:

-Internet Security: Antivirus (DeviceProtection) and unlocking unsafe sites (OnlineSecurity);

- Dedicated technical support line (TechSupport);

- cloud file storage for data backup (Onlinebackup);

- StreamingTV StreamingTV and Film Catalog (StreamingMovies).

- Operators want to learn to predict the outflow of customers.If it turns out that the user plans to leave, prompted promotions and special conditions.

Data consists of files obtained from different sources:

- contract.csv - information about the contract;

- Personal.csv - customer personal data;

- internet.csv - information about Internet services;

- Phone.csv - information about telephony services.

All files column Customerid contains the client code.Information about contracts is relevant on February 1, 2020.
