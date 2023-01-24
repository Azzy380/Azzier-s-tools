# Attributes v2.3.0
Plugin allows modifying attributes, adding attribute modifiers to items and creating custom attributes!
### You need to turn on java plugins for it to work.

#### Full releases you can download through Releases tab.

## Version 2.3.0:
- Changed Custom Attribute GUI and some localisation (thanks @NerdyPuzzle :>)
- Added blocks allowing getting/setting and add modifiers to attribute from other mods by using modid:attribute
- Moved procedure translations into texts file.

## Version 2.2.9:
- Small code reorganisation
- [BugFix] Added casting check in "Has attribute" procedure
- [BugFix] Added a check in Player Persistent Custom Attributes.

## Version 2.2.8:
- Added "has attribute" to fix error while modifying attributes in some global trigers. NOTE: User has to make sure given entity is LivingEntity and use this to check if it has attribute.
- Removed casting checks in multiple procedures.****

## Version 2.2.7b:
- [HotFix] Fixed casting error in "get attribute value" in Forge 1.16.5

## Version 2.2.7a:
- Removed not supported procedure blocks
- [HotFix] Fixed attribute procedures trying to work on non living entities (like chests etc.)

## Version 2.2.7:
- Added Forge 1.19.2 support
- Added Forge Attributes: Step Height Addition, Attack Range
- Added Player persistent custom attributes
- Added Remove Modifier
- Rewoked attriute modifiers (when creating new modifiers, UUID has to be static set)

## Version 2.2.6:
- Added localisation for custom attributes
- [BugFix] Fixed a bug when adding a new custom attribute modifier in version 1.18.2

## Version 2.2.5:
- Remade Attribute Modifiers procedures
- Added "Calculating attribute modifiers" global trigger
- Added "For slot..." procedure to determine equipment slot before adding modifiers
- Added Modifier variable for attribute modifiers

## Version 2.2:
- Added forge attributes
- [BugFix] Fixed Get Base Value and Get Value for forge 1.16.5

## Version 2.1:
- Added blocks for getting whole attribute value (base value + modifiers)
- Changed "Get value of.." to "Get base value of.." for blocks returning base value
- Added support for Forge 1.16.5

## Version 2.0:
- Changed to Java Plugin - you need to turn on java plugins for it to work.
- Replaced old procedures with 2 new ones.
- Added attribute modifier procedures.
- Added Custom Attribute mod element and procedures for it.

## Version 1.1.2:
- Small bug fix
- Localisation changes

## Version 1.1.1:
- Added missing Movement Speed attribute.
- Renamed plugin to Attributes.

## Version 1.1:
- Removed 1.15.2 support.
- Added special attributes for horses, zombies and flying mobs.
- [BugFix] Attributes for 1.16.5.

## Version 1.0:
- First release. 
