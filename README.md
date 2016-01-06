###Git training


Repository for the Meetup "Open source contribution training: Git" on 07/01/2016.
See on [Meetup.com](http://www.meetup.com/PyLadiesLondon/events/227540804/)


####Event description

There are several plans for us to contribute to open source projects at meetup events in the future.

In the meantime let's work on our Git skills in preparation! =)

[Git](http://git-scm.com/) is a widely used version control system which means it helps several people work on a project at the same time.

It's a great tool to master for open source but also professional as well as personal projects.

[Open Hatch](https://openhatch.org/) as several Training missions for contributing to open source.

We'll do the [Git mission](https://openhatch.org/missions/git) together.

Before the meetup: [Install Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) if you don't already have it installed on your laptop.


####Git tutorials
* For beginners to Git: [Try Git](https://try.github.io/levels/1/challenges/1) is a short intereactive tutorial made by Github.

* For junior-ish Git users: [Using Git](https://openhatch.org/missions/git) tutorial for new contributors to open source by OpenHatch.


####About version control

Version control is a system to help keep track of file changes over time.
It can be use for code or any other kind of file (text, images...).

Using version control enables you to go back to previous version of your work, to compare the changes and it can serve as backup.

You would typically have a local version of your work on your computer and a remote repository on a server (a widely used tools for remote repositories is [Github](http://github.com/)).


Read more [here](https://git-scm.com/book/en/v2/Getting-Started-About-Version-Control).



#### Brief history of Git

Git was created by the Linux development community in 2005 as a version control tool for the Linux kernel.

Here are the main property they develop Git on:

* Speed
* Simple design
* Strong support for non-linear development (thousands of parallel branches)
* Fully distributed
* Able to handle large projects like the Linux kernel efficiently (speed and data size)


#### About Git

Git works by taking a snapshot of your files over time and stores a reference to be able to go back to each snapshot if needed.

You can go through all the changes in the history of your project on your local machine so you can work offline.

Git has three main states for your file to be in:

* modified: you have changed the file locally but haven't commited it,
* staged: you have marked the modified file in its current version to go into your next commit snapshot,
* committed: the snapshot is saved and referenced.


Here what a basic Git workflow looks like:

1. You modify files in your working directory.

2. You stage the files, adding snapshots of them to your staging area.

3. You do a commit, which takes the files as they are in the staging area and stores that snapshot permanently to your Git directory.


#### Basic use of Git

There are several graphic user interfaces (GUIs) available for Git but it is highly recommanded to learn the basic commands to use on a terminal.

The first thing to do is to initialise a Git repository:
```
~$ git init
```

Once you have made changes (file modified) you stage the file:
```
~$ git add my-name.py
```

Then you commit your changes:
```
~$ git commit -m "initial version"
```

You can update a remote repository:
```
~$ git push origin master
```

Note: to start using an existing repository you clone it (usually from a Github project):
```
~$ git clone https://github.com/user-name/repository-name.git
```


For more details: check the extensive [documentation](https://git-scm.com/doc).
