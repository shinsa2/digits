<h1>Digits</h1>
<img src="doc/landing-page.png">

<h3>Installation Instructions:</h3>
<p><a href="https://www.meteor.com/install">Install meteor</a></p>
<p>Download <a href="https://github.com/shinsa2/digits">a copy of Digits</a>. You may need to request permission to gain access to the repo.</p>
<p>cd into the app directory and type:</p>
<p>meteor npm install</p>
<p>run the application by typing:</p>
<p>meteor npm run start</p>
<p>The first time running this app will create default users and data.</p>
<p>Ignore any bcrypt warnings for the early stages of development.</p>
<p>The template application will appear at <a href="http://localhost:3000">http://localhost:3000</a>. You can login using the credentials in <a href="http://github.com/ics-software-engineering/meteor-application-template-react/blob/master/config/settings.development.json">settings.development.json</a>
<p>Check for any ESLint errors with</p>
<p>meteor npm run lint</p>

<h3>User Interface Walkthrough</h3>
<h4>Landing Page<h4>
<p>You will see the homepage / landing page that gives you information of the site's features.</p>
<p><img src="doc/landing-page.png"></p>
<h4>Registration<h4>
<p>Register for an account by clicking "Login" then "Sign Up"</p>
<p><img src="doc/registration.png"></p>
<h4>Sign In<h4>
<p>Click "Login" then "Sign in" to take you to the login page and sign in to your account</p>
<p><img src="doc/login.png"></p>
<h4>User Home Page</h4>
<p>After logging in, it takes you back to the home page with an updated navbar.</p>
<p><img src="doc/homepage.png"></p>
<h4>Add Contact</h4>
<p>The Add Contact page lets you add a new contact.</p>
<p><img src="doc/add-contact.png"></p>
<h4>List Contacts</h4>
<p>The List Contact page shows a list of all of your contacts.</p>
<p><img src="doc/list-contacts.png"></p>
<p>You can also add a timestamped note at the botton of their contact info.</p>
<p><img src="doc/add-note.png"></p>
<h4>Edit Contact</h4>
<p>Clicking on "edit" lets you edit the selected person's contact info.</p>
<p><img src="doc/edit-contact.png"></p>
<h4>Admin User</h4>
<p>It is possible to designate one or more users as “Admins” through the settings file. When a user has the Admin role, they get access to a special NavBar link that retrieves a page listing all Contacts associated with all users.</h4>
<p><img src="doc/admin.png"></p>