# Feathers SDK Release Notes

Noteworthy changes in official, stable releases of the [Feathers SDK](http://feathersui.com/sdk).

## 3.0.0-beta - April 2016

* Fixed issue where `[Bindable]` metadata without an event caused a compiler error in library projects.
* `StarlingBootstrap` sets static `Starling.multitouchEnabled` to `true` by default.
* `StarlingBootstrap` sets `skipUnchangedFrames` on its `Starling` instance to `true` by default.
* `StarlingBootstrap` now scales using `ScreenDensityScaleFactorManager`.

## 2.3.0 - December 2015

* When an `id` is set in MXML on a Feathers component, it may now be accessed as a property at runtime.
* The type of the `theme` property from `feathers.core.IApplication` is changed to `Class` instead of `String`. The value of this property is now accessible at runtime.
* `Application`, `StackScreenNavigatorApplication`, and `DrawersApplication` updated to set native window visible on startup in AIR because Flash Builder defaults to `false`. Flex changes visibility dynamically, so Feathers needs to do the same since we cannot change Flash Builder's behavior.
* `StarlingBootstrap` updated to support themes that require `AssetManager` to load textures and other assets.
* External files to be loaded by themes with `AssetManager` now included next to SWC files.
* Unit tests for both Feathers UI and Starling may be run with the `test` target in the Ant build script.

## 2.2.0 - August 2015

First stable version.