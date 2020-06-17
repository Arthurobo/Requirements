Cd into your desktop on the command line and run the following command step by step. I am still unable to get tensorflow work on my PC cos it stops my PC from working entirely. Too bad.
NOTE: Before executing step 6, try to install all the packages you guys used in working on the function that blurs and detects faces, i listed some in STEP 5 not sure if they are complete. If they are not complete, use the command pipenv instead of pip to install packages just as its done in STEP 5



STEP 1: mkdir blog
STEP 2: cd blog
STEP 3: pip3 install pipenv
STEP 4: pipenv shell
STEP 5: pipenv install django pillow numpy tensorflow mtcnn
STEP 6: django-admin startproject test_project
STEP 7: cd test_project
STEP 8: python manage.py runserver
STEP 9: pip freeze > requirements.txt

NOTE 2: We are runnning all above command to get a requiremennts.txt file. Once you've successfully installed all these up to step9, clone this to a new github repo (New) and add me as a contributor so i can lay my hands on the requirements.txt.


NOTE 3: Example of how i ran the command on my pc
C:\Users\Arthur PC\Desktop>mkdir blog
C:\Users\Arthur PC\Desktop>cd blog
C:\Users\Arthur PC\Desktop\blog>pip3 install pipenv
C:\Users\Arthur PC\Desktop\blog>pipenv shell
(blog-vTTWXYWU) C:\Users\Arthur PC\Desktop\blog>pipenv install django pillow tensorflow mtcnn
(blog-vTTWXYWU) C:\Users\Arthur PC\Desktop\blog>django-admin startproject test_project
(blog-vTTWXYWU) C:\Users\Arthur PC\Desktop\blog>cd test_project
(blog-vTTWXYWU) C:\Users\Arthur PC\Desktop\blog\test_project>python manage.py runserver
(blog-vTTWXYWU) C:\Users\Arthur PC\Desktop\blog\test_project>pip freeze > requirements.txt
