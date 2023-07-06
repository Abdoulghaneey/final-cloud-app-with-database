
**General Notes**

An `onlinecourse` app has already been provided in this repo upon which you will be adding a new assesement feature.

- If you want to develop the final project on Theia hosted by [IBM Developer Skills Network](https://labs.cognitiveclass.ai/), you will need to create the same project structure on Theia workspace and save it everytime you close the browser
- Or you could develop the final project locally by setting up your own Python runtime and IDE
- Hints for the final project are left on source code files
- You may choose any cloud platform for deployment (default is IBM Cloud Foundry)
- Depends on your deployment, you may choose any SQL database Django supported such as SQLite3, PostgreSQL, and MySQL (default is SQLite3)

**ER Diagram**
For your reference, we have prepared the ER diagram design for the new assesement feature.

![Onlinecourse ER Diagram](https://github.com/ibm-developer-skills-network/final-cloud-app-with-database/blob/master/static/media/course_images/onlinecourse_app_er.png)

## Dependencies (Student's comment)
I'm using a Windows machine with Python 3.11.4 installed, so I had to update packages to get the app to run. I've updated all dependencies to the latest version as of 2023-07-04:
- Django == 4.2.3
- Pillow == 10
- jinja2 == 3.1.2
- gunicorn == 20.1.0
contextvars
- typing-extensions == 4.7.1
- aiohttp == 3.8.4
- click == 8.1.3
- wheel == 0.40.0
- multidict == 6.0.4

