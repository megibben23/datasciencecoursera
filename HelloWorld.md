## This is a markdown file


1 In GitHub account - Create repository named datasciencecoursera

2 Now create directory named coursera project on your desktop to do this

3 Navigate to desktop by command cd desktop then, make directory by command mkdir courseraproject ( you can use any name for your new directory, I used courseraproject )

4 Navigate to this directory by cd courseraproject

5. Create an empty Git repository in this directory named courseraproject by command git init

6. screen will show that empty git repo is been created.

7. Now we need to setup connection of Git terminal on laptop with the Github available online using HTTPS link – connecting this two is must to push your file present on desktop to Github account. So to do this give command

8. $ git remote add courseraproject < your repo link for datasciencecoursera available on github > ..... Do not use <>.

9. Till now you connected your Git with GitHub and created empty Git repository in directory courseraproject

10. Now we need local copy of repository created on Github on your laptop. To do this you need to pull courseraproject master to for this give command $ git pull courseraproject master

11. To check if local copy is added to your repository courseraproject give command

$ ls now you can see Read.md file

12. Now our task is to create Markdown file named HelloWorld.md in directory courseraproject to do this give command $ touch HelloWorld. md

13. to add content to this file give command $ echo ## This is a mark down file >> HelloWorld.md

14. Your file is ready to be sent to staging environment. To do this give command

$ git add HelloWorld.md

15. Now give command $ git status You can see that your file helloworld.md is already added to staging phase and now ready to be committed.

16. Now we will commit the file, while doing so you need to mention the changes you made to the orginal file that pulled from master branch. So give command

17. $ git commit – m “Added HelloWorld.md file & added text to it.”

18. Now give command $ git status to check the status of your project. You will see notice -on branch master nothing to commit.

19. Then its time to push your project to github ( your remote repository ) and share your files with world.

20. Give command $ git push –u courseraproject master.

Done.

Later you can check github account and check for HelloWorld.md file in your repository .. you can open it and check if it has text content in it…. When I completed this task i was not able to find written text in file HelloWorld.md, so I just edited this file on Github account. But my task got completed.

Good Luck! Hope this helps you. Any corrections from others are most welcomed, if I was wrong anywhere in explaining.

