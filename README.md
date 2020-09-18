# Angular-Django-JWT-Example
In this assignment I've used Angular 8 as front-end and Django at back-end to create a JWT (Json Web Token) authentication chat platform.

I've used Angular due to the following reasons:
- I've experience in Angular as I've worked before developing the official MI website in the platform
- The codebase is much cleaner in Angular and it is an ideal platoform for small scale websites with limited functionality

The project is divided in two submodules:
- The Angular Front End which can also be accessed from [here](https://github.com/AnujAgrawal30/Angular-JWT-Example)
- The Django Back End which can also be accessed from [here](https://github.com/AnujAgrawal30/Django-JWT-Example)

To clone the project, follow the steps:
- `git clone https://github.com/AnujAgrawal30/Angular-Django-JWT-Example.git`
- `cd Angular-Django-JWT-Example`
- `git submodule update --init --recursive`
- `cd .\Django-JWT-Example\`
- `python manage.py runserver`

And on another terminal, first go to Angular-Django-JWT-Example folder then type following commands:
- `cd .\Angular-JWT-Example\`
- `npm install`
- `npm audit fix --force` (If it shows some sort of error)
- `npm install --save rxjs-compat`
- `ng serve --open`

The detailed instructions on how to set up the seperate applications is provided in the seperate Repositories

Please contact me at 6264837310 if you find any difficulty in opening the project
