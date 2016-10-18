# Change Log

## Version 0.4.3 (2016-10-17)

#### Supports: AutoValue 1.3

* Updates AutoValue dependency to 1.3
* Initializes known non-nullable collection types to empty collections. (#71)
* Use `getDeclaredClass()` instead of `getClass()` on enums. (#72)

## Version 0.4.2 (2016-08-05)

#### Supports: AutoValue: 1.3-rc1

* Bumps version number to fix release.

## Version 0.4.1 (2016-08-01)

#### Supports: AutoValue: 1.3-rc1

* Adds support for generic AutoValue types!!

## Version 0.4.0 (2016-07-28)

#### Supports: AutoValue: 1.3-rc1

* Adds alternate serialization names
* Changes to AutoValue-esque factory generation.

## Version 0.3.2-rc1 (2016-06-13)

#### Supports: AutoValue: 1.3-rc1

* Updates extension to support AutoValue 1.3-rc1
* Removes final modifier from AutoValueGsonAdapterFactory.

## Version 0.3.1 (2016-05-17)

#### Supports: AutoValue 1.2
 
* Replaces equals check with `isAssignableFrom` in generated type adapter factory.

## Version 0.3.0 (2016-05-11)

#### Supports: AutoValue 1.2
 
* Adds support for single AutoValueGsonTypeAdapterFactory for all AutoValue gson types.
* Fixes generation of TypeAdapter.read() for 'char' values
* Adds sample project.

## Version 0.2.5 (2016-04-13)

#### Supports: AutoValue 1.2
 
* Fixes issue causing failure for non-standard class and package names.

## Version 0.2.3 (2016-04-13)

#### Supports: AutoValue 1.2
 
* Adds selective generation based on public static method returning TypeAdapter<Foo>

## Version 0.2.2 (2016-04-05)

#### Supports: AutoValue 1.2-rc1
 
* Fixes issue causing method prefixes (`get`, `is`) to be ignored.

## Version 0.2.1 (2016-03-22)

Fixes snapshot issues with 0.2.0 release. Only guaranteed to support AutoValue 1.2-rc1

## Version 0.2.0 (2016-03-21)

Initial release. Only guaranteed to support AutoValue 1.2-rc1
