# generate google sheets api key

This is a support document for darideveloper projects, which require connection with google spreadsheets

--------------------------------

In order to connect the project with google spreadsheets, you need to generate an API Key from the google console. Below are the steps.

1. Go to your Google Clud COnsole home screen: https://console.cloud.google.com/home/

![image 1](screenshots/1.PNG)

2. Make sure you use the correct user account

![image 1](screenshots/2.PNG)

![image 1](screenshots/2.1.PNG)

![image 1](screenshots/2.2.PNG)

3. Create a new project

![image 1](screenshots/3.PNG)

![image 1](screenshots/3.1.PNG)

4. Name the new project as "sheets" or something similar

![image 1](screenshots/4.PNG)

5. Select the project you just created

![image 1](screenshots/3.PNG)

![image 1](screenshots/5.PNG)

6. Go to APIs & Services > Credentials

![image 1](screenshots/6.PNG)

7. Create a new Service account

![image 1](screenshots/7.PNG)

8. Give it the name "service sheets"

![image 1](screenshots/8.PNG)

9. Edit the generated service account

![image 1](screenshots/9.PNG)

10. In keys tab, create a new key

![image 1](screenshots/10.PNG)

![image 1](screenshots/10.1.PNG)

11. Select json and click in the "create" button

![image 1](screenshots/11.PNG)

12. Save the Json file a in secure place

13. Search "sheets" in the top search bar

![image 1](screenshots/13.PNG)

14. In the Marketplace results, select "Google Sheets API"

![image 1](screenshots/14.PNG)

15. Enable it

![image 1](screenshots/15.PNG)

16. Done. Now, with yout json file, you can connect the project with yor google sheets