# Wizards Castle

## Background
In early 2019, @beejjorgensen gave a tech talk for the [Bend Hackers Guild](http://bend.hackersguild.us) introducing the Rust language.  The talk and language were very interesting, but a tangential detail stuck out.  Beej had taught himself Rust by using it to implementing a 40 year old game called [Wizard's Castle](https://github.com/beejjorgensen/Wizards-Castle-Rust). In support of that, he researched the origins of the game, got it's original source code, and reverse engineered a technical spec.  All that info is [here](https://github.com/beejjorgensen/Wizards-Castle-Info), and I recommend giving it a look through, it's pretty awesome.

Inspired by this, I decided to use the same game to learn F#.  I wrote a partial implementation in c# to get my feet wet, [available here] (https://github.com/tallseth/Wizards-Castle-csharp).

## How To

This project is written in .NET Standard, so given a Visual Studio or VS Code environment and Nuget, you can run it in the usual ways.  

For Example:
- `dotnet build`
- `dotnet test`
- `dotnet run` (from the WizardsCastle project folder)
