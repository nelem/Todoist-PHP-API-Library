[![GitHub tag](https://img.shields.io/github/tag/FabianBeiner/Todoist-PHP-API-Library.svg)](https://github.com/FabianBeiner/Todoist-PHP-API-Library/tags) * [![GitHub stars](https://img.shields.io/github/stars/FabianBeiner/Todoist-PHP-API-Library.svg)](https://github.com/FabianBeiner/Todoist-PHP-API-Library/stargazers) * [![GitHub issues](https://img.shields.io/github/issues/FabianBeiner/Todoist-PHP-API-Library.svg)](https://github.com/FabianBeiner/Todoist-PHP-API-Library/issues) * [![GitHub license](https://img.shields.io/github/license/FabianBeiner/Todoist-PHP-API-Library.svg)](https://github.com/FabianBeiner/Todoist-PHP-API-Library/blob/master/LICENSE) * [![Codacy Badge](https://api.codacy.com/project/badge/Grade/a8cad853a2b041a896753b4dda5659ad)](https://www.codacy.com/app/FabianBeiner/Todoist-PHP-API-Library?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=FabianBeiner/Todoist-PHP-API-Library&amp;utm_campaign=Badge_Grade)# Todoist PHP API Library**This repository contains an _unofficial_ open source PHP client library that provides a native interface to the official [Todoist REST API](https://developer.todoist.com/rest/v8/) (v8).**## Requirements- [PHP](http://php.net/): >= 5.5- [guzzlehttp/guzzle](https://packagist.org/packages/guzzlehttp/guzzle): ~6.3## InstallationYou can either use [**Composer**](https://getcomposer.org/) or simply [**download the latest release**](https://github.com/FabianBeiner/Todoist-PHP-API-Library/releases) and do your stuff.### ComposerIf you don’t have Composer installed, follow the [installation instructions](https://getcomposer.org/doc/00-intro.md).Once composer is installed, execute the following command in your project root to install this library:```shcomposer require fabian-beiner/todoist-php-api-library```Finally, remember to include the autoloader to your project:```phprequire __DIR__ . '/vendor/autoload.php';```## Obtain your personal API tokenOpen the [Todoist web app](https://todoist.com), click on the gear icon ![gear icon](https://user-images.githubusercontent.com/86269/32700618-cc113902-c7c7-11e7-9a8c-263f64510ccb.jpeg), select “Settings”, then “Integrations”. Your API token is listed on the bottom of this page.## Usage```php<?php$Todoist = new FabianBeiner\Todoist\Todoist('YOUR_API_TOKEN');```## Methods & Examples### [“Projects” methods and examples](https://github.com/FabianBeiner/Todoist-PHP-API-Library/wiki/Methods:-Projects#projects-methods-and-examples)* [getAllProjects()](https://github.com/FabianBeiner/Todoist-PHP-API-Library/wiki/Methods:-Projects#get-all-projects)* [createProject('PROJECT_NAME')](https://github.com/FabianBeiner/Todoist-PHP-API-Library/wiki/Methods:-Projects#create-a-new-project)* [getProject('PROJECT_ID')](https://github.com/FabianBeiner/Todoist-PHP-API-Library/wiki/Methods:-Projects#get-a-project)* [updateProject('PROJECT_ID', 'NEW_PROJECT_NAME')](https://github.com/FabianBeiner/Todoist-PHP-API-Library/wiki/Methods:-Projects#update-actually-rename-a-project)* [deleteProject('PROJECT_ID')](https://github.com/FabianBeiner/Todoist-PHP-API-Library/wiki/Methods:-Projects#delete-a-project)### [“Labels” methods and examples](https://github.com/FabianBeiner/Todoist-PHP-API-Library/wiki/Methods:-Labels#labels-methods-and-examples)* [getAllLabels()](https://github.com/FabianBeiner/Todoist-PHP-API-Library/wiki/Methods:-Labels#get-all-labels)* [createLabel('LABEL_NAME')](https://github.com/FabianBeiner/Todoist-PHP-API-Library/wiki/Methods:-Labels#create-a-new-label)* [getLabel('LABEL_ID')](https://github.com/FabianBeiner/Todoist-PHP-API-Library/wiki/Methods:-Labels#get-a-label)* [updateLabel('LABEL_ID', 'NEW_LABEL_NAME')](https://github.com/FabianBeiner/Todoist-PHP-API-Library/wiki/Methods:-Labels#update-actually-rename-a-label)* [deleteLabel('LABEL_ID')](https://github.com/FabianBeiner/Todoist-PHP-API-Library/wiki/Methods:-Labels#delete-a-label)## ContributingI’d be happy if you contribute to this library. Please try to follow the existing coding style and use proper comments in your commit message. 🙏## LicensePlease see the [license file](https://github.com/FabianBeiner/Todoist-PHP-API-Library/blob/master/LICENSE) for more information.