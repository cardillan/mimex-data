# Mimex data

This repo contains Mindustry metadata, extracted from a live game environment using the [Mindustry Metadata Extractor mod](https://github.com/cardillan/mimex).

The data are stored in individual text files in tabular form (semicolon separated). Each file contains a comment line (`// DO NOT EDIT! Generated by mimex - Mindustry Metadata Extractor`), followed by column headers amd actual data. New columns may be introduced into the list, and the column order may change.

Several versions of the metadata are kept, each in a separate directory:

* `v126.2`: corresponds to **Mindustry 6.0 Build 126.2**
* `v146`: corresponds to **Mindustry 7.0 Build 146**
* `v149`: corresponds to **v8 Build 149 Beta**
* `be`: corresponds to the bleeding-edge version of Mindustry.

In each directory, the following files are present (some files may be missing in older metadata versions, as the data was added in later game versions): 

* `mimex-alignments.txt`: possible alignments for the `draw print` instruction (without the `@` prefix)  
* `mimex-block-flags.txt`: block groups used in the `ulocate` instruction
* `mimex-blocks.txt`: block types
* `mimex-colors.txt`: named colors
* `mimex-commands.txt`: initial unit commands for units produced by factories
* `mimex-conditions.txt`: conditions used in `jump` and `select` instructions 
* `mimex-contents.txt`: content types
* `mimex-cutscene-actions.txt`: actions for the `cutscene` instruction
* `mimex-effects.txt`: effect types for the `effect` instruction 
* `mimex-fetch-types.txt`: types of data being fetched
* `mimex-graphics-types.txt`: `draw` commands
* `mimex-icons.txt`: printable icons, including the UTF-16 value of the corresponding character
* `mimex-items.txt`: item types
* `mimex-laccess.txt`: sensable properties
* `mimex-layers.txt`: map layers
* `mimex-liquids.txt`: liquid types
* `mimex-locate.txt`: types of objects for the `ulocate` instruction 
* `mimex-logic-rules.txt`: map rules for the `setrule` instruction
* `mimex-marker-control.txt`: marker properties
* `mimex-markers.txt`: marker types
* `mimex-message-types.txt`: message types for the `message` instruction
* `mimex-operations.txt`: operations for the `op` instruction
* `mimex-radar-sorts.txt`: sorting categories for the `radar` instruction
* `mimex-radar-targets.txt`: types of targets for the `radar` instruction
* `mimex-sounds.txt`: logic sounds
* `mimex-status-effects.txt`: unit status effects
* `mimex-unit-control.txt`: `ucontrol` commands
* `mimex-units.txt`: unit types
* `mimex-vars.txt`: predefined variables in logic processors
* `mimex-weathers.txt`: types of weather

