# github_tutorial_https_option
here we are using the https method in place of ssh key method for cloning and all

# tutorial used 
https://www.youtube.com/watch?v=Ez8F0nW6S-w&ab_channel=ApnaCollege
time: 24:01 

added this line now.

# added the above line using the following steps from local machine

use https option 
first copy the https link from 
code>>clone>> https - in github repository.

then in visual studio 
git clone https://github.com/dvikramgoud/github_tutorial_https_option.git

once you clone - just edit it 
now we need to add and then commit and then push

git add .
(once you add it's status will change to staged state)

PS H:\visual_studio\git_hub_learning\github_tutorial_https_option> git commit -m "added_new_line"
[main c0605d3] added_new_line
 1 file changed, 2 insertions(+)
PS H:\visual_studio\git_hub_learning\github_tutorial_https_option> git status
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

now we need to push it 
PS H:\visual_studio\git_hub_learning\github_tutorial_https_option> git push origin main 
it will open the browser - just enter password, then we are done.

then we can open git hub and check the whether it is updated or not..
