# Ex03 Time Table
## Date:14/03/2024
## NAME : NITHISH KUMAR S
## REG NO: 212223240109

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create a static folder and inert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html.

### STEP 4
Add header row using ```<th>``` tag.

### STEP 5
Add your timetable using ```<td>``` tag.

### STEP 6  `       
Execute the program using runserver command.

## PROGRAM
```
<html>
        <head>
                <title>My Time Table </title>
        </head>
        <body>
        <center>
            <img src="logo.png" height="100" width="540">
        </center>
        <br>
            <table align ="center" border="2" cellspacing="5" cellpadding="5" width="40" height="50">
                <tr>
                    <tr align ="center">
                    <th bgcolor="red">DAY/TIME</th>
                    <th bgcolor="orange">MONDAY</th>
                    <th bgcolor="yellow">TUESDAY</th>
                    <th bgcolor="green">WEDNESDAY</th>
                    <th bgcolor="blue">THURSDAY</th>
                    <th bgcolor="indigo">FRIDAY</th>
                    <th bgcolor="violet">SATURDAY</th>
                </tr>
                <tr>
                    <tr align ="center">
                    <th bgcolor ="red">8:00 to 10:00</th>
                    <th bgcolor ="orange">DE</th>
                    <th bgcolor ="yellow">INTRO TO ML</th>
                    <th bgcolor ="green">PROB</th>
                    <th bgcolor ="blue">FREE SLOT</th>
                    <th bgcolor ="indigo">WEB</th>
                    <th bgcolor ="violet">FREE SLOT</th>
                </tr>
                <tr>
                    <tr align ="center">
                    <th bgcolor ="red">10:00 to 12:00</th>
                    <th bgcolor ="orange">ROBOT</th>
                    <th bgcolor ="yellow">C PROG</th>
                    <th bgcolor ="green">FREE SLOT</th>
                    <th bgcolor ="blue">C PROG</th>
                    <th bgcolor ="indigo">FREE SLOT</th>
                    <th bgcolor ="violet">FREE SLOT</th>
                </tr>
                <tr>
                    <tr align ="center">
                    <th bgcolor ="red">1:00 to 3:00</th>
                    <th bgcolor ="orange">EMPD</th>
                    <th bgcolor ="yellow">WEB</th>
                    <th bgcolor ="green">FREE SLOT</th>
                    <th bgcolor ="blue">WEB</th>
                    <th bgcolor ="indigo">DE</th>
                    <th bgcolor ="violet">EMPD</th>
                </tr>
                <tr>
                    <tr align ="center">
                    <th bgcolor ="red">3:00 to 5:00</th>
                    <th bgcolor ="orange">PROB</th>
                    <th bgcolor ="yellow">FREE SLOT</th>
                    <th bgcolor ="green">FREE SLOT</th>
                    <th bgcolor ="blue">FREE SLOT</th>
                    <th bgcolor ="indigo">ROBOT</th>
                    <th bgcolor ="violet">FREE SLOT</th>
                </tr>
            </table>
        </br>
        <br>
            <table align="center" cellspacing="2" cellpadding="4" border="2">
                <tr>
                    <tr align="center">
                        <th>S. No.</th>
                        <th>Subject Code</th>
                        <th>Subject Name</th>
                </tr>
                <tr>
                    <td align="center">1.</td>
                    <td align ="center">19AI303</td>
                    <td>ENGINEERING MECHANICS AND PRODUCT DEVELOPMENT</td>
                </tr>
                <tr>
                    <td align="center">2.</td>
                    <td align ="center">19AI304</td>
                    <td>FUNDAMENTALS OF C PROGRAMMING</td>
                </tr>
                <tr>
                    <td align="center">3.</td>
                    <td align ="center">19AI410</td>
                    <td>INTRODUCTION TO MACHINE LEARNING</td>
                </tr>
                <tr>
                    <td align="center">4.</td>
                    <td align ="center">19AI414</td>
                    <td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
                </tr>
                <tr>
                    <td align="center">5.</td>
                    <td align ="center">19AI533</td>
                    <td>INTRODUCTION TO ROBOTICS</td>
                </tr>
                <tr>
                    <td align="center">6.</td>
                    <td align ="center">19EE404</td>
                    <td>DIGITAL ELECTRONICS</td>
                </tr>
                <tr>
                    <td align="center">7.</td>
                    <td align ="center">19MA222</td>
                    <td>PROBABILITY OF QUEUEING MODELS</td>
                </tr>
            </table>
        </br>
        </body>
</html>
```


## OUTPUT
![alt text](<Screenshot 2024-03-14 154155.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
