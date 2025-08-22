Architecture:
  Compare and contrast the types of frontend development you used in your full-stack project, including Express HTML, JavaScript, and the single-page application (SPA).
      In this project, one side of the site utilized Express, HTML, and JavaScript to display the pages. Using Express and JavaScript along with routes and controllers were
      created to handle the requests from the browser for the page. The browser requests a page, Express then sends back an HTML file with CSS and JavaScript. If a user 
      selects something on the page, the page will reload the entire page by asking the server again. JavaScript adds dynamic behavior like form validation, but the server is
      the main renderer. On the admin side of the project, the admin side used Angular as a single-page application, where the browser loads the application and is updated 
      dynamically with API calls, providing a smoother and more interactive experience.
      
  Why did the backend use a NoSQL MongoDB database?
    It was a good fit for this project to be able to store flexible travel data like trips, prices, and user information. MongoDB also scales very well and queries very fast.     
Functionality:
  How is JSON different from Javascript, and how does JSON tie together the frontend and backend development pieces?
    JSON is different from JavaScript because JSON is a lightweight data format used to exchange information, while JavaScript is a full programming language used to build 
    logic and functionality. JSON is what ties the frontend and the backend together by carrying data from the server to the client in a format that both are able to process.
    
  Provide instances in the full stack process when you refactored code to improve functionality and efficiencies, and name the benefits that come from reusable user interface 
  (UI) components.
    In this project, I refactored code by moving repeated API calls into services, normalizing data into structured JSON, and also creating reusable components like trip cards 
    to simplify the UI. Having reusable UI can make it easier to maintain and scale the application. 
    
Testing:
  Methods for request and retrieval necessitate various types of API testing of endpoints, in addition to the difficulties of testing with added layers of security. Explain your 
  understanding of methods, endpoints, and security in a full-stack application.
    In a full-stack application like this project, methods that are used are GET, POST, PUT, and DELETE, which define what kind of action is being taken when the frontend 
    communicates with the backend. Endpoints are how the client communicates with the server, utilizing HTTP methods. When layers of security are added, like authentication tokens or 
    role-based access, testing can become more complex because not only do you have to verify the overall functionality of the endpoint, but you also user role access. Together, methods,
    endpoints, and security are what ensure safe and reliable communication between frontend and backend. 
Reflection:
  How has this course helped you in reaching your professional goals? What skills have you learned, developed, or mastered in this course to help you become a more marketable candidate in your career field?
    This course has shown me what it is like to create a full-stack application. Past courses have just been snippets of frontend or backend development. I also realized how much time an application can take 
    to create when you are doing front-end and back-end. This course helped provide me with a little more insight into what kind of developer I want to be: full-stack, frontend, or backend. Along with languages 
    that I had not used before. I have learned the majority of the things that it takes to create a full application but insections but being able to utilize a lot of things I have learned over the last couple of 
    years and pull them all together while learning new things to create an application was a lot of fun. Like I said, I now know what I want to do as a developer. 
  
