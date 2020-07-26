# esolJavaBlogs

Developed the application to post the announcement of the text regarding the project using the backend application through Rest Api.

Application is developed using Springboot framework.


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
