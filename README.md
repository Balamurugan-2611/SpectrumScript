Step-1: Create Virtual Environment (using CMD):

Change the Directory where you want to create an Virtual Environment in CMD.
IN CMD use this code to create a Virtual Environment - py -m venv myworld.

Step-2: Install packages in Virtual Environment:

Change directory into myworld/scripts in CMD.
Paste the requirements.txt file into myworld/scripts.
IN CMD use this code to install packages - pip install -r requirements.txt.

Step-3: Migrate the folder:

Download SpectrumScript Folder and paste in the same folder or near where Virtual Environment is created.
Change Directory to SpectrumScript/.
IN CMD use this code to Migrate - py manage.py migrate.

Step-4: Run the server:

Change Directory to SpectrumScript/ (if needed).
IN CMD use this code to Runserver - py manage.py runserver.
Paste the localhost into a browser.
