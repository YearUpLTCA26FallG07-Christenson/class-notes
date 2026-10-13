On github, create a new repo.

Be sure that your organization is selected.

Give the repo a name, don't use spaces, use dashes instead.

i.e.    repo-demo.

Make it public.

Click create.

Copy the repo URL into your clipboard.

In Terminal:

Navigate to the folder where I want this repo to be inside of. 

for us that's ~/pluralsight/workbook-{?}/

cd ~/pluralsight/workbook-1

(optional) use git status to confirm that this folder is *not* a repository.

clone your repo with:

git clone {url from clipboard}

(optional)  use ls to see the new folder.

change into the new directory

observe that this is a repo by noting the "(main)"

open intellij, create new project.

location should be the folder we used above as the parent folder.
( ~/pluralsight/workbook-1 )

name should be the name of the folder that clone created, which should be the name of the repo.

Ensure we use Maven.
Do NOT select "create git repo"
click create.

in terminal:

git add .
git commit -m "initial commit"
git push

go see files in github.
