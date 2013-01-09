# Event Espresso Language Repository

![Event Espresso icon](https://secure.gravatar.com/avatar/77273ea7c83f75d52ca0cbe25dae693a&d=https://a248.e.akamai.net/assets.github.com%2Fimages%2Fgravatars%2Fgravatar-org.png)

## Overview

This is the repository for all the **[Event Espresso](http://eventespresso.com)** [language files](http://eventespresso.com/glotpress/projects/event-espresso).

### Description

Starting in Event Espresso 3.1.30, the plugin will load all language files from the relevant language branch dynamically based on your `define('WP_LANG,'');` setting in `wp-config.php`. On an update, Event Espresso will download the latest version of the language file from the repository automatically.

#### Becoming a translator

If you would like to be an Event Espresso translator, please fill out the [form on our website](http://eventespresso.com/features/languages/#form). We offer free [Personal](http://eventespresso.com/product/personal-license/) and [Business](http://eventespresso.com/product/business-license/) licenses depending on your contribution to the language file and whether it is a partial or complete translation. 

Our language files are managed by a [GlotPress installation](http://eventespresso.com/glotpress/projects/event-espresso). All you need to be a contributor is [an account](http://eventespresso.com/wp-login.php?action=register) on [our forums](http://eventespresso.com/support/forums/), but to be able to approve and submit translations, you will need to [fill out the form](http://eventespresso.com/features/languages/#form) and request to be a validator. For more information about GlotPress, visit the [GlotPress Trac](http://glotpress.trac.wordpress.org/).

#### Using these files

There are two ways you can use these files. As mentioned above, the language files will automatically update with an update to Event Espresso. If you would like to update your language file to the latest version *before an update to Event Espresso is available*, you can do so by navigating to that language's .mo file and downloading the file, then upload via FTP to the `/event-espresso/languages` directory.

If you would like to make modifications to the language file, e.g. to customize the text of a particular string, download the file as described, but upload the modified file to `/wp-content/uploads/espresso/languages`. You will be responsible for keeping your customized language file up-to-date. 

Updating language files requires a program like [Poedit](http://www.poedit.net/), and that you download the .po file. An .mo file (which is used by WordPress/Event Espresso) will be generated automatically when you save. You don't need to download the .mo file.

These language files will work with both the free and premium versions of Event Espresso.

#### Getting help

If you have any questions or problems, let us know in the  [Translations support forum](http://eventespresso.com/forum/translations/). 

#### Making changes to the language files

Please do not submit pull requests to these files as they will be ignored. Any changes to the language files must be made via the [GlotPress site](http://eventespresso.com/glotpress/projects/event-espresso).