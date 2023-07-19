# Github Tutorial: Jaime Andrés Núñez González

## Checkpoint
1. Create a new repository 

2. Create a README file 

    - Create a new file called `README.md` and write your name in it. 

    - Create another called `main-code.js` and add some small piece of code (a hello-world or something like that) 

    - Save the changes and commit it to your main branch 

3. Create a new branch: 

    - Create a new branch named `feature-branch`. 

    - Switch to the newly created branch 

4. Make changes and commit: 

    - Open the `main-code.js` file and make a small change (change a variable name or a value). 

    - Save the changes and commit them to the `feature-branch`. 

5. Switch back to the main branch: 

    - Switch back to the `main` branch 

    - Open the `main-code.js` file again and make a small change. 

    - Save the changes but don't commit them. 

6. Stash some changes 

    - Stash the changes. 

    - Using `git stash list` copy the output and save it in the `README.md` file 

    - Unstash your stashed changes. 

6. Merge conflict resolution: 

    - Still on your main branch 

    - Merge the `feature-branch` into the `main` branch 

    - Resolve the merge conflict that arises in the `main-code.js` file. Copy the conflict part and add it to `README.md`. 

7. Finalize and submit: 

    - Push your changes to your remote repository
   
Optional: Add any issues your ran into or any comments you want into `README.md` and how you fixed them. 

## Results
The results are listed below

**Stash:** 
`stash@{0}: WIP on main: 56621ba Update README.md`

**Merge:** 
*<<<<<<< HEAD* <br />
`console.log('Hello beautiful world');` <br />
*=======* <br />
`console.log('Hello pretty world');`
*>>>>>>> feature-branch* <br />

**Optional:** Any changes make directly in the github website are not make in the local repository. Then, before making any push from the local the user must write in the terminal `git pull` for do the correspondant update.


