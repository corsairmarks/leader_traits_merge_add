# Overview

With Stellaris version 3.3 "Libra" it is now possible to enable traits like Cybernetic and Psionic to be applied to your Pops via gene-modding!  Beginning in version 3.2 "Herbert," Stellaris disallows these traits from being merged onto subspecies which don't already have them, which put a damper on creating super species that melded mind, machine, and science.  This mod revives that gameplay - gene-mod away!

# Changes

The Cybernetic, Latent Psionic, Psionic, Brain Slug Host, species traits can be merge-added from one species template to another of the same overall species.

This mod also adds a couple extra tweaks:

* Empires with Engineered Evolution can remove Cybernetic (mostly for role-play reasons)
* Empires with Synthetic Evolution that have completed the corresponding special project can choose to add Cybernetic to biological or lithoid species templates (thus providing an alternative to full conversion to synthetics)

## Compatibility

Overwrites two core Stellaris files, and thus is not compatible with other mods that make changes to the same files:

* `common/traits/04_species_traits.txt`
* `common/traits/06_distant_stars_traits.txt`

This is due to how the game handles overwrites for traits.  Mods that add new traits or edit other trait files will work just fine.

Built for Stellaris version 3.3 "Libra." Not compatible with achievements.

### Recommended Dependency Mods

 [Leader Traits: All Eligible Species Traits](https://steamcommunity.com/sharedfiles/filedetails/?id=2499031295) ensures your leaders have all the appropriate leader traits for their species traits, which is often why players want to create species with Psionic/Cybernetic/Brain Slug Host/Erudite.  Technically optional, but highly recommended so the game adds leader traits like you intuitively expect.

### Recommended Companion Mods

Like leaders?  Try a couple of my other leader-related mods that work with this one.

* [Leader Traits: Scientist AI Assistant Upgrader](https://steamcommunity.com/sharedfiles/filedetails/?id=2498166286) will help your scientists upgrade to "Sapient AI Assistants" from "Custom AI Assistants" when you discover the right technology
* [Leader Traits: Synthetic Leader Traits for Machine Units](https://steamcommunity.com/sharedfiles/filedetails/?id=2642820468) will enable Machine Unit leaders to have the same special traits as Synthetic leaders
* [Leader Traits: Enhanced Randomisation](https://steamcommunity.com/sharedfiles/filedetails/?id=2553806265) will help your leaders get species-appropriate traits (no more substance abusing robots!) and can randomly get _any_ of the class-appropriate traits when levelling up
* [Retain Leaders from Integrated Subjects](https://steamcommunity.com/sharedfiles/filedetails/?id=2553818684) will let you choose whether you would like to keep leaders from integrated subjects or conquered/infiltrated primitives

### When to Install

This mod can be safely added or removed from your savegame after the game has started.  It replaces two core trait definitions files but does not add gameplay objects.  If you remove it, your game will work normally.  All species will keep their current traits, but you will no longer be able to apply species templates with them to Pops without those traits.

## Changelog

* 1.0.0 Initial version

## Source Code

Hosted on [GitHub](https://github.com/corsairmarks/leader_traits_merge_add)

### Development Notes

It is best to clone this repository into `<Stellaris User's Directory>/Paradox Interactive/Stellaris/mod`, and then make a connection to the `mod` folder via a `*.mod` file's `path` property.  That will ensure the game can see the files, and also that CWTools will parse them.  Also note that the README.md file exists in the `mod` directory but is symbolically linked in the root directory.