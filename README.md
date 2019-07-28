# Clouddeveloper-image-filter
Submission for Udacity Cloud Developer program homework #2
This program exposes an endpoint running on Elastic Beanstalk, and uses a query parameter to download an image from a public URL, filter it, and then return the filtered image to the client.


# Usage
### Installation
- Once the repository has been downloaded, you will need to first install all dependencies by running `npm i`. 
- You can then run the program by running `npm run dev`.
- Once the server is running, you can access the URL endpoints using your browser at `localhost:{{PORT}}`.

### Endpoints to access
- Using the development server, you will be able to access the following 3 endpoints:
> `http://localhost:{{PORT}}/`
> `http://localhost:{{PORT}}/api/v0/`
> `http://localhost:{{PORT}}/filteredimage?image_url=https://timedotcom.files.wordpress.com/2019/03/kitten-report.jpg`
- Likewise with Elastic Beanstalk, you will be able to access the following 3 endpoints:
> `http://{{eb_server}}/`
> `http://{{eb_server}}/api/v0/`
> `http://{{eb_server}}/filteredimage?image_url=https://timedotcom.files.wordpress.com/2019/03/kitten-report.jpg`

### Postman
- Load the `cloud-cdnd-c2-final.postman_collection.json` file into Postman, and you will be able to run the 6 tests for both local and Elastic Beanstalk servers. 

### Kudos
- Many thanks to cdCarlos for the inspiration: https://github.com/cdCarlos

