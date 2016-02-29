# proj7-Gcal

## IX Path

Files may be found ix at /home/users/zgj/CIS399/Project7/proj7-Gcal

## Authors 

Initial version by M Young; revised by Zachary Jones 

## Files Changed

main.py
index.html

## File to run

main.py



## Hints

You'll need a 'client secret' file of your own.  It should *not* be
under GIT control.  This is kind of a
developer key, which you need to obtain from Google.  See
https://auth0.com/docs/connections/social/google and
https://developers.google.com/identity/protocols/OAuth2 .
The applicable scenario for us is 'Web server applications'  (since
we're doing this in Flask).  

Your client secret will have to be registered for the URLs used for 
the oauth2 'callback' in the authorization protocol.  This URL includes
the port on which your application is running, so you you will need to 
use the same port each time you run your application.  I suggest you 
generate one random port in the range 5000-8000 and stick with it for the 
remainder of the term (unless someone else randomly draws the same port). 

More about the client secret file is described in our Piazza group. 

Whether or not you already have a Google calendar, it's a good idea to
create one or two 'test' calendars with a known set of appointments
for testing.








