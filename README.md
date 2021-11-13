# Blog-Site-v2
Web app that stores blog posts and dynamically creates a web page for each post.

Version 2: Database

Version 2 now uses mongoDB on the back end so we can store our blogs on the mongoDB database. We now don't have to worryaboutlosing our blogs upon page refresh.
 
Functionality

Can create and post blog articles to the home page. Each blog post can be viewed on it's own dynamic page.

Styling

Used Bootstrap 5.0 and a personal stylesheet to create the basic style of the page.

Node/Express

Used Node to render web pages and Express to route web pages and help post blog articles to our home page and their own unique pages.

EJS

Used Embedded Javascript Templating for header and footer partials on the web page. This makes it easier to maintain a consistent style throughout the web app. EJS was also used to post blog data on the pages as well as post each blog on it's own page. EJS helps make the site more dynamic (ex: slicing posts on the home page.)

How to Run

1.Clone the git repository onto your local machine.

2.Open the directory on your CLI.

3.'node app.js' or 'nodemon app.js' to run.

4.http://localhost:3000/ to view the web app on your browser.

5.You would need to have mongo db installed and entered 'mongod' into a seperate shell terminal.
