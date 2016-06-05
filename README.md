# Android-Tips
A list of Android Tips to improve your development workflow 

## Contents

1. [Tool Window](#ToolWindow)
2. [Global Navigation](#GlobalNavigation)
3. [Editing Files](#EditingFiles)
4. [Local Navigation](#LocalNavigation)
5. [Refactoring](#Refactoring)
6. [Bookmarks](#Bookmarks)
7. [Breakpoints](#Breakpoints)
8. [Live Templates](#LiveTemplates)
9. [Gradle](#Gradle)


---


## 1. <a name="ToolWindow">Tool window</a>

### 1.1 Find the location of a class

* Click the `target button` in the `Project` tool window

### 1.2 Open Tool Window

* CMD + NUMBER FOR WINDOW
* CMD + 1 for Project
* CMD + 2 for Structure etc.

### 1.3 Build and run

* CONTROL + R


---


## 2. <a name="GlobalNavigation">Global Navigation</a>

These shortcuts will bring up fuzzy text search to navigate to the file or symbol. You can prefix your search with `:` then the line number to open the file or symbol and jump to that line number. e.g. `MyClass:23` will go to line 23.

### 2.1 Jump to any class

* CMD + O

### 2.2 Jump to any file

* CMD + SHIFT + O

### 2.3 Open symbol (method or field)

* CMD + ALT + O

### 2.4 Show recently opened files

* CMD + E

### 2.5 Show recently edited files

* CMD + SHIFT + E

### 2.6 Go to last edited location

* CMD + SHIFT + BACKSPACE

### 2.7 Navigated back/forward in file history

* CMD + ALT + LEFT / RIGHT

### 2.8 Navigate between tabs

* CMD + SHIFT + LEFT / RIGHT

### 2.9 Search everywhere

* DOUBLE TAP SHIFT

### 2.10 Find actions

* COMMAND + SHIFT + A

### 2.11 Switcher

* CONTROL + TAB


---

## 3. <a name="EditingFiles">Editing Files</a>

### 3.1 Auto import

* CMD + ALT + O
* Just go to `Preferences`, search `Auto import`. Turn on `import on paste` and `add unambiguous imports on the fly` so you don't have to do this again.

### 3.2 Sublime text multi selection (current select + next selection)

* CONTROL + G

### 3.3 Move lines up/down

* ALT + SHIFT + UP/DOWN

### 3.4 Delete line

* COMMAND + BACKSPACE

### 3.5 Duplicate line

* COMMAND + D

### 3.6 Surround with

* COMMAND + ALT + T

### 3.7 Complete statement

* COMMAND + SHIFT + ENTER

### 3.8 Unwrap / remove

* COMMAND + SHIFT + DELETE

### 3.9 Code formatting

* ALT + COMMAND + L
* Should just set up code styles in preferences and set it to auto format though

### 3.10 Negation completion

* Press `!` instead of `enter` to autocomplete a boolean

### 3.11 Column selection

* ALT + MOUSE DRAG

### 3.12 Quick fix

* ALT + ENTER

### 3.13 Add missing methods

* CMD + I

### 3.14 Override methods

* CMD + O

### 3.15 Show documentation

* F1 (+ FN depending on settings)

### 3.16 Show parameter information

* CMD + P

### 3.17 Highlight every occurance of symbol in file

* CMD + SHIFT + F7 (+ FN depending on preferences)

### 3.18 Quick definition in popup

* COMMAND + Y

### 3.19 Move method

* COMMAND + SHIFT + UP/DOWN

### 3.20 Generate / New File (in Project Window)

* COMMAND + N


---

## 4. <a name="LocalNavigation">Local Navigation</a>

### 4.1 Jump to line in current file

* CMD + L

### 4.2 Next / Previous method

* CONTROL + UP / DOWN (Mac shortcuts take over this)

### 4.3 Show usage

* ALT + F7 (+ FN depending on settings)

### 4.4 Show usage in popup

* CMD + ALT + F7 (+ FN depending on settings)

### 4.5 Go to declaration

* CMD + B
* CMD + CLICK (also used on tab to go to file location in finder)

### 4.6 Go to implementation

* CMD + ALT + B

### 4.7 Go to type declaration

* CMD + SHIFT + B

### 4.8 Go to super/parent

* CMD + U

### 4.9 Select Target

* ALT + F1 (+ FN depending on preferences)

### 4.10 Related files

* CONTROL + COMMAND + UP

### 4.11 Show call hierarchy

* CONTROL + ALT + H

### 4.12 Show class member list

* CMD + F12


---


## 5. <a name="Refactoring">Refactoring</a>

### 5.1 Extract Variable

* COMMAND + ALT + V

### 5.2 Extract Parameter

* COMMAND + ALT + P

### 5.3 Extract method

* COMMAND + ALT + M

### 5.4 Inline

* COMMAND + ALT + N

### 5.5 Rename

* SHIFT + F6

### 5.6 Push up / pull down

* CONTROL + T

### 5.7 Refactor

* SHIFT + F6

### 5.8 Refactor move

* F6

### 5.9 Refactor this

* CONTROL + T


---


## 6. <a name="Bookmarks">Bookmarks</a>

### 6.1 Add bookmark

* F3 (+ FN depending on preferences)

### 6.2 Add bookmark with mnemonic

* ALT + F3 (+ FN depending on preferences)

### 6.3 Go to bookmark

* CONTROL + BOOKMARK NUMBER (0-9)

### 6.4 Show bookmarks

* COMMAND + F3 (+ FN depending on preferences)
* Then you can press the letter mnemonic e.g. `J`


---


## 7. <a name="Breakpoints">Breakpoints</a>

### 7.1 Toggle breakpoints

* COMMAND + F8

### 7.2 Conditional / Logging breakpoints

* COMMAND + SHIFT + F8

### 7.3 Temporary breakpoints

* COMMAND + ALT + SHIFT + F8

### 7.4 Disable breakpoint

* ALT + LEFT CLICK ON BREAKPOINT

### 7.5 Evaluate Expression

* ALT + F8

### 7.6 Inspect Variable

* ALT + LEFT CLICK

### 7.7 Show execution point

* ALT + F10

### 7.8 Mark object

* F3


---


## 8. <a name="LiveTemplates">Live Templates</a>

### 8.1 Autocomplete from live templates

* COMMAND + J

### 8.2 Add a live template 

---


## 9. <a name="Gradle">Gradle</a>

### 9.1 See a build time breakdown

* `./gradlew clean assembleDebug --profile`

### 9.2 Enable gradle daemon for faster build times

* Create or open the `gradle.properties` file in `.gradle` in your `home directory`. e.g. `{HOME_DIRECTORY}/.gradle/gradle.properties`. 

* Add the line `org.gradle.daemon=true` if it doesn't already exist


---

