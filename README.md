# Design of a Standard Calculator

## AIM:

To design a web application for a standard calculator.

## DESIGN STEPS:

### Step 1:
Clone the github repository and create the Django Admin interface.

### Step 2:
Change the settings.py file to allow request from all hosts.

### Step 3:
Use CSS for creating attractive colors.

### Step 4:
Write Java Script for implementing five diffrent operations.

### Step 5:
Validate the HTML and CSS code.

### Step 6:
Publish the website in the given URL. 

## PROGRAM :
  ### CSS:#style.css:
     ```
     *{
    margin: 0;
    padding: 0;
    font-family: 'Poppins', sans-serif;
    box-sizing: border-box;
}


.container{
    width: 100%;
    height: 100vh;
    background: #e3f9ff;
    display: flex;
    align-items: center;
    justify-content: center;
}
.calculator{
    background: #3a4452;
    padding: 20px;
    border-radius: 10px;
}
.calculator form input{
    border: 0;
    outline: 0;
    width: 60px;
    height: 60px;
    border-radius: 10px;
    box-shadow: -8px -8px 15px rgba(255, 255, 255, 0.1),5px 5px 15px rgba(0, 0, 0, 0.2);
    background: transparent;
    font-size: 20px;
    color: yellow;
    cursor: pointer;
    margin: 10px;
}

form .display{
    display: flex;
    justify-content: flex-end;
    margin: 20px 0;
}
form .display input{
    text-align: right;
    flex: 1;
    font-size: 45px;
    box-shadow: none;
}
form input.equal{
    width: 145px;
}



form input.operator{
    color: #33ffd8;
}
```
### calc.html:
 ```
  *{
  margin: 0;
  padding: 0;
  font-family: 'Poppins', sans-serif;
  box-sizing: border-box;
}


.container{
  width: 100%;
  height: 100vh;
  background: #e3f9ff;
  display: flex;
  align-items: center;
  justify-content: center;
}
.calculator{
  background: #3a4452;
  padding: 20px;
  border-radius: 10px;
}
.calculator form input{
  border: 0;
  outline: 0;
  width: 60px;
  height: 60px;
  border-radius: 10px;
  box-shadow: -8px -8px 15px rgba(255, 255, 255, 0.1),5px 5px 15px rgba(0, 0, 0, 0.2);
  background: transparent;
  font-size: 20px;
  color: yellow;
  cursor: pointer;
  margin: 10px;
}

form .display{
  display: flex;
  justify-content: flex-end;
  margin: 20px 0;
}
form .display input{
  text-align: right;
  flex: 1;
  font-size: 45px;
  box-shadow: none;
}
form input.equal{
  width: 145px;
}



form input.operator{
  color: #33ffd8;
}
```
### index.js:
  ```js // This function clear all the values
function clearScreen() {
    document.getElementById("result").value = "";
}
 
// This function display values
function display(value) {
    document.getElementById("result").value += value;
}
 
// This function evaluates the expression and returns result
function calculate() {
    var p = document.getElementById("result").value;
    var q = eval(p);
    document.getElementById("result").value = q;
}
```

## OUTPUT:
![Screenshot from 2023-12-19 01-23-27](https://github.com/RAGULRAAJAN/standard-calculator/assets/147473144/d4e2bfce-eb3d-476f-aa80-f7b93536ae12)

## Result:
Thus the program has been executed successfully.
