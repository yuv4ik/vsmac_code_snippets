# VS for Mac Code Snippets

Is a collection of useful code snippets (shortcuts) to reduce the amount of boilerplate code typing.

## What is a code snippet?
> Code snippets are ready-made snippets of code you can quickly insert into your code.

There are a couple of code snippets that are shipped with Visual Studio:

```
ctor - Creates a constructor for the containing class.	
prop - Creates an auto-implemented property declaration.
forr - Creates a for loop that decrements the loop variable after each iteration.
```

More information and the full list of built-in code snippets can be found in the [official docs](https://docs.microsoft.com/en-us/visualstudio/mac/snippets).

## How to add a code snippet
> Visual Studio > Preferences > Text Editor > Code Snippets

![Demo](https://github.com/yuv4ik/vsmac_code_snippets/raw/master/screenshots/vs_mac_add_code_snippet.png)

Alternatively you can copy all `*.xml` files from `/snippets/$lang$` to `~/Library/VisualStudio⁩/{version}/Snippets`.

## How to use a code snippet?
Simply type the `shortcut` for example `ctor` and double press the `Tab` key.

## The snippets
### C#
| Shortcut        | Description
| ------------- |:-------------:
| dw            | Template for `Debug.WriteLine($)`
| classnpc      | Template for a class implementing `INotifyPropertyChanged`.
| measure       | Template for measuring execution time using Stopwatch
| propb         | Template for a `BindableProperty`
| propnpc         | Template for a Property with `INotifyPropertyChanged`

*Please note that you can set your own shortcut and customize the snippet according to your needs.*

## How to contribute
If your favorite code snippet is not in the list you are more than welcome to contribute! <br/>Please follow the next simple steps:
- Create a snippet using `VS for Mac` or copy an existing one from `~/Library/VisualStudio⁩/{version}/Snippets` to `vsmac_code_snippets/snippets/$lang$` directory. 
- Update the `README.md`.
- Create a Pull Request.
