# APL-Skeleton

After you get inspired with APL, how do you get started writing your own application that works with GitHub and that you can easily deploy? 

This basic APL Skeleton is designed to get you started on writing your own APL applications that can be self-contained and deployed easily. We are focusing on using the Git-friendly SALT-based approach, which uses native text files to store source code rather than a more traditional workspace.

This skeleton gives you everything to get started, including:

* A namespace script in which to write your code
* A namespace application file to see how to launch your code from a file
* A workspace to see how to create an auto-starting application using a workspace
* A sample framework for setting up testing for your code using APLUnit

## Getting Started

To get started, you'll want to load the HelloWorld workspace. Here's how:

**On Windows:** Double-click on the `HelloWorld` workspace.

**On Linux:** `cd` into the `APL-Skeleton` directory and run `mapl HelloWorld`.

**On Mac:** Use `]cd` to change into the `APL-Skeleton` directory and run `)load ./HelloWorld.dws`.

## Using DYAPP Scripts

The `Run.dyapp` script gives you an example of launching an APL application using the DYAPP scripting functionality instead of using the workspace function. You can double click on the `Run` application script to see it work on Windows.