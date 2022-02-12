# File upload app

The goal of the project is to upload a file and write the file information to the database. This app is used together with user-sequelize-app (https://github.com/ks-ieremenko/user-sequelize-app).

* Install dependencies with `npm install`
* Run the express server with `npm start`
* Open your browser in `localhost:3001` and try the example REST endpoints.


**! Uploading file and reading it's info from db is available only for admin role. !**

  * Used endpoints
	  * `localhost:3001/read` (GET) - read file info
	  * `localhost:3001/upload` (POST) - upload a file
		  * Body format: file.txt
	  * `localhost:3000/user?uuid=some_id` (GET) - get user by id to check if uuid is admin's


Used technologies: express, mongodb+mongoose, multer
