THIS IS THE COVID AI BOT.
DOWNLOAD THE FILE AND FOLLOW THE STEPS BELOW

1. OPEN A TERMINAL
2. write :- mkdir (FILE NAME)
3. write :-  cd (FILE NAME)
4. write :- sudo apt install python3-venv
5. write :- python3 -m venv my-project-env
6. write :- source my-project-env/bin/activate

Here you can see you virtual enviroment is activated(for deactivating virtual enviroment directly write deactivate, throughly suggest you to work in virtual enviroment otherwise every aspect will be joined in the global level)

7. write :- pip install rasa
8. write :- pip install spacy==2.3.5
9. write :- python -m spacy download en
10. write:- python -m spacy download en_core_web_md
11. write:- python -m link en_core_web_md en --force

Now you have installed every dependencies, it's time to code, but it can be easy for you if you install the initial rasa project.

12.write:- rasa init

Now you can see your project structure.

After this you have to replace all yaml file with that own file in the same structure it is given into, My advice is to write code dont copy paste, it will increase your skills.

YAML file is very sensitive toward indent and whitespaces, so be sure your yaml file is valid. check yaml checker online to confirm it

After you can write every code same as it is attached in the file you have to write some code in the terminal.

First of all we have to train our codes

13.write:- rasa train

After this open one more terminal for the same directory, You have to write and run code on the both simuntaneously.

14.write:- rasa shell

On second terminal

15.write:- rasa run actions

Now you can see your bot is ready to go.
