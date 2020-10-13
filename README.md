This assumes you have "CYGWIN" installed on a windows machines:
Download CYGWIN and run the setup:
Run setup, click through to the 'Cygwin Setup - Select Packages' window, and type 'rsync' in the 'Search' box at upper left. At this writing, this shows three lines, one of which is 'Net'. Expand Net and you'll find rsync. Click the circular arrow icon to mark it for install, then click Next at lower right.

This is useful .bat file to use on Windows with Rsync to copy files in a batch file script. This example copies C:\temp\test recursively to G:\temp incrementally, only if the source / local file changes.
