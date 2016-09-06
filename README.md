# language-assembly

An assembly grammar for Atom. Currently only supports Intel syntax and x86 instruction sets.

![Yay, pretty colours!](https://raw.githubusercontent.com/oliverkeeble/atom-language-assembly/master/screenshot.png)

## To Do List
* Other syntaxes
	* AT&T
	* Others?
* Other instruction sets
	* ARM
	* MIPS
	* Others?
* Lots of testing.
* More instructions.
* Even more instructions.
* Fix all the bugs.
* Fix even more bugs.
------------

## Code snippets
```
'.source.assembly.asm.x86.intel':
    'Assign code origin':
        'prefix': 'ORG'
        'body': 'ORG ${1:40}H'
    'Assign locations':
        'prefix': 'EQU'
        'body': '$1 EQU $2'
    'Move instruction':
        'prefix': 'MOV'
        'body': 'MOV $1, $2'
    'Move to Accumulator':
        'prefix': 'MOVA'
        'body': 'MOV A, $1'
    'Add':
        'prefix': 'ADD'
        'body': 'ADD A, $1'
    'Subtract':
        'prefix': 'SUBB'
        'body': 'SUBB A, $1'
```
