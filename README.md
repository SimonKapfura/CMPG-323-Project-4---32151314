# CMPG-323-Project-4---32151314
Use of Robotic Process Automation to automate basic functions of the web app
# How to use the Connected Office Web Application User Acceptance testing project for Automation:
- After openning the Automation Project in UiPath, click on the button indicated in the image below

![](Photos/1.png)

- You will be prompted to enter the login details to the https://connectedoffice-devicemanagement.azurewebsites.net/ website
- Entere credentials and check the checkbox indicated on the image below to save them then click "OK"

![](Photos/2.png)

- Chrome will be Opened and the UiPath will use the provided credentials to automatically log in

![](Photos/3.png)

- It will first go to Zones page and open Excel in the back ground as seen in the image below

![](Photos/4.png)

- It will read all the Zones in the Excel file and create them on the website 1 by 1
- As it is testing the Create functions on the website it will also test Editing, and Reading for each zone read from excel

![](Photos/5.png)

- After the Zone iterations it will read all the Categories in the Excel file and create them on the website 1 by 1

![](Photos/6.png)

- As it is testing the Create functions on the website it will also test Editing, and Reading for each category read from excel

![](Photos/7.png)

- After the Category iterations it will read all the Devices in the Excel file and create them on the website 1 by 1

![](Photos/8.png)

- As it is testing the Create functions on the website it will also test Editing, and Reading for each device read from excel

![](Photos/9.png)

- Atfer testing the Create, Update and Read it will now test delete by deleting each and every device it created

![](Photos/10.png)

- After deleting Devices it will now test Zone delete by deleting each and every zone it created

![](Photos/11.png)

- After deleting Zones it will now test Category delete by deleting each and every category it created

![](Photos/12.png)

- After testing All the CRUD (Create, Read, Update, Delete) automations it will write the results to an Excel file showing wich items and operations failed or passed indicated by TRUE if successful or FALSE if it failed.
- Then it will go back to UiPath and as indicated in the image below you can see how long it took to perform the Automation

![](Photos/13.png)
