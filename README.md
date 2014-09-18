Unknown Well-Known
=================

There are the well-known well-knowns the unknown-well-knowns and the uknowable-well-knowns.. we have all learnt to like robots.txt but there are some many of those flourishing currently. So...

This repository will be a repository for the miscellaneous .well-known files popping all around so we can track them. the root directory representing a root of a web server with example files all around.

And first..

### DNT - do not track policy the millenial's P3P (Platform for Privacy Preferences Project) 
Did Privacy Badger block images on your site? Add this one ./well-known/dnt-policy.txt and all will be forgotten

  * https://www.eff.org/files/dnt-policy-preliminary.txt

next up, an api for apis..

### apisjson - not to be confounded with jsonapis .. lists apis on your domain
Wonderfully enough http://apisjson.org/apis.json responds with a 404.. still go ahead and read a format to describe what apis you might be providing. Oh LRDD I miss you.

* http://apisjson.org/

### robots - the venerable inspired by Asimov's three rules.
Tells crawlers and other non human visitors to your site what would be an acceptable behaviour. I put in as an example google's robots.txt, http://www.google.fr/robots.txt because thats funny.

* http://www.robotstxt.org/ 

##Trolling section
I don't have strong feelings about well-known uris though it does sound ecologically unsound. How many extra requests and extra 404 lines in log files will we see if everyone has his own "well known" uri, which might potentially break stuff if you don't put it there..?

##License
The MIT License (MIT), thats fine right?

##Contributing
Please do .. please I don't have the patience to go around and list all of those.. fork .. pull request..
