# logdebugg

Filters and collects all logs based on user input log path and modes of filter.
Greps logs based on:
		1) timestamp = logs touched in last t minute
		2) no-of-lines = n lines of logs from all specified logs

	-a,		append new logs that are generated by grepping all logs
			to previous log file.

	-d,		It takes path of log file(s) from log.properties file which
			is auto generated in present working directory.

	-f,		It takes folder(s) as an input, and searches all log files
			within folder and filters all logs based on timestamp or
			no. of. logs.

	-fs,		It takes folder(s) as an input, and searches all log files
			within folders and sub-folders and filters all logs based on
			timestamp or no. of. logs.

	-h,		It shows help menu.

	-n,		It greps logs based on no-of-lines. It expects an integer
			argument. Last 'n'(integer argument) lines of all logs are filtered.
			If any integer is not passed after '-n' then by default it
			takes 50 lines of logs.

	-p,		It takes path of log file(s) from user through terminal
			window. User can pass any number of path(s). Enter path of
			log file(s) just after '-p'.

	-t,		It greps logs based on timestamp. It expects an integer
			argument. Logs touched after 't'(integer argument)mins are filtered.
			If any integer is not passed after '-t' then by default it
			takes 5 mins.

	-z,		It changes naming convention of new log file. By passing '-z' as
			an argument, new name of log file becomes 'log_.yyyy-mm-dd.hh:mm.log'.
			This helps users to keep logs of every minute and can later be used for
			comparison.


# Installation 

Report bugs to 'rishi.anand0@outlook.com'.

