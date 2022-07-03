![image](https://user-images.githubusercontent.com/94545831/169682812-65b02c76-7064-41ba-8326-d70eacc78013.png)


- A two-player game where players one and two have to fill the grids of 3*3 with X and 0 respectively.
- The winner would be declared when all the grids are filled.
- The project operates in offline mode and the player can play as Multiplayer.
- There are 3 activities in the project which is shown below along with one dialog box. 


|Main Activity|Start Activity| Game Activity|Dialog Box|
| ------- | --- | --- |---|
|![Screenshot (85)](https://user-images.githubusercontent.com/94545831/169682572-9dae95c4-f509-4b8b-ac13-90a2027888c4.png)|![Screenshot (86)](https://user-images.githubusercontent.com/94545831/169682627-53ca92be-0498-4dba-995d-953965ade441.png)|![Screenshot (87)](https://user-images.githubusercontent.com/94545831/169682669-664d2f4a-e07c-45d2-8400-53127960724d.png)|![Screenshot (91)](https://user-images.githubusercontent.com/94545831/169682773-e137362b-0733-4f41-bc9b-66f4074f6fa4.png)

- The key observation is that in order to win Tic-Tac-Toe you must have the entire row or column.
-  Thus, we don't need to keep track of an entire n^2 board. We only need to keep a count for each row and column. 
-  If at any time, a row or column matches the size of the board then that player has won.

## Constraints
- 1 <= moves.length <= 9.
- moves[i].length == 2.
- 0 <= moves[i][j] <= 2.
- Here, are no repeated elements on moves.

## Project Demo


https://user-images.githubusercontent.com/94545831/177042451-500fa28a-ef37-4a5e-b181-4ccaa7bcc97d.mp4


<br>

# CONTRIBUTING GUIDELINES 😄
If you think that you can add a new feature or want to fix a bug, we invite you to contribute to TIC TAC TOE and make this project better. To start contributing, follow the below instructions:

1. Create a folder at your desired location at your desktop.

2. Open Git Bash Here

3. Create a Git repository.

4. Run command ``git init``

5. Fork this Repo

6. Clone your forked repository of project.

7. ```git clone https://github.com/<your_username>/TIC-TAC-TOE.git```

8. Navigate to the project directory.

9. ```cd TIC-TAC-TOE```
10. Add a reference(remote) to the original repository.
11. ```git remote add upstream https://github.com/utkarsh006/TIC-TAC-TOE.git```
12. Check the remotes for this repository.
     ```git remote -v```
13. Always take a pull from the upstream repository to your main branch to keep it updated as per the main project repository.
14. git pull upstream main
15. Create a new branch(prefer a branch name that relates to your assigned issue).
16. ```git checkout -b <YOUR_BRANCH_NAME>```
17. Perform your desired changes to the code base.

Check your changes.

- git status
- git  diff
- Stage your changes.
- git add . <\files_that_you_made_changes>
- Commit your changes.
- git commit -m "relavant message"
- Push the committed changes in your feature branch to your remote repository.
- git push -u origin <your_branch_name>
- To create a pull request, click on compare and pull requests.

- Add an appropriate title and description to your PR explaining your changes.

- Click on Create pull request.
