# ESD Group 1 Project Code Tutorial

##When Testing
These three lines need to be exacuted in python shell before the code can be used in it's entirety:

Run this command in console first:
```
python manage.py shell
```

Enter these lines in shell:
```
from uweflixapp.models import User
User.objects.createCinemaManager("admin","admin","cineadmin","1234")
User.objects.createAccountsManager("adminAcc","adminAcc","accadmin","1234")
```

They add an account manager account and a cinema manager account.

Then run this command in console to start server:
```
python manage.py shell
```

You are then able to use the website normally. 
