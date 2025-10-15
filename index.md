---
layout: default
---

Text can be **bold**, _italic_, or ~~strikethrough~~.

[Link to another page](./another-page.html).

# Software Design and Engineering

  The artifact is a static HTML website based on a theoretical Chinese cuisine restaurant that I developed for my GRA-310 Digital Graphic Design for the Web course. The course primarily focused on digital graphic design theory and its application to web design. I was responsible for coordinating the web’s design to meet the business’s requirements that relate to its theme. I used HTML to provide the structure for the content of the web page and CSS to control the presentation and visual styles for the application. I developed this project between August and September of 2023.
  I’ve selected this item due to the opportunity I saw in turning a generic static HTML website into a full-stack application using a MEAN (MongoDB, Express, Angular, NodeJS) architecture to further add dynamic features and server-side functionality established with a NoSQL database. Development for the artifact will demonstrate my skills and abilities in software development across three categories. This initial enhancement fulfills the first category, software design and engineering, by designing the architecture for the full stack using a JavaScript based framework that aligns with a MEAN stack. I used an MVC (Model-View-Controller) architecture to convert the static elements of the web application for the customer’s end of the site using the Express web framework configured with the Handlebars (HBS) view engine. I used routes to establish the client/server interactions to define the responses for requests in the form of URL paths associated with each page in the application. Controllers are in place to handle user input with the current model to update or retrieve data that gets reflected by the view and those results are then sent back to the user. I’ve also converted each static HTML page into Handlebars (HBS) templates with JSON to render the application’s data dynamically.
  Previously, I’ve had experience developing a full MEAN stack application for a theoretical travel booking site. Enhancing and modifying my chosen artifact has helped me reinforce everything I’ve already gone over from creating and initializing a Node Express web application configured with the Handlebars (HBS) view engine installing all the necessary Node packages. Establishing an MVC routing architecture where all the routes, controllers, and handlebars views were set up to dynamically generate the application’s content. As well as converting all the HTML files to utilize JSON to format and display information, this is where I ran into a bit of trouble when I had to replace all of the static HTML list entries for the available listed meals on the menu for the restaurant, with an #each directive using JSON that would create a loop for each object. This is because it was the first time I had to use an array to render the data, due to three different categories of meals that needed to be listed separately. Within the HTML handlebar template containing the section that would format the list of meals, I had to initialize the JSON file containing the structured data containing the meal information and retrieve the specific index containing the list of meals appropriate for the type of meal to be displayed. 

