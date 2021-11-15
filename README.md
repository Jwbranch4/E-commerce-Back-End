# E-commerce-Back-End

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Description

The back end for an e-commerce site. Using working Express.js API and configured it to use Sequelize to interact with a MySQL database.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)
- [Links](#links)

## Links

| To github repository:                            | To video:                                              |
| ------------------------------------------------ | ------------------------------------------------------ |
| https://github.com/Jwbranch4/E-commerce-Back-End | https://watch.screencastify.com/v/rxRAbClQlFkSA8otoaR6 |

![screenshot](/assets/images/ecommerce-back-end.png)

## Installation

- command line type npm install (installs dependencies)
- create a .env file in project folder will need your MySQL username, password, and database name (database name will be ecommerce_db)
- enter mysql command line and source db/schema.sql ( creates database)
- type USE ecommerce_db then quit mysql command line ( changes database to ecommerce_db and leaves mysql)
- command line type node seeds/index.js ( runs seeds that populate data into the database)
- command line type npm start ( starts server )

## Usage

Running this application makes it possible to use API calls for E-commerce site.

## Credits

Project from UT coding-boot-camp

## License

MIT License(https://opensource.org/licenses/MIT)

    Permission is hereby granted, free of charge, to any person obtaining a copy
    of this software and associated documentation files (the "Software"), to deal
    in the Software without restriction, including without limitation the rights
    to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
    copies of the Software, and to permit persons to whom the Software is
    furnished to do so, subject to the following conditions:

    The above copyright notice and this permission notice shall be included in all
    copies or substantial portions of the Software.

    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
    FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
    AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
    LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
    OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
    SOFTWARE.
