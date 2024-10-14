Activity 45: Research CSS GRID
apply it on 5 pages (ex. list of products, list of employees, list of students, etc.) - name your repo CSS_GRID - add documentation on README.md of your repo - Submit GitHub repositories

Step 1: Project Structure You can organize your project files as follows: CSS_GRID/ │ ├── index.html # Home page to link other pages ├── products.html # Page with a product list using CSS Grid ├── employees.html # Page with a list of employees using CSS Grid ├── students.html # Page with a list of students using CSS Grid ├── gallery.html # Page with a photo gallery using CSS Grid ├── contact.html # Page with a contact form using CSS Grid ├── styles.css # Main CSS file containing Grid styles └── README.md

Step 2: Create HTML and CSS Files Here are example layouts, code snippets, and descriptions for each of the pages.

Home Page (index.html) This page links to all other pages.
<title>Home</title>
Welcome to CSS Grid Showcase
List of Products
List of Employees
List of Students
Photo Gallery
Contact Form
Products List (products.html) This page displays a grid of products.
<title>List of Products</title>
Products
Product 1
Product 2
Product 3
Product 4
Product 5
Product 6
Employees List (employees.html) This page displays employee cards.
<title>List of Employees</title>
Employees
Employee 1
Employee 2
Employee 3
Employee 4
Students List (students.html) This page showcases student profiles.
<title>List of Students</title>
Students
Student 1
Student 2
Student 3
Student 4
Student 5
Photo Gallery (gallery.html) A grid layout for images.
<title>Photo Gallery</title>
Gallery
Image 1
Image 2
Image 3
Image 4
Contact Form (contact.html
A simple contact form structured with CSS Grid.

<title>Contact Form</title>
Contact Us
Name:
Email:
Style the Pages with CSS (styles.css)

Here’s how to style the pages using CSS Grid:

{ box-sizing: border-box; }
body { font-family: Arial, sans-serif; margin: 0; padding: 20px; }

.grid-container { display: grid; grid-template-columns: repeat(auto-fill, minmax(150px, 1fr)); gap: 10px; }

.grid-item { background-color: #f1f1f1; border: 1px solid #ccc; padding: 20px; text-align: center; border-radius: 5px; }

form { display: grid; grid-template-columns: 1fr 2fr; gap: 10px; }

(CSS_GRID)

This repository showcases different layouts using CSS Grid. The project includes five pages demonstrating how to use CSS Grid for responsive design.

Pages Included
Home: Links to all other pages.
List of Products: Displays products in a grid layout.
List of Employees: Shows employee cards in a grid layout.
List of Students: Displays student profiles in a grid.
Gallery: A photo gallery organized with CSS Grid.
Contact Form: A simple contact form designed with Grid.
How to View
Clone this repository and open the HTML files in your web browser.

Technologies Used
HTML
CSS
AND THE LAST

Commit and Push to GitHub Open your terminal or command prompt. Navigate to your project folder containing the files. Run the following commands to initialize git, add, commit, and push the files to your GitHub repository:

git init
git add . 
git commit -m "Css Grid" 
git branch -M main 
git remote add originhttps://github.com/jinat123/Research-CSS-GRID.git 
git push -u origin main
