# Flask Blog

Flask Blog is a simple web application built using Flask and SQLAlchemy. It allows users to create, view, edit, and delete blog posts.

## Features

- **Create Post:** Users can create new blog posts by filling out a form with the post title, subtitle, author, image URL, and content.
- **View Post:** Users can view individual blog posts by clicking on their titles.
- **Edit Post:** Users can edit existing blog posts, updating their title, subtitle, author, image URL, and content.
- **Delete Post:** Users can delete existing blog posts.
- **Rich Text Editing:** The application integrates CKEditor for a rich text editing experience when creating or editing blog posts.

## Installation

1. Clone the repository:

```
git clone <repository_url>
```
2. Install dependencies:

```
pip install -r requirements.txt
```

3. Run the application:

```
python app.py
```

4. Access the application in your web browser at http://127.0.0.1:5003.

## Usage

- Navigate to the homepage to view all existing blog posts.
- Click on a post title to view the full post.
- To create a new post, click on the "New Post" button and fill out the form.
- To edit an existing post, click on the "Edit" button below the post and make the desired changes.
- To delete a post, click on the "Delete" button below the post.

## Technologies Used

- Flask
- SQLAlchemy
- Flask-WTF
- Flask-CKEditor
- Bootstrap 5

## Credits
- Original idea and app structure by Angela Yu, 100 Days of Code - The Complete Python Pro Bootcamp 
- Bootstrap Theme: [Start Bootstrap - Clean Blog](https://startbootstrap.com/theme/clean-blog)
  - Copyright 2013-2023 Start Bootstrap
  - Licensed under MIT ([License](https://github.com/StartBootstrap/startbootstrap-clean-blog/blob/master/LICENSE))
- Bootstrap: [Bootstrap v5.2.3](https://getbootstrap.com/)
  - Copyright 2011-2022 The Bootstrap Authors
  - Copyright 2011-2022 Twitter, Inc.
  - Licensed under MIT ([License](https://github.com/twbs/bootstrap/blob/main/LICENSE))
