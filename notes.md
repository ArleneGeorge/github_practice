a distributed version control system allows the full version of code to be mirrored on mulitple coders  computers
it allows working offline
more vunerable as someone could break into one of the computers with the full code
Flatiron uses github for 

Git flow
to see what is going on in my local repository type   git status
    may have untracked file stage it to track changes

    github is a remote repository

stage - changes first have to be staged.  
git add "name of file" shortcut is git add . this will save all the files that are not tracked

if make changes will have to stage it again

not saved yet just tracking

commit - to save file after staged 
git commit -m "this is the message for you to remember what the commit does example adds notes."
message must be in quotes
-m is the tag for message. always need a message with a commit
this is still on local machine

push - command  git push origin master
pushes all code on local to  the origin

to know what remote repositories are connected use git remote -v
customary to call the first one origin