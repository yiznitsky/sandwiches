# Command Line Crash Course:

## List of Commands

**pwd**
> print working directory

**hostname**
> my computer’s network name

**mkdir**
> make directory

**cd**
> change directory

**ls**
> list directory

**rmdir**
> remove directory

**pushd**
> push directory

**popd**
> pop directory

**mv**
> move a file or directory

**less**
> page through a file

**cat**
> print the whole file

**xargs**
> execute arguments

**find**
> find files

**grep**
> find things inside file

**man**
> read a manual page

**apropos**
> find what man page is appropriate

**env**
> look at your environment

**echo**
> print some arguments

**export**
> export/set a new environment variable

**exit**
> exit the shell

**sudo**
> DANGER! become superuser root DANGER!

**chmod**
> change permission modifiers

**chown**
> change ownership

**tldr**

------------------------------------------------------------------------------------------

## Paths, Folders, Directories (pwd)

print working directory. Directories = folders. They are the same thing and used interchangeably. On my mac: pwd prompts: /Users/alexyiznitsky
**use pwd to check where you’re at!

## What’s Your Computer’s Name? (hostname)
hostname displays name of computer, or at least one of them.
On my Mac: hostname prompts : Alexs-Air

## Make a Directory (mkdir)

mkdir makes directories. Making directories within directories is called a “path” (mkdir temp/stuff/things). This says, “ first temp, then stuff, then things, and that’s where I want it.” It’s a set of directions to the computer of where you want to put something in a tree of folders (directories) that make up computer’s hard disk.

## mkdir -p will make an entire path even if all the directories don't exist.


## Change Directory (cd)

(CLI) Command Line Interface. Important to know how a CLI and GUI work together.

```bash
cd .. # to move up.
cd ~ # Home Directory
cd / # Root
```

## List Directory (ls)

ls command lists out the contents in current folder, also helps to see which directory to cd into next.
**`ls -lR` ? what’s this command mean? CHUCK

-l does a longer, fuller listing
-R does a recursive search through child directories and children of children directories.

## Remove Directory (rmdir)

rmdir DIR. easy. Could not delete temp/domore/commandcode ..temp/domore..temp/stuff -> come back to later… error: ‘directory not empty’
Once you've confirmed that you really, really don't want any of that content, you can do `rm -rf folder_name`. But be extremely careful, because `rm -rf /` will delete your entire computer very, very quickly.

## Moving Around (pushd, popd) **Nobody uses this


These commands let you temporarily go to a different directory and then come back, easily switching between the two.

pushd - takes current directory and "pushes" it into a list for later, then it changes to another directory.  “Save where I am, then go here.”

pops - takes the last directory you pushed and “pops” it off, takes you back there.

** I think I get this part, but makes my brain hurt a bit.

## Making Empty Files (touch, new-item)

touch - creates empty files. On Unix touch also changes the times on the file. new-item is the Windows command, does same as touch.





## Copy a File (cp)


Use the `cp -r` command to copy more directories with files in them.
/ (slash) at the end of a directory? That makes sure the file is really a directory, so if the directory doesn't exist I'll get an error.

To copy from one location to another: cp ~/Desktop/file.txt ~/folder

cp command will overwrite files that already exist. Be careful.

## Moving Files (mv)

Moving files or, rather, renaming them. It's easy: give the old name and the new name

## View a File (less, MORE)

This is one way to look at the contents of a file. It’s useful because the file has many lines, it will ‘page’ so that only one screenful at a time is visible.

‘q’ to exit.

space bar and ‘w’ to scroll up and down.

## Stream a File (cat)

Another way to look at content from a file but instead of displaying in ‘pages’ it spews the whole file onto the page. no paging.

## Removing a File (rm)

Similar to rmdir command. -r will recursively remove all it’s contents.
rm file name
Be extra cautious when running ‘-r’ command. It’s a good way to delete computer.
Learn Python the Hard Way:

```bash
git add .
git commit
git push origin master
git init ---kinda rare
```


