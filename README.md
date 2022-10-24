# E-Commerce Back End

## Description

An ecommerce platform is arguably the most popular of web applications to show case an individuals understanding of relational databases and being able to dynamically add/update/delete information across multiple tables. This web application allows users to input products, update those products, add categories to those products, add tag ids to those products, delete products/categories/tags, and update all of the afforementioned data. 

This is done with Express.js, Sequelize, MySQL2.0, and also protects important data by hiding the database info inside a .env file for added protection. Please see the video walkthroughs and installation instructions to see how this app could help you with your ecommerce needs.

## Usage/Walkthrough Videos

Set up (MySQL & Server Side)
[mysql and server setup.webm](https://user-images.githubusercontent.com/103971233/197649852-69090149-24aa-4f69-addb-1e74bd9825d8.webm)

Product view/add/update/delete demo
[Product Demo.webm](https://user-images.githubusercontent.com/103971233/197649925-18d66258-3cde-4c7d-829a-0d414352b71f.webm)

Tag view/add/update/delete demo

[Tag Demo.webm](https://user-images.githubusercontent.com/103971233/197649967-139505ca-d2dd-4760-89b2-e951f5a6b02e.webm)

Category view/add/update/delete demo

[Uploading Category Demo.webm…]()

## Credits

Using MySQL2.0 to add the tables to our application (navigate to db folder, open in integrated terminal, use SOURCE schema.sql; and then USE ecommerce_db; to get started).

To download dependencies for this application (navigate out of db into the main folder and run npm i).

To see the database with basic product info/category info/tag info (run the command npm run seed).

To finally run the server (run the command node server). 

We also will be using Insomnia to show case the json data being translated behind the scenes.

## License

MIT License

Copyright (c) 2022 Brandon Maggiano

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
