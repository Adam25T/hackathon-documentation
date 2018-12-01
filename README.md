# Hackathon-Documentation
Welcome! Contributing to open source can be daunting especially to such a large effort like .NET Core. Here are some things to get you started. Don't be afraid to ask the curators of the projects questions and get involved in discussion. They are quite prompt in responding and are always polite. Feel free to poke around the code, pull requests, issues, and discussions to further familiarize yourself with the open source environment. 


### Getting Started with CoreFX
Overall information for working on the project can be found [here](https://diaryofadev.net/getting-started-contributing-to-corefx/).

### Install CMake
1. [Download the binary distribution](https://cmake.org/download/)
2. Add Cmake to your Path (In environment variables add C:\Program Files (x86)\CMake 3.13\bin\)
3. To test if it is on your path open command prompt and type cmake. If you get "cmake is not recognized as an internal or external command" it didn't work.

### Install Git if not already installed
1. [Download git](https://git-scm.com/downloads)
2. Install git
3. Check if you have git bash or git on the command line. If on the command line type git. If you get "git is not recognized as an internal or external command" it didn't work. On windows I recommend getting into the habbit of using git bash.

### Getting the repository on your computer
1. If you do not have a github account, create one [here](https://github.com).
2. Fork the repository to your personal github account by following [these instructions](https://github.com/dotnet/corefx/wiki/Checking-out-the-code-repository).
3. After you have followed these instructions you should have all the files up to date with the master branch on your computer.

### Building and running tests for corefx
Now you should be able to build all the files. Follow the instructions in [Buidling CoreFX](https://github.com/dotnet/corefx/blob/master/Documentation/project-docs/developer-guide.md).

### Picking an issue
We will be focusing targeting issues marked with the **up-for-grabs**, **easy**, and **increase-code-coverage**. These issues are generally the simplest and most straight forward. 
[Picking an issue](https://github.com/dotnet/corefx/wiki/Pick-issue).

**Note** - For increasing code coverage you don't need to create a ton of tests and effectively complete the issue. They accept even small contributions to increase code coverage by a little bit.

### Coding
1. In your fork create a branch off of the most up to date master branch to do your work in. Make your branch a name that effectively communicates your intent. Look at [completed pull requests for examples](https://github.com/dotnet/corefx/pulls?q=is%3Apr+is%3Aclosed).
2. In visual studio developer command prompt navigate to the directory of the library you will be working on.
3. In Visual Studio open that librarys solution file.
4. Add code and tests to work on the issue.
5. Commit your work to your branch. Generally you don't want to commit something that doesn't work.
6. Repeat 4 and 5 until complete.
7. When you feel completed your work [**create a pull request**](https://github.com/dotnet/corefx/wiki/Creating-a-Pull-Request) and wait for feedback.

This repository coding style uses "Visual Studio defaults". The coding style guide can be found [here](https://github.com/dotnet/corefx/blob/master/Documentation/coding-guidelines/coding-style.md). You can also see correctly formatted code in the pull requests that have been completed.

### Debugging Tests 
Currently debugging in visual studio is not working with the project after build tools were updated. Now there are some work arounds [in this issue thread](https://github.com/dotnet/corefx/issues/30913) 

### Code Coverage
[Coverage Document](https://github.com/dotnet/corefx/blob/master/Documentation/building/code-coverage.md)

### Documentation
[Here are other docs and references](https://github.com/dotnet/corefx/tree/master/Documentation#coding-guidelines).







