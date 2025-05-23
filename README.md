# Ex03 Time Table
## Date: 23.04.2025

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

### STEP 6
Execute the program using runserver command.

## PROGRAM

```
<html>
    <body>
        <center><img src="/static/logo.png" height="100px" width="650px"></center>
        <h3 align="center"> SLOT TIME-TABLE :D.BALA SUBRAMANYAM(212224040062)</h3>
        <table border="1px" align="center" bgcolor="skyblue">
            <tr bgcolor="yellow"><th>DAY/TIME</th><th>MONDAY</th><th>TUESDAY</th><th>WEDNESDAY</th><th>THURSDAY</th><th>FRIDAY</th><th>SATURDAY</th></tr>
            <tr><td align="center" bgcolor="yellow">8-10</td><td align="center">OS</td><td align="center">-</td><td align="center">-</td><td align="center">OS</td><td align="center">-</td><td align="center">-</td></tr>
            <tr><td align="center" bgcolor="yellow">10-12</td><td align="center">DS</td><td align="center">SE</td><td align="center">WEB</td><td align="center">SE</td><td align="center">-</td><td align="center">DS</td></tr>
            <tr><td align="center" bgcolor="yellow">12-1</td><td align="center" colspan="6">LUNCH BREAK</td>
            <tr><td align="center" bgcolor="yellow">1-3</td><td align="center">PHY</td><td align="center">QA1</td><td align="center">MENTOR</td><td align="center">PP</td><td align="center">PP</td><td align="center">-</td></tr>
            <tr><td align="center" bgcolor="yellow">3-5</td><td align="center">-</td><td align="center">-</td><td align="center">PHY</td><td align="center">-</td><td align="center">WEB</td><td align="center">-</td></tr>
       </table>
       <br>
       <hr>
       <br>
       <table border="1px" align="center">
        <tr><th>S.No</th><th>SUB CODE</th><th>SUBJECT NAME</th></tr>
        <tr><td align="center">01.</td><td align="center">19AI301</td><td align="center">PYTHON PROGRAMMING (PP)</td></tr>
        <tr><td align="center">02.</td><td align="center">19AI403</td><td align="center">INTRODUCTION TO DATA SCIENCE (DS)</td></tr>
        <tr><td align="center">03.</td><td align="center">19AI414</td><td align="center"> FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT (WEB) </td></tr>
        <tr><td align="center">04.</td><td align="center">19PH814</td><td align="center">PHUSICS FOR QUANTUM COMPUTING (PHY)</td></tr>
        <tr><td align="center">05.</td><td align="center">19CS408</td><td align="center">SOFTWARE ENGINEERING (SE)</td></tr>
        <tr><td align="center">06.</td><td align="center">19CS405</td><td align="center">OPERATING SYSTEM (OS)</td></tr>
        <tr><td align="center">07.</td><td align="center">19EY710</td><td align="center">QUANTITATIVE ABILITY 1 (QA1)</td></tr>

        </table>
    </body>
</html>
```

## OUTPUT

![alt text](<Screenshot (8).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
