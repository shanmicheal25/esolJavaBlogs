# esolJavaBlogs

Developed the application to post the announcement of the text regarding the project using the backend application through Rest Api.

Application is developed using Springboot framework.

# Download or clone the Front end application from the below URL,

git clone https://github.com/shanmicheal25/esolBlogClient.git

Front end application developed using Angular framework, you can install all package and run the application using below commands,

npm install

ng serve

# Rest API 

Post Blogs

POST http://localhost:9096/rest/blogs

Requst Body:
{
"text": "secnd  post",
"imageURL": "petshop.jpg"
}

Read a Blogs

GET http://localhost:9096/rest/blogs

Post a comment for particular blog with postId

POST http://localhost:9096/rest/comment
{
"postId": 2,
"commentText": "afasd fsadf ads fsda fsadf sd"
} 
