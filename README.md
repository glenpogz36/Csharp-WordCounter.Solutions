# _C#-Word Counter_

#### _Single Webpage for Epicodus, 11.16.2018_

#### By _**Glen Sale**_

## Description

_Create a program that gathers both a word and sentence from a user, then checks how frequently the word appears in the sentence. It should check for full word matches only. (For instance, if provided the word "cat" and sentence "I'm walking to the cathedral." the first three letters of the word cathedral would not be counted.)_


###_Basic Structure of Directory for Program and Testing_

__Word-Counter.Solution
├── WordCounter
│   ├── WordCounter.csproj
│   └── obj
│       ├── WordCounter.csproj.nuget.cache
│       ├── WordCounter.csproj.nuget.g.props
│       ├── WordCounter.csproj.nuget.g.targets
│       └── project.assets.json
└── WordCounter.Tests
    ├── WordCounter.Tests.csproj
    └── obj
        ├── WordCounter.Tests.csproj.nuget.cache
        ├── WordCounter.Tests.csproj.nuget.g.props
        ├── WordCounter.Tests.csproj.nuget.g.targets
        └── project.assets.json__

* _For More click the link :_ ** https://www.learnhowtoprogram.com/c/c-basics-and-testing/mstest-configuration-and-setup_        
### Specs
| Spec | Search | Text | Result |
| :-------------     | :------------- | :------------- | :------------- |
| **Program matches lowercase or uppercase Letters** | Search: "basketball" | Text: "Basketball is my favorite sport" |  Result: No match found |
| **Program Counts The Word that matches in the sentence** | Search: "test" | Text: "This test is a sample testing" |  Result: "matches 1" |
| **Program Gathers Sentence** | Search : "This sample is a sample" | Text: "This sample is a sample"|  Result: matches 1 |
| **Program Gathers List of Words** | Search: "sample" | Text: "sample, sample, sample"|  Result: "sample matches 3" |


## Setup/Installation Requirements
* Clone this repository https://github.com/glenpogz36/Csharp-WordCounter.Solutions
* _Download .NET Core 2.1.3 SDK and .NET Core Runtime 2.0.9 and install them. Download Mono and install it._
* _Change into the work directory:: $ cd WordCounter.Solution_
* _To edit the project, open the project in your preferred text editor._
* _To run the program, first navigate to the location of the WordCounter.cs file then compile and execute: $ cd WordCounter/Models $ mcs WordCounter.cs; mono WordCounter.exe;_
* _To run the tests, use these commands: $ cd WordCounter.Tests $ dotnet test_

## Technologies Used

* _C#_
* _.NET_
* _mono_
* _Atom_
* _GitHub_


### License

*This software is licensed under the MIT license.*

Copyright (c) 2018 ** _Glen Sale_ **
