A publishing house wants to create a web app to manage their content (publishing, editing, etc). As part of their database setup, there is an articles table in the database which has columns (id, title, description, status, created_by, created_at). The created_by is a foreign key that references the admin table with columns (id, name, email_address, created_at).
Articles are created by an admin and new articles have a default status value of unpublished.

As the Tech resource of the publishing house you have been tasked with creating;

An endpoint to create a new article.
An endpoint to update an existing article.
An endpoint to delete an existing article.
An endpoint to publish an unpublished article.
An endpoint to show all published articles
An endpoint to retrieve just a single article
