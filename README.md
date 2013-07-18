Sublime-Text-Settings
=====================

This repo has things for my personal Sublime Text from prefs to quick keys I use often and would like to remember.

## Quick Keys

<table>
    <tr>
        <td>CTRL + ~</td>
        <td>Opens Sublime's console</td>
    </tr>
    <tr>
        <td>CMD + SHIFT + P</td>
        <td>Opens command pallete</td>
    </tr>
    <tr>
        <td>CMD + P</td>
        <td>Opens Goto Anything prompt. Good for jumping from file to file.</td>
    </tr>
    <tr>
        <td>CMD + P + fuzzy seach CSS file + @element</td>
        <td>Pro Tip: Type CMD + P to open goto prompt, then type style@h1. This will take you to your CSS file in place where the h1 was so you can edit super fast.</td>
    </tr>
    <tr>
        <td>CMD + R</td>
        <td>Allows you to jump to methods based on their name. Can also use CMD + P and start search with @. This can also be used with CSS.</td>
    </tr>
    <tr>
        <td>CMD + D</td>
        <td>when cursor is in word, will select entire word. Once a word is selected CMD + D will select the next instance of the word.</td>
    </tr>
    <tr>
        <td>CMD + U</td>
        <td>Goes back one from the word just selected</td>
    </tr>
    <tr>
        <td>CTRL + CMD + G</td>
        <td>Selects every instances of a word</td>
    </tr>      
    <tr>
        <td>CMD + Left Arrow Key</td>
        <td>Goes to begining of line</td>
    </tr>
    <tr>
        <td>CMD + Right Arrow Key</td>
        <td>Goes to end of line</td>
    </tr>
    <tr>
        <td>CMD + SHIFT + Arrow Key</td>
        <td>Selects entire line</td>
    </tr>
    <tr>
        <td>CMD + L</td>
        <td>Selects entire line and goes to next line</td>
    </tr>
    <tr>
        <td>CMD + I</td>
        <td>Incremental search, similar to find. Finds the next instance of the word you search for based on cursor location. Can press enter after you find the word to exit the search.</td>
    </tr>
    <tr>
        <td>CMD + K + B</td>
        <td>Toggles sidebar</td>
    </tr>
    <tr>
        <td>CMD + CTRL + Up/Down Arrows</td>
        <td>Moves line that cursor is on up or down in source code</td>
    </tr>
</table>

## Tips

Create snippets for things you find yourself doing often.

Download community snippets.

jQuery Snippets, CSS snippets, Sass snippets.


## Emmet plugin

`>`  use for children

`ul>li`
    
    <ul>
        <li></li>
    </ul>

`+`  use for siblings

`div+div+div`

    <div></div>
    <div></div>
    <div></div>

`*`  use for creating multiples

`ul>li*3`
    
    <ul>
        <li></li>
      	<li></li>
      	<li></li>
    </ul>

`^`  use for going up a level

`header>h1^main`

    <header>
	    <h1></h1>
    </header>
    <main></main>

`lorem20` use for display lorem ipsum with x about of words

## Plugins

* Tag
* Advanced New File plugin
  * CMD + OPTION + N: Ability to create new files/folders from within Sublime
* Sidebar Enhancements plugin
* SublimeLinter plugin
* DocBlockr plugin
* LiveReload plugin (Not Installed, Havn't tried yet)
* Sublime css auto comments (Installed, Havn't tried yet)
  * https://github.com/sc8696/sublime-css-auto-comments
* Sublime list stylesheet vars (Not Installed, Havn't tried yet)
  * https://github.com/MaciekBaron/sublime-list-stylesheet-vars
