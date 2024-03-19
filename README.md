# Ex03 Time Table
## Date:19.03.2024

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
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Slot Timetable</title>
    <style>
      .table1 {
        background-color: rgb(244, 135, 213);
        border-color: gray;
        text-align: center;
        width: 1200px;
        height: 250px;
      }

      .table2 {
        border-color: gray;
        text-align: center;
        width: 1200px;
        height: 250px;
      }

      .name {
        padding-left: 185px;
      }

      .row1 {
        background-color:rebeccapurple;
      }

      .c1 {
        background-color: rgb(201, 201, 85);
      }
      .x{
        background-color: rgb(120, 175, 234);
      }
    </style>
  </head>

  <body>
    <img
      src="logo.png" height="200" width="1200"/>
    <h3 class="name">SLOT TIMETABLE - Charitha K (212221040068)</h3>
    <table border="1" class="table1">
      <tr class="row1">
        <th class="c1">Day/Time</th>
        <th>Monday</th>
        <th>Tuesday</th>
        <th>Wednesday</th>
        <th>Thursday</th>
        <th>Friday</th>
        <th>Saturday</th>
      </tr>
      <tr>
        <td class="c1">8-10</td>
        <td>FS</td>
        <td>Ethical Hacking</td>
        <td colspan="2">FS</td>
        <td>WEB</td>
        <td>MPMC</td>
        
      </tr>
      <tr>
        <td class="c1">10-12</td>
        <td>MPMC</td>
        <td>SPM</td>
        <td>FS</td>
        <td>SPM</td>
        <td>YOGA</td>
        <td>FS</td>
      </tr>
      <tr>
        <td class="c1">12-1</td>
        <th colspan="6" class="x">LUNCH BREAK</th>
      </tr>
      <tr>
        <td class="c1">1-3</td>
        <td>DS</td>
        <td>WEB</td>
        <td>MPMC</td>
        <td>WEB</td>
        <td>AQLR</td>
        <td>ETHICAL HACKING</td>
       
      </tr>
      <tr>
        <td class="c1">3-5</td>
        <th colspan="5">FS</th>
        <td>DS</td>
      </tr>
    </table>
    <br />
    <br />
    <table border="1" class="table2">
      <tr>
        <th>S.No.</th>
        <th>Subject Code</th>
        <th>Subject Name</th>
      </tr>
      <tr>
        <td>1.</td>
        <td>19EC408</td>
        <td>Microprocessor and Microcontroller (MPMC)</td>
      </tr>
      <tr>
        <td>2.</td>
        <td>19AI403</td>
        <td>Introduction To DS(DS)</td>
      </tr>
      <tr>
        <td>3.</td>
        <td>19CS417</td>
        <td>Ethical Hacking</td>
      </tr>
      <tr>
        <td>4.</td>
        <td>19AI414</td>
        <td>Fundamentals of Web Applications Development (WEB)</td>
      </tr>
      <tr>
        <td>5.</td>
        <td>19CS504</td>
        <td>Software Project Management(SPM)</td>
      </tr>
      <tr>
        <td>6.</td>
        <td>19EN616</td>
        <td>Yoga And Meditation</td>
      </tr>
      <tr>
        <td>7.</td>
        <td>19EY704</td>
        <td>Advanced Quantitative and Logical Reasoning</td>
      </tr>
    </table>
  </body>
</html>
```


## OUTPUT
![alt text](<Screenshot 2024-03-19 132246.png>)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
