# Default C# Repository Files

A couple of files that I generally add to each repository I create containing C# code

## Installing the template

To install the template, run the following command:

```bash 
dotnet new install GordonBeeming.DefaultFiles.CSharp
```

You'll see an update similar to this 

```bash
Template Name                Short Name          Language  Tags
---------------------------  ------------------  --------  ----------------------------
Default C# Repository Files  gb-defaults-csharp  [C#]      .NET/CSharp/git/editorconfig
```

and now to use the files in your repository, simple run

```bash
dotnet new gb-defaults-csharp
```

If you have any of the files already, you'll need to run the command with a `--force` argument.

## Updating files

Updating files is simple... just add them and they should be published as `DefaultCSharpRepoFiles.nuspec` includes all files off the repository root.
