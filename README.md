# Handlebars Snippets + Handlebars Template Generator for Visual Studio Code
___

**Handlebars Snippets** extension provides handlebars snippets as well as generates handlebars templates.

[![Marketplace Version](https://vsmarketplacebadge.apphb.com/version/JayShah.handlebars-vsce.svg "Current Release")](https://marketplace.visualstudio.com/items?itemName=JayShah.handlebars-vsce)
[![Marketplace Installs](https://vsmarketplacebadge.apphb.com/installs/JayShah.handlebars-vsce.svg)](https://vsmarketplacebadge.apphb.com/installs/JayShah.handlebars-vsce.svg)
[![Marketplace Downloads](https://vsmarketplacebadge.apphb.com/downloads/JayShah.handlebars-vsce.svg)](https://vsmarketplacebadge.apphb.com/downloads/JayShah.handlebars-vsce.svg)
[![Marketplace Rating](https://vsmarketplacebadge.apphb.com/rating/JayShah.handlebars-vsce.svg)](https://vsmarketplacebadge.apphb.com/rating/JayShah.handlebars-vsce.svg)

![handlebars-demo](https://user-images.githubusercontent.com/52373384/63845757-1bd2cf80-c9a8-11e9-92ba-821b840ba270.gif)

## Installation
1. Press <kbd>Shift</kbd> + <kbd>Ctrl</kbd> + <kbd>P</kbd> (Windows) or <kbd>Shift</kbd> + <kbd>Cmd</kbd> + <kbd>P</kbd> (Mac OS X) to launch Command Pallete.
2. Search for **handlebars-snippets** and install it.

## Supported languages for handlebars snippets(file extensions)

- Handlebars (.handlebars)
- hbs (.hbs)
- HTML (.html)
- JavaScript (.js)

## Snippets command
Press <kbd>Tab</kbd> to trigger snippet commands

| **Prefix**  | **Method**                         |
|:----------- |:-----------------------------------|                               
| `hif`       | `{{#if }} {{/if}}`                 |
| `hifelse`   | `{{#if }} {{else}} {{/if}}`        |
| `hunless`   | `{{#unless }} {{/unless}}`         |
| `heach`     | `{{#each list}} {{/each}}`         |
| `heachelse` | `{{#each list}} {{else}} {{/each}}`|
| `hwith`     | `{{#with }} {{/with}}`             |   
| `hpar`      | `{{> }}`                           |


## Supported languages for handlebars template(file extensions)

- Handlebars (.handlebars)
- hbs (.hbs)

## Handlebars Template Generator command
Press <kbd>Tab</kbd> to trigger template commands

| **Prefix**   | **Description**                                          |
|:-----------  |:---------------------------------------------------------|                               
| `hif`        | `Will load hbs template`                                 |
| `hifelse`    | `Will load hbs with bootstrap4 template`                 |
| `hbs4navnar` | `Will load hbs template with boostrap4 template + navabr`|

___