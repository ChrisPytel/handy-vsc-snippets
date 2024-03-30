# Handy VSC Snippets
A handful of useful Visual Studio Code `(VSC)` scripts to make your coding faster. <br> <br> Features a handful of expressions and lines of logic that we've done loads of times,



<br><br><br>

# Installation
Adding this scripting functionality to your VSC  is straight forward. 

1. Go to https://raw.githubusercontent.com/ChrisPytel/handy-vsc-snippets/main/keybindings.json

2. Select all of the script text and copy it to your clipboard. <i>(Control + A and Control + C)</i>

3. Open your VSC go to your command bar and type  `>Preferences: Open Keyboard Shortcuts (JSON)`

4. Click the dropdown option that says `Preferences: Open Keyboard Shortcuts (JSON)`. <br>Don't accidentally open `Preferences: Open Default Keyboard Shortcuts (JSON)` and modify its contents. <i> (You won't have a good time.)</i>

5. Paste what we had copied earlier in the clipboard into your local keybindings.json

6. <b>Installation complete.</b> Go and try out some scripts!
<br><br><br>

# List of scripts in this library
Below is a list of scripts and their default shortcut. You can configure which buttons they are bound to in your `keybindings.json` file.

Scripts 


----------------------------------------
### Console.log
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


test






### Check with cohort peeps
----------------------------------------
I'm experimenting with writing more scripts for faster coding and I'm checking with people for their input. Is there anything that you write a lot of that you find annoying to type out often?