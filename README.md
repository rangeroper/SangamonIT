# SangamonIT 
![image](https://user-images.githubusercontent.com/62531841/108911795-5fce8100-75ed-11eb-8c69-f7cc92163207.png)
### Languages
![](https://img.shields.io/badge/FrontEnd-JavaScript-informational?style=flat&logo=<LOGO_NAME>&logoColor=white&color=5F7FF6)
![](https://img.shields.io/badge/BackEnd-Node-informational?style=flat&logo=<LOGO_NAME>&logoColor=white&color=5F7FF6)
![](https://img.shields.io/badge/Database-MongoDB-informational?style=flat&logo=<LOGO_NAME>&logoColor=white&color=5F7FF6)
![](https://img.shields.io/badge/Other-Express-informational?style=flat&logo=<LOGO_NAME>&logoColor=white&color=5F7FF6)

### Intro

As a repair shop, handing out quotes is probably something that you find yourself doing all the time.  It gets repetitive and most of the times can be a distraction from more important work that needs to be done to keep the business thriving.  One way to cut back on all of this time is by developing a custom quote system that can accomodate for a large percentage of the devices you find yourself repairing for clients.  

### Site Images

Below are some snapshots of the site in action

![image](https://user-images.githubusercontent.com/62531841/108917358-39144880-75f5-11eb-888d-d357d2446b99.png)
![image](https://user-images.githubusercontent.com/62531841/108914223-a8d40480-75f0-11eb-8fa8-3ad6ad7c753d.png)

### Functions 

This site was developed with the intentions of creating and integrating a custom quote modal that could save time and money from an owner perspective.  Basic CRUD functionality has been implemented (account creation/register).  A dashboard for registered accounts has been developed for future use.    

![image](https://user-images.githubusercontent.com/62531841/108910719-de2a2380-75eb-11eb-9702-c012f8d86221.png)

Users can obtain a free quote by clicking on the "Free Quote" button on the top right of the homepage, which pulls up the 6 quote modals, each of which is configured independently as it's own database table and schema, allowing for more flexibility and customization between product lines.  Each quote modal is comprised of a custom object which stores the integral details related to the object, such as Manufacturer, model, repair type, price, etcetera.  

![image](https://user-images.githubusercontent.com/62531841/108914492-09634180-75f1-11eb-8884-ab7c8eb0508c.png)

Customers are able to keep track of the quote system progress with the help of a progress bar which represents the progress in the form of a percentage.  

![image](https://user-images.githubusercontent.com/62531841/108912102-c3f14500-75ed-11eb-8ad8-700ba8b47a43.png)

### Business Logic

Essentially, each selection made by the user is captured and stored temporarily until the quote is finalized.  Once the selections are made, the user can progress to the customer details page, where they input their personal information.

![image](https://user-images.githubusercontent.com/62531841/108912647-893bdc80-75ee-11eb-9ff3-6f1fa1177a80.png)

Once the user finalizes the quote, all the data pertaining to the schema is sent back to the database and the user is presented with their quote information.  

![image](https://user-images.githubusercontent.com/62531841/108912483-5396f380-75ee-11eb-88c4-4f51567f9b5d.png)

### Future Updates

Currently, the users must contact us outside of the site - I am using Facebook Business Page as my main contact method with customers.  Ideally, a way to schedule and correspond to customers will be integrated in future updates, as will Stripe payments. I have a backend dashboard page for registered accounts where it will display and allow easier retrieval and access to quotes, invoices, payments, and other pertinent information.  




