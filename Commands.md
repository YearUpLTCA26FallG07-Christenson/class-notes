cd                   // change directory
ls                   // list files (don't show hidden)
ls -a                // list files, show all, including hidden files and folders.
cd ~                 // go to this users home directory
cd ~/pluralsight     // go to the pluralsight folder in this users home directory.
cd ..                // change to the parent directory of the current directory.

pwd                  // print working (current) directory.

git --version         // use to see if git is installed, what version is it?
git status
git init
git add .            // when used in the repo root, will select all changed, new, or deleted files for the next commit.
git commit -m "some message that describes the work done"    //create a commit.


// these run just one time per machine user to configure git.
git config --global user.email "youremail@domain.com"
git config --global user.name "your-github-username"


<up arrow>           // cycle through previous commands.



------------------------------

Three main commands after a change:

git add .
git commit -m "some message that describes the work done"
git push


