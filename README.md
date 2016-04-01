## SilverStripe OptionalTreeDropdownField

This module extends SilverStripe TreeDropdownField to allow clearing a selection.

**Note:** This module was built to supersede [richardsjoqvist/silverstripe-optionaltreedropdownfield](https://github.com/richardsjoqvist/silverstripe-optionaltreedropdownfield) which may be abandoned. 

## Requirements

* SilverStripe 3.1 (or higher)

## Installation ##

1. Run `composer require patricknelson/silverstripe-optionaltreedropdownfield`
1. Run `sake /dev/build`

## Usage ##

```php
$fields = new FieldList();  
$treeField = new OptionalTreeDropdownField('MyFieldID', 'My Field Title', 'SiteTree');  
$treeField->setEmptyString('No page');
$fields->push($treeField);
```
