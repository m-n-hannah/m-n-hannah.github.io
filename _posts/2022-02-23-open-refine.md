---
title:  "Open Refine"
mathjax: true
layout: post
categories: workshops, digital humanities
---

![Image](https://labinoteca.files.wordpress.com/2017/01/openrefine-bdu-logo.png)

Often when working in DH, you’ll need to begin collecting materials into spreadsheets to work with in various tools. Many of the tools we’ll be using will require you to collect data into spreadsheets to use and such data can contain errors or mistakes. Open Refine allows you to work with messy data at scale, data that isn’t perfect.

1.	Find where you extracted your Open Refine folder. Click on the folder, and open the application. Open Refine is a web server that you download and access via a web browser. This black loading screen is simply the back end of Open Refine.

2.	Choose Files. Note the different file types Open Refine will accept. Notice you can use Google Data documents too such as Google Sheets. You can also connect to a database if you have connection information.

![image](https://user-images.githubusercontent.com/22083340/156191965-bf1bb32e-36de-44ff-82a9-0e7425d78bf8.png)

3.	Find the Titanic Passenger List I sent you, which you’ll notice is saved in a CSV file. CSV means comma separated values and refers to a way of organizing data as you’ll see. Click Next.

4.	Open Refine reads our spreadsheet and tries to determine where columns should go, giving us a preview of our data. We can choose some different parsings, but we want CSV. We can also choose to ignore the first few lines if we want. Try 5. We can also parse the first line to appear as column headers rather than in our spreadsheet. This is important if you have explanatory info in the spreadsheet or if you have column headings like we do here. We can also choose how many rows we want to load into our data set.

![openrefine2](https://user-images.githubusercontent.com/22083340/156192426-de1b02ab-3a24-48e8-bfa0-6d5d638a1819.png)

5.	Parse cell text into numbers, dates, etc. to have Open Refine try to work with our data types.

6.	Create Project

7.	Now we can work with our data. You can see that our dataset is loaded into Open Refine and is showing the first 10 lines OF 1309 ROWS. We can navigate through our data 50 lines at a time…or jump to the end!

8.	UNDO/REDO can be used to undo or redo a mistake!

![openrefine3](https://user-images.githubusercontent.com/22083340/156192668-593c966e-86df-4d91-9d08-70be14af3a5b.png)

FACETS 
9.	Facet 1: Name. Sort names by count.

![openrefine4](https://user-images.githubusercontent.com/22083340/156192885-fe5d82e3-7aa1-4930-b703-9a754e91fc25.png)

10.	Facet 2: Home Destination. Cluster and choose. Select what you’d like to change each item to and check the boxes for merge. We’ve now edited 14 cells at once!

11.	Edit individual locations in facet box. Change ?Havana to Havana. Now edit one MA to be Massacussetts and one to be Massachusetts.

![openrefine5](https://user-images.githubusercontent.com/22083340/156193082-0def63dc-51b2-40d9-baf9-05c3518b9453.png)

12.	Facet 3: Age. Facet age by number, notice that we get a visualization of our data’s statistics.

TRANSFORMS: Cells and Columns

13.	Transforms. Click on sex. Go to “edit cells.” Go to common transforms and change to title case.

![openrefine6](https://user-images.githubusercontent.com/22083340/156193263-2a8cd45c-d91d-4a23-b585-2c72c932d321.png)

14.	Go to tickets, go to common transforms, and change to text. Now change back to number.

![openrefine7](https://user-images.githubusercontent.com/22083340/156193476-09a10303-4a7d-4aa6-8f87-cc20ac7d2284.png)

15.	We can also edit columns, including renaming them and moving them. Go ahead and remove the embarked column as we don’t need it. 

KEY/VALUE PAIRS
16.	Now let’s combine columns using key/value pairs.

17.	Click on sex. Click on transpose and choose “Columnize by Key/Value Columns.” It will ask you to choose the key column by which the value column will be organized. Choose sex as your key and survived as your value to determine if women and children really are first off the boat. Sex is now spilt into two columns, and shows the data for survived or not.

![openrefine8](https://user-images.githubusercontent.com/22083340/156193643-fa669aec-8898-4cca-831c-d2fb42b25d80.png)

18.	Now click each column, edit cells, and replace 0, 1 with died, survived.

19.	USING GREL TO CHANGE DATA
USING GREL

20.	We can also use Open Refine’s Regular Expression interface to make large scale changes. Open Refine operates using a language called GREL. GREL = Global Regular Expression Language.

21.	Click on names, go to transform. Now enter the GREL script: value.split(",").reverse().join(" "). 

![openrefine9](https://user-images.githubusercontent.com/22083340/156193892-4b8affb1-6bd4-4c21-b45c-1a7570021d96.png)

22.	Now click on ticket, go to transform. Enter the GREL script: value.replace("PC", "").

![openrefine10](https://user-images.githubusercontent.com/22083340/156194071-f4779b88-0ff4-4438-9cdd-c82f87209034.png)

23.	[A guide to using GREL.](https://docs.openrefine.org/manual/grelfunctions)

EXPORTING
24.	Open Refine will save your data in your particular instance of it so you’ll want to make sure you remember where you saved it.

25.	Once you’ve got your data ready, you can export it. 

26.	Click export. Choose what type of file you want to export. For our purposes a CSV will do, but we could export as CSV, Excel, or even an SQL schema if we were working on a database design.
