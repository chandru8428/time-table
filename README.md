# Ex03 Time Table
# Date:02/12/2024
# AIM
To write a html webpage page to display your slot timetable.

# ALGORITHM
## STEP 1
Create a Django-admin Interface.

## STEP 2
Create a static folder and inert HTML code.

## STEP 3
Create a simple table using <table> tag in html.

## STEP 4
Add header row using <th> tag.

## STEP 5
Add your timetable using <td> tag.

## STEP 6
Execute the program using runserver command.

# PROGRAM
....
<!DOCTYPE html>
<html style="color: rgb(235, 252, 9);font-weight: bolder ;">
    <p style="font-size: 130%;margin-left: 560px;font-family: sans-serif;color: aquamarine;text-shadow: 20px;">
         SLOT TIMETABLE - CHANDRU.K(24013579)</p>
    <center>
        <header> <img src="/static/WhatsApp Image 2024-10-14 at 04.19.24_14728869.jpg"></header>        
    </center>
    <center>
   
<table border="8" style="align-border: center; " cellpadding="20px">
        <body>
            <tr style=" background-color: rgb(240, 147, 33);">
                <th>TIME\<BR>DAY</th>
                <th>8AM-9AM</th>
                <th>9AM-10AM</th>
                <th>10AM-11AM</th>
                <th>11AM-12PM</th>
                <th>12PM-1PM</th>
                <th>1PM-2PM</th>
                <th>2PM-3PM</th>
                <th>3PM-4PM</th>
            </tr>
             <tr>
                <th style=" background-color: rgb(240, 147, 33);" >MON</th>
                <th>COM-ARCH</th>
                <th>WEB</th>
                <th>PUPLIC SPEAKING</th>
                <th>__</th>
                <th rowspan="6" style="writing-mode: vertical-rl; font-size: 25px; letter-spacing: 5px;" >L  U  N  C  H </th>
                <th>ENG</th>
                <th>CHE</th>
                <th>__</th>
             </tr>
             <tr>
                <th style=" background-color: rgb(240, 147, 33);">TUS</th>
                <th>ENG</th>
                <th>PUPLIC SPEAKING</th>
                <th>__</th>
                <th>COM-ARCH</th>
                <th>CHE</th>
                <th>MAT</th>
                <th>__</th>
             </tr>
             <tr>
                <th style=" background-color: rgb(240, 147, 33);">WED</th>
                <th>CHE</th>
                <th>PUPLIC SPEAKING</th>
                <th>__</th>
                <th>STATISTICS</th>
                <th>WEB</th>
                <th>__</th>
                <TH>COM-ARCH</TH>
             </tr>
             <tr>
                <th style=" background-color: rgb(240, 147, 33);">THS</th>
                <th>ENG</th>
                <th>PUPLIC SPEAKING</th>
                <th>COM-ARCH</th>
                <th>__</th>
                <th>CHE</th>
                <th>STATISTICS</th>
                <th>ENG</th>
             </tr>
             <tr>
                <th style=" background-color: rgb(240, 147, 33);">FRI</th>
                <th>STATISTICS</th>
                <th>__</th>
                <th>WEB</th>
                <th>WEB</th>
                <th>CHE</th>
                <th>PUPLIC SPEAKING</th>
                <th>__</th>
             </tr>
             <tr>
                <th style=" background-color: rgb(240, 147, 33);">SAT</th>
                <th>CHE</th>
                <th>PUPLIC SPEAKING</th>
                <th>__</th>
                <th>STATISTICS</th>
                <th>web</th>
                <th>__</th>
                <TH>ENG</TH>
             </tr>
             <tr>
                <th style=" background-color: rgb(240, 147, 33);">SUN</th>
                <th colspan="8" style="font-size: x-large;">H O L L Y  D A Y </th>
             </tr>
             <br>

<table border="5" cellpadding="8" cellspacing="2" align="center" style="margin-top:100px ;border-radius: 5px;font-weight: bolder;">
        <tr style="background-color: rgb(240, 147, 33);">
            <th>
                <h4>S.NO</h4>
            </th>
            <th>
                <h4>SUBJECT CODE </h4>
            </th>
            <th>
                <h4>SUBJECT NAME </h4>
            </th>
        </tr>
        <tr>
            <th style="background-color: rgb(240, 147, 33);">1.</th>
            <td>4S3-1</td>
            <td>PYTHON PROGRAMMING </td>
        </tr>
        <tr>
            <th style="background-color: rgb(240, 147, 33);" >2.</th>
            <td>4V1-2</td>
            <td>PUPLIC SPEAKING </td>
        </tr>
        <tr>
            <th  style="background-color: rgb(240, 147, 33);">3.</th>
            <td>4I3-1</td>
            <td>PRICIPLES OF CHEMISTRY IN ENGINEERING</td>
        </tr>
        <tr>
            <th  style="background-color: rgb(240, 147, 33);">4.</th>
            <td>4L1-1</td>
            <td>COMPUTER ARCHITECHTURE </td>
        </tr>
        <tr>
            <th  style="background-color: rgb(240, 147, 33);">5.</th>
            <td>4M3-1</td>
            <td>STATISTICS AND NUMERICALS METHODS </td>
        </tr>
        <tr>
            <th  style="background-color: rgb(240, 147, 33);">6.</th>
            <td>6J1-1</td>
            <td>FUNDAMENDALS OF WEB APPLICATION DEVELOPMENT </td>
 </tr>
</table>
</body>

</html>
             <style>
               table {
                  background-image: url("/static/book.png"); border-image-width: 15cm;
               border-color: rgb(236, 14, 14);
            border-radius: 28px; table-layout: initial;}
                  body {text-emphasis-color: rgb(181, 160, 177);}
             header {
               height: 5cm;: cm;
             }
             th{
                rgb(240, 147, 33)
             }
             </style>


 </body>
</table>
</center>
</html>
....

# OUTPUT
![alt text](<Screenshot 2024-12-02 125539.png>)

# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
