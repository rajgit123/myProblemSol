# myProblemSol
there are the issues i faced and while doing projects

ssh "permissions are too open"
What permissions should I give to the id_rsa file?
sol:
The keys need to be read-writable only by you:

chmod 600 ~/.ssh/id_rsa
