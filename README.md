# Ex02 Time Table
# Date:24/12/25
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
time_table.html:

<html>

<head>
    <title>Timetable</title>
</head>
<body>
    <center>
        <img src="logo.png.png" height="150" width="700">
    </center>

    <table align="center" bgcolor="green" border="2" cellspacing="5" cellpadding="5">
        <caption>Slot Time Table - M.Dinesh (25007655)</caption>

        <tr align="center" bgcolor="red">
            <th>Day/Time</th>
            <th>Monday</th>
            <th>Tuesday</th>
            <th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
            <th>Saturday</th>
        </tr>

        <tr>
            <th bgcolor="yellow">8-10</th>
            <td>public speaking</td>
            <td>public speaking</td>
            <td>FREE SLOT</td>
            <td>FREE SLOT</td>
            <td>FREE SLOT</td>
            <td> python Programming</td>

        </tr>

        <tr>
            <th bgcolor="yellow">10-12</th>
            <td>FREE SLOT</td>
            <td>python Programming</td>
            <td>public speaking</td>
            <td>FREE SLOT</td>
            <td>web application</td>
            <td>FREE SLOT</td>
        </tr>

        <tr>
            <th bgcolor="yellow">12-1</th>
            <td colspan="6">LUNCH TIME</td>
        </tr>

        <tr>
            <th bgcolor="yellow">1-3</th>
            <td>web application</td>
            <td>FREE SLOT</td>
            <td>mentor meet</td>
            <td>FREE SLOT</td>
            <td>FREE SLOT</td>
            <td>web Application</td>
        </tr>

        <tr>
            <th bgcolor="yellow">3-5</th>
            <td>FREE SLOT</td>
            <td>python Programing</td>
            <td>python pragraming</td>
            <td>python Programing </td>
            <td>web application</td>
            <td>web application</td>
        </tr>
    </table>

    <br>

    <table align="center" bgcolor="red" border="2" cellspacing="5" cellpadding="5">
        <tr>
            <th>S.NO</th>
            <th>SUBJECT CODE</th>
            <th>SUBJECT NAME</th>
        </tr>
        <tr>
            <td>1</td>
            <td>19AI414</td>
            <td>Fundamentals of Web Application Development (FWAD)</td>
        </tr>
        <tr>
            <td>2</td>
            <td>19AI301</td>
            <td>Python Programming (pyt)</td>
        </tr>
        <tr>
            <td>3</td>
            <td>19EN105</td>
            <td>public speaking (eng)</td>
        </tr>
    </table>
</body>
</html>

# OUTPUT
<img width="1913" height="1077" alt="image" src="https://github.com/user-attachments/assets/4f7e9a87-f1aa-4260-80c7-63f905378676" />


# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
