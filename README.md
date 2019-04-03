# wikinamer

## Overview
wikinamer is a command line tool for unix based operating systems to update filenames in a directory of a tv show using a wikipedia URL of the list of episodes of the desired show

**Default format:** S0xE0x Episode Name

## Demo


## Requirements
* `python`
* `bs4` && `urllib5`
	* `$ sudo apt-get install pip`
	* `$ pip install bs4`
	* `$ pip install urllib5`

## Installation
`$ git clone https://github.com/beffiom/wikinamer`

## Usage
`$ bash /path-to-directory/wikinamer/wikinamer [Path to Directory Where File Names Should Be Changed]`

What season number are the episodes in this directory apart of?

`$ Enter season number:`

Check the listing of episodes on the wikipedia page. Enter the number in the first column of the first episode you want in your list.

`$ Enter episode number to start at:`

Copy and paste and the wikipedia URL with the episode listing here

`$ Enter sauce: `

## Issues
Some episodes on wikipedia listings are listed as 13.5. In such instances, the episode names and numbers after this event will be off by one.




