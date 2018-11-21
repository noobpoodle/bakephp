# bakephp
A modern, extensible, efficient, and fast revision of the cake frame work version 1.2.0.4451alpha


# content
Please read further for a project introduction, a personal introduction, a top three most asked QA, and an advisement on why I created this repo.

This is my first ever github repository, and although I 
have considered handling this several different ways 
one fun idea I had was to introduce a personal project
of mine to the general developing public, to raise some
eye brows, maybe I don't know, get a little attention
for all the right reasons. In that spirit I have taken
it on myself to consider releasing a project that has
taken on a somewhat standardized approach through it's
versions and that is my customization of a cakePHP frame
work or install et al.

In the spirit of honoring standards I thought to myself,
what use would the general public have for such a funny
idea. Probably a question even those most beloved of the
cakePHP fan base posed in self reflection over the idea,
no the concept, of reversioning and releasing a dated 
model of the frame work, no less one of the first 
versions. But I challenge, this was not done as a joke,
it's as "cool" as I would like to think it sounds, and 
interestingly enough as extensible as a any RESTful 
application of customized MVC code base needs to be.

    "Your description says 'A modern, extensible, efficient, and fast revision of the cake frame work version 1.2.0.4451alpha' .. surely, uh, i mean.."


So, why, on earth would some one want to bring version
1.2 alpha back from the depths of history to attempt a
modern take on a frame work still arguably struggling 
for it's place among beloved MVC design paradigms and
code bases. Well that's a good question, but of course
in the end I made the attempt just to see if it could
be done, and if I could be the one to do it. I also 
still maintain a certain appreciation for this design
paradigm in general over all others. In my humble 
opinion I think the cakePHP frame work represents the
best of design topologies ever realized using what is
now to date version 7 of our beloved scripting lang.,
and I will probably argue that to the end. But to be 
perfectly honest, it's boss. I mean really this IS
cool, it's fast, it's not bloated, it keeps server
RDMS queries at a minimum, it's from a time before
plugins and libraries were even really fleshed out
as official releases for this frame work, and I intend
to show how, with a proper approach to templating and
WYSIWYG almost "Wix" like inline and real time design
and development -how, the cakePHP fan base can claim
to have had the best frame work for proprietery web
DEVELOPMENT since day one, hands down, game over. The
truth is I've already showed that to myself over the 
years as a blossoming Drupal and Wordpress themer, and
now I intend to show you. And to start and yes I did
mention Wix, one might wish to begin with any version
of php from 5.2.6 through 7.1.13 to date and doing so
with no sacrifices.


    "Your first github, your first repo, your first public release of code, by posting an extremely dated version of the cake frame work??"
    
Actually it is not entirely my first public release of
code. My first release of code publicly was actually a
color spy and an mp3 player designed in Visual Basic 6
many moons ago. I then toyed with a Javascript super 
class which has since major CDN releases of jQuery and
Prototype, and nodeJS become..unnecessary, to put it
bluntly. In fact I often find myself using Skeleton and
Bootstrap with a preference of an all locally hosted JS
code base and library. I released my own library called
Jellow.lib for those seeking a RESTful approach to the
proprietery development of real estate applications and
data pulls in general, With little else interesting my
own personal proprietery development in my later career
aside from this very code base, the one I am to show off,
and module development for PHP in C, with a growing and
warranted concern for the impact nodeJS is having on all
languages, and my own blossoming interest in Ruby and 
JAVA programming in general.


    "So you're trying to show off with this. We know how to handle trolls alright! What exactly are you hoping to accomplish here?!"



In fact, I have decided to create my first repository and to truly commit to versioning my projects by publicly showing collaberative (those NDA will allow) examples starting
with this most excellent error free, efficient frame 
work that we can call, bakePHP. And with good reasons,
but in the end none better than to show case what I 
hope you will agree is true extensibility by example.,
And for those of you who don't know me my by name 
my name is Nathan Addison Stamm, I've been quietly
teaching myself web design development and server
administration for the past fourteen of nineteen
years with many collaberations with major companies,
an occasionally stable client base, and many hopes
and dreams of continuing my career path in that
regard as I have always had little need for any type
of recognition. From 2013 to 2018 I have been moving
back and forth, traveling, and breaking from any real
serious work as I reach my mid life to consider how
I will move forward. I apologize for the littany but,
I felt the aforementioned necessary before releasing
what is my first repo.


In general, I really just want to experience GitHub!
And if you are at all interested, laughing, crying, or
enticed to dive further into this repository I am sure
that saavy developers will find plenty to recommend
changes or updates to. 

# Example 1.a. - Use of routes, why /app/url/html??

