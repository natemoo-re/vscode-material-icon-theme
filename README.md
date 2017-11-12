# Material Icon Theme

[![Version](https://vsmarketplacebadge.apphb.com/version-short/pkief.material-icon-theme.svg)](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)
[![Rating](https://vsmarketplacebadge.apphb.com/rating-short/pkief.material-icon-theme.svg)](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)
[![Installs](https://vsmarketplacebadge.apphb.com/installs/PKief.material-icon-theme.svg)](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)
[![Build Status](https://travis-ci.org/PKief/vscode-material-icon-theme.svg?branch=master)](https://travis-ci.org/PKief/vscode-material-icon-theme)

The Material Icon Theme provides lots of icons based on Material Design for Visual Studio Code.

### File icons

<img src="https://raw.githubusercontent.com/PKief/vscode-material-icon-theme/dev/images/fileIcons.png" alt="file icons" width="100%">

### Folder icons

<img src="https://raw.githubusercontent.com/PKief/vscode-material-icon-theme/dev/images/folderIcons.png" alt="folder icons" width="100%">

#### Customize folder color

You can change the color of the default folder icon using the command palette:

<img src="https://raw.githubusercontent.com/PKief/vscode-material-icon-theme/dev/images/set-folder-color.gif" alt="custom folder colors" width="80%">

or via user settings:

```json
"material-icon-theme.folders.color": "#ef5350",
```

#### Folder themes

You can change the design of the folder icons using the command palette:

<img src="https://raw.githubusercontent.com/PKief/vscode-material-icon-theme/dev/images/set-folder-theme.gif" alt="folder themes" width="80%">

or via user settings:

```json
"material-icon-theme.folders.theme": "specific"
```

## Custom icon associations

You can customize the icon associations directly in the user settings.

### File associations

With the `*.[extension]` pattern you can define custom file icon associations. For example you could define an icon for `*.sample` and every file that ends with `.sample` will have the defined icon. If there's no leading `*` it will be automatically configured as filename and not as file extension.

```json
"material-icon-theme.files.associations": {
    "*.ts": "typescript",
    "fileName.ts": "angular"
}
```

You can see the available file icon names (e.g. 'angular') in the overview above.

### Folder associations

The following configuration can customize the folder icons. It is also possible to overwrite existing associations and create nice combinations. For example you could change the folder theme to "classic" and define icons only for the folder names you like.

```json
"material-icon-theme.folders.associations": {
    "customFolderName": "src",
    "sample": "dist"
}
```

You can see the available folder icon names (e.g. 'src') in the overview above.

## One-click activation

After installation or update you can click on the 'Activate'-button to activate the icon theme, if you haven't already. The icons will be visible immediately.

<img src="https://raw.githubusercontent.com/PKief/vscode-material-icon-theme/dev/images/oneclickactivation.png" alt="activation" width="80%">

## Commands

Press `Ctrl-Shift-P` to open the command palette and type `Material Icons`.

<img src="https://raw.githubusercontent.com/PKief/vscode-material-icon-theme/dev/images/commandPalette.png" alt="commands" width="80%">

- **Change Folder Theme**: Change the design of the folder icons.

- **Restore Default Configuration**: Reset the default configurations of the icon theme.

- **Change Folder Color**: Change the color of the folder icons.

- **Hide Folder Arrows**: Hides the arrows next to the folder icons.

- **Configure Icon Packs**: Select an icon pack that enables additional icons (e.g. for Angular, React, Ngrx).

- **Activate Icon Theme**: Activate the icon theme.

## Icon sources

* [Material Design Icons](https://materialdesignicons.com/)
* official icons

## How to contribute

Read the [contribution guidelines](https://github.com/PKief/vscode-material-icon-theme/blob/master/CONTRIBUTING.md).

If you have some questions or icon requests open a [new issue](https://github.com/PKief/vscode-material-icon-theme/issues) on Github.

## Follow me

- [Twitter](https://twitter.com/PhilippKief)
- [Github](https://github.com/PKief)