# Citrix Script Packager

This project is an npm global tool that help developers package up their scripts (powershell, javascript, shell scripts) for use within the [Citrix Developer Extension for Visual Studio Code.](https://marketplace.visualstudio.com/items?itemName=CitrixDeveloper.citrixdeveloper-vscode)

## Installation

We distribute this tool using npm. To install this in your environment, execute the following command

```sh
npm install -g citrix-script-packager
```

## Usage

To get the CLI help, execute

```sh
citrix-script-packager --help
```

This is created to help you do two basic items

1. Start creating your script template

2. Package up your template into a .vsix file for use with the Citrix Developer extension.

## Getting Started

### Creating a template

The easiest way to start creating a script package is to run the following command

```sh
citrix-script-packager --create
```

This will prompt you for a few items and then create your base template layout. PLease note the friendly name that you enter, you will use this later.

### Packaging a script template

Once you have your template all set, copied the correct script files into the friendly name location, you will need to package it up to be used within the Citrix Developer extension. You can do this with the following command

```sh
citrix-script-packager --package
```

This will create a .vsix file that can then be shared with the community and imported into the Citrix Developer extension.

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags).

## Authors

* **John McBride** - *Initial work* - [github: johnmcbride](https://github.com/johnmcbride)
[Twitter: johnmcbride](http://twitter.com/johnmcbride)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
