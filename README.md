# Takes
Gcstats takes a garbage collection log as an argument and prints the time that was spent performing GC. This script was written as part of my debugging Java performance problems talk:

http://prefetch.net/presentations/DebuggingJavaPerformance.pdf

# Example:
$ gctime gc.log
Total execution time               : 66.30secs
Time application ran               : 55.47secs
Time application was stopped       : 10.84secs
% of time application ran          : 83.65%
% of time application was stopped  : 16.35%
