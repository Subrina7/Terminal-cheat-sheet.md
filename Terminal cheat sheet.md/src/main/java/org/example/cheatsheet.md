<h1>Terminal cheat sheet </h1>

**The terminal is an example of a shell where we can run UNIX commands. 
When we go into a terminal, there is a tilde `~` symbol that can be 
followed by commands or anything you input
The terminal's default setting begins with your 
current directory. You can check this uding the `pwd` command.**

***
### `Creating Files and Folders`
* `mkdir` - make directory
* `touch` - creates new file

When naming a file, avoid spaces- instead use **underscores** or 
**capitals** to separate words.

***

### `Navigating the file systems`
* `pwd` - print working directory 
* `cd` - change directory

  * `ls` - lists files and folders including permissions, owner and date last modified
  * `ls -al` - lists files and folders including hidden files 
* `open .` - open a file

The `cd` or `cd~` command can also be handy to go back to your
**home directory** if you get lost. Alternatively, if you accidentally
change directory you can go back to the **previous directory** by entering `cd -`.
You can also go one step back using `..` and go **one directory above the
current one**.

***

### `Manipulating files and folders`

* `mv` - move file
*  `rm -r` - remove (recursive)

When **moving** a file you need the name of your current folder and the folder you're 
moving it to, separated by a space **ie. `mv bnta_work Downloads`**

***

### `Using Git and GitHub`
Start off by making a directory: `mkdir.`Then go into that 
directory using `cd`

Using `git init` you can create a new **repository**, this can convert 
an existing project or initialize a new, empty repository.

Using the `touch` command you can access an existing file. 

You can check the modification and status of a file using the command 
`git status` which should initially output that the file is unmodified
(with a little red arrow) and is **untracked**. 

To add changes and begin more focused tracking you can 
`git add __.md`

After the initial 'adding' command, the file should be ready to 
commit, this is known as the **staging** changes, an essential step 
in creating a repository.


Following the **staging**, we can **commit** the changes using 
`git commit` using the a **message** as follows:. `git commit -m "add __.md`
(This is where `.gitignore` comes to use. It lets Git know that it 
should ignore certain files and not track them.)

To create the cloud (online) repository, you can go on the Github
website, click on the `+` dropdown and select **new repository**. Once 
the initial formatting is done, use the provided code: `git remote add origin 
git@github.com:Subrina7/Terminal-cheat-sheet.md.git
git branch -M main
git push -u origin main` 
to upload your updated file. 

Any further changes can be made and will continue to update in the 
file using the `git add .` command.















