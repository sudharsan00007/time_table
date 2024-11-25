![Screenshot 2024-11-25 132000](https://github.com/user-attachments/assets/d25a38fb-b1e0-47bb-84a5-5b220f7a437a)# Ex03 Time Table
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

# PROGRAM sudharsan.s
          24009664

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SLOT TIMETABLE - Sudharsan S (24009664)</title>
    <style>
        table {
            border-collapse: collapse;
            width: 100%; /* Set table width to match image width */
        }

        th, td {
            border: 8px solid black;
            padding: 6.5px;
            text-align: center;
        }

        th {
            background-color: palegoldenrod;
        }

        .day {
            background-color: green;
        }

        img {
            width: 100%; /* Set image width to match table width */
            height: auto;
        }
    </style>
</head>
<body>
    <h1>SLOT TIME TABLE - SUDHARSAN S</h1>

    <img src="C:\Users\sudharshan\OneDrive\Pictures\Screenshots\Screenshot 2024-10-19 110840.png" alt="Timetable Logo">
    
    <table>
        <thead>
            <tr>
                <th>TIME</th>
                <th>MONDAY</th>
                <th>TUESDAY</th>
                <th>WEDNESDAY</th>
                <th>THURSDAY</th>
                <th>FRIDAY</th>
                <th>Saturday</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>8:00 AM - 10:00 AM</td>
                <td>DIGITAL</td>
                <td>ENVIRONMENTAL SCIENCE</td>
                <td>FREE HOUR</td>
                <td>ML</td>
                <td>ML</td>
                <td>FREE HOUR</td>
            </tr>
            <tr>
                <td>10:00 AM - 12:00 PM</td> <!-- Fixed AM/PM format -->
                <td>PHYSICS</td>
                <td>FREE HOUR</td>
                <td>PYTHON PROGRAMMING</td> <!-- Fixed typo -->
                <td>MATHS</td>
                <td>WEB APPLICATIONS</td>
                <td>WEB</td>
            </tr>
            <tr>
                <td>12:00 PM - 1:00 PM</td>
                <td colspan="6">LUNCH</td>
            </tr>
            <tr>
                <td>1:00 PM - 3:00 PM</td>
                <td>WEB</td>
                <td>DIGITAL</td>
                <td>FREE HOUR</td>
                <td>PHYSICS</td>
                <td>PYTHON</td>
                <td>PROBABILITY</td>
            </tr>
        </tbody>
    </table>

    <br><br>

    <h1>Subject Code</h1>
    <table>
        <thead>
            <tr>
                <th>S.No</th>
                <th>Subject Code</th>
                <th>Subject Name</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>1</td>
                <td>SH3214</td>
                <td>Quantum Physics</td>
            </tr>
            <tr>
                <td>2</td>
                <td>19MA222</td>
                <td>Maths</td>
            </tr>
            <tr>
                <td>3</td>
                <td>19EE404</td>
                <td>Digital Electronics</td>
            </tr>
            <tr>
                <td>4</td>
                <td>19CS420</td>
                <td>IOT</td>
            </tr>
            <tr>
                <td>5</td>
                <td>19AI414</td>
                <td>Web Application</td>
            </tr>
            <tr>
                <td>6</td>
                <td>19AI410</td>
                <td>Machine Learning</td>
            </tr>
            <tr>
                <td>7</td>
                <td>19AI301</td>
                <td>Python Programming</td>
            </tr>
        </tbody>
    </table>
</body>
</html>

# OUTPUT
![Screenshot 2024-11-25 133110](https://github.com/user-attachments/assets/f8003780-d779-4695-ae9a-f0c601e6a975)
![Screenshot 2024-11-25 133139](https://github.com/user-attachments/assets/3b11ceaf-df3b-4938-8946-6fa77ef30465)


# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
