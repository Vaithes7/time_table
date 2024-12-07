 # Ex03 Time Table
# Date:07.10.2024
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
<!DOCTYPE html>
<html lang="en-us"></html>
    <head>
        <title>Time Table  Vaitheswaran N (24901212)</title>
        <style>
            table, th, td{
                border: 6px gray;
                border-style: groove;
                border-collapse: collapse;
                margin: auto;
                text-align: center;
                width: 900px; ;
            }
            td{
                padding: 10px
            }
         body{
            background-color: lightblue;

         }
         
         th{
            background-color: aqua;

         }
         td{
            background-color: rgb(0, 0, 0);
            color: aqua;
         }
          .ta2{
            border-style: solid;
            border-collapse: collapse;
            border-width: 2px;
            width: 800px;;
          }
            
        </style>
    </head>
    <body>
        <header><img src="c:\Users\admin\Downloads\sec-logo-.png" width="1500" height="190"></header>
      <h1 style="text-align: center">Time Table Vaitheswaran N (24901212)</h1>
        <table>
            <tr>
                <th>Day/Period</th>
                <th>1 <br> 8.00-10.00</th>
                <th>2 <br> 10.00-12.00</th>
                <th>3 <br> 12.00-1.00</th>
                <th>4 <br> 1.00-3.00</th>

            </tr>
            <tr>
                <th>Monday</th>
                <td>Free</td>
                <td>Eng</td>
                <td rowspan="6" style="  writing-mode: vertical-rl;
                text-orientation: upright;"> LUNCH </td>
                <td>Web Application</td>
                

            </tr>
            <tr>
                <th>Tuesday</th>
                <td>EDM</td>
                <td>Phy</td>
                <td>C Programming</td>

            </tr>    
            <tr>
                <th>Wednesday</th>
                <td>EDM</td>
                <td>DE</td>
                <td>Mentor Meet</td>

            </tr>   
            <tr>
                <th>Thrusday</th>
                <td>Eng</td>
                <td>C Programming</td>
                <td>Career Developement</td>

                 </tr>
            <tr>
                <th>Friday</th>
                <td>Phy</td>
                <td>Web Application</td>
                <td>Free</td>
                
            </tr>
            <tr>
                <th>Saturday</th>
                <td>DE</td>
                <td>Web Application</td>
                <td>Free</td>
            </tr>
        </table>
        <br><br><br><br>


        <table class="ta2">
            <tr>
                <th>S.NO</th>
                <th>SUB CODE</th>
                <th>SUN NAME</th>
            </tr>
            <tr>
                <td>1</td>
                <td>SH3214</td>
                <td>Physics For Quantum Computing</td>
            </tr>
            <tr>
                <td>2</td>
                <td>19EY708</td>
                <td>Career Developement Skills</td>
            </tr>
            <tr>
                <td>3</td>
                <td>19EN101</td>
                <td>Communicative English</td>
            </tr>
            <tr>
                <td>4</td>
                <td>19EE404</td>
                <td>Digital Electronics</td>
            </tr>
            <tr>
                <td>5</td>
                <td>19AI414</td>
                <td>Fundamentals of Web Application Developement</td>
            </tr>
            <tr>
                <td>6</td>
                <td>19AI304</td>
                <td>Fundamentals of C Programming</td>
            </tr>
            <tr>
                <td>7</td>
                <td>19AI302</td>
                <td>Engineering Design and Modelling</td>
            </tr>
            


        </table>
    </body>
    </html>
```

    


# OUTPUT



![screencapture-file-C-Users-admin-Desktop-HTML-Vaithes-TT2-html-2024-12-02-23_08_58](https://github.com/user-attachments/assets/32ce4be6-c2e6-4407-a3bc-8c4a0270f697)




# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
