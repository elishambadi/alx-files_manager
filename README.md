<h1 align='center'><u>File Manager Mini Project</u></h1>
    <p align = 'center'>
    This project is a summary of the back-end trimester which covers topics like authentication, NodeJS, MongoDB, Redis, pagination, and background processing.
    </p>
<h2 align ='Center'><u>Objectives</u></h2>
<p align='center'>
The objective of this project is to build a simple platform that allows users to upload and view files. The following features will be implemented:
</p><br>

<h2 align='center'><u>Product Features</u></h2><br>
<div>
<ol align='center'>
    <li>User authentication via a token</li>
    <li>List all files</li>
    <li>Upload a new file</li>
    <li>Change permission of a file</li>
    <li>View a file</li>
    <li>Generate thumbnails for images</li>
</ol>

</div><br>

<p align='center'>
    <i>
    We will guide you step-by-step in building this application. You have the freedom to implement it as you wish, including splitting the code into multiple files. The utils folder will be your friend.</i>
</p>


<p align ='center'><i><b>Note that similar services already exist in real life. However, this project serves as a learning opportunity to assemble each piece and build a complete product.
        </b>
    </i>
</p>

<b>Enjoy!</b>

<h2 align="center"><u>Technologies Used:</u></h2><br>\
    <div  align='center'      >
        <ul>
        <li>Node.js</li>
        <li>Express.js</li>
        <li>MongoDB</li>
        <li>Redis</li>
        <li>Multer</li>
        <li>Sharp</li><br>
        </ul>
    </div>

The following technologies will be used in this project:


</p>

<h2 align='center'>Installation</h2>
<ol align='center'>
    <li>Clone the repository</li>
    <li>Install the dependencies using npm install</li>
    <li>Start the server using npm start</li>
    
</ol>
 

<h2 align='center'>API Endpoints</h2>
<p align='center'>
The following API endpoints are available:

</p>

<h3 align= Center>Authentication</h3>
    
    ~ POST /auth/signup: Creates a new user account
    
    ~ POST /auth/login: Logs in a user and returns a JWT token
  <h3 align='center'>Files</h3>
    
    ~ GET /files: Returns a list of all files

    ~ POST /files: Uploads a new file
    
    ~ PATCH /files/:id: Changes the permission of a file
    ~ GET /files/:id: Returns the file with the specified ID
    ~ GET /files/:id/thumbnail: Returns a thumbnail of the image file with the specified ID

<h3 align='center'>Credits</h3>

This project was built by [Elisha Mbadi](https://github.com/elishambadi) and [Dovine K.](https://github.com/dovineowuor) as part of a back-end trimester.

