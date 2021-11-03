
# Harmons' VSCode

> VSCode custom styles and config to make VSCode less annoying and more like Atom.

## Features

**Styles**

 - Hide action icons above Explorer and Editor unless hovering

**Settings**
 - Remove clutter (breadcrumbs, minimap)
 - Disable annoying character and line highlighting
 - Disable annoying occurrences highlighting
 - Add multicursor with command key
 - Auto save on focus change
 - Don't alphabetize namespace imports/use statements

**Extensions in Use**
 - [Atom One Dark Theme](https://marketplace.visualstudio.com/items?itemName=akamud.vscode-theme-onedark)
 - [Subtle Match Brackets](https://marketplace.visualstudio.com/items?itemName=rafamel.subtle-brackets)

## How to use

Clone this repo somewhere safe, such as documents.

Install VSCode extension: Custom CSS and JS Loader.

Open command palette *(shift + command + p)* and run:

``` bash

open settings

```

Select **"Open Settings (JSON)"**.

Add the following to your **settings.json** to load my CSS:

``` bash

"vscode_custom_css.imports": [

	"file:///{{your machine path to this folder}}/VSCode/custom.css"

],

```

Or, you can paste my entire settings.json to use everything.

Next, in command palette *(shift + command + p)*, run:

``` bash

enable css

```

Select **"Enable CSS and JS"** and restart VSCode.

To modify other elements of the VSCode UI, open **Help > Toggle Developer Tools** for inspection.