# TYPO3 Extension ``address`` 

## Features

- Based on extbase & fluid, implementing best practices from TYPO3 CMS
- Frontend template variant based on Twitter Bootstrap (v4)
- Circumference search / Radius search
- Different types of records with different fields: Address, company, person
- Flexible layouts in each plugins. Addable via TSconfig.

## Usage


### 1) Installation

#### Installation using Composer

The recommended way to install the extension is by using [Composer][1]. In your Composer based TYPO3 project root, just do `composer require wapplersystems/address`. 

#### Installation as extension from TYPO3 Extension Repository (TER)

Download and install the extension with the extension manager module.

### 2) Minimal setup

1) Include the static TypoScript of the extension.
2) Create some address records on a sysfolder.
3) Create a plugin on a page and select at least the sysfolder as startingpoint.

## Credits ##

* Sven Wappler
* A lot of code is based on the [news extension][2] by Georg Ringer.

[1]: https://getcomposer.org/
[2]: https://github.com/georgringer/news
