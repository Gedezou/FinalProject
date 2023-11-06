#SLOW CENTER#
### Video Demo: <https://youtu.be/Eeffo272tpI> ###


###Discription
This is a web app
website I created

The first file are my python files one to view what files are displayed on the page
app.py is there to generate the website and create the app.
auth.py is my authorization page, for hashing the password, email and to check the database for that user if they are sign up. in order to sign in

and to log them out.

then the views.py is for those who are logged in
to view any pages or information on the website.
via get and post methodes, and to redirect them to the homepage when needed.

Models.py is created to store all of the data that is needed, users id
notes, events created, emails, password, id, usernames.
 init is created to generate a hash dor securing the passwords the usr is using, so when your looking at the layout the user's information is kept safe'

 sql stores the data and is created for each user login_manager help in this process
login_view to authorize the viewing page and init.py pages

the static pages is created for my javasript pages css, images, pdf's for all the links which will be called by my html pages for functions, styles,  and images i intended to use but got distracted.
inside templates you will find an array of html pages, base is the main one and home is extending that page with my lauout, fonts, headers, time, text, where you will find most of the details about my homepage, there's references to styles on base to bootstrap for different styling, and javascript which is blocked out on there.
There's the loging in layout page, which mostly came from bootstrap.
theres a link in base for the layout.

inside the sign_up page youll find the layout for the sign up page which is also created via bootstrap, you'll find a link to that in base.
and iside the auth.py page you'll find the query for the sign_up  verification, and database to store the email, password and to flash a message once all the fields are meant that you have created an account.

inside index you'll find its a list created once  you prompt the website to get view.py responds by posting the content of index.

home is then reference to by a navbar button abd log out on the views.py on the website once you have sucessfully sign_up and logged in.

you are now inside of the base.html and home.html and are able to click various button on that is a friend us, and another a quote.

theres a drop down button which is created inside of the home.html to navigate to different links to index.html which is a calendar created using javascript, css and sql to create the layout, day month, year, css for the style and java for the function of all  buttons and a envet feature to be stored on the claendar.

there are various css style pages created, had a lot of design idea's, and calendar function ideas. 

###
