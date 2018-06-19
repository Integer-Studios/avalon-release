# Avalon Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.0.2] - 2018-06-19
### Added
- Stockpile Building
- Granary / Silo Building
- On Disconnect Screen 
- ESC Menu

### Changed
- Changed Construction Requirements for several buildings
- Forester's range to find trees is increased
- Foresters now only allow 2 workers at a time (from 4)
- Buildings must be placed facing a road with some exceptions (town center, farm, granary, stockpile, roads)
- Roads take wood to build instead of stone
- When you tell the villagers to chop a tree they will do it first now instead of waiting to finish everything else
- Added information to building descriptions
- Nerfed quarry production


### Fixed
- Foresters no longer break
- When villagers are idle and wandering around, they will now immediately stop to do any task queued
- Chop Command now chops all trees on the tile
- Farm tiles can be walked on now
- UI elements such as inspect are now more intuitive (or should be)
- Fixed a bug where tasks to build things where the items could not be found would bog down the queue
- Dramatically reduced lag from movement
- Loading no longer reuses phrases
- Inspector UI blocked people from interacting
- Fixed town center ghost