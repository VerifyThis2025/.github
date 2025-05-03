## VerifyThis 2025

This GitHub organization is used for the VerifyThis 2025 competition, a hybrid verification competition event held on May 3-4 as part of ETAPS 2025 at McMaster University, Hamilton, Canada.

More information about the event, including its program are available at:

https://www.pm.inf.ethz.ch/research/verifythis.html

### Verification Challenges

There will be four verification challenges published throughout the day of the competition. 

* Challenge 1 (Challenge Session 1)
* [Challenge 2](https://classroom.github.com/a/ghhZ3MU6) (Challenge Session 2)
* Challenge 3 (Challenge Session 3)
* Challenge 4 (Challenge Session 3)


### Getting your copy of the challenge repositories

Before you can get started working on a challenge, you first need to create your own
private copy of the template repository for that challenge. The template repository contains the description of the challenge and the related verification tasks. You will also use this repository to submit your solution.

When a challenge is released, we will update this page to publish a GitHub Classroom link that will automate the process of creating the challenge repository for you. 

After clicking on the link, select the name of your team to join it or
if your team does not yet exist, create a new team. Please do not use whitespace characters in the team name. If you are part of a two-person team, please coordinate with your teammate. Only one of you should create the team and the other one should then join that team. The assignment system will allow at most two people to join the same team.

After accepting the assignment, a fresh private repository will be created for your team within this GitHub organization. The repository will be available at
`https://github.com/VerifyThis2025/challenge-<CHALLENGE-NUMBER>-<YOUR-TEAM-NAME>`
where `<YOUR-TEAM-NAME>` is your team's name in all lower case characters. For example, if your team's name is `TuringsHeirs`, then the created repository for the first challenge will be at `https://github.com/VerifyThis2025/challenge-1-turingsheirs`. You can see the list of all your repositories by clicking on the [Repositories](https://github.com/orgs/VerifyThis2025/repositories) link in the menu at the top of this page.

* Open a browser at `https://github.com/VerifyThis2025/challenge-<CHALLENGE-NUMBER>-<YOUR-TEAM-NAME>` to confirm that the repository has been created.
* Choose a place on your computer for your copy of the repository to reside and open a terminal to that location.
* Then execute the following git command: <br/>
  ```bash
  git clone https://github.com/VerifyThis2025/challenge-<CHALLENGE-NUMBER>-<YOUR-TEAM-NAME>.git challenge-<CHALLENGE-NUMBER>
  cd challenge-<CHALLENGE-NUMBER>
  ```
  You may of course use any Git client of your choice as an alternative to using a command line Git client. 
  


### Submitting your solution

You will submit your solution to a challenge via your team's Github repository. To do so, place any relevant files of your solution in the local copy of the challenge repository. Then execute the following commands in the root directory of the repository:
```bash
git add .
git commit -m "solution"
git push
```
Refresh the Github page of the repository to check that the solution has indeed been submitted.

We do not prescribe a specific format for submitting your solution. However, to help us with the evaluation, please include a text file called `progress.md` with your submission that lists all the tasks that you have attempted or completed.

If you want to provide any auxiliary explanations that may help us (and others) to better understand your solution, please put them into a text file `solution.md`.

Feel free to use the repository to collaboratively work on the solution. You can commit and push as often as you like. We will consider the last commit before the deadline for the challenge as the authoritative version of your solution.

Please note that GitHub classroom tracks the timestamp of your last commit before the deadline separately from the timestamps that appear in the Git history of your repository. Any attempt at manipulating the Git history so that commits that have happened after the deadline appear to have happened earlier will be visible to us. If we were to discover such an attempted manipulation, you would be tarred and feathered (and also disqualified from the competition).

