<h1>File Manager Mini Project</h1>
<p align = 'center'>This project is a summary of the back-end trimester which covers topics like authentication, NodeJS, MongoDB, Redis, pagination, and background processing.

The objective of this project is to build a simple platform that allows users to upload and view files. The following features will be implemented:

1. User authentication via a token
2. List all files
3. Upload a new file
4. Change permission of a file
5. View a file
6. Generate thumbnails for images
 

We will guide you step-by-step in building this application. You have the freedom to implement it as you wish, including splitting the code into multiple files. The utils folder will be your friend.


Note that similar services already exist in real life. However, this project serves as a learning opportunity to assemble each piece and build a complete product.

<b>Enjoy!</b>

## Technologies Used
The following technologies will be used in this project:
<ul>
<li>Node.js</li>
<li>Express.js</li>
<li>MongoDB</li>
<li>Redis</li>
<li>Multer</li>
<li>Sharp</li><br>
</ul>
</p>

## Installation
<ol>
    <li>Clone the repository</li>
    <li>Install the dependencies using npm install</li>
    <li>Start the server using npm start</li>
    
</ol>
 

## API Endpoints
The following API endpoints are available:

#### Authentication
    ~ POST /auth/signup: Creates a new user account
    
    ~ POST /auth/login: Logs in a user and returns a JWT token
  #### Files
    ~ GET /files: Returns a list of all files

    ~ POST /files: Uploads a new file
    
    ~ PATCH /files/:id: Changes the permission of a file
    ~ GET /files/:id: Returns the file with the specified ID
    ~ GET /files/:id/thumbnail: Returns a thumbnail of the image file with the specified ID

## Credits
This project was built by [Elisha Mbadi](https://github.com/elishambadi) and [Dovine K.](https://github.com/dovineowuor) as part of a back-end trimester.

