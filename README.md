# Ex03 Time Table
# Date:
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
'''
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>24010127</title>
    <link rel="icon" href="C:\Users\ravip\OneDrive\Desktop\HTML\TIMETABLE\download.jpg">
    <style>
        table {
            width: 60%;
            border-collapse: collapse;
            margin: 20px auto;
        }
        th, td {
            border: 2px solid black;
            text-align: center;
        }
        th {
            background-color:rgba(87, 186, 181, 0);
            height: 40px;
        }
        td {
            background-color: rgba(87, 186, 181, 0);
        }
        body{
            background-image: url(brown-wallpaper-with-retro-watch-design_1308-18196.jpg);
            background-size: cover;
            background-repeat: no-repeat;
            background-position: center;
        }
        span{
            writing-mode: vertical-lr;
            text-orientation: upright;
        }
    </style>
</head>
<body>
    <div style="display: flex;justify-content:right;" >
    <img src="WEB_LOGO-01.png" alt="TimeTable" width="600" height="100px">
</div>
    <h2 style="text-align: center;"><marquee>🕔🗒TIMETABLE - RAVIPRASATH K [24010127]🗒🕔</marquee></h1>
    <table align="right">
        <tr>
            <th>Days</th>
            <th>8AM to 10AM</th>
            <th>10Am to 12pm</th>
            <th>12PM to 1PM</th>
            <th>1PM to 3PM</th>
            <th>3PM to 5PM</th>
        </tr>
        <tr>
            <th>MONDAY</th>
            <TD>-</TD>
            <TD>19AI403</TD>
            <TD rowspan="6"><span>LUNCH</span></TD>
            <TD>19AI414</TD>
            <TD>-</TD>
        </tr>
        <TR>
            <TH>TUESDAY</TH>
            <TD>-</TD>
            <TD>SH3214</TD>
            <TD>19AI304</TD>
            <TD>-</TD>
        </TR>
        <TR>
            <TH>WEDNESDAY</TH>
            <TD>-</TD>
            <TD>19EY708</TD>
            <TD>-</TD>
            <TD>19CY205</TD>
        </TR>
        <TR>
            <TH>THURSDAY</TH>
            <TD>-</TD>
            <TD>19AI304</TD>
            <TD>19AI403</TD>
            <TD>19CY205</TD>
        </TR>
        <TR>
            <TH>FRIDAY</TH>
            <TD>-</TD>
            <TD>19AI414</TD>
            <TD>SH7801</TD>
            <TD>-</TD>
        </TR>
        <TR>
            <TH>SATURDAY</TH>
            <TD>-</TD>
            <TD>19AI414</TD>
            <TD>SH3214</TD>
            <TD>-</TD>
        </TR>
</table>
<table align="right" style="height: 50px;">
    <tr>
        <th>SUBJECT CODE</th>
        <th>NAME OF THE SUBJECT</th>
    </tr>
    <tr>
        <td>19AI403</td>
        <td>Introduction of Data Science</td>
    </tr>
    <tr>
        <td>19AI414</td>
        <td>Fundamentals of Web Application Development</td>
    </tr>
    <tr>
        <td>19AI304</td>
        <td>Fundamentals of C Programming</td>
    </tr>
    <tr>
        <td>SH3214</td>
        <td>Physics for Quantum Computing</td>
    </tr>
    <tr>
        <td>SH7801</td>
        <td>Human Values and Professional Ethics</td>
    </tr>
    <tr>
        <td>19EY708</td>
        <td>Career Development</td>
    </tr>
    <tr>
        <td>19CY205</td>
        <td>Principles of Chemistry in Engineering</td>
    </tr>
</table>
    </body>
</html>
'''
# OUTPUT
![image](https://github.com/user-attachments/assets/47681eb2-cc9a-41e2-bc55-c699df9ea929)

# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
