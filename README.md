Syntax Safari - Flask-based web app running on virtualenv for development. Instructions and installation are Windows based.


### Requirements ###
Python 3.3+
Git


### Installation ###
1. Clone the Git repo. In your terminal type:

		git clone https://github.com/santiago-AG/Syntax-Safari.git

	Then enter the new directory:

		cd Syntax-Safari

2. Create a virtual environment. Make sure to install the latest version of virtualenv:
		
		pip3 install virtualenv

	Activate the virtual environment:

		env\scripts\activate

	Install dependencies:

		pip3 install -r requirements.txt

	To run the app:

		python app.py

	Then connect to the website "localhost:5000"


### Committing your changes to Git ###
1. When you have your changes done, save them locally.
2. Check your current unstaged changes:

		git status

3. Stage these changes:

		git add -A

4. Commit these changes with a message:

		git commit -m "Your Message"

5. Push your changes:

		git push origin main

	You can just do "git push" since there is currently only one branch.


### Pulling changes ###
1. (Idk how to do this really)
2. Pull the latest git version?:

		git pull

3. Use git checkout to make sure you're working on the latest version?

		# Not sure how. Please add.


### Notes ###
1. The idea is that you create your own virtual environment so we don't have to run a server that everyone shares. As a result, the env\ directory is added to the .gitignore.
2. Using autosave in your IDE might be a big headache saver. 