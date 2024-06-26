## Step 4: Log into ieng6
![Image](4.png)
> After opening VSCode, click on `Terminal` from the toolbar at the top, then choose `New Terminal`. A new terminal has been opened. Type `ssh<space>yul239@ieng6.ucsd.edu`, then press `<enter>` to connect with ieng6.
>
> 
## Step 5: Clone your fork of the repository from your GitHub account (using the SSH URL)
![Image](5.png)
> Go to the GitHub lab 7 repo page which is forked from the class folder. Click on `Code`, then `SSH`, select the entire URL which is `git@github.com:BlackQuantum9/lab7.git`, then press `<command>` and `<c>` together to copy it. Then go back to VSCode, in the terminal, type `git<space>clone<space>`, then paste the SSH URL `git@github.com:BlackQuantum9/lab7.git` by entering `<command>` and `<v>` together. Then press `<enter>` to clone the entire repo.
>
> 
## Step 6: Run the tests, demonstrating that they fail
![Image](6.png)
> Then type `cd<space>lab7` in the terminal to change the working directory under lab7. Enter `bash<space>test.sh` then press `<enter>` to run the test. It shows there is one failure in file `ListExamples.java > line42`.
>
> 
## Step 7: Edit the code file to fix the failing test
![Image](7-1.png)
> Type `vim<space>ListExamples.java` then press `<enter>` to start the vim editor. In this way, it prints the content in the terminal which allows the user to edit it directly from the terminal.
> 
![Image](7-2.png)
> Then change the `index1` to `index2` to fix the error.
> 
## Step 8: Run the tests, demonstrating that they now succeed
![Image](8.png)
> Then, rerun the test by typing `bash<space>test.sh` then press `<enter>`.
>
> 
## Step 9: Commit and push the resulting change to your GitHub account (you can pick any commit message!)
![Image](9-1.png)
![Image](9-2.png)
> For step 9, type `git<space>add<space>ListExamples.java` then press `<enter>` to add a change in the working directory to the staging area, then type `git<space>commit<space>-m<space>"X"` then press `<enter>` in order to capture a snapshot of the project's currently staged changes, `-m<space>"X"` means to return message "X", and finally `git<space>push` then press `<enter>` to upload local repo content to a remote repo.
