# MyShoppingList

A Page for your own shopping list along side GoogleSheets. 
You can insert new values and read data from it.

Composed of HTML, CSS, Javascript(jquery).


## Getting Started

1. Create a new Google Sheet and have it's first row as column names for your list.
2. Give your sheet a name: at the buttom double click 'Sheet1' and rename it to whatever you want, and copy that name also to be the value of `var sheetName = ` under function doGet(e){ of GoogleScript.txt file.
3. Copy the Sheet's URL at the top (should end with **edit#gid=0**) and paste that URL as the value of `var sheetURL = ` under function doGet(e){ of GoogleScript.txt file.
4. Go to https://script.google.com/home and create a new script.
5. Paste content of GoogleScript.txt to the Code.gs editor, and save your script as a new project.
6. Click on **Publish** -> **Deploy as a WebApp** -> change `Who has access to the app:` to 'Anyone, even anonymous' and click on **Deploy** and approve all.
7. Copy the url address under **Current web app URL:** and paste as the value of `const SCRIPT_URL = ` under <script> tag of MyShoppingList.html file.
8. Edit column names at **readData** function of MyShoppingList.html file to be your sheet's column names.
9. Edit all other components of the HTML and Javascript code to match your desired page and ID names.
10. Run the page & Enjoy...

