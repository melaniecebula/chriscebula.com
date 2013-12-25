alexcebula.com
===============

simple starter website for alex

Hi Alex!  You're a CS major, and that means you should have your own site to play around with.  This is a basic guide to ezpz web development.  There are a bunch of things you can use, but here's what I use!

For reference, this repo sets up a basic website using node.js and express (ejs).

Domain:  I registered alexcebula.com for you.  For domains, namecheap.com tends to be the cheapest place to get one.
<br>
	<strong>GOAL</strong>:  Create a namecheap account so that I can transfer the domain to you!

Hosting:  Even though you've got a domain, you probably want to put something on it.  There are several different options.  Personally, I'd go with Amazon Web Services.  If you register as a student with Amazon Web Services, you get a free micro-instance (which is enough to run your website year-round without paying a cent!).  
<br>
	<strong>GOAL</strong>:  Create a student AWS account.

Web-page:  So you've got a domain, and a place to host stuff, but you don't have stuff!  So you're going to want to set up something for people to see.  This is where HTML (and CSS) come in.  
<br>
	<strong>GOAL</strong>:  learn/review basic HTML  
<br>
	<strong>OPTIONAL</strong>:  learn/review basic CSS  (Hint:  all you really need so far is like some text)

Server:  Okay!  You've got a *really* basic page, but how do you get people to see it?  You need a server to serve up html pages, images, documents (like resumes), and anything else you want people to see.  I use node.js and express.js to do this.  Its super duper easy to do.  
<br>
	<strong>GOAL</strong>:  Download the following (from terminal or elsewhere): node.js, expressjs/ ejs, npm (node package manager)
<br>
	<strong>GOAL</strong>:  Make a package.json and server.js file.  (Copy my code for server.js- its fairly standard.  Modify the package.json- the important bit is the dependencies- in this case I am using specific versions of node.js and ejs because I haven't bothered to learn the newer versions).
<br>
	<strong>GOAL</strong>:  Type npm install in your terminal to get the dependencies from your package.json.  If you get OKs you should be good, otherwise you may have to fix problems with the file or npm.
<br>
	<strong>GOAL</strong>:  get the general node set up working (hint:  copy the basic structure from my repo on github.  Your server.js file expects a /views and /static directory to exist in your repo.  Views has the .html and .ejs files, and Static has cs, img, and js subdirectories)
<br>
	<strong>GOAL</strong>:  change your .html file to .ejs and have it load on '/' from your server.  (hint:  my code looks for a index.ejs file in /views)
<br>
	<strong>GOAL</strong>:  Run the server.  Type 'sudo node server.js', or just 'node server.js (you may get an EACCES error though, which I override with sudo).  If you don't get an error message, and getting ("Server running on port 80") in your terminal, you're all good to go!  More likely, you'll have to deal with some minor issues before you get it up and running.  If you are serving up your index.ejs file, you should see whatever text you have on your file by going to localhost:80 in your browser

<br>
What else?
	Assuming I haven't missed any vital steps, you've got an index page running on localhost.  Now the main thing left is using AWS.  You'll have to run a micro-instance through aws, ssh into the instance, and then run the server from there (you'll have to look into making a server run in the background- simply running 'sudo node server.js' won't do if you want something running ALL the time!)
<br>
	<strong>GOAL</strong>:  Look into the nohup command or similar, for uninterrupted servers.
<br>
	<strong>GOAL</strong>:  Launch a micro-instance using AWS.  Be warned, its a bit of a doozy working on it the first time!  (It can get a little complicated.  You can follow a guide or grab me and we can suffer together)
<br>
	<strong>GOAL</strong>:  Put the repo you have containing your website on the micro-instance, and run it from there (preferrably with no hangup).
<br>
	<strong>GOAL</strong>:  Retrieve the domain privileges from me if you haven't already.
<br>
	<strong>GOAL</strong>:  Take the AWS link you have for your micro-instance (its long and complicated so just copy it), and go to your domain --> Host Management --> URL FORWARDING and under HOST NAME www, put the link to the instance (http://ec2-....), save it as URL FRAME.
<br>
	<strong>GOAL</strong>:  You may need to mess around with it, but navigate to your website and fiddle until its up and running!
<br>
Extra bits:
	<br>
	<strong>GOAL</strong>:  Use CSS!
	<br>
	<strong>GOAL</strong>:  Use an image!
	<br>
	<strong>GOAL</strong>:  Use a link! (or an image with a link! or a button!)
	<br>
	<strong>GOAL</strong>:  Use bootstrap to AUTOMAGICALLY make everything prettir.  Or use a bootstrap snippet (they're buttons, for example) since they're so pretty and do the work for you
	<br>
	<strong>GOAL</strong>:  Look into using git and github for easily moving code around and version control.
	<br>
	<strong>GOAL</strong>:  Make a favicon, use a title so the tab is pretty.
	<br>
	<strong>GOAL</strong>:  Have more than one page!
	<br>
	<strong>GOAL</strong>:  Have a link to a pdf of your resume.



