# Transpiler from Scala to C++
A tool for translating a program written in a simplified version of Scala (only basic features) to C++.
It uses ANTLR to create parsers which are later used to deduct types (which can be dynamic in Scala) and translate the syntax to C++.
It features a simple UI that allows users to either manually input Scala code or import it from a file.
