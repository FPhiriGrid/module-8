# module-8
Testing Tools tasks


Postman task:
1. Install Postman REST Client

2.Create Account in Trello using PERSONAL mail (not Grid)

3. Sign In to Account

4. Get and save API Key: https://trello.com/app-key

5. Get token (Use token button)

6. Check that everything works By typing URL to address line: https://api.trello.com/1/members/me?key={YOUR_KEY}&token={YOUR_TOKEN}

7. If Step 6 returned JSON go to Step 8 if not go to Google

8. Create Postmen collection for:

- Creating a new board (POST) *

- Getting board by ID (GET)

- Updating board (PUT)

- Remove board

* you need to use the same board id for all requests, so please extract the variable from the response to the POST request.

USE DOC: https://developer.atlassian.com/cloud/trello/rest/api-group-boards/



Charles Proxy task:

Pre-conditions

Set up charles proxy

You need an Instagram account for testing (create new or you can use your own). Please, use the web version.


Do the following tasks using Map Local, Rewrite, breakpoints features in Charles:

1. Change the number of subscribers to 13 00000

2. Change the number of subscriptions for -12

3. Change the biography (Description) to text with 300 characters

4. Return 500 when opening a publication

5. Return 400 when opening profile page

5. Return 0 posts and check the text on the page

6. Delete your profile photo and check what present instead of photo

Attach the screenshots of each step.



Chrome dev tool taks:
1 Open the page https://www.amazon.com/


Elements Tab
2 Change a headline on the card to bigger one (more than 1 line text)

3 Change the color and font (type, weight, size etc) for headlines

4 Make an image size 2 times smaller.

5 Make a screenshot of the new page view on Galaxy Note 3

6 Refresh the page. Choose one of the category blocks. Describe the block size, picture size and margins.


Console Tab

7 Filter Errors only in the console. Describe what you understand from each message. Attach the screenshot


Network Tab

8 Compare the time DOMContentLoaded and Finish time for your usual internet connection and Slow 3G


Performance Tab

9 Profile the page with Fast 3G connection
Analyze the results.





SQL task:
1. Download DB and pdf schema:

https://drive.google.com/drive/folders/1seZq0a15lFxH0mO78fG2pyNk1O5zSOO6?usp=sharing

2. Prepare query for:

- Select all publishers (publishers) that are from USA

- Select all publishers (publishers) that are NOT from USA sort by name


Attach requests for queries and screenshots with results




GIT Basics task: 
Part 1


Create account on https://github.com/ 
Install GIT on your workstation (https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
Setup git: change your global configs (add name and email, setup core text editor).
Generate ssh-key and integrate it with GitHub.
Create a new "GD_Internship" project on GitHub.
Clone project to your workstation.
Provide access for a mentor to your repository on GitHub.
Part 2

Open the git console in the  "GD_Internship" directory and do the next steps.
Do all your experiments in the folder “task1_git_practice”.
Create an empty readme.txt file.
Make an init commit.
Create a develop branch and checkout on it.
Create index.html empty file. Commit.
Create a branch with the name “images”. Checkout. Add some images folder with images inside it. Commit.
Change your index.html. Add some image source inside it. Commit.
Go back to the develop branch.
Create a branch with the name “styles”. Add some styles folder with styles source inside it. Commit.
Change your index.html. Commit.
Go to the develop branch.
Merge two new branches into develop using git merge command. Resolve conflict if it appears.
Do not delete any branches!
Merge develop branch into master.
Checkout to the develop branch and repeat 7 items once more (use names “images2”, “styles2” for new branches). Now use the git rebase command for merging.
NOTE: As a result master/develop branches should contains all commits that were done in process


Part 3

Try to inspect your repository with the git log command. Use different options with this command (git log --help).
Push all your changes with all your branches to origin (git push origin all).
Execute the command “git reflog“ and save its content somewhere (not in the repository) with filename “GIT_Basics_homework.txt”.
