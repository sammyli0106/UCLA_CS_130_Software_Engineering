# UCLA_CS_130_Software_Engineering

# Activity Diagram  

Activity Generator is a high level DSL representing an actviity diagram by the development of a code generator that generate the PlantUML from a DSL file.

## Activity.xtext

The Xtext grammar for an activity diagram DSL that supports parsing an activity diagram.

## ActivityGenerator.xtend

A DSL code generator that takes the following activity diagram and generates the equivalent PlantUML code that draws the following activity diagram.

## ActivityValidator.java

A DSL Validator that produces: 
A warning if a particpant is delcared but not used anywhere.
An error if participants are declared but the activity does not reference one of them. 

## Credit 
This is one of the assignment project created and implemented under the CS 130 - Software Engineering instructed by Professor Maged Elaasar in Winter 2021.
This repository is mainly for inspirations for similar assignments only.
Please be aware of the consequences of code plagiarism. Thank you.
