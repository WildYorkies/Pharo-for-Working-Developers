# Setting Up Your Project

- What is a Pharo application?
  - How is it different from a Node package? etc
  - Can you make a *library* and an *executable*? What differences would that make in setting up a project?
- Create a new VM for every task?
- Where to get a clean VM?
- Get rid of classes you don't need? Tree shaking when finished?

This project will be a typical ETL "script":
- Get data from some API
- Format the JSON payload into a dataframe
- Convert the Dataframe to a CSV file
- Save the file on disk and email a copy to yourself

First we need to set up version control with Iceberg/Git/Github etc
