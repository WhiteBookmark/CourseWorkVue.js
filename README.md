# CourseWorkVue.js

Checklist:

• General Requirements (20%): 
A. [GitHub Repositories] the code of the Vue.js App must be hosted in a 
GitHub repository, with at least 10 commits, and the code of the 
Express.js App must be hosted in another GitHub repository, with at 
least 10 commits (6% if 2 separated repositories are used, 3% if only 1 
repository is used).

[X] 1 Repo for frontend

[ ] 1 Repo for backend 

B. [GitHub Pages] the Vue.js App must be hosted and demonstrated on/via GitHub Pages and connected (via Fetch) to your AWS (or render.com) Express.js App (7% if requirement is fully covered, 3% if app is running locally).

[X] Host on Github pages

C. [AWS (or render.com)] the Node/Express server must be hosted on Amazon AWS ( https://aws.amazon.com/ ) or on Render ( https://render.com ) (7% if requirement is fully covered, 3% if the server is run locally, 0% if the server is hosted in another cloud-based solution).

** [Front-End] “Display List of Lessons” functionality (7%):
**
[X] A. there should be at least 10 lessons, and each lesson should have 5 spaces (or availability) (1%).

[X] B. each lesson should have at least (5%): Subject (1%), Location (1%), Price (1%), Spaces (or availability: this indicates how many spaces are left) (1%), a Font Awesome icon (or an Image) (1%).

[X] C. v-for must be used for the display of the lesson list (1%).

**• [Front-End] Sort functionality (10%): 
**
[X] A. the user can choose to sort the lessons by one of the following attributes (8%): subject (2%), location (2%), price (2%), or spaces (i.e. availability) (2%).

[X] B. there must be an option to sort in ascending or descending order (order dependent on the sorting attribute selected), which should work for each of the attributes (2%).

**• [Front-End] “Add to Cart” functionality (5%): 
**
[X] A. each lesson must have an “Add to Cart” button (1%). 

[X] B. the button is always visible, and only enabled when space is larger than 0 (1%). 

[X] C. clicking the button once (related interactions implemented by using v-on) will add one space to the shopping cart, reducing the remaining space by one (2%).

[X] D. once there is no more space, i.e. space = 0, the “Add to cart” button should be disabled but still visible, i.e. clicking it will not further reduce “space” nor add lessons to the cart (1%).

**• [Front-End] “Shopping Cart” functionality (5%): 
**
A. the shopping cart button should only be enabled after at least one lesson is added to cart (1%).

B. clicking the shopping cart button should show the cart page, and clicking the button again goes back to the lesson page (1%).

C. the shopping cart, in the cart page, should show all the lessons added (1%).

D. in the shopping cart page, the user should be able to remove lessons from the shopping cart; the removed lesson is added back to the lesson list (in the lesson page) (2%).

• [Front-End] Checkout functionality (6%): 
A. the checkout is part of the shopping cart page (not part of the lessons 
page) (1%). 
B. the “checkout” button is always visible and only enabled (clickable) after 
valid “Name” and “Phone” are provided (2%). 
C. the “Name” must be letters only and the “Phone” must be numbers only; 
the check must be done using JavaScript (suggestion: regular 
expressions) (2%).  
D. clicking the “checkout” button should display a message confirming the 
order has been submitted (1%).