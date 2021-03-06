# Declaro

Robot to automate the process of tax declaration in the Mexican IRS (SAT) for independet professionals (Personas físicas con actividad empresarial)

## Getting Started

You need to mount in Mongo Atlas a Data base named "api" with the following collections:
- usuarios
- facturas

Adapt Mongo's string for the conection and also create a file named "pw.txt" where you save your password of Mongo Altas in the first line of the file.

### Prerequisites

Needed libraries:

- pymongo
- selenium

You need to install

```
pip3 install pymongo
pip3 install selenium
```
This is working over the Chrome driver of Selenium, be sure to install it before you try to run the api. For this just download the lastest stable version of the driver from the [Chrome Driver](https://chromedriver.chromium.org/) webpage. In Mac OS once download copy the exec file in one path environment location, normally `/usr/local/bin` location will do the trick.

## Running the tests

You can run every module separatly to check that is working (Modules 3 to 7) but first you need to run modules 1 and 2 regarding the libraries and the functions



## Built With

* [Selenium](https://selenium-python.readthedocs.io/) - Web driver
* [PyMongo](https://api.mongodb.com/python/current/) - Database access API

## Presentation

* [Presentation](https://drive.google.com/file/d/1-cUxaw-jtuoiAdAmFrsDuqsH-0JRHHBO/view?usp=sharing)
* [Video Demo](https://drive.google.com/file/d/1qi4kE-DnfxuyPhi7VKpuU9OUZPJ9uuF1/view?usp=sharing)

## Author

* **Alberto Ibarra** - *Initial work* - [Alberto Ibarra](https://github.com/albertoid)
