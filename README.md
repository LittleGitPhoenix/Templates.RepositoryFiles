# Example README

> This is the header. It contains the name of the repository and a very brief description. Optionally it may contain the repository's [platform compatibility](#Platform-compatibility).

This is an example each README file in a ME repository should adhere to. It outlines the structure and shows typical use cases. 
___

# Table of content

[toc]
___

# General Information

> This part is optional. If present, it should explain in some sentences, what this repository is all about.

README files are written in markdown (MD) language. It is a very simple and efficient description language. More information and appropriate cheat sheets can easily be found online.

___

# Usage

> The **Usage** part is **mandatory**.
>
> It should describe how to use the code within a repository. Use explanations, code snippets and whatever is needed to give another developer a good starting point.
>
> Please update the README, if you notice, that something is unclear or missing. Keeping things up-to-date will help us all in writing better code faster.

## Elements

> For better structure and therefore readability, use different header types.

### Links

> Use links to other headers within the README file, to help navigating.

Jump back to the [top](#Example-README).

## Platform compatibility

> As seen in many of the README files, the repository's platform compatibility is either specified directly at the top under the name and / or based on separate packages that are all combined within a repository.
> 
> Here are some examples:

Full compatibility:

| .NET Framework | .NET Standard | .NET Core |
| :-: | :-: | :-: |
| :heavy_check_mark: 4.6.1 | :heavy_check_mark: 2.0 | :heavy_check_mark: 2.0 |

.NET Standard compatible:

| .NET Framework | .NET Standard | .NET Core |
| :-: | :-: | :-: |
| :heavy_minus_sign: | :heavy_check_mark: 2.0 | :heavy_check_mark: 2.0 |

.NET Core only:

| .NET Framework | .NET Standard | .NET Core |
| :-: | :-: | :-: |
| :heavy_minus_sign: | :heavy_minus_sign: | :heavy_check_mark: 3.0 |

.Net 5 only:

| .NET Framework | .NET Core | .NET |
| :-: | :-: | :-: |
| :heavy_minus_sign: | :heavy_minus_sign: | :heavy_check_mark: 5.0 :heavy_check_mark: 6.0 |

## Boxes

### Annotation-Box

> :information_source:
> Here be dragons

> :bangbang:
> Here be dragons

### Html-Box

This variant is not defined in default markdown syntax and may therefore not be rendered properly.

<div style='padding:0.1em; border-style: solid; border-width: 0px; border-left-width: 10px; border-color: #37ff00; background-color: #37ff0020' >
	<span style='margin-left:1em; text-align:left'>
    	<b>Information</b>
    </span>
    <br>
	<div style='margin-left:1em; margin-right:1em;'>
		Here be <i>dragons</i>
    </div>
</div>

<div style='padding:0.1em; border-style: solid; border-width: 0px; border-left-width: 10px; border-color: #ffd200; background-color: #ffd20020' >
	<span style='margin-left:1em; text-align:left'>
    	<b>Advice</b>
    </span>
    <br>
	<div style='margin-left:1em; margin-right:1em;'>
		Here be <i>dragons</i>
    </div>
</div>

<div style='padding:0.1em; border-style: solid; border-width: 0px; border-left-width: 10px; border-color: #ff0000; background-color: #ff000020' >
	<span style='margin-left:1em; text-align:left'>
    	<b>Warning</b>
    </span>
    <br>
	<div style='margin-left:1em; margin-right:1em;'>
		Here be <i>dragons</i>
    </div>
</div>

## Code highlighting

### Code snippets

> When showing code snippets, it is good practice to write a short explanation what the code does above it. 

**Create an instance**

Just create the instance, so it can be used.
``` csharp
var foo = new DisposableString();
```

**Assign a variable**
``` csharp
var foo.Value = "bar";
```

**Clean up**
``` csharp
var foo.Dispose();
```
> Don't forget to dispose the instance once you are finished using it.


### In-line mentioning

> When writing descriptions, highlight type names declared by your code, so that they pop-out.
>
> Own code is displayed as `inline code`.
>
> Foreign code is just marked as **bold**.

This repository declares the `IFoo` interface which is implemented by the abstract class `Bar`. It has dependencies to a few NuGet packages like **Newtonsoft.Json** and **morelinq**.

___

# Authors

> This part it is not only meant to give credit to the author, but more importantly to show who can be contacted for further details.

* **Felix Leistner**: _v1.x_
* **Jon Doe**: v2.x _Rewrote the whole codebase_.