If you don't like my routing, or use of routes, or 
file folder heirarchy to be blunt, you can change it!
And really it's meant to be changed.. /html/whatever
is just the default. Remember, we are actually using
default routing for this particular version of cake
using the default methods. This setup was always 
quite View > Controller with Model relationships
arguably optional in less complex database and data
relationship situations. Where more complexity or the desire to BAKE your app on the fly become important, models can and should be considered.


But for simplicity sake, routing is still default,
it's that simple really. And if some one challenges
it is lacking the most basic of paradigms in dynamic
web application functionality, just remind them that
your entire webroot is still intact, can still spawn
from your main website DocumentRoot, and with good
application design be as dynamic and CRUDworthy as it
needs to be afterall.

Arguing a lack of dynamic or bake content - worthy in server side development flexibility and speed is like comparing Wordpress taxonomy to the petals of a rose that has
not yet bloomed full. The functionality for creating,
reading, updating, and deleting and the interaction
with the RDMS is only a nuisance to one who has not
yet created a good templating schema for the taxonomy
of basic app data using their system. I provide this
basic functionality in a simplified version, given 
how the "application" (s) are abstracted from default
for read and usability I consider this an acceptable
trade for baking apps.


And I think you will too, after all you can still feel
free to bake your app. In short that is a no, dynamic 
creation of taxonomies exists in my default as it is
provided through my own Admin back end over "baking".
Just login to your APP by default at the simple url
/html/admin/user/  session management is handled by 
default in my version.

Quite simply how ever, the Admin back end is not 
required to "bake".

# Example 1.a. (Redux) - So I can still bake my app?


Absolutely. Pull routing controllers out of the sub
directories if you desire as well and use the start
baking cake page. The system will provide all of the
functionality you have been used to for naming of
relational urls, taxonomies, sub directories and the 
like, I simply prefer to call a spade a spade and
acknowledge that we are managing taxonomies and meta
data and can do so with session management integrated
instead of baking.

Your "later baker" will probably prefer to just keep baking and heck why not, you will still be using an efficient and version saavy core.



# Example 1.b - A config.sandbox.php file, but why??

Why do the stars twinkle! There are reasons but in 
the end it's a quite important file. Establish your
paths and definitions here and instantly you will be
able to appreciate just how extensible the core code
base is in totality.

# Example 1.c - I am used to /APP and /webroot as my
defaults

Not a problem at all. Remember what we were told by
default from our default application index.php, IF
installed in a directory layout "other than the way
it was distributed". You will note changes to base
names and paths are appropriate for this new and
refined reversion and revision. And if you risk a
problem with older PHP installs and ini_set() issues,
note where we originally set these values. Remember
that good old configuration sandbox file ?? Aha they
got a lot of people with that one, and using a custom
layout and routing structure is more of a preference,
so this really never was a paradigm issue, the entire
layout and directory structure can be made efficient
due to PREFERENCE in honor of prototyping and really,
the general nature of abstraction in it's most core
essence of concept. Push this issue further with the
right client side gui, JS code base, bring plugins 
up to standards and give your clients responsive 
design templates similar to Wordpress or Drupal and
you have a killer CMS in disguise here folks, it's
just that simple.

# Example 1.c Redux - It seems like it's just well..
separated

From what, it's original path layout and definition?
I should have mentioned the focus here is on your
own proprietery development and coding. This can be
but never was intended for cake baking as the system
has developed. Of course baking your cake app and
doing so easily and quickly through the web interface
always was a focus but that's why this is a newer
older reversioning and release. I had contemplated
for a time challenging the latest code base with a
self baking app. I decided with the right tutorials
and help files, a saavy coder can get into the core
essence using THE SAME PLUGINS and component libs
that even the latest cake frame work uses allowing
a proficient (if you are) developer to concentrate
as much on presentational logic and the topology of
their application as a themer would on aesthetic
design, I mean really ..why rebake the same cake
over and over again.

YOU are the proficient developer, set up your routes
and paths as you want them and call it your own, I
simply show one way.


    "So you're just trying to show off a CMS that  you may or may not have used in a different flavor for paid development projects you may or may not have created yourself"
    
    
Absolutely, and here I'm going to call it bakePHP. I
honestly got tired of calling it some - thing - cool
CMS when I realized what I'm introducing for free, I
sort of think showing it off as a reversioned error
free cake frame work version 1.2 alpha as I have set 
it up was enough.

Also I am doing little more in a different way than  can be done by just baking an app using cake core libs, but taxonomically I am offering more flexibility "out of the box".
While still providing all the functionality that the
core cake baker would be used to should they 
wish to keep that.

    "And you're going to provide this all for nothing, show us it's features, it's quirks, it's differences, and it's potential as a back end for a proprietery CMS?"
    
    
