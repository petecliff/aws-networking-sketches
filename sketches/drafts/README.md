The sketches in here are rougher around the edges than even the other
sketches. I couldn't think of a good word for draft sketches so these
are draft sketches. :-)

In here are the early stages of talks on saving an unloved, undevelopable (your
Lisp gal just left the organisation) app. It used to sit on a VM on the internet
and now needs hiding away due to a security vulnerability. Options include moving
it behind an ALB or fronting it with API gateway. Then either apply WAF and leave 
it at that or slowly move paths/routes/features into a new app and eventually
retire it.

There is also the outline of a fully private entity extraction application using
Comprehend, though that could easily be Rekognition or anything else. That
uses a lot of endpoints to keep data inside of the AWS network and off the internet.
It also uses a NAT to pull code from Github but keep things hidden.