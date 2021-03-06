# Changelog

## v1.0.2

* Add an option to set gear ratios to optimized defaults
* Update menu usage
* Fix an issue where a missing node was reported with an unidentifiably name

## v1.0.1

* Add generic auto-loading for models
  * You can now save a generic preset that applies to all cars of that model. It is overriden by a license plate specific preset.
* Add an option to override changes GTA makes to the car ratios
  * When tuning in Los Santos Customs or using a trainer, the gear ratios can be reset. This option checks the ratios every second and re-applies them if the game has changed them during that time.
* Add a feature to remove gear ratio presets in the Load menu
  * You can now mark gear ratios for deletion. The ratios are removed when closing the menu. <b>Caution: The files are permanently removed from disk!</b>
* Experimental: Add a custom CVT (continuously variable transmission) option
  * Script emulates a CVT when setting a non-CVT car to have only one gear
* Disable gear ratio changes for real CVT cars
  * Cars that have the CVT handling flag set only have one gear and the game doesn't shift up, so changing the ratios won't have any effect.
* Add an option to enable or disable notifications
* Fix an issue where the save prompt reads an enter too early, closing it too early
* Fix an issue where DriveForce is overwritten, causing cars to lose all power
* Change how filenames are generated

## v1.0.0

* Initial release
