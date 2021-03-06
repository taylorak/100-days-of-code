# 100 Days Of Code - Log

### Day 1: January 1, 2017

**Today's Progress**: Added a new angular component and set up a new route. Started
adding in unit tests for components. Began getting back into python by writing a
simple client and server.

**Thoughts:** I struggled a bit with sending params to an angular component with ui-router. I want to eventually switch to a version of ui-router that lets me pass in my component instead of a template. Setting up testing for my app was the real problem. I am still trying to figure out the best way to setup my project for unit testing with Karma, Jasmine, and Webpack. Today I also began getting back into python. I started by writing a simple client and server program. I want to eventually make a web scraper using python so I will continue learning more python on the side.

**Link to work:** [Lemon App](https://github.com/taylorak/lemon)

### Day 2: January 2, 2017

**Today's Progress**: Continued learning python by creating a simple socket echo
server and began writing a simple socket http server.

**Thoughts:** Ran into problems connecting the browser to my simple http server but curl worked fine. Need to figure out what is blocking the browser connection.

**Link to work:** [python-demo](https://github.com/taylorak/python-demo)

### Day 3: January 3, 2017

**Today's Progress**: Unboxed my rasberry pi 3 and set it up. Continued fixing
up my simple socket server in python and started writing a simple web crawler.

**Thoughts:** Spent too much time fixing some basic python syntax to get my socket server and web crawler running. It's been a long time since I last used python so I am going to go back and relearn the basics. Looking forward to making something with python or node on my rasbperry pi.

**Link to work:** [python-demo](https://github.com/taylorak/python-demo)

### Day 4: January 3, 2017

**Today's Progress**: Started looking through the node dominos pizza api. Began
testing out code on my raspberry pi for ordering pizza.

**Thoughts:** Dominos garlic parmesian sauce(white sauce) is the bomb.

### Day 5: January 4, 2017

**Today's Progress**: Started writing a dashboard to display pizza orders and
configure customer information. Looked through nodejs libraries for raspberry pi
gpio pins.

**Thoughts:** Should have checked that I had all the necessary items for
connecting with my raspberry pi. Need to get some wires and a button before continuing with my pizza button.

### Day 6: January 7, 2017

**Today's Progress**: Skipped a few days because I moved to a new apartment in
Washington. Worked on learning more python basics and data structures.

**Thoughts:** Left a bunch of my raspberry pi stuff in Hawaii and my internet has not been set up in my new apartment. Was really busy but I managed to work in a little time to at least play with python.

### Day 7: January 8, 2017

**Today's Progress**: Worked on routing with angular ui router for individual
project page in my project managment app. Modified links on my project list page
to redirect to their respective individual pages.

**Thoughts:** Working with no wifi, but managed to power through adding routing. Next time I work on my angular app I need to fix up the service that is returning projects since it is currently not filtering correctly.

**Link to work:** [Lemon App](https://github.com/taylorak/lemon)

### Day 8: January 9, 2017

**Today's Progress**: Started working on the api for my angular app. Decided to
use asp dotnet core. Learned about making new projects and how to make an api
with asp dotnet.

**Thoughts:** There are so many different generators for asp dotnet core projects and theres a lot of magic that I don't understand. I need to continue watching some tutorials and make some test projects before I add dotnet core to my angular app.

**Link to work:** [Lemon App](https://github.com/taylorak/lemon)

### Day 9: January 10, 2017

**Today's Progress**: Followed a couple tutorials from Pluralsight about making
API's with dotnet core. Worked on setting up the server and forms for adding
project details to my angular app.

**Thoughts:** New apartment, new job, 1 hour of code is feeling pretty tough right now. Slowly working on my angular app when I have time and once I gete some of my stuff moved in I can begin working on my raspberry pi project again.

**Link to work:** [Lemon App](https://github.com/taylorak/lemon)

### Day 10: January 12, 2017

**Today's Progress**: More practice with dotnet core. Started reading Docker in
Action to practice setting up a multi container environment that will contain
angular frontend and dotnet core backend.

**Thoughts:** Used docker several times before but never really got a deep understanding of it. I hope that by setting up a full project with it that I can really understand how it works.

**Link to work:** [Lemon App](https://github.com/taylorak/lemon)

### Day 11: January 13, 2017

**Today's Progress**: Remade my dotnet api from scratch following a tutorial on
pluralsight instead of using a prebuilt template so that I can better understand
what is going on.

**Thoughts:** Found that the template I was using included too many dependencies
and parts that it made it hard for me to grasp what is going on as a beginner.
Using an empty template included just enough templating to start a project
without it being too much.

**Link to work:** [Lemon App](https://github.com/taylorak/lemon)

### Day 12: January 14, 2017

**Today's Progress**: Added in CORS to my dotnet API so my angular app could
communicate with it. Added several more dummy routes for getting specific
projects and adding projects. Still working through pluralsight videos and will
eventually integrate an actual database with data into my ap.

**Thoughts:** When I changed my angular app to start hitting the API started
running into CORS errors but it was a simple fix to get the basic CORS service
working on the server. Still learning how to make APIs with dotnet core, so not
much real data yet but I will eventually get more into Entity Framework and
attach an actual database.

**Link to work:** [Lemon App](https://github.com/taylorak/lemon)

### Day 13: January 15, 2017

**Today's Progress**: Ran in to several more issues with CORS, that were fixed
after looking through the docs. Added a create and update route for my API.
Updated my angular API to hit the get individual projects and create new
projects with the new API.

**Thoughts:** Got stuck on fixing CORS issues after I tried to hit my create
project API route from my angular app. Needed to add a line to my startup config
file to fix it. Also found a watcher tool that updates my server when I change
my cs files, very helpful.

**Link to work:** [Lemon App](https://github.com/taylorak/lemon)

### Day 14: January 16, 2017

**Today's Progress**: Added a route for deleting projects to my API. Learned
about dependency injection in dotnet core web apps and added Nlog to my project.

**Thoughts:** Got stuck with adding Nlog to my project. My configuration was
wrong and I didn't know how to see what I was doing wrong. Eventually I found
that I misstyped something and everything worked fine after that.

**Link to work:** [Lemon App](https://github.com/taylorak/lemon)

### Day 15: January 17, 2017

**Today's Progress**: Started Adding Entity Framework to my application.

**Thoughts:** Using MS SQL but I have not used it very much before. A lot of
unknown quirks.

**Link to work:** [Lemon App](https://github.com/taylorak/lemon)

### Day 16: January 18, 2017

**Today's Progress**: Learned more about the Entity Framework and played around
with MS SQL. Also, learned how to do migrations with dotnet.

**Thoughts:** Was stuck on how to add migrations until I realized that you need
to add Microsoft.EntityFrameworkCore.Tools.DotNet to the tools section of
project.json.

**Link to work:** [Lemon App](https://github.com/taylorak/lemon)

### Day 17: January 21, 2017

**Today's Progress**: Wrote some code for my arduino for change of pace and practiced with
ocLazyLoader for angular lazy loading.

**Thoughts:** Missed two days because I had work to do. Wasn't really feeling
like working on my Lemon App so I decided to work on something else and get back
to it later.

### Day 18: January 22, 2017

**Today's Progress**: Got really deep into angular-ui-router.

**Thoughts:** Trying to understand the underlying components of
angular-ui-router to be able to build something similar.

### Day 19: January 24, 2017

**Today's Progress**: Working on adding production and development webpack
configs to my angular project. Also trying to come up with a Dockerfile that I
can use for the angular project as well.

**Thoughts:** I am rusty with both webpack and docker so I need to spend a
little time re learning the technology, but this project should be the perfect
chance. I want to split my current webpack config into several smaller chunks.

**Link to work:** [Lemon App](https://github.com/taylorak/lemon)

### Day 20: January 25, 2017

**Today's Progress**: Added more necessary configuration for building a
production build with webpack. Breaking my giant config file into manageable
pieces.

**Thoughts:** There is a lot of configuration options that I am learning about
that will improve my bundled app. I am going with a fairly basic build because I
don't want to dive too deep into webpack but it is interesting.

**Link to work:** [Lemon App](https://github.com/taylorak/lemon)

### Day 21: January 27, 2017

**Today's Progress**: Got a monitor and my raspberry pi stuff in the mail. I
worked on setting up my pi and can hopefully get back to some project i shelved.
Started reading and practicing docker a little bit more. Going to add a
Dockerfile to my angular app next.

**Thoughts:** I am pretty beginner at docker and need to read up a lot on how to
configure dockerfiles. Hopefully with my hour of code a day that won't take too
long.

**Link to work:** [Lemon App](https://github.com/taylorak/lemon)
