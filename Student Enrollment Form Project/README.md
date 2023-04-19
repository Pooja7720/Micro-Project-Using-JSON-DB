# Student Enrollment form

## Description:
I have created one mini project in which I have used JSON Power DB for databases, and HTML, CSS and JS languages for frontend and connecting to database. In this project, I have created 3 buttons for save, change or reset the data entered in form. **The most important thing is the primary key is student roll number in this case.**. This entered code is readable. It was very exciting experience for me to build this mini project 🤩. Without any page referesh it gives the output records and it was so amazing. You can check it on by running the index.html file. I am also uploading the output images of this form.

## Benifits of using JSONPowerDB:
- Simplest way to retrieve data in a JSON format.
- Schema-free, Simple to use, Nimble and In-Memory database.
- It is built on top of one of the fastest and real-time data indexing engine - PowerIndeX.
- It is low level (raw) form of data and is also human readable.
- It helps developers in faster coding, in-turn reduces development cost.
- We do not need to refresh the page everytime, because Javascript is used here.
- It's much better than RDBMS, because if we insert new row in it, then it will take it without any error.
- It's faster than MYSQL.
- Minimum development cost.
- Minimum time to market.
- Minimize the complexity of interoperability of different applications.
- Maximum data processing performance.
- minimize total cost of ownership.
- Includes document DB from MongoDB, key-value DB and Geospatial from Redis, RDBMS from MYSQL, Time series DB from Influx DB, Wide column stores from HBase.

## How to check released code:
Here in public_html folder, you can see the three subfolders of CSS, JS and Images. In CSS folder there is a .css file used for this form, in JS folder there is .js file which is the main file for storing all the functions used to perform operationa and in Images folder, there is a single image.
Here index.html is a frontend file to display the form.

### Screenshot of Dashboard:

![image](https://user-images.githubusercontent.com/63993424/233018534-1093264c-6553-43bb-8e1a-2f9b597315ed.png)

### Screenshot of Database:
![image](https://user-images.githubusercontent.com/63993424/233018808-2348a47b-6874-4653-96f1-212a7415fa99.png)

### Screenshot of Form page:
**This above heading in the form is moving, you can check it after opening index.html file**

![image](https://user-images.githubusercontent.com/63993424/233019022-93c85f54-d338-44ae-abf5-bb722a6c8ff7.png)

#### Reseting of buttons is also done as follows:
- At the starting, disable all the buttons
- If the roll number entered is not present in database, then enable save and reset button
- If the roll number entered is present in the database, then enable change and reset button

