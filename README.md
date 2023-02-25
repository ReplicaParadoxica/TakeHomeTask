Support Desk App
==
This is an internal support desk app built using Django, which allows customers to create support tickets and agents to view and manage those tickets. The app also provides quick actions for agents to reassign a ticket and mark a ticket as completed.


Usage
--
To use the app locally:
- Clone the repo: git clone https://github.com/ReplicaParadoxica/TakeHomeTask.git
- Install the requirements: pip install -r requirements.txt
- Create the database: python manage.py migrate
- Create a superuser: python manage.py createsuperuser
- Start the server: python manage.py runserver
- Access the app at http://localhost:8000

Existing urls:
<br> Authentication
- /auth/login
- /auth/register

Placeholder
- /supportdesk/placeholder

For customer:
- /supportdesk/
- /supportdesk/support

For agent:
- /supportdesk/
- Other urls are accessed via interacting with tickets itself

Deployment
--
The app has been deployed to Flyio and can be accessed at https://supportdesk.fly.dev
<br> The according deployed version of SupportDesk can be found at this repository https://github.com/ReplicaParadoxica/TakeHomeTask-Deployed
