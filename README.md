Markdone
========

A syntax for TODO lists based on Markdown.

Markdone is a superset of Markdown. Every Markdone document is a valid Markdown document. Markdone documents extend Markdown syntax by adding TODO lists. 

## Why Markdone

Plain text / Text based TODO lists are extremely comond. Despite many available tools such as online and client apps, plain text is more appropiate in certain occasions. It's allows for easy editing and portability.

Plain text plus syntax hightlighting allows to use any simple text editor such as Textmate or Sublime to manage TODO lists.

![example](https://github.com/omarrr/markdone/blob/master/images/example.png?raw=true)

## Markdone syntax

A Markdone document is comprised of Markdown syntax and TODO lists.

TODO lists are regular Markdown lists that always start with a `+` or `-` symbol. Lists that start with `*` remain regular unordered lists.

Each line item of a TODO list is a task: 

* List items starting with a `-` symbol are pending tasks.
* Line items starting with a `+` symbol have already been completed.

Eg:

	+ Task A
	+ Task B
	- Task C
	+ Task D
	- Task F


## Todo Lists
Each line item is a task

	- Lines starting with a `-` are pending tasks
	+ Line items starting with a `+` have already been completed

### Subtasks

Sublists can be used to split a task in subtasks

	+ This is completed task
		+ This is a subtask of A
	- This is an incomplete task
		- This is an incomplete subtask
		+ Incompleted tasks might have completed subtasks

### Tags
Tasks can have metadata in the form of tags (#, @)

	+ Task A #tag1 #tag2
	- Buy milk #store
	- Call Dad #7pm

### Example


	- TODO syntax
		+ Create a github project
		- Define TODO grammar
		- Write TODO tmLanguage for Textmate #pc
		+ Write TODO example
	- Call Dad #7pm


## Tools
### Grammar File for Textmate and Sublime

#### Sublime Text 2
Install the contents of the folder `sublime/package` (Sublime language files) under
	
	~/Library/Application Support/Sublime Text 2/Packages/Markdone

#### Textmate
[ details to follow ]

### Syntax Highlight for Textmate and Sublime Text 2

#### Sublime Text 2
Install the contents of the folder `sublime/themes` (Sublime theme files) can under
	
	~/Library/Application Support/Sublime Text 2/Packages/Color Scheme - Default

Curretly only the [Solarized theme](https://github.com/altercation/solarized) has been adapted to support Markdone.

#### Textmate
[ details to follow ]


## Resources

* [Markdown](http://daringfireball.net/projects/markdown/)
* [Markdown syntax](http://daringfireball.net/projects/markdown/syntax)
* [Solarized theme](https://github.com/altercation/solarized)
* [todo.txt](http://todotxt.com/) is another text based TODO list format.


