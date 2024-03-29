# Python Files Tutorial

## Summary of steps to complete

- [ ] Fork this repository so you have your own copy to work on.
- [ ] Clone the repository on your local machine. 
- [ ] Create a Jupyter Notebook in your repository.
- [ ] Watch the tutorial and execute commands.
- [ ] Push your new files to your GitHub repository.
- [ ] Submit a link to this GitHub repository in Canvas.

## Fork & Clone this repository

* We did this in a previous assignment. Instructions are here: https://github.com/cmcntsh/exerGitPractice
  * A reminder about forking a repository:
  * Forking a repository is copying it from an original GitHub account to your own GitHub account.
  * Forking a repository is done by clicking on the Fork button located at the top, right corner of the main repository page.
  * You can only fork a repository once. If you try to fork a repository on your own GitHub account, you'll get an error message. If you try to fork a repository you already forked (without deleting it on your own account first), you'll also get an error message that you already forked the repository.
* Cloning a repository can also be done directly in VSCode
  * Create a new folder on your machine where you want to put this repository if you don't already have one you want to use.
  * Copy the Clone or Download path for this repository from GitHub.
  * In VSCode from the command pallette (Ctrl-Shift-P) run Git: Clone
  * Paste the path into the path field which pops up
  * Select your new folder you created on your machine
  * A new folder for the repository with the repository files should be in the folder you selected showing in the Explorer window in VSCode on the left side.

## Create a Jupyter Notebook .ipynb file

* 2022 update: There's already a Jupyter Notebook included in the repository. Complete the assignment using that notebook.
* In Jupyter Notebook or VSCode navigate to your repository folder.
  * Create a new Jupyter Notebook called FilesTutorial.ipynb

## Watch Tutorial

* Follow along with Python tutorial: File objects (25 min): https://www.youtube.com/watch?v=Uh2ebFW8OYM&list=PL-osiE80TeTskrapNbzXhwoFUiLCjGgY7&index=12&t=0s
* Execute code examples in separate cells.
  * Create a test.txt file in your repository similar to the one he uses in the tutorial.
  * open() with reading, writing, appending, and reading and writing
  * close()
  * give an example of a context manager
  * read()
  * readlines()
  * readline()
  * while len() > 0:
  * tell()
  * seek()
  * write()
  * copy test.txt file to another file called test_copy.txt
  * open and copy an image file using binary mode (You'll need to find an image file of your choice online.)
  * copy a binary file using chunks
  
* When you're done make sure you save your file.

## Push your updated file to your GitHub repository

* This can be done in VSCode.
  * In VSCode click on the Source Control button.
  * You should see the files that had changes. (Mine has the original file which shows an M next to it and a new file which says checkpoint in the name. You really only need to push the original file, but if you push both it shouldn't hurt anything.)
  * Hover over the changed file. Click the + sign to stage the change.
  * Enter a commit message in the message field and click the checkmark to commit the change.
  * Click on the 3 dots for more actions and select Sync. This will push the updated file to your GitHub repository.
  * Submit the link to your GitHub repository on Canvas.
