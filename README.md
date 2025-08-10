# Date:
09.08.25
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
Add header row using `<th>` tag.

## STEP 5
Add your timetable using `<td>` tag.

## STEP 6
Execute the program using runserver command.

# PROGRAM sudharsan.s (212224040335)
<!DOCTYPE html>
<html>
<head>
    <title>Slot Time Table</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
        }
        table {
            border-collapse: collapse;
            margin: auto;
        }
        table, th, td {
            border: 2px solid black;
        }
        th {
            background-color: yellow;
        }
        td {
            background-color: cyan;
            padding: 10px;
        }
        .free {
            background-color: cyan;
        }
        .header {
            background-color: yellow;
            font-weight: bold;
        }
    </style>
</head>
<body>

    <!-- College Logo Header -->
    <img src="c:\Users\sudharshan\OneDrive\Documents\micro folder\OneDrive\Pictures\Screenshots 1\Screenshot 2024-10-19 110840.png"alt="Saveetha Engineering College" style="width:100%;max-width:900px;">

    <h3>SLOT TIME TABLE - SUDHARSAN.S (212224040335)</h3>

    <table>
        <tr class="header">
            <th>Day/Time</th>
            <th>8-10</th>
            <th>10-12</th>
            <th>12-1</th>
            <th>1-3</th>
            <th>3-5</th>
        </tr>
        <tr>
            <th>Monday</th>
            <td>Computer Architecture (19CS305)</td>
            <td>FREE SLOT</td>
            <td rowspan="6">LUNCH</td>
            <td>Fundamentals of C Programming (19AI304)</td>
            <td>Computer Networks (19CS406)</td>
        </tr>
        <tr>
            <th>Tuesday</th>
            <td colspan="4">LEAVE</td>
        </tr>
        <tr>
            <th>Wednesday</th>
            <td>Cryptography (19CS415)</td>
            <td>Fundamentals of C Programming (19AI304)</td>
            <td>Mentor Meet</td>
            <td>Financial Accounting (19MS154) <br> (4-5 PM)</td>
        </tr>
        <tr>
            <th>Thursday</th>
            <td class="free">FREE SLOT</td>
            <td>Computer Networks (19CS406)</td>
            <td>Cryptography (19CS415)</td>
            <td>Computer Architecture (19CS305)</td>
        </tr>
        <tr>
            <th>Friday</th>
            <td class="free">FREE SLOT</td>
            <td>DBMS (19CS404)</td>
            <td>FOWA (19AI414)</td>
            <td class="free">FREE SLOT</td>
        </tr>
        <tr>
            <th>Saturday</th>
            <td>FOWA (19AI414)</td>
            <td>Financial Accounting (19MS154)</td>
            <td class="free">FREE SLOT</td>
            <td>DBMS (19CS404)</td>
        </tr>
    </table>

    <br><br>

    <table>
        <tr>
            <th>S. No.</th>
            <th>Subject Code</th>
            <th>Subject Name</th>
        </tr>
        <tr><td>1</td><td>19CS305</td><td>Computer Architecture</td></tr>
        <tr><td>2</td><td>19AI304</td><td>Fundamentals of C Programming</td></tr>
        <tr><td>3</td><td>19CS406</td><td>Computer Networks</td></tr>
        <tr><td>4</td><td>19CS415</td><td>Cryptography</td></tr>
        <tr><td>5</td><td>19MS154</td><td>Financial Accounting</td></tr>
        <tr><td>6</td><td>19CS404</td><td>Database Management Systems</td></tr>
        <tr><td>7</td><td>19AI414</td><td>Fundamentals of Web Application Development</td></tr>
    </table>

</body>
</html>

         

    <h1>SLOT TIME TABLE - SUDHARSAN S</h1>
    

   

# OUTPUT

<img width="1919" height="1199" alt="image" src="https://github.com/user-attachments/assets/9cd2ccf6-f7ae-4c4b-af79-cc458b839854" />


# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
