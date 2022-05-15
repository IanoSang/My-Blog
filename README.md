# My-Blog
<p>This is a personal blogging website where you can create and share your opinions and other users can read and comment on them. </p>
<p> Additionally, It has a feature that displays random quotes to inspire users.</p>


### Technologies Used

- Python
- Flask
- Sqlalchemy

### Prerequisites
- git
- Package manager - pip
- Environment manager - virtual env

### Setup Instructions and Installation
- In your preferred location in your file system, create a virtual environment and activate it
- Launch your terminal and paste the following command: `git clone https://github.com/BrianMwevi/news-flash.git`
- Change directory to news-flash `cd news-flash`
- Open the project with your preferred IDE and run the following command in the terminal: `pip install -r requirements.txt`
- Go to [NewsApi](https://newsapi.org/) and generate an API Key for your application
- create a file named `start.py` in the root of your application and change it's permissions: `chmod a+x start.py`
- Create two variables in the start.py file:
    >>> `export NEWS_API_KEY='your apikey'` <br>
    >>> `export SECRET_KEY='your secret key'`
- Run the application by typing the following in the terminal: `./start.py`

### User Stories
<ul>
  <li>The user is able to view the blog posts on the site</li>
  <li>The user is also able like to comment on blog posts</li>
  <li>The user is able view the most recent posts</li>
  <li>The user is to receive an email alert when a new post is made by joining a subscription.</li>
  <li>The user is to see random quotes on the site.</li>
  <li>The user is to like to sign in to the blog.</li>
  <li>The user is also able to create a blog from the application.</li>
  <li>The user is able to delete comments that I find insulting or degrading.</li>
  <li>The user is able to update or delete blogs I have created.</li>
 
 
 </ul>

### Known Bugs

No known bugs.


### License

_MIT Licence_
Copyright (c) 2022 **Ian Sang**<br>
Email: ianosang18@gmail.com<br>
[Read More](https://github.com/IanoSang/My-Blog/blob/main/LICENSE)


[Go Back To Top](#My-Blog)
