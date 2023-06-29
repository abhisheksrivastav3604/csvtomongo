# How to store CSV data in a MongoDB table using Apache NiFi

## Aim

The Aim is to store CSV data in a MongoDB table using Apache NiFi.

## References

Video: `https://www.projectpro.io/recipes/store-csv-data-mongodb-table-nifi`

## Prerequisites

To run this project, you need the following prerequisites:

Apache NiFi: You need Apache NiFi installed on your system. If you don't have it, you can follow the instructions on `https://nifi.apache.org/docs/nifi-docs/html/getting-started.html#downloading-and-installing-nifi` to install it.

User and Password: You need  user and password to login the Apache NiFi. 

MongoDB: You need MongoDB installed on your system. If you don't have it, you can follow the instructions on `https://www.geeksforgeeks.org/how-to-install-mongodb-on-windows/` to install it.

Full flow in NiFi involves fetching the CSV file, converting it to JSON, changing the file type, and storing the data in MongoDB given below:

![csvtojson](https://github.com/abhisheksrivastav3604/csvtomongo/assets/117782915/3367af43-4e8a-47ff-bc0f-6a938cb6edbc)


## How to Run

To run the project:
Draw The process Flow and, 
Click the "Run" button in Apache NiFi to execute the flow.

