<h1>Form Authentication </h1>

<i>(This project is made using Django as an backend language.)</i>

It consists of login page for the user that already exist in the system whereas for new user it provides signup.

Initially when entering the site, it automatically redirects to login page.

<img src="images/login.png" alt="login page" width="60%"/>

While login; if given a wrong credentials like wrong username or password, it shows error.

<img src="images/wrong-credential.png" alt="wrong credential in login page" width="60%"/>

For signup, just click the signup hyperlink in login page and it redirects to the signup page.

<img src="images/signup.png" alt="wrong credential in login page" width="60%"/>

Similar to the error message shown in login page, the signup page shows the same: the email field must include '@' character, and the password field and confirm password field must be same.

<img src="images/signup-wrong-credential.png" alt="wrong credential in signup page" width="60%"/>

On successfull signup, it redirects to login page showing "account creation" message and on logging in - redirects to the inner page linked to successfull login.

<img src="images/inner-page.png" alt="page after successfull login" width="60%"/>

To run this app - open terminal, direct to the repository consisting *manage.py* file and run the server using code *python manage.py runserver*

*(Note: all the requirements/packages needed must be fulfilled.)*