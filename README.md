# Transfering-sheets-to-Datagrip-using-sqlite-3
##### Took me two days to find this out, hopefully this can help you transfer your google sheet files onto DG and run sql scripts  
Ok so I dont to waste your time as much I wouldnt want you wasting mine in a situation where you need the results you want quickly

###### Lets make this snapy

* You are trying to transfer your csv or tsv over from execl/google sheets over to Datagrip (this is the only IDE I know of currently where what im teaching you can be done)

You have been getting errors most likely, so what you want to do is open up a new file on datagrip and start fresh

* You are gonna go to datagrip and add a new data source from the plus sign over on the database explorer and add a sqlite source(search for it around the bottom of the page if not in your recents
<img width="1418" alt="image" src="https://user-images.githubusercontent.com/77177531/147793762-b7f47fb9-b0b9-4d11-8401-ad27a7ac72a5.png">
<img width="1440" alt="image" src="https://user-images.githubusercontent.com/77177531/147793803-c40b18ca-24b2-48f0-885d-805d322ce567.png">

* Once you've done that, you are going to be in the data sources and drivers window. Name the sqlite file whatever you want on the top where it says "Name:"
<img width="1440" alt="image" src="https://user-images.githubusercontent.com/77177531/147793867-ca59b336-bf0d-419b-8cc3-ff9e9ccadd37.png">

* Then aorund the middle of the data sources and drivers window you will see a file section with the "identifier.sqlite" name on it , go the the three lines on the left to it, choose the .csv or .tvs file that you had downloaded from execl or sheets, or any other program along the lines of that. 
<img width="1440" alt="Screen Shot 2021-12-30 at 6 18 48 PM" src="https://user-images.githubusercontent.com/77177531/147794109-0975ca0e-a405-485b-a352-04e730833304.png">

* search your file on your computer and once you find it just open it, then just import into datagrip, then press apply and ok on the bottom right of the data sources and drivers window
<img width="1440" alt="Screen Shot 2021-12-30 at 6 24 24 PM" src="https://user-images.githubusercontent.com/77177531/147794143-02494992-7172-426a-bf1a-a12f6d4846c0.png">

* after that the .csv or .tsv file should be in the database explorer, if everything goes right you shouldn't get a yellow warning notification from datagrip on the bottom right of your screen saying that the file isnt a database file. 
* if that does happen, refactor the .tsv to .csv. , that should do the trick
* after that once the file is completely on the IDE, you have to go to database scripts, its on the top right, left of the green triangle (the Run icon), click on it and add a config / or edit 
<img width="1440" alt="image" src="https://user-images.githubusercontent.com/77177531/147794162-ca95028a-beac-4784-be32-2a556a195d5d.png">

*  then you will be inside the run/debug configurations window
*  for the target data source/schema, that plus sign sign on the top left , click it
<img width="1440" alt="Screen Shot 2021-12-30 at 6 26 03 PM" src="https://user-images.githubusercontent.com/77177531/147794190-5127480b-7041-4871-90ba-ca2ffbad513f.png">

*  you'll see the file you are running, select it, then click on main or whatever your database is named , and hit enter, 
*  then for the execute file
*  also click the top left plus and add the .csv or .tsv that you added, and then import it on the execute section, after that hit apply and ok
<img width="1440" alt="image" src="https://user-images.githubusercontent.com/77177531/147794234-05185850-6839-46d6-979f-40291e4400f0.png">

* Yup it was that simple, hopefully this made sense, and it got you the results you wanted, if not and you are having issues then please dont refrain from emailing me, ill see if I can help you, you can access my email from my github profile

