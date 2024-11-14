# **Overview: Green Basket - Online Grocery Shopping Platform**

Green Basket is a web-based grocery shopping platform built to provide an efficient and personalized experience for users. The application allows shoppers to browse, add products to their cart, and checkout with ease. Unique features include meal planning, product recommendations based on user behavior, and nutritional information to support informed, health-conscious choices.

# **Core Features**
* **Personalized Shopping:** A user-friendly platform that recommends products based on individual preferences and shopping history.
* **Meal Planning and Suggestions:** Users can receive meal ideas tailored to selected products and dietary needs, with options like vegan or gluten-free.
* **Health-Centric Options:** Comprehensive nutritional data is available for each product, along with meal planning features for specialized diets.
* **Flexible Shopping and Delivery:** The platform supports secure checkout, real-time order tracking, and flexible delivery options, including same-day delivery and store pickups.

# **Functional Roles:**
* **Shopper Experience:** Provides secure registration, search and filter options, cart management, order tracking, and a history of past purchases for reordering.
* **Employee Dashboard:** Includes tools for order management, fulfillment tracking, and notifications for new orders to streamline backend operations.

# **Technologies and Architecture:**
* **Frontend:** Built with React, JavaScript, HTML, and CSS to create responsive, dynamic user interfaces.
* **Backend:** Python (Flask) and MySQL power the server and database, following an MVC structure for efficient data handling and seamless integration.
   - Model: MySQL tables manage data for users, grocery items, orders, and recommendations.
   - View: React components provide a tailored experience for shopper and employee roles.
   - Controller: Flask routes manage user actions, data processing, and API interactions for smooth functionality.
* **Development Tools:** Git for version control, Postman for API testing, and DB Browser for SQLite to test and refine database tables, ensuring reliability and accuracy.

# **Skills Developed:**
* **Full Stack Development:** Gained practical experience across frontend and backend technologies.
* **UI Management in React:** Developed responsive and engaging interfaces using React and JavaScript.
* **Flask API Integration:** Managed backend logic, data handling, and API endpoint interactions in Flask.
* **Database Management with MySQL:** Created and optimized tables for user data, orders, and meal plans.
* **Collaborative Development:** Worked within a team to meet project milestones and refine the user experience.
* **Debugging and Testing:** Strengthened troubleshooting skills through extensive testing.

# **How to Install**
To run the following files in your local machine, follow the instructions below: <br/>

1.) Clone the Repository from github to your code editor:
	
	git clone https://github.com/EJG2023/Online-Grocery-Application-Project.git
	
2.) Install the necessary dependencies for the application:

gh-pages
	
	npm install gh-pages --save-dev


 axios
	
	npm install gh-pages --save-dev


 react-scripts (if not already included):
 	
	npm install react-scripts


3.) Move to the Backend directory:
	
	cd backend

 
4.) Initialize Database:
	
	python main.py

 5.) To start the application, open a new terminal and go to the main application directory:
	
	npm start

 6.) By following the steps beforehand, the application should be running on your local machine with the database initialized.
 

  
 7.) Here are other dependencies that may help if there are issues occur:
	
	pip install python-dotenv flask-restx flask-cors

 8.) Check to manage dependencies
	
	pip freeze > requirements.txt
	


# **User Roles**
* **To use Shopper Role:** Sign up and create an account normally
*  **To use Employee Role:** Sign up and create an account with the Username ending with ".emp" to indicate that you are an employee. Ex.) "Eli.emp".
