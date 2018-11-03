
# Testing web API
Have a look at api docs:
https://developer.github.com/v3/gists/

Then, (prefered restassured http://rest-assured.io) test that API user can:

- create gist.
- retrieve gist and returned gists have all the fields documentation specify
- delete gist

Note that:
- It is required to create a github account
- It should be possible to pass github credentials using config or jvm params or command line params (it should be documented...)

Upload solution on github with short documentation (how to use tests, dependencies, tools
explained) > README file.
