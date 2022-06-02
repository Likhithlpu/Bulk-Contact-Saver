# Lazy-Contacts
## Prerequisites

First Download the XAMPP from here: 

**For Windows:** https://www.apachefriends.org/xampp-files/8.0.9/xampp-windows-x64-8.0.9-0-VS16-installer.exe
**For Other Versions:** https://www.apachefriends.org/index.html

## Start the Servers

Once you downloaded the XAMPP install it and open the application and start apache and mysql server

## Download the code

**Step1:** Now Download the code from this repo and copy the folder named contact to the inside the htdocs in xampp. For example you installed xampp in server named folder it will be **server/htdocs/** in your case 

**Step2:** Open the numbers.csv file and paste all the numbers you want to save in coloumn A and saveit 

 **Step3:** Go to https://localhost/contact

**Step4:** A file will be Downloaded for you save it in your computer.

## Google Contacts

**Step1:** Download the google contacts application in your mobile and signin with your gmail account 

**Step2:** Go to https://contacts.google.com/ on your computer

**Step3:** In the Side Navigation bar there is a option stated as Import click on that and upload the file which is downloaded now

**Step4:** Now wait for to upload

**Step5:** Open the Google contacts application in your phone and wait for 1-2 min

**Step6:** It will be automatically synced to your mobile contacts and it will be saved in your mobile

**You can see the contacts named as newmembers_somerandomlettersandnumbers. Ex: newmember_d9s1dv8vad5d55d6. If you wish to change check developer options below**


## Developer Options and Line to Line Explanation

Got to **index.php**

**Line 1** States the csv file which is having numbers to save

**Line 2** States the name of the file which is going to be downloaded

**Line 3** States the Prefix Currently **newmembers** you can change it accordingly like **sectionA, Batch2021, Teammbers etc**

**Line 4** States the name of the group which is created in google contacts. You can change it Accordingly

**Line 5** States the type of file **Like CSV, XLSX, XLS, XLTX etc

**Line 6** States its Disposition

**Line 7** States its Directive

**Line 8** States the Expiring time of the session

**Line 9** Variable

**Line 10** Writing the Coloums according to the format of Google contacts import file

**Line 11,12** A for loop which takes the input from the uploaded file and writes the output to a file along with the labels and prefix which we stated in the **lines 3,4**


**Please Fork, Star, Follow if you found this useful for you.**

**Thanks and Regards**

**Bala Likhith Kanigolla**


