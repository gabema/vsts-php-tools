![](https://github.com/incarnate/vsts-php-tools/blob/master/images/Icon128.png)

# Visual Studio Team Services PHP Tools

This extension contains the following tasks for Microsoft Visual Studio Team Services:<br>

1. Install PHP & Composer
2. Run a PHP command
3. Run a Composer command

## Installation

Coming soon to [Visual Studio Marketplace](https://marketplace.visualstudio.com/vsts)

## Source Code

The source code can be found on [Github](https://github.com/incarnate/vsts-php-tools)

## License

[MIT](https://github.com/incarnate/vsts-php-tools/master/LICENSE)

## Helpful Links

[Add a build or release task](https://docs.microsoft.com/en-us/vsts/extend/develop/add-build-task?view=vsts)

### Creating/Building the VSTS extension
```
tfx extension create --manifest-globs vss-extension.json
```

### Publishing the extension
```
tfx extension publish --manifest-globs your-manifest.json --share-with youraccount
```

### Utilizing the vsts task library
[Powershell VSTS Task Library](https://github.com/Microsoft/vsts-task-lib/blob/master/powershell/Docs/Consuming.md#package-the-sdk-with-the-task)

Downloading the library into this project requires running the following command:
```
vsts-php-tools> mkdir ps_modules; Save-Module -Name VstsTaskSdk -Path .\ps_modules\
```