[Enhancement One]({%https://github.com/KevinJCa/CS-499/tree/EnhancementOneProgress%})

# Algorithms and Data Structures

The artifact is a static HTML website based on a theoretical Chinese cuisine restaurant that I developed for the GRA-310 Digital Graphic Design for the Web course. The course primarily focused on digital graphic design theory and its application to web design. I was responsible for coordinating the web’s design to meet the business’s requirements that relate to its theme. I used HTML to provide the structure for the content of the web page and CSS to control the presentation and visual styles for the application. I developed this project between August and September of 2023.
	I’ve selected this item due to the opportunity I saw in turning a generic static HTML website into a full-stack application using a MEAN (MongoDB, Express, Angular, NodeJS) architecture to further add dynamic features and server-side functionality established with a NoSQL database. Development for the artifact will demonstrate my skills and abilities in software development across three categories. This second enhancement focuses on the second category, algorithms and data structures, by the integration of RESTful API endpoints for the application’s code that has been fully implemented with the NoSQL Mongoose database and the single-page application (SPA) that will utilize the endpoints to fetch and manipulate the site’s restaurant menu data. Within each endpoint I have begun development for the algorithms that will allow administrative users to add, remove, or modify menu information through structured components, forms, and routes simultaneously updating the app’s logic backend for additional features. I will also be applying security measures on both the ends of the application through authorization algorithms to verify user identity using a username/password pair.
	Relative to the course outcomes, I am developing a security mindset anticipating the possibilities of vulnerabilities users may encounter by accessing the site. My goal is to prevent users from possessing any sensitive information as well as any privilege that may otherwise affect the general end-user experience through data breaches, code injections, denial of service (DDoS) attacks, or malware.
	While enhancing and modifying my artifact, I’ve reinforced the concepts of developing a RESTful API that will enable interactions between MongoDB and application interactions to fetch or manipulate data. I had to modify the file structure for the RESTful API by modifying the top-level folder in the project’s directory to include the route, controller, and model sub-folders associated with a Model-View-Controller (MVC) architecture. The model illustrates the database schema that I had to organize that would illustrate three different arrays containing three types of “meal” objects based on their type labeled on the menu out of three options (Breakfast, Lunch, Dinner). The controllers contain the methods used to retrieve, remove, modify the data on the application with routes held responsible for wiring up the ‘/api’ path based on the HTTP command to be given. I used Postman to look at every API transaction that occurred on the application to verify its functionality and debug any issues that I encountered. 

[Enhancement Two]({/https://github.com/KevinJCa/CS-499/tree/EnhancementOneProgress})

# Databases

  The artifact is a static HTML website based on a theoretical Chinese cuisine restaurant that I developed for the GRA-310 Digital Graphic Design for the Web course. The course primarily focused on digital graphic design theory and its application to web design. I was responsible for coordinating the web’s design to meet the business’s requirements that relate to its theme. I used HTML to provide the structure for the content of the web page and CSS to control the presentation and visual styles for the application. I developed this project between August and September of 2023.
	I’ve selected this item due to the opportunity I saw in turning a generic static HTML website into a full-stack application using a MEAN (MongoDB, Express, Angular, NodeJS) architecture to further add dynamic features and server-side functionality established with a NoSQL database. Development for the artifact will demonstrate my skills and abilities in software development across three categories. This third and last enhancement for the artifact focuses on satisfying the third category, databases, by integrating my application’s code with MongoDB using data models representing the stored information on the front-end and back-end of the application. Furthermore, using schemas to structure the application’s data to store menu-related information or authentication details in each document.  The NoSQL database has also been seeded using the JSON files containing the site’s menu data providing a method of manually verifying the stored information within the database through the MongoDB Compass graphical user interface (GUI). Lastly, I have enabled interaction between the database on the application’s front-end using RESTful API routes to retrieve or populate the seeded collections/documents within the database.
	My third enhancement demonstrates my ability to use a well-founded and innovative technique to provide a solution for data storage and retrieval by implementing a NoSQL database for scalability and performance in comparison to using relational database technologies.
	During my database enhancement process, I have reinforced my skills to integrate a NoSQL database to satisfy a full MEAN stack application starting with installing Mongoose as the NodeJS package that enables interaction with a MongoDB database. Followed by creating a model according to an MVC (Model-View-Controller) architecture that would contain a schema that would structure the menu’s data to organize the stored information representing all the meals provided by the restaurant. To establish a connection to the database, I had to place seeded JSON data into the database to provide another method of creating, modifying, or removing information using the MongoDB compass GUI. Since there are three types of meals represented on the site being, breakfast, lunch, and dinner. I came across an issue establishing the schema and picking the best data structure to organize all the meals without jeopardizing the site’s ability to retrieve the information or affect the administrative end of the single page application. I had to decide whether to use three different arrays representing each type of meal containing meal objects or using one array to hold all the available meal items. I decided on using a singular array to store all of the meal objects to reduce the complexity of my artifact to meet the requirements and deadlines while leaving room for future adaptations to integrate more features enabling the categorization of the type of meal being added, modified, or removed on the menu. 

[Enhancement Two]({/https://github.com/KevinJCa/CS-499/tree/EnhancementThreeProgress})

```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Large image

![Branching](https://guides.github.com/activities/hello-world/branching.png)

