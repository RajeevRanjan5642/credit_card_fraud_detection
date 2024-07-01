# Credit Card Fraud Detection

Dataset 🔗 : https://www.kaggle.com/mlg-ulb/creditcardfraud

## 👨🏽‍💻Project Setup Steps

I. Create a Virtual Environment:
<ul>
<li>Open your terminal or command prompt.</li>
<li>Navigate to your project directory (where you want to create the virtual environment).</li>
<li>Run the following command to create a virtual environment:</li>

        virtualenv venv
        
</ul>
 NOTE: venv is name of virtual environment. we can give any name which we want.

II.Activate the Virtual Environment:
<ul>
<li>Depending on your operating system:
<ul>
<li>On Windows:</li>

        venv\Scripts\activate 

<li>On macOS/Linux:</li>

        source venv/bin/activate

</ul>
</li>
</ul>
III.Install Project Dependencies:
<ul>
<li>Make sure you have a requirements.txt file in your project directory. If not, create one and list all the required packages (dependencies) for your Django project.</li> 
<li>Run the following command to install the dependencies:</li>

        pip install -r requirements.txt

</ul>
IV.Create a Superuser:
<ul>
<li>In your project root directory (where manage.py is located), run the following command:</li>

        python manage.py createsuperuser

<li>Follow the prompts to set a username, email, and password for the superuser. This user will have administrative privileges in your Django application.</li>
</ul>
V.Run the Development Server:
<ul>
<li>Start your Django development server by running:</li>

        python manage.py runserver

<li>Open your web browser and visit http://127.0.0.1:8000/ to see your Django app in action.</li>
</ul>

NOTE:- If you are adding some model in models.py or changing something don't forget to make migrations 

        python manage.py makemigrations

and migrate it to database

        python manage.py migrate

This ensures that your database schema is up to date with your model changes.

