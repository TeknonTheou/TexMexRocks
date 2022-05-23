# PYTHON LIVE PROJECT

<h2>TexMexRocks</h2>
<ul>
  <li><p><a href="#intro">Introduction</a></p></li>
 <li> <p><a href="#CRUD">CRUD Functionality</a></p></li>
  <li><p><a href="#scrape">Web Scraping</a></p></li>
  <li><p><a href="#api">API</a></p></li>
 <li><p><a href="#front">Front End Development</a></p></li>


<li><h3 id="intro">Introduction</h3></li>
During the time period of May 9-20, 2022, I took part in a live coding project, designing a web-application in PyCharm, using the Python web framework Django.  This project used Agile methodologies including scrum, daily standups, and weekly code retrospectives in a 2 week (10 business days) sprint environment.  For my project, I selected to create a user-editable recipe database themed on TexMex cuisine, with API and Beautiful Soup scraping functionality. Stories were assigned using Azure DevOps boards.

<li><h3 id="CRUD">CRUD Functionality</h3></li>
For this project the completed app was required to meet minimum CRUD functionality, allowing a user to add their own entries, as well as reading, updating, and deleting existing records using a user-friendly interface.

<li><h4>Create</h4></li>
The project began with creating the model upon which the app would be built, adding a migration, and planning out all the categories to track for the object. This requirement included creagting an objects manager for accessing the database.

I also created a model form to include any inputs the user needs to make, and added templates to my app folder for creating a new item. A views function was made that renders the create page and utilizes the model form to save the collection item to a relational database using SQLite.
  
  
  ![image](https://user-images.githubusercontent.com/99988665/169723675-dbf6e6b6-28de-4cb5-aa6b-a491bf0cd11a.png)


<li><h4>Read</h4></li>
In this stage, I created a new HTML page, linked from my home page, to display a list of all items in the database. A function was added that gets all the items from the database and sends them to the template.

I also added a details template to the template folder, and registered the template to the url pattern. A views function was created to find a single item from the database and send it to the template.

I added in a link for each item on the list page that directed the user to the details page for that item, on which ALL recorded details of the item were displayed.

 ![image](https://user-images.githubusercontent.com/99988665/169723873-f6de80c8-5a4f-404f-ba96-efacff669f4d.png)


<li><h4>Update and Delete</h4></li>
At this stage in the project, I added an edit page to the templates and url patterns, using model forms and instances to display the content of a single item from the database, and having a views function send the information for the single item and save any changes. I also included the option to delete an item, with a confirmation that the user wants to delete.

 ![image](https://user-images.githubusercontent.com/99988665/169723950-1d55b4e3-50e1-49ac-ab4d-91bb26a581dc.png)

<li><h3 id="api">API</h3></li>
In this story, I connected to the "Tasty" API to receive a JSON response, and added in a template for displaying the information. This involved creating the template and rendering with a function, going through the API documentation connecting to the API, parsing the JSON response and sending the desired elements to the template. The API request page was then linked to the app's navigation bar.
  
 ![image](https://user-images.githubusercontent.com/99988665/169723987-912dd6e2-5d79-48bd-9776-5087ae9891fd.png)

<li><h3 id="scrape">Web Scraping</h3></li>
For this segment of the project, I used Beautiful Soup to scrape info for my favorite recipes on AllRecipes.com, and added in another template for displaying the information. This involved creating the template and rendering with a function, parsing the Beautiful Soup html info, and sending the desired elements to the template. The Beautiful Soup scraping page was also linked to the app's navigation bar.
  
 ![image](https://user-images.githubusercontent.com/99988665/169724041-9fdaaf91-1cb1-4303-8155-5bf1bb46f100.png)


<li><h3 id="front">Front End Development</h3></li>
The final stage of my project was adding in UI/UX improvements such as styling, hover effects, animations, etc., to make the page more visually appealing as well as more user-friendly. 

<li><h3>Skills Acquired</h3></li>
Going into the project, I had not used APIs, Beautiful Soup, or JSON parsing skills.  This project provided a great opportunity to learn and practice these skills, as well as to experience Agile project management methodologies and utilize tools such as Azure DevOps and GitHub version control functionality.
