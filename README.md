# MonoMakeFiles

Some example makefiles for using mono with make

Useful for providing basic makefiles when starting a new project

These are very very simple makefiles. We can always improve on them (PRs accepted!) they are however still useful when wanting to make say just a quick and dirty console app etc. They also show the basics of using make with mono

usage:

-Create a new directory you want to code in.

-Copy somewhere/srcbin_makefile ./makefile

-edit the makefile change things like OUTPUTTYPE PROJECTNAME etc

-Edit some code ... save as .cs files.

-make

- srcbin_makefile is a simple makefile for source (recursive) in ./src and output to ./bin you can edit both to be the same if you want to build in place or even use /bin/Debug 

Feel free to add your own.
