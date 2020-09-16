# RateIt


## Built By [Dan Kariuki](https://github.com/Buttonupd/)

## Description
This a python application, developed using django framework, based on a rest Api.It gives users the ability to post projects and users can respond by reacting on its performance. 
## User Stories

Users would like to:

   * View posted projects and their details
   * Post a project to be rated/reviewed
   * Rate/ review other users' projects
   * Search for projects 
   * View projects overall score
   * View my profile page


## Admin Abilities

Admin should:
* Sign in to the RateIt
* Update image post details.
* Delete Offensive Material


## Specifications
| Behaviour | Input | Output |
| :---------------- | :---------------: | ------------------: |
| Admin Authentication | **On demand** | Access Admin dashboard |
| Display all images | **Home page** | Clickable links to open any images in a modal |
| Display graded Projects| **HomePage** | All details should be viewed through a link|
| To add an project  | **Through Admin dashboard** | Add a project|
| To edit project/s  | **Through Admin dashboard** | Edit projects and userprofiles|
| To delete an project | **Through Admin dashboard** | Delete object/project|
| To project search | **Enter text in search bar** | Users can search by project name|
| To vote for or against projects  | **Vote** | Users can comment and like projects|


## SetUp / Installation Requirements
### Prerequisites
* python3.7
* pip3
* virtualenv
* Requirements.txt

### Cloning
* In your terminal:

        $ git clone https://github.com/Buttonupd/RateIt
        $ cd RateIt

## Running the Application
* Creating the virtual environment

        $ Virtualenv env(* 'env is the name of the enviroment')
        $ source env/bin/activate
        $ curl https://bootstrap.pypa.io/get-pip.py | python

* Installing Django and other Modules

        $ see requirements.txt

* To run the application, in your terminal:

        $ ./manage.py runserver

## Testing the Application
* To run the tests for the class files:

        $ ./manage.py test Eject

## Technologies Used
* Python3.7
* Django Framework
* Postgresql Database

## License

Copyright (c) 2020 Dan Kariuki

------------
