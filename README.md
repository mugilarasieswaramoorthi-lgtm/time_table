# Ex03 Time Table
# Date:26/09/2025
# AIM
To write a html webpage page to display your slot timetable.

# ALGORITHM
## STEP 1
Create a Django-admin Interface.

## STEP 2
Create a static folder and inert HTML code.

## STEP 3
Create a simple table using `<table>` tag in html.

## STEP 4
Add header row using `<th>` tag.

## STEP 5
Add your timetable using `<td>` tag.

## STEP 6
Execute the program using runserver command.

# PROGRAM
```
<html>
    <head>
        <title>
            Timetable
        </title>
    </head>
    <body>
        <img src="c:\Users\acer\Downloads\saveetha-engineering-college-(sriperumbudur)-chennai.png "width="50%">
        <table border="1px" cellpadding="20px" cellspacing="3px" align="center" bgcolor="pink"
           <caption><b><i>SLOT TIME TABLE-MUGILARASI E (25017644) </i> </b> </capyion>
           <tr bgcolor="baby pink">
               <th>DAY </th>
               <th>8-10</th>
               <th>10-12</th>
               <th rowspan= "7" bgcolor="pink">LUNCH</th>
               <th>1-3</th>
               <th>3-5</th>
           </tr>
           <tr>
               <th>Monday</th>
               <td>FREE</td>
               <td>WEB</td>
               <td>FREE</td>
               <td>PYTHON</td>
           </tr>
           <tr>
               <th>Tuesday</th>
               <td>WEB</td>
               <td>ML</td>
               <td>WEB</td>
               <td>FREE</td>
           </tr>
           <tr>
               <th>Wednesday</th>
               <td rowspan ="2">ML</td>
               <td rowspan ="2">PYTHON</td>
               <td>MENTOR MEET</td>
               <td>ML</td>
           </tr>
           <tr>
               <th>Thursday</th>
               <td>FREE</td>
               <td>FREE</td>
           </tr>
           <tr>
               <th>Friday</th>
               <td>PYTHON</td>
               <td>FREE</td>
               <td>WEB</td>
               <td>FREE</td>
           </tr>
           <tr>
               <th>Saturday</th>
               <td>WEB</td>
               <td>ML</td>
               <td>FREE</td>
               <td>PYTHON</td>
           </tr>
        </table>
        <table style="margin-top: 2cm;" border="1px" cellpadding="20px" cellspacing="3px" align="center" bgcolor="skyblue">
            <tr bgcolor="white">
            <th>S.NO</th>
            <th>COURSE CODE</th>
            <th>COURSE NAME</th>
        </tr>
        <tr>
            <td>1</td>
            <td>19AI414</td>
            <td>FUNDAMENTALS OF WEB APPLICATION(WEB)</td>
        </tr>
        <tr>
            <td>2</td>
            <td>19AI410</td>
            <td>MACHINE LEARNING(ML)</td>
        </tr>
        <tr>
            <td>3</td>
            <td>19AI301</td>
            <td>PYTHON</td>
        </tr>
        </table>
    </body>
</html>
```
# OUTPUT
![alt text](<Screenshot 2025-09-26 141133.png>)


# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
