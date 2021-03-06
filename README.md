OroCRM User Import
========================

This bundle adds user import feature to OroCRM which allows import user from CSV files.

HexBrain is working on improvements for this bundle, if you find a bug or error please create a [Pull request][2].

Requirements
------------

User Import bundle supports OroCRM version 1.1 or above.

Instructions
------------
You need to set the default password under `System -> Configuration -> User Import`, only this feature is available for now, we will add sending pass to email ability in future
#### Screenshots
![Configuration](Resources/public/img/config.png)
![User Grid with import button](Resources/public/img/usergrid.png)
![Popup](Resources/public/img/dialog.png)


Installation
------------

#### Marketplace

Follow `System > Package Manager` to install it from [OroCRM Marketplace][1]

#### Composer

Add as dependency in composer
```bash
composer require hexbrain/orocrm-userimport-bundle:dev-master
```

In addition you will need to run platform update
```bash
php app/console oro:platform:update
```

[1]: http://marketplace.orocrm.com/package/user-import
[2]: https://github.com/HexBrain/HexBrainUserImportBundle/pulls
