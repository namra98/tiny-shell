# CS:APP Shell Lab

### Files:

Makefile	# Compiles the shell program and runs the tests

README	# This file

tsh.c	# The main shell program

tshref	# The reference shell binary.

### The remaining files are used to test the shell

sdriver.pl	# The trace-driven shell driver

trace*.txt	# The 15 trace files that control the shell driver

tshref.out # Example output of the reference shell on all 15 traces

### Helper C programs that are called by the trace files

myspin.c	# Takes argument and spins for seconds

mysplit.c	# Forks a child that spins for seconds

mystop.c # Spins for seconds and sends SIGTSTP to itself

myint.c # Spins for seconds and sends SIGINT to itself
