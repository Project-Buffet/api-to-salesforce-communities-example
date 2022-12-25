# api-to-salesforce-communities-example
This integration takes a set of Communities objects from a Mock REST API and inserts them into Salesforce. This project can be repurposed for any data type beyond just Communities. This project supports Upsert functionality, but be sure to clear Salesforce of any Communities that match what is incoming from the REST API before moving the data if you'd like new Communities to appear.

This project requires creating a mock API to pass the data from. This is the site I use to create mock API endpoints: https://mockapi.io/projects
