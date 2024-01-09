# Visitor Groups for Optimizely Data Platform

Optimizely DAM picker button for TinyMCE for Optimizely CMS 12

## Features

Adds a button to the TinyMCE toolbar to select images from the Optimizely DAM

----

## Installation

Install the package directly from the Optimizely Nuget repository.

``` 
dotnet add package TinymceDamPicker
```
```
Install-Package TinymceDamPicker
```

## Configuration (.NET 6.0+)

*Startup.cs*
``` c#
// Adds the registration for visitor groups
services.AddDamSelectButton();
```
 ---
 ## Version History

 |Version| Details|
 |:---|:---------------|
 |1.0|Initial Release|