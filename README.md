# Traffic Sign Recognition - Bosch
<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-9-orange.svg?style=flat-square)](#contributors-) <img src="https://img.shields.io/badge/Maintained-No-red.svg?style=flat" style="float: left;margin-right: 10px;"  hspace="20" alt="Not maintained"><img src="https://img.shields.io/github/license/pranav2812/9th-inter-iit-traffic-sign?style=flat" style="float: left;margin-right: 10px;" hspace="20" alt="Apache License v2.0
">

<!-- ALL-CONTRIBUTORS-BADGE:END -->


### The contingent won Bronze Medal in the Bosch Traffic Sign Recognition Problem Statement in Inter IIT Tech Meet 9.0.

## View the presentation here:
[PDF Presentation](./H1_BSC_9_Presentation_final.pdf)

## View the website demo video here:
[![9th InterIIT Bosch Traffic Sign recognition, IIT Bombay](thumb.png)](https://www.youtube.com/watch?v=0AiCw3MFePM "9th InterIIT Bosch Traffic Sign recognition, IIT Bombay")

## The Team
![Team pic](team.jpg)


# Running the code:
This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 9.1.1.

## Read the flow of code [here](./FlowReadme.txt)

## Installation Steps

### Installing Node
We need Node v14.5.0. To install it, follow the installation instructions [here](https://www.digitalocean.com/community/tutorials/how-to-install-node-js-on-ubuntu-18-04). Make sure you use **14.x** instead of **10.x**

### Installing Angular  
`npm install -g @angular/cli` to install angular CLI.

### Install project dependencies
Navigate to *traffic-sign-recognition* directory and run `npm install`. This will install required dependencies specific to the project.

### Install Python dependencies
Navigate to *traffic-sign-recognition/backend* folder and run `pip install -r requirements.txt`

## Running Project
### Running Backend
* Navigate to *traffic-sign-recognition/backend* and run `python3 manage.py migrate`.
* Run `python3 manage.py runserver`
* Proceed to running frontend

### Running Frontend
* Navigate to *traffic-sign-recognition* directory and run `ng serve`
* Navigate  to `localhost:4200` on your browser to view the webpage.


## Further steps:

### Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

### Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

### Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

### Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

### Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

### Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).


## Downloading the training dataset (GTSRB):

Download the dataset from the official site [INI](https://benchmark.ini.rub.de/gtsrb_dataset.html) and convert all .ppm images to .png images

Else, download the dataset from here: [Kaggle link](https://www.kaggle.com/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign) (already converted to .png)

Place the downloaded dataset in `backend/Data/Train` folder

## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="http://homepages.iitb.ac.in/~pranav.deo/"><img src="https://avatars.githubusercontent.com/u/35232938?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Pranav Deo</b></sub></a><br /><a href="#projectManagement-pranav2812" title="Project Management">📆</a> <a href="#ideas-pranav2812" title="Ideas, Planning, & Feedback">🤔</a> <a href="#content-pranav2812" title="Content">🖋</a> <a href="#design-pranav2812" title="Design">🎨</a></td>
    <td align="center"><a href="https://gurnoor6.github.io/homepage/"><img src="https://avatars.githubusercontent.com/u/62883198?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Gurnoor Singh Khurana</b></sub></a><br /><a href="https://github.com/pranav2812/9th-inter-iit-traffic-sign/commits?author=gurnoor6" title="Code">💻</a> <a href="https://github.com/pranav2812/9th-inter-iit-traffic-sign/commits?author=gurnoor6" title="Documentation">📖</a></td>
    <td align="center"><a href="https://github.com/jayeshs999"><img src="https://avatars.githubusercontent.com/u/55800453?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Jayesh Singla</b></sub></a><br /><a href="https://github.com/pranav2812/9th-inter-iit-traffic-sign/commits?author=jayeshs999" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/AnujAgrawal30"><img src="https://avatars.githubusercontent.com/u/45514513?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Anuj Agrawal</b></sub></a><br /><a href="https://github.com/pranav2812/9th-inter-iit-traffic-sign/commits?author=AnujAgrawal30" title="Code">💻</a> <a href="#mentoring-AnujAgrawal30" title="Mentoring">🧑‍🏫</a></td>
    <td align="center"><a href="https://github.com/mitali72"><img src="https://avatars.githubusercontent.com/u/58500087?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Mitali Meratwal</b></sub></a><br /><a href="https://github.com/pranav2812/9th-inter-iit-traffic-sign/commits?author=mitali72" title="Code">💻</a> <a href="https://github.com/pranav2812/9th-inter-iit-traffic-sign/commits?author=mitali72" title="Documentation">📖</a></td>
    <td align="center"><a href="http://omkarghugarkar.me"><img src="https://avatars.githubusercontent.com/u/62425457?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Omkar Ghugarkar</b></sub></a><br /><a href="https://github.com/pranav2812/9th-inter-iit-traffic-sign/commits?author=omkarghugarkar007" title="Code">💻</a> <a href="#data-omkarghugarkar007" title="Data">🔣</a></td>
    <td align="center"><a href="https://github.com/atharva-diwan"><img src="https://avatars.githubusercontent.com/u/64583671?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Atharva Diwan</b></sub></a><br /><a href="https://github.com/pranav2812/9th-inter-iit-traffic-sign/commits?author=atharva-diwan" title="Code">💻</a> <a href="#data-atharva-diwan" title="Data">🔣</a></td>
  </tr>
  <tr>
    <td align="center"><a href="http://homepages.iitb.ac.in/~nihalbarde/"><img src="https://avatars.githubusercontent.com/u/34839591?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Nihal Barde</b></sub></a><br /><a href="https://github.com/pranav2812/9th-inter-iit-traffic-sign/commits?author=nilbarde" title="Code">💻</a> <a href="#mentoring-nilbarde" title="Mentoring">🧑‍🏫</a></td>
    <td align="center"><a href="https://thesmilingsky.github.io/"><img src="https://avatars.githubusercontent.com/u/42549409?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Gagan Jain</b></sub></a><br /><a href="https://github.com/pranav2812/9th-inter-iit-traffic-sign/commits?author=TheSmilingSky" title="Code">💻</a> <a href="#ideas-TheSmilingSky" title="Ideas, Planning, & Feedback">🤔</a></td>
  </tr>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!

Special thanks to Anirudh Mittal, General Secretary - Technical Affairs, IIT Bombay (2020-21), and Aryan Agal and Manthan Dhisale as the Contingent Leaders of the IIT Bombay Contingent, Bombay76, for the 9th Inter-IIT Tech Meet.
