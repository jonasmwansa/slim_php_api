A publishing house wants to create a web app to manage their content (publishing, editing, etc). As part of their database setup, there is an articles table in the database which has columns (id, title, description, status, created_by, created_at). The created_by is a foreign key that references the admin table with columns (id, name, email_address, created_at). Articles are created by an admin and new articles have a default status value of unpublished.

 this work constitutes of : <br />
-- An endpoint to create a new article <br />
-- An endpoint to update an existing article. <br />
-- An endpoint to delete an existing article.<br />
-- An endpoint to publish an unpublished article. <br />
-- An endpoint to show all published articles <br />
-- An endpoint to retrieve just a single article

below is a documentation for the api <br/>

[documentation here ](https://documenter.getpostman.com/view/21359265/UzBnqmD2)

