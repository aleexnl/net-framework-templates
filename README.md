# .NET Framework SDK Project Templates

NET Framework SDK Project Templates is a template package that allows programmers to create .NET Framework projects using [new SDK format](https://www.hanselman.com/blog/upgrading-an-existing-net-project-files-to-the-lean-new-csproj-format-from-net-core).

## Prerequisites

Before you begin, ensure you have met the following requirements:

- You have the lates version of [.NET Core](https://learn.microsoft.com/en-us/dotnet/core/install/)
- You have Windows, Linux, or macOS
- asd

## Installing .NET Framework SDK Project Templates

To install .NET Framework SDK Project Templates, follow these steps:

```bash
dotnet new install Aleexnl.Templates.Net.Framework.Sdk
```

## Using .NET Framework SDK Project Templates

To use .NET Framework SDK Project Templates, follow these steps:

1. You can search all the templates abailable using this command

   ```sh
   dotnet new list --author aleexnl
   ```

2. Once you find your desired template, you can use the `Short Name` to create the project using that template

   ```sh
   dotnet new netFrameworkSdkClassLibrary
   ```

Also you can check the [options reference](https://github.com/aleexnl/net-framework-templates/wiki) or use --help argument to list all the options of the template

```sh
dotnet new netFrameworkSdkClassLibrary --help
```

## Contributing

To contribute to .NET Framework SDK Project Templates, follow these steps:

1. Fork this repository.
2. Create a branch: `git checkout -b <branch_name>`.
3. Make your changes and commit them: `git commit -m '<commit_message>'`
4. Push to the original branch: `git push origin <project_name>/<location>`
5. Create the pull request.

Alternatively see the GitHub documentation on creating a [pull request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request).

## Contact

If you want to contact me you can reach me at alex.nieto027@gmail.com

## License

This project uses the following license: [MIT License](https://github.com/aleexnl/net-framework-templates/blob/main/LICENSE).
