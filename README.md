*********************************************************************README************************************************************************
***************************************************************************************************************************************************

Name: Madhusudhan Sankaran.

***************************************************************************************************************************************************
***************************************************************************************************************************************************


This program was developed in the Eclipse Juno IDE in Microsoft Windows 7 Operating System using java as the programming language.

There are three java files included. They are:

1. Calculate.java
2. ReadFile.java
3. Viterbi.java


Instructions for compiling the program:
---------------------------------------

1. Compile the programs using the javac command in the following order:

		javac Calculate.java
		javac ReadFile.java
		javac Viterbi.java

2. This should produce the .class files and the program should be ready for execution.


Instructions for running the program:
-------------------------------------

1. To run the program, type the following command :

		java Viterbi <arg1> <arg2>

2. arg1 and arg2 atand for the following:

		arg1 : The name of the model file.
		arg2 : The name of the file containing the observation sequences.

3. For example, the following is a valid execution of the algorithm:

		java Viterbi model.dat test.dat

4. This should run the algorithm and the results should be produced.

5. Both the sample model.dat and test.dat files are provided. Feel free to execute the code on them and check out the results.
