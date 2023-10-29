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

## Using the template

Once installed, you can easily use the files by using the following command:

```bash
dotnet new gb-defaults-csharp
```

If you have any of the files already, you'll need to run the command with a `--force` argument.

## Checking for template updates only

If you already have the template installed you can run the following command to see if there is an update available

```bash
dotnet new update --check-only
```

To update all templates, remove the `--check-only` argument, to update this template only, run the install command again.

## Updating files to be included in the template

Updating files is simple... just add them and they should be published as `DefaultCSharpRepoFiles.nuspec` includes all files off the repository root.
