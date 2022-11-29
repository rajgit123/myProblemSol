# myProblemSol
there are the issues i faced and while doing projects

ssh "permissions are too open"
What permissions should I give to the id_rsa file?
sol:
The keys need to be read-writable only by you:

chmod 600 ~/.ssh/id_rsa
-----------------------------------------
I am following this link to create my first docker Image and it went successfully and now I am trying to push this Image into my docker repository from this link. But whenever I am trying to push this Image into repository, I got this type of error.
denied: requested access to the resource is denied
sol: you may need log out first `docker logout` ref. https://stackoverflow.com/a/53835882/248616
again
docker login
-------------------------------------------
