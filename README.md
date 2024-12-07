# Ex.05 Design a Website for Server Side Processing
## Date:

## AIM:
 To design a website to calculate the power of a lamp filament in an incandescent bulb in the server side. 


## FORMULA:
P = I<sup>2</sup>R
<br> P --> Power (in watts)
<br> I --> Intensity
<br> R --> Resistance

## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Create python programs for views and urls to perform server side processing.

### Step 5:
Create a HTML file to implement form based input and output.

### Step 6:
Publish the website in the given URL.

## PROGRAM :
```
<html>
    <head>
        <script>
            function check() {
                var i = parseFloat(document.getElementById('t1').value);
                var r =  parseFloat(document.getElementById('t2').value);
                var z= i*i*r;
                
                document.getElementById('result').innerText="Power:"+z
            }
        </script>
        <style>
            .box
            {
            background-color: rgb(94, 93, 92);
            width:30%;
            padding: 20px;
            margin: auto;
            
            }
        </style>
    </head>
    <body aria-setsize="20px" bgcolor="teal"><br><br><br><br><br><br><br><br>
        <div class="box" align="center"><br>
            <h1>Power</h1>
        <form fontsize="3px">
            <input type="number" placeholder="Intensity" id="t1" ><br><br>
            <input type="number" placeholder="Resistance" id="t2" ><br><br>
            <input type="button" value="calculate" onclick="check()" ><br><br>
            <label id="result"></label>
        </form>
        </div>
    </body>
    </html>
    ```

## SERVER SIDE PROCESSING:
```
    <script>
            function check() {
                var i = parseFloat(document.getElementById('t1').value);
                var r =  parseFloat(document.getElementById('t2').value);
                var z= i*i*r;
                
                document.getElementById('result').innerText="Power:"+z
            }
    </script>

```


## HOMEPAGE:
![alt text](<../Screenshot 2024-12-07 102929.png>)

## RESULT:
The program for performing server side processing is completed successfully.
