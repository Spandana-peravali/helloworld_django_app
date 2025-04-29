1. Clone the Repository

First, clone this repository to your local machine using the following command:

git clone https://github.com/your-username/helloworld_django_app.git

2. Set Up a Virtual Environment

It's best to set up a virtual environment to manage dependencies:

python3 -m venv myenv

Activate the virtual environment:

    On Linux:

source myenv/bin/activate

3. Install Dependencies

Install the required dependencies from the requirements.txt (if you have one, otherwise manually install Django as shown earlier):

pip install django

4. Apply Database Migrations

Run the following command to apply database migrations:

python manage.py migrate

5. Run the Django Development Server

Start the development server with the following command:

python manage.py runserver

This will start the server at http://127.0.0.1:8000/.

6. Access the "Hello World!" Message

Open your browser and navigate to http://127.0.0.1:8000/. You should see the following JSON response:

{
  "Message": "Hello World!"
}


