### How do you write programs that are maintainable, readable, and adaptable? Especially consider your work on the CRUD Python module from Project One, which you used to connect the dashboard widgets to the database in Project Two. What were the advantages of working in this way? How else could you use this CRUD Python module in the future?

By building each component of an application in a modular format you are able to seperate pieces of the code into logical sections. By structuring your application using the MVC pattern you are able to keep specific functionalities isolated from eachother. For example, by placing all the CRUD functions in a "standalone" object class you can more easily maintain all operations related to communication with the database.

In the future, this Proof of Concept could be expanded to include a full range of database interactivity, including:
* Update existing records
* Insert new records
* Delete records
* Filter by additional fields
* Sort by specific fields
* Change the page size returned by a query 

### How do you approach a problem as a computer scientist? Consider how you approached the database or dashboard requirements that Grazioso Salvare requested. How did your approach to this project differ from previous assignments in other courses? What techniques or strategies would you use in the future to create databases to meet other client requests?

A developer is dependant upon the client and/or business analyst to supply clear and concise acceptence criteria for the application they are building. While the Agile process does allow for greater flexibility than Waterfall, it is still very important to have each functionality "fleshed" out by following Agile's refinement process.

This project was quite different than any of the other assignments I've had in previous courses. I had very minimal experience with Python and limited experience with the Linux terminal. I had no previous experience working with MongoDB databases. I had no previous experience using the PyMongo, Plotly, or Leaflet libraries.

Fortunately, I was able to adapt my existing understanding of application development and apply the rules of the SDLC to learn, implement, test and iterate my code until it satisfied the requirements of the assignment.

### What do computer scientists do, and why does it matter? How would your work on this type of project help a company, like Grazioso Salvare, to do their work better?

Computer scientists programatically find solutions. The primary purpose of building an application is to take input, process it, and return output. If this output is meaningul, we call it "information". Software development is perhaps the single most important career to emerge in the last few generations as ever greater facets of our lives revolve around interacting with software. From smartphones to litter boxes; code is running everywhere. Especially with the advent of the "Internet of Things", more and more devices are communicating with eachother to hopefully solve problems. From simplifying tasks, like turning on a light with voice activation, to world redefining endeavors, like sequencing DNA to create vaccines, software development has huge implications across the entire spectrum of human endeavor.

Even though the range of possible applications are vast, almost every program follows the same sort of interaction formula: A user opens an application or navigates to a website, they enter some data and make a request. That request is sent to an external server where it is run through business logic which generates the requisite query to a datasource to return a response back to the user and render meaningful information back to them. From posting pictures on Facebook to watching a movie, all of these common tasks are utilizing CRUD commands to create, read, update, or delete data.
 
