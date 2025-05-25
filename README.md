# RPA_Ex-08

# Exercise-8-Basic-Web-Automation---Fill-a-Web-Form
~~~
Name : Subikshan p
Reg.No : 212223240161
~~~

## Aim
To create a UiPath workflow that automates the process of filling out a basic contact form on a website and submits the form using Web Automation techniques.

## Materials Required
UiPath Studio (Community or Enterprise Edition)

Google Chrome or Microsoft Edge (with UiPath Extension Installed)

A sample contact form URL (e.g., https://www.seleniumeasy.com/test/input-form-demo.html or any dummy form)

Internet connection

## Procedure
### Step 1: Launch the Browser
Open UiPath Studio and create a new project called WebFormAutomation.

Drag and drop the Use Application/Browser activity.

Indicate the browser window or enter the form URL manually in the Application Path:
~~~
https://www.seleniumeasy.com/test/input-form-demo.html
~~~
### Step 2: Fill Form Fields
Inside the Use Application/Browser, add multiple Type Into activities for each field.

Example:

Field	Type Into Value
First Name	"John"
Last Name	"Doe"
Email	"john.doe@example.com"
Phone	"9876543210"
Address	"123 Sample Street"
City	"Chennai"
Zip Code	"600001"

Use Click Before Typing and Activate options in Properties for accuracy.

### Step 3: Select Dropdown (Optional)
Use the Select Item activity to choose a state or country from a dropdown if present.

### Step 4: Submit the Form
Use a Click activity to click the Submit or Send button on the form.

### Step 5: Add Delay (Optional)
Add a Delay activity if the form takes time to load or submit.

## OUTPUT:
The bot will:
Open the web page
Fill out all fields with pre-defined data
Click the submit button

![8-1](https://github.com/user-attachments/assets/8464f7ef-06c6-44c8-9a18-f7b8d8cc0eab)

![8-2](https://github.com/user-attachments/assets/eb601585-30b2-4931-bff9-8f324946229b)

![8-3](https://github.com/user-attachments/assets/b3e748d0-c3af-4eff-ada8-ed0c1bc2fe2e)

![8-4](https://github.com/user-attachments/assets/9bec3f3b-a146-44fa-b4a4-5be33470c7c8)


## Result:
UiPath successfully automates form-filling tasks in a browser and submits a web-based contact form using Web Automation techniques.
