# Android-Tips
A list of Android Tips to improve your development workflow 

---

## 1. Navigation windows

### 1.1 Find the location of a class

* Click the target button

### 1.2 Open project window

* CMD + NUMBER FOR WINDOW


---

## 2. Navigating files/symbols

This will bring up a textual input that you can enter the name of the file/symbol you want to find. This uses a fuzzy text search and you can use `:` then the line number to jump to any line number e.g. `MyClass:23` will go to line 23.

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

### 2.10 Show usage

* ALT + F7 (+ FN depending on settings)

### 2.11 Show usage in popup

* CMD + ALT + F7 (+ FN depending on settings)

---

## 3. Navigating through currently open file

### 3.1 Jump to line in current file

* CMD + L

---

## 4. Editing current file

### 4.1 Auto import

* CMD + ALT + O
* Just go to `Preferences`, search `Auto import`. Turn on `import on paste` and `add unambiguous imports on the fly` so you don't have to do this again.

---

## 5. Refactoring

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

### 5.7 Sublime text multi selection (current select + next selection)

* CONTROL + G

### 5.8 Next / Previous method

* CONTROL + UP / DOWN (Mac shortcuts take over this)

---

## 6. Bookmarks

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

## 7. Breakpoints

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

## 8. Live templates

### 8.1 Autocomplete from live templates

* COMMAND + J

---

## 9. Not organised yet

### Go to declaration

* CMD + B
* CMD + CLICK (also used on tab to go to file location in finder)

### Go to implementation

* CMD + ALT + B

### Go to type declaration

* CMD + SHIFT + B

### Go to super/parent

* CMD + U

### Show class member list

* CMD + F12

### Show documentation

* F1 (+ FN depending on settings)

### Show parameter information

* CMD + P

### Quick fix

* ALT + ENTER

### Refactor

* SHIFT + F6

### Refactor move

* F6

### Add missing methods

* CMD + I

### Override methods

* CMD + O

### Build and run

* CONTROL + R

### Highlight every occurance of symbol in file

* CMD + SHIFT + F7 (+ FN depending on preferences)

### Show call hierarchy

* CONTROL + ALT + H

### Quick definition in popup

* COMMAND + Y

### Find actions

* COMMAND + SHIFT + A

### Move lines up/down

* ALT + SHIFT + UP/DOWN

### Delete line

* COMMAND + BACKSPACE

### Duplicate line

* COMMAND + D

### Surround with

* COMMAND + ALT + T

### Move method

* COMMAND + SHIFT + UP/DOWN

### Complete statement

* COMMAND + SHIFT + ENTER

### Select Target

* ALT + F1 (+ FN depending on preferences)

### Unwrap / remove

* COMMAND + SHIFT + DELETE

### Column selection

* ALT + MOUSE DRAG

### Switcher

* CONTROL + TAB

### Refactor this

* CONTROL + T

### Related files

* CONTROL + COMMAND + UP

### Code formatting

* ALT + COMMAND + L
* Should just set up code styles in preferences and set it to auto format though

### Negation completion

* Press `!` instead of `enter` to autocomplete a boolean

---

## Gradle

### See a build time breakdown

* `./gradlew clean assembleDebug --profile`

### Enable gradle daemon

---

## Android Phone

1. Press and hold on spacebar in Google Keyboard to 

---