Happiness-Is-Homemade :
Happiness-Is-Homemade is a website where people can search, share, and upload homemade recipes. Users can view some recipes for free, sign up for more, and pay for a membership to unlock all recipes.

Features
Search Recipes: Find recipes by name, ingredients, or category.
Upload Recipes: Add your own recipes after signing up.
User Accounts: Sign up or log in to access more recipes.
Recipe Access Levels:

Guest (not logged in): view 5 recipes
Logged-in users: view 10 recipes
Members: unlimited access
Membership Plans:

₹100 – Basic Membership

₹150 – Premium Membership

Technologies Used
Frontend: HTML5, CSS3, JavaScript
Backend: Python, Django
Database: SQLite
Payments: Razorpay

Step-by-Step Setup
Follow these instructions carefully to run the project on your computer.
1. Install Python
Make sure Python is installed. Check by running:
python --version
If it’s not installed, download it from python.org.

2. Clone the Project
Open a terminal (Command Prompt or PowerShell) and run:
git clone [your-repo-url]
cd [your-repo-folder]

3. Install Required Packages
Install the Python packages needed for Django and other dependencies:
pip install -r requirements.txt

4. Set Up the Database
Run the following to create the database:
python manage.py migrate

This will create a SQLite database to store users and recipes.

6. Configure Razorpay for Payments
Sign up at Razorpay
Get your Key ID and Key Secret
Add them in settings.py under Razorpay configuration

6. Run the Project
Start the Django server:
python manage.py runserver

Open your browser and go to:
http://127.0.0.1:8000

How to Use the Website

Browse Recipes – Guests can see 5 recipes without signing in.
Sign Up / Log In – Access 10 recipes after registering.
Membership – Pay to unlock all recipes (₹100 or ₹150).
Upload Recipes – Share your own recipes after logging in.

Future Improvements

Add ratings and reviews for recipes
Filter recipes by categories or ingredients
Enable social sharing of recipes
Add more secure and flexible payment options

Project Discussion
Purpose: A simple platform to discover, share, and enjoy homemade recipes while motivating users to register and subscribe.

Challenges:
Smoothly limiting recipe access for guests vs logged-in users
Secure user authentication and payment handling
Storing recipes and user data efficiently

Conclusion:
This project makes sharing and discovering recipes easy, enjoyable, and encourages community participation.