Absolutely. This is just a README right now, my first
creation on GitHub., it's a pleasure to be apart of 
this community and I am still actually developing the
CMS aspect currently as a responsive fluidic inline
context editable WYSIWYG editor that is already now
working fine, but requires some attention to my own
asynchronous calls to match up to the menus it shows,
again in a very "Wix" like presentational layout of
real time editable containers. I'm very excited, but,
very strapped for time in my real life, so enjoy what
I can provide and please feel free to take any thing
you need, any way you need, any way you like, hope-
fully to benefit the greater whole. In the end, this
repo will represent the core frame work underlying
that content management system which I plan to use 
myself in my projects.


And lastly it was not my intention to pull any part of the cake community from baking their apps by default, the modern code base is quite awesome.


I simply want bakers to realize that they are appli-
cation devcelopers and that when it comes to urls
and paths, taxonomies and routing, the basics of 
managing that data is more important to setup with
respect to a properly configured RDMS and a proper
taxonomical templating ENGINE backend- I believe
I am promoting good database design and optimization
by doing this, not leading any one astray. After all
the same paths and urls can be realized using either
my own functions provided to the user through Admin
as can be had baking.


Yes with proper model relationships and schema in place the cake system provides all of this functionality, Which is why my functions use them too.

In it's core I also feel that I am addressing old
long forgotten struggles of the cake frame work 
which have most certainly been "mostly" addressed.
No pun intended, but if cake ever felt bloated it
was always related to how the core handled baking
for only a few versions.

		"Are you saying that MVC is being challenged due to the limitations imposed in web server application logic"

That would be an interesting topic to discuss in
terms of some thing like nodeJS, it is not really
appropriate here, because if I can provide an app
that does this better by abstracting the nature
of it's models through more RDMS calls or by
controller logic I am still doing nothing new but
we would be using functionality I have provided
that would manage taxonomical data through
differently structured tables and table 
relationships without the building of bloated
queries which use nearly the same amount of
data, ergo my /html/admin app included as a
backend for "baking", which can be disregarded
for a view controller setup or promoted over
core functionality in favor of ongoing taxonomy
and data "type" management ultimately pushing
the view to a /html/client or similar doc root
front facing web app.

This is also why the user is presented with the 
option to have bake by themselves or with the 
help of cake core libs.

And so of course MVC has been actually been challenged in context of paradigm, But rarely perfected in terms of speed.
I feel that Cake's core libs come close to it sure
but with a few extra data fields and using my 
own functions I have in reality realized major
speed boosts in content, data, and data type
creation AND presentation to an extent that
that reason alone is enough for me to want to
put this code base public, And I will provide
bench marks as well.



And this also addresses a major point of contention in considering data management with PHP in general, And "which engine" best uses PHP's engine.


This is where we are at as PHP developers in the
Autumn of 2018. Yes this is because of nodeJS, 
no there is no answer. At least none I feel safe
putting off on any one elses system aside from 
my own, cake custom.


The speed of the system, and the handling of "virtual" models in context over files used to build queries is reason enough to be involved in the project.


I would not expect any one who has not dealt with an improperly configured baked cake app hacked up to work, to understand, but speed gains are 
quite significant there.
And at the cost of a few extra data fields per
tabular taxonomical data type, parent to child,
etc. was worth learning how to perfect, debug,
and develop fully., as I learned the nuiances of 
how the cake core libs handle models and build
queries moons ago. I still remember the eureka
moment as I learned how to reduce those query
processing durations to a few ms by virtualizing
the queries built using my own database library,
database functions, using default routing setup
in a nondefault and "abstracted" as I call it, app
view controller schema that also reduced time
to render due to the simple and basic nature of
request handling in http, tcp ip and so forth by
separating view paths to even so far as the doc
root (need not be at /html/client etc) so that 
the data returned by an optimized query had
less application logic to traverse before being
rendered to the user. 

Staring directly at the before and after queries, comparing lesser application logic and routed paths to boot, was amazing, as I had bested core libs.
And so began my disdain for using the core libs
for baking ANY app whatsoever as has made
the frame work popular with a majority of it's
user base! Imagine seeing little change in this
regard and knowing you bettered the frame 
work over the past six years since 2012, enter
my current repository.

I would not contend to have created better 
handling of taxonomies or data types and 
meta data than the cake core libs can, any
more than I would challenge the community
of beloved Wordpress and Drupal devs. But,
I have benchmarked my system in it's past,
and speed wasn't even close, not only have I
made it faster than it exists "baking" apps by
using default libs, it is worlds faster than the
better setup WP and Drupal apps I have ever
come across in simple terms, and I look to
to reaching that juncture publicly in comparing
a similarly setup application using default
methods with comparable systems. The 
proprietery developer in me partly designed
this system as one last rebellion against
joining the crowd of Wordpress templaters,
and themers, and also partly because of
basic licensing & royalty,


If by chance you have used my system and found it to be as efficient and straight forward as I intended it to be please drop a positive line any time.
