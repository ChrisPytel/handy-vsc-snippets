# Handy VSC Snippets
A handful of useful Visual Studio Code `(VSC)` scripts to make your coding faster. <br> <br> Features 20 useful expressions and lines of logic that we've done loads of times.


Please leave me a Star on my Repo if you found these scripts useful



<br><br><br>

# Installation
Adding this scripting functionality to your VSC is quite simple. No need to run npm. 

1. Go to https://raw.githubusercontent.com/ChrisPytel/handy-vsc-snippets/main/keybindings.json

2. Select all of the script text and copy it to your clipboard. <i>(Control + A and Control + C)</i>

3. Open your VSC go to your command bar and type:  `>Preferences: Open Keyboard Shortcuts (JSON)`

4. Click the dropdown option that says `Preferences: Open Keyboard Shortcuts (JSON)`. <br>Don't accidentally open `Preferences: Open Default Keyboard Shortcuts (JSON)` and modify its contents. <br><i>(You won't have a good time.)</i>

5. Paste what we had copied earlier in the clipboard into your local keybindings.json file and save it.

6. <b>Installation complete.</b> Go and try out some scripts!
<br><br>

<!--  version 4 UPDATE - Handled in keybindings.json script at the bottom, disables Control + Shift + W automatically.

 <b>Optional</b> - Its probably a good idea to unbind the default `Control + Shift + W` shortcut. Its assigned to close your VSC window without warning which is really annoying. To do so, go to:

1. File -> Preferences -> Keyboard Shortcuts
2. In the search bar at the top type: `Close Window`
3. Right click the command and select Remove Keybinding
4. Optional: You can do the same for: `View: Close Editor`   -->
<br><br><br>

# List of scripts in this library
Below is a list of scripts and their default shortcut. You can configure which buttons they are assigned to in your `keybindings.json` file by changing what the "key" value is defined as.

Click a link below to jump to a visual preview of each script

### JavaScript Scripts

  1. Insert blank console.log()
  2. Insert console.log() for checking variable assignment
  3. Insert console.log() for checking variable datatype
  4. Insert blank template literal
  5. Creates a template for an object literal
  6. Creates a template for a function expression  
  7. Creates a C-style loop template

  8. Generate a if / else if / else statement chain
  9. Generates a template for a ternary operation
  10. Generates a template for a switch statement
  11. Generates a template for an array.map() method  

  12. Generates a template for module import require statement
  13. Generate a template for setting up a promise
  14. Generate a template for completing a promise
  15. Generate a template for a returning promise chain *coming soon*

  16. Generates a template for a jQuery event listener
  17. Generates a template for an AJAX request


### HTML / Markdown Scripts
  1. Easy tag creation
  2. Wrap a selection and assigns a tag to it

### CSS Scripts
  1. Quick border generator for reference
  2. Flexbox container and child element centering


----------------------------------------
### 01 - Console.log()
 <b> Shortcut =</b> `Control + Shift + C`<br>

Creates a blank console.log(); and places your cursor inside the brackets.
If text is selected, it wraps the selection inside its brackets.

console.log(`~insertCursorHere~`);

Demo:

----------------------------------------
### Console.log with variables



console.log("Our `variableToCheck` is:  ", `variableToCheck`);

I like to put this at the top of functions to double check my incoming parameters

----------------------------------------
### Template literal


Places a template literal and inserts cursor inside the brackets, 

`${`insertcursor`}`


----------------------------------------

###  Function Expression

const `functionName` = function(`parameters`)<br> {
  `// Function code goes here` <br>
};

###  If / Else if / Else Chain

if (`condition1`) {
  `// Run this code`
  
} else if (`condition2`) {
  `// If that doesnt resolve, run this instead`
  
} else {
  `// Otherwise, run this code`
  
}





### Secret bonus shortcuts
----------------------------------------
Since you made it to the bottom, heres some extra shortcuts that are built into VSC by default:


Type `fore` and press tab   = Generates a template .forEach() array method<br>
Type `fori` and press tab   = Generates a template for...in loop  (useful when iterating through objects)<br>
Type `foro` and press tab   = Generates a template for...of loop  (useful when iterating through arrays)<br>