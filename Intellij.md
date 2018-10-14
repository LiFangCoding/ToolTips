# Intellij Structure
 [] .idea
 
 [] src
 
    [] main
    
      [] java  
      
      [] resources
      
    [] test
    
      [] java
      
           com.simpleproject
           
      [] resources
      
Working with modules
https://www.jetbrains.com/help/idea/creating-and-managing-modules.html


# Code Navagation and Generation
https://help.github.com/articles/basic-writing-and-formatting-syntax/

## Search files
Global search everywhere: double shift

Actions: shift + command + A

*Search code class file: command + o
in the search bar, can add line number. 

Search method, field, or other symbol: option + command + o

*Search file: shift + command + o

*Recent files: command + e

## code navigation

Project: command + 1

open target type(class, method): command + B

click green items on interface left side, can see the classes implement interface

show definition of the method:  command + mouse hover.  option + space (esc, exit) 

show all members: command + fn + f12

Navigate between tabs: ???
Navigate to line: command + l

Hierachy calss: control + H

## quick code generation 
generate constcutor: command + N

move cusor to previous word: option + shift + left arrow

slelect fileds, use generate. Getter and setters.

surroound with clauses. option + command + T

# Code inspections and intentions

show intention actions: option + enter

move cursor to next word: option + shift + right arrow

code intentions: option + enter
can change in setting, intentions.

# Refactoring in intellij

## common refactoring
extract variable option + command + v(variable)

Rename   shift + f6

change parameters of method  control + T. change signature. click Delegate, can modify, add, delete

make the parameters more than 3 as a object .  control + T. extract parameters object (this is useful. validation argument)

move method from one class to another class .  contral + T and move.

add interface of class .   control + T, choose interface

## larger refactoring
change control + T, type migration

class control + T  replace constructor with fatory 

# Live templates
save a lot of code, faster and accurately

extend selection .  option + up arrow

fori  tap, has the for loop there.

see all templates, insert live template.  command + j

psf    private static final

psvm  public static void main

ifn   if (== null)

make templates .  in system preferendce, click add to add group, add template. avvreviate, description.


# Debugging Essentials
## Debugging fundamentals
debug . control + D

add,delete break point during debug session. Jump to the cursor.   rightdown arrow

##step in, out of code
step . F8

add specific items to watch window.  right click, add to watches.  No need to set the breakpoint at the line. run to cursor

can use calculator to calculate value of function of current frames   click calculator on the top level

see all breakpoints .          on left side, favorites, breakpoints

Hide active tool window .        shift + esc

## Advanced debugging options
breakpoints . right click it. only when condition is met        in condition part

right click breakpoints.  select more.  
see all the breakpoints.    
java filed points.  click the add arrow.

# Git integration
                                                   
VCS . create git repository .         

commit changes  cmmand + K

checkout new branch    right corner.

Authorbox .   select differenct author

pugin .ignore    git ignore file. select java, means project on java

left side. Can see local changes.   

git command can see on console, log


##Github
in system preference.  github, host, github.com

vcs, share on github.

# Junit test

## Testing with Junit

Directory, package, test.  

create test class. @Test.  automaticlly

hightlight class name in src, option + enter, create test for this class methods. (very fast)

Run tests for different modules together.   In edit configuration, left side, for the modules to add, click share. Then change name, click add in bottom, run another configuration. 

## Code coverage
This only works in module, not modules together.
Right clisk test, run all test with coverrage. Or run with icon next to debug.

clear coverage.   Analyze -> clear coverage

Run the project with coverage.   show the code covered.


TODO:
#Fun tips and tricks with the IDE

## Demo: Tips and Tricks

Extend Selection   option + up arrow
move selection up and down .  shift + command + up arrow

find action . shift + command + A  color picker

auto format code: option + command + L

click Anallyze -> cleanup  

Refactor: Find and replace code duplicates

change editor view:  control + `

Move caret to next word with selection  option + shift + right arrow

know the parameters of method . command + P
Autocomple the parameters.   basic ompletion  control + spance

Complete current statement .     shift + command + enter

Find effective commands .   use command +shift + A, open productivity guide. show the commands.


 



















