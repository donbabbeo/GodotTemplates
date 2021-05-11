# Godot Templates
[![CI](https://github.com/donbabbeo/GodotTemplates/actions/workflows/NetFxCI.yml/badge.svg)](https://github.com/donbabbeo/GodotTemplates/actions/workflows/NetFxCI.yml)
[![License](https://img.shields.io/github/license/donbabbeo/GodotTemplates)](https://github.com/donbabbeo/GodotTemplates/blob/master/LICENSE)

SDK style C# project templates for Godot projects.

This extension contains a couple of templates that you can use on your Godot project with Visual Studio 2019.

## Godot Class Library
If you are like me and want to keep you code clean sooner or later you will need to add another project to your solution. 
This template will add an SDK style C# project with the Godot library references to your workspace.

## Godot Runner
As you may know the official [Godot C# extension for Visual Studio](https://github.com/godotengine/godot-csharp-visualstudio) has an issue regarding the new SDK style template that disable the ability to debug your code.
This template is based on [the workaround discussed on the official repository](https://github.com/godotengine/godot-csharp-visualstudio/issues/10) and add a new empty project with the old style .csproj.
Add it to your solution, set it as startup project, add the entry point project (the one created directly by Godot) as a reference and enjoy again your debugging power!
