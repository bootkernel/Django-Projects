# My understanding of Django
I'm learning Django, I'll keep putting some Django projects in this repository as I progress. I'll also include a short documentation on python's virtualenv for better usability.

<b> Virtualenv Stuffs - You can skip this step if you're not</b>

I have a couple of Python scripts that are based on Python 2.7 and they run almost every day using cron. When I decided to start learning Django, I wanted to learn it using python3 but I realized, if I made python3 default in my BSD machine, those scripts won't run. At first, I was thinking of creating a VM or an isolated container using docker but I realized that would still be an overkill. So, those options were out of the table. Finally, I decied to use virtualenv to create an isolated python programming environment in order to learn Django 2.x since it requires python3.

For those who might face similar issues, here's a short tutorial on how to get started with Django 2.x using virtualenv. I'm assuming your system is Unix based:

<code> mkdir djangoProjects </code>

contd..
