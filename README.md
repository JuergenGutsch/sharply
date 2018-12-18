# sharply
It's a Blockly based C# Editor

I plan to use the following components to create a Blockly C# Editor

* [Google Blockly](https://developers.google.com/blockly/) (obviously)
* [Electron](https://electronjs.org/)
* [scriptcs](http://scriptcs.net/) to execute it
* to be executed on  [.NET Core](https://dotnet.microsoft.com/)

The [Blockly](https://developers.google.com/blockly/) editor needs to get running inside an [Electron](https://electronjs.org/) window and **I need to create a custom C# generator for Blockly** and to find a way to run the generated code using [scriptcs](http://scriptcs.net/) and https://dotnet.microsoft.com/

I plan to 

* add blocks to talk to the RaspberryPI GPIO pins
* add more C# specific blocks

## Why

Because my first son likes to learn programming and he like to use Blockly and Scratch. Scratch isn't available in German but Blockly is and it is easy to customize and to extend. To better support my son, I would prefer to generate C# code. 

## Contributions

I like any kind of contribution. File an issue, add an PR or just mention this project-
