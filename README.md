# Authentication
About how to do authentication in the real world
# Authentication
anyone can hit your backend servers how do you make sure that they have access to certain resource?

Dumb way = ask username and password in all requests as headers.

Better way ->

1) give the user back a token on signup/signIn

2) ask the user to send back the token in all future requests.

3) when the user logs out ask the user to forget the token.

