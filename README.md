Description: 
This is a Django-based project that allows users to manage and interact with various features. Follow the instructions below to clone and set it up on your local machine.

Installation Instructions: 
1. Clone the Repository: 
git clone https://github.com/SRR23/Devskill-Assignment-1.git
cd repo-name

3. Create and Activate a Virtual Environment (Optional but Recommended): 
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

5. Install Dependencies: 
pip install -r requirements.txt

7. Set Up the Database: 
python manage.py makemigrations
python manage.py migrate

9. Create a Superuser (Admin Account): 
python manage.py createsuperuser

11. Run the Development Server: 
python manage.py runserver
