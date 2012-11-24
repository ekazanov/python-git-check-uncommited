python-git-check-uncommited
==========
# Info #
Author: Evgeny Kazanov
# Introduction #
Script check your local repositories and prints to standard output the
states of them. Sample output:

	evgeny@krolik:~$ __git_check_uncommitied
	--------------------------------------------------------------------------
	Name                            Commit                  Push              
	--------------------------------------------------------------------------
	ORG                             Not commited            Pushed            
	BIN                             All commited            Pushed            
	EMACS                           All commited            Pushed            
	--------------------------------------------------------------------------

# System requirements #

1. Linux (Script was tested with Ubuntu 12.04)
1. Python (Script was tested with 2.7 and 2.6 versions),

# Installation #

1. Copy "__git_check_uncommitied" to the directory which is in your $PATH.
1. Change the LIST_FILE variable to your local repositories list file name.
1. Fill your local repositories list file. A sample is in doc/local_repositories_list_sample.txt file

# Usage #
Just run __git_check_uncommitied from terminal.
