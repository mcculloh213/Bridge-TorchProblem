Name: Howell D. McCullough IV
E-mail: mccullough.213@osu.edu
Date: 9/13/2016
Class: CSE 3521 Introduction to Artificial Intelligence
Assignment: Programming Assignment 03
Python Version: 2.7.10/12

Directory Contents:
    CSE3521_Lab3
        |__8puzzle.txt -- 8 puzzle config from assignment
        |__action.py -- Contains mapping of rules
        |__AStarAgent.txt -- A* Search Agent
        |__AstarSearch.py -- Executable script
        |__AStarSearch.txt -- Example A* output
        |__checkinversions.py -- Algorithm that checks if an 8 puzzle configuration is solvable. Doesn't work with the
        |                        required end state, requires the zero to be in the bottom corner, so it's not really
        |                        used
        |__dev.py -- Personal development
        |__node.py -- Node implementation
        |__ParseInput.py -- Input Parsing function
        |__ProjectStatesTruthTable.ods -- For my sanity
        |__Puzzle.py -- Model for puzzle
        |__puzzlestate.py -- Model for puzzle states
        |__README.txt -- Read me
        |__robots.py -- Robot mapping, not really used besides reference
        |__state.py -- State lookup table
        |__TestHarness.py -- Test Harness function
        |__UCAgent.py -- Uniform Cost Search Agent
        |__UCSearch.py -- Executable script
        |__UCSearch.txt -- Example UCS output


Instructions:
    There are two main scripts for execution:
        AstarSearch.py - Utilizes an A* Searching agent
        UCSearch.py - Utilizes a Uniform-Cost Searching agent
    To run, input:
        $ python AstarSearch.py <left state string> <right state string>
        $ python UCSearch.py <left state string> <right state string>
    There is a solution for the 8-puzzle problem, but it takes a long time. A seriously long time. Unless it's a very
    simple, quickly solvable input, don't use it.
    THIS WAS WRITTEN USING PYTHON 2.7.10/12 AND WILL NOT WORK WITH VERSIONS 3.x.x.
