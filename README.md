Bash Helpers
============
I've decided to make a repository of useful helper functions that I have put
together that are useful for performing annoying tasks from within bash

Contents
--------
So far this is all I have:

*	Remote diff
	
		Usage: remotediff file host1 host2

	Written in bash, this uses ssh to grab a copy of the file from both host1
	and host2 and diff them
