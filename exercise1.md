I have chosen the programming langugage python for this exercise

For python there are many different test runners but the most popular test runners are:
 - unittest
 - nose
 - pytest
They are all great test runners but the unittest is build in into the python standard library and is thus usable without installing anything extra

There are many different Linters where we can chose, but there are also a couple of combo-linters wich packge multiple linters nicely together for more functionality. An example of that is Flake8 wich can be used for this team and combines the following linters: PyFlakes, Pycodestyle, Mccabe.

An alternative CI besides Jenkins and GitHub Actions is CircleCI wich is used by many big companys like LINE and Travelex. This is a verry proffesional CI with free and payed cloud options but also gives the flexbilility to self-host it. It supports a lot of different tool chains to build in including python. And can be intergrated in to different git hosters.

This setup would be best in cloud-based solution because it is a small team working on a python project who doesn't need any special requirements and wil be able to run all te test in the cloud/ building in de cloud