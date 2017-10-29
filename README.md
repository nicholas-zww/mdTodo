TODO lists in markdown for Sublime Text
------------------

mdTodo is a tool for managing todo list in markdown files in Sublime Text editor.


Installation
------------------

Simply install this plugin via **PackageControl**.


Usage 
------------------

1. <kbd>CTRL</kbd> + <kbd>SHIFT</kbd> + <kbd>d</kbd> : toggle task completed
2. <kbd>CTRL</kbd> + <kbd>SHIFT</kbd> + <kbd>n</kbd> : create new task 


Examples 
------------------

Suppose we have the following todo file:

	# Project A:
	- call mum tomorrow at 8 am.
	- send pull request

Highlight this item line and press <kbd>CTRL</kbd> + <kbd>SHIFT</kbd> + <kbd>d</kbd>, it marks a tag "@done" and also appends timestamp.

	# Project A:
	+ call mum tomorrow at 8 am. @done (2012-01-08 18:12)
	+ send pull request @done (2012-01-08 18:12)
	
Pressing <kbd>CTRL</kbd> + <kbd>SHIFT</kbd> + <kbd>n</kbd>, will insert `-` on a new line.

	# Project A:
	+ call mum tomorrow at 8 am. @done (2012-01-08 18:12)
	+ send pull request @done (2012-01-08 18:12)
	-

Contribution
------------------

- Thanks to Taskmate for TextMate (https://github.com/svenfuchs/taskmate).
- This is a fork of https://github.com/chagel/itodo.
