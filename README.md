# Puppeteer Voting Script

[![Build Status](https://travis-ci.com/Alex-Camman/Voting-Auto-Script.svg?branch=main)](https://travis-ci.com/Alex-Camman/Voting-Auto-Script/builds/3)
[![Coverage Status](https://img.shields.io/badge/Coverage-100%25-success.svg)](https://coveralls.io/github/Alex-Camman/Voting-Auto-Script?branch=main)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
![Node.js](https://img.shields.io/badge/Node.js-v14.17.5-brightgreen.svg)
![Puppeteer](https://img.shields.io/badge/Puppeteer-Web%20Automation-brightgreen.svg)

Automate website voting with Puppeteer and random email generation.

## Table of Contents

- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
    - [Windows](#windows)
    - [Linux](#linux)
- [Usage](#usage)
  - [Windows](#windows-usage)
  - [Linux](#linux-usage)
- [Safety](#safety)
- [License](#license)
- [Author](#author)

## Getting Started

### Prerequisites

Before you can use this script, ensure you have the following prerequisites:

- **Node.js:** Ensure you have Node.js installed on your computer. If not, download it from [nodejs.org](https://nodejs.org/).

- **Google Chrome:** Puppeteer uses Google Chrome for automation. Make sure you have Google Chrome installed.

### Installation

#### Windows (1)

1.1 **Clone the Repository:**
   Download this repository to your local machine by opening your command terminal (CMD or PowerShell on Windows), navigating to the directory where you want to store the project, and running:

   ```shell

   git clone https://github.com/Alex-Camman/Voting-Auto-Script.git

   
This will create a local copy of the project on your computer.

2.1 Navigate to the Project Directory:
Change your working directory to the project folder by running:

shell
Copy code

cd Voting-Auto-Script


3.1 Install Dependencies:
Install the required Node.js packages by running:

shell
Copy code

npm install


This will download and install the necessary libraries for the script.

4.1 To install Puppeteer in your Node.js project, you can use the following code:

shell
Copy code

npm install puppeteer


You can run this command in your project's root directory using your terminal or command prompt. This will download and install the Puppeteer package and its dependencies for your project.

5.1 Install the fast-csv package again using npm:

shell
Copy code

npm install fast-csv


This command will make sure that the necessary package is installed in the correct directory.

6.1 Run the Script:
You can run the script with the following command:

shell
Copy code

node AAa11-fiver-csv-voter-email.js


The script will launch a headless Chrome browser, generate random email addresses, and vote on the specified website automatically.



####Linux (2)
1.2 **Clone the Repository:**
Open Terminal and run:

shell
Copy code

git clone https://github.com/Alex-Camman/Voting-Auto-Script.git


This will create a local copy of the project on your computer.

2.2 Navigate to the Project Directory:
Use the cd command to change your working directory to the project folder:

shell
Copy code

cd Voting-Auto-Script


3.2 Install Dependencies:
Install the required Node.js packages by running:

shell
Copy code

npm install


This will download and install the necessary libraries for the script.

4.2 To install Puppeteer in your Node.js project, you can use the following code:

shell
Copy code

npm install puppeteer


You can run this command in your project's root directory using your terminal. This will download and install the Puppeteer package and its dependencies for your project.

5.2 Install the fast-csv package again using npm:

shell
Copy code

npm install fast-csv


This command will make sure that the necessary package is installed in the correct directory.

6.2 Run the Script:
Start the script by running:

shell
Copy code

node AAa11-fiver-csv-voter-email.js


The script will launch a headless Chrome browser, generate random email addresses, and vote on the specified website automatically.
