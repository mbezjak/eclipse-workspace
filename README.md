## Installation procedure

    # assuming target directory is ~/workspace
    $ git clone https://github.com/mbezjak/eclipse-workspace.git ~/workspace/.metadata

## Configured behaviour

Following describes what you get when this project is used as `.metadata`
directory in eclipse workspace.

### General

 * Use UTF-8 encoding
 * Use unix line separator
 * Auto refresh workspace
 * Use 4 spaces instead of tabs in text editor
 * Show print margin at `80` characters
 * Show authors in compare editor
 * Console buffer set to `1MB` (maximum)
 * Console tab width set to `4`
 * Launch selected resource or active editor on `ctrl + F11`
 * Launch the previously launched application if not selected resource or active
   editor isn't launchable on `ctrl + F11`
 * `ctrl + h` opens file search instead of general search dialog
 * `ctrl + alt + c` opens mercurial commit dialog

### Java

 * Use 4 spaces instead of tabs
 * Enable formatter off/on tags (`@formatter:off`, `@formatter:on`)
 * Don't show members in package explorer
 * Automatically insert semicolons at correct position
 * Automatically insert braces at correct position
 * Limit content assist proposals to: Java (task-focused) and template
 * Enable `Java Type Indicator` as label decorator
 * Report malformed javadoc as warnings
 * Raise warning on compiler problem: unnecessaryElse, incompleteEnumSwitch,
   possibleAccidentalBooleanAssignment, redundantNullCheck,
   potentialNullReference, missingDeprecatedAnnotation,
   missingOverrideAnnotation, localVariableHiding, redundantSuperinterface,
   missingSynchronizedOnInheritedMethod, unusedParameter, unnecessaryTypeCheck,
   emptyStatement, unusedDeclaredThrownException, missingHashCodeMethod
 * Enable save action: add missing `@Override` and `@Deprecated` annotations and
   remove unnecessary casts

### Javascript

 * Use 4 spaces instead of tabs
 * Add new line at end of file if missing
 * Unbind `shift + ctrl + t` when in javascript editor. This causes
   `shift + ctrl + t` to open java types instead of javascript ones.

### Maven

 * Download sources
 * Download javadoc
 * Open XML page in the POM editor by default

### XML

 * Use 2 spaces instead of tabs
 * Set line width to `80` characters

### Ant

 * Use 2 spaces instead of tabs
 * Mark occurences
 * Wrap long lines

### Mylyn

 * Start week is `Monday`

### Plugin: mercurialeclipse

 * Use username from `~/.hgrc`

### Plugin: moreunit

 * Use `junit4` test type
 * Tests location is `src/test/java`
 * Use no prefix for tests
