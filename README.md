<h1 align="center"> [click a book](http://click-a-book.herokuapp.com/)</h1>
<div align-itmes="center">
<h2 align="center">
    <a  href=""  target="_blank"><img  src="/documentation/gifs-view/desktop.png"  alt="click-a-book desktop screen"/></a>
<br>
    <a  href=""  target="_blank"><img  src="/documentation/gifs-view/mobile.gif" alt="click-a-book mobile Screen"/></a>
</h2>
</div>
<h2 align="center">[click a book](http://click-a-book.herokuapp.com/)</h2>


**click a book**  is a website of for a fictional book club set up by the founders of the book club. 

***

This project is created for the Practical Python and Data-Centric Development module at the **Full Stack Software Development Course** with **Code Institute**.

**The brief** 

_Project purpose_: In this project, you'll build a full-stack site that allows your users to manage a common dataset about a particular domain.

_Main Technologies Required_: HTML, CSS, JavaScript, Python, Flask, MongoDB.

_Optional_: Additional libraries and external APIs.

_Value provided_:

1. Users make use of the site to share their own data with the community, and benefit from having convenient access to the data provided by all other members.

2. The site owner advances their own goals by providing this functionality, potentially by being a regular user themselves. The site owner might also benefit from the collection of the dataset as a whole.

   

   

***

This web app will use ***\*CRUD\**** operations so the users can create, read, update and delete data from the database (MongoDB) and is hosted on Heroku.com.

**THE IDEA**

_click a book_ is a web app of a book club set up by the founders of the book club. They post suggestions of books for the next meetup and members can log in and pick the book they are interested in reading for the next meetup.

 I have chose this theme for the website because I like reading books and I think I can understand better how a user will navigate the site and what are their expectations when they open the website. 

### The need:

The book club founder wants to have a platform where the book club members can see her book suggestions for the next meetup. This way they can pick their favourite and they can comment on it why they would like to read that book.

### The goals of this website are:

* The books  on the website are posted by the book club founder through the MongoDB Database and fetched on the website.
* Provide a choice of books to the book club members, so they can pick which book they would like to read for their next book club meetup.
* Only registered  members can see the comments posted by other users or post their comments  on the site.
* Provide a clean feel and easy to navigate website, on all screen sizes.

***

###  UX

Common characteristics of a user:

* Avid reader who likes discovering new books, sharing their reading list and review books.
* Book club member or someone who is interested in joining the book club.

#### Design and colours

##### Fonts

For logo I have used two fonts: _Merryweather_ and _Old Standard_ to emphasise the word _book_.

I have used two fonts, _Open Sans_ for general text displayed on the site. It's easy to read and looks good on all devices. Where I need to put more emphasis on a piece of text, I have used Libre Baskerville. Because is a books/reading related website, I think it fits well with the theme.

##### Colour Scheme

I wanted the user to get a sense of calmness and warmth when they open the website. To invite them to think about the feel and look of the books they have read or they will like to read. 
I have used the website [Coolors.co](https://coolors.co/) to create the colour scheme. I have used #e3c6b9 ![#e3c6b9](https://placehold.it/15/e3c6b9/000000?text=+) , #F6FEDB ![#F6FEDB](https://placehold.it/15/F6FEDB/000000?text=+) , #f4f4f4![#f4f4f4](https://placehold.it/15/f4f4f4/000000?text=+) as main colours. 

These colours bring a sense of calmness and cleanness for the reader to put them in a peaceful  state when they read through the website.

#### Design wireframes / mock-ups:

At the beginning of the  project, the ideas a bit more complex, but I downsized it, so I can meet the submission deadline. 

Click on the below links to see the wireframes or you can view them in the  [wireframes](/documentation/wireframes) folder.

#### Wireframes

* **[Desktop view](/documentation/wireframes/desktop)**
* **[Mobile view](/documentation/wireframes/mobile)**


#### Users stories:

* As a _general user_ I would like to get a clean and calm feel of the website when I open it.

* As a _general user_, I want to be able to create an account with password protected.

* As a _general user_, I want to be able to read synopsis of the books the book club founder posted on the website.

* *As a registered user*, I want to navigate my way easy on the website, to browse around through the content.

* As a _registered user_ I would like to be able to log in and log out from my account to keep it secure and private.

* As a _registered user_ I would like to be able to delete my account at any point.

* As a _registered user_ I would like to be able to comment on books.

* As a _registered user_ I would like to be able delete comments I've posted.

* As a _registered user_ I would like to be able update any comments I've posted.

* As a _registered user_ I would like to be able delete any comments I've posted.

  

***

## Database

### Database Type



### Database Design



_______________________________________



### FEATURES

#### EXISTING FEATURES

#### Logo 

I have created the logo for _click a book_ web app with [Canva](https://www.canva.com/). 


#### FEATURES left to implement

* 

### Technologies Used

I have created this website with the help of a multiple technologies:

* [HTML](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5) to creating the main structure of my pages.

* [CSS](https://www.w3.org/Style/CSS/Overview.en.html) for styling my components and layout on the page.

* [Python](https://www.python.org/) for the back-end development.

* [PyMongo](https://api.mongodb.com/python/current/) as the Python API for MongoDB to bring the data from the database to the web app.

* [Flask](https://flask.palletsprojects.com/en/1.0.x/) is a Python microframework.

* [Jinja](https://jinja.palletsprojects.com/en/2.10.x/) for templating with Flask and HTML. It simplies the code to avoid repetition and links data from MongoDB.

* [MongoDB](https://cloud.mongodb.com/) as a database to keep all the records. 

* [Visual Studio Code](https://code.visualstudio.com/) and [Gitpod](https://gitpod.com) was used as IDE.

* [JavaScript](https://www.javascript.com/) for adding interactivity on the page.

* [jQuery](https://jquery.com/) for JavaScript functionality and Materialize.

* [git](https://git-scm.com/) for saving my code in Github.

* [Bootstrap](https://getbootstrap.com/) as a framework to make the web app respnsive.

* [Google Fonts](https://fonts.google.com/) for linking fonts.

* [GitHub Desktop](https://desktop.github.com/) for pushing code from Visual Studio code from my machine to Github.

* [Heroku](https://www.heroku.com/) for hosting and deploying the web app.
  

***

### TESTING



***

### Deployment

At the beginning I have started the development on my machine with Visual Studio code and I was saving  regularly the code 
in a repository I have created on GitHub. When I have connected my MongoDB to my app, I have started using Gitpod online IDE.

To make sure the data is linked and displayed correctly I have created an account on Heroku and deployed my web app live. 
This helped me with the debugging part as well.


##### How to run this project locally:

To run this web app locally on your machine you need to have these technologies in place:

- [Python3](https://www.python.org/downloads/) to run the app.py files and the application
- [PIP](https://pip.pypa.io/en/stable/)
- An IDE - Visual Studio Code or online Gitpod
- [git](https://www.atlassian.com/git/tutorials/install-git)
- [MongoDB](https://www.mongodb.com/) - database

***

## Credits

#### Content



#### Media



##### Acknowledgement



#### Disclaimer

The content of this Website is for educational purposes only.