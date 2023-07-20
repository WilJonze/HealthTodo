# HealthTodo

## A healthcare focused todo app that manages health-related tasks, and reminders effectively. 

Built in PostgreSQL,Express,Vue,Nodejs in a Test-Driven Object-Oriented Way.

Possible Key Features:

Perscription Manager -
    -Keeps record of Medications, dosages, and sechedules
    -Recieves reminders for Medication intake, decresing missed dosages
    -Provides details on Medication usage, and side effects
    -Offers Price Comparision for Prescriptions

Health Metrics Tracking - 
    -Monitor Health Metics such as blood pressure, heart rate, weight or glucose levels
    -Visulizing progress through charts and graphs


Todo for the Todo
### General
- [x] set up project and dependencies
- [x] connected expressjs
- [x] connected postgresql
- [x] create foudational frontend
- [ ] Figma design of project
### Todo
- [ ] Create 'Add' Button that creates that allows user to search/add perscription information that saves into an accordion
- [ ] Perscription infomation that is input by user is stored in Database
- [ ] Connect to the GoodRx API that pulls info about the perscription pricing and general information about medication
- [ ] Create 'Delete' Button that allow user to remove selected perscription from Todo Listing
- [ ] Create 'Taken' Button that verifys that user has taken selected medication
- [ ] 'Taken' Button changes color and presents a green checkmark when user has clicked the Button
### Tracking
- [ ] When the user has taken all scheduled medication for the day, it will log into a database tracking all completed days of medication intake.
- [ ] A weekly log will use the intake database and show the user how many completed day they have acheived. 
