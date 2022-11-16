# Engineer Hamziey Markdown Git Version Control Tutorial And MarkDown Tutorial
*This is an ongoing class with my student at Hamzatronics and it will be well documented soon when the class is completed*

## S 
cd  
  change directory i.e move to a new
 always use double-quotes " to wrap files names that has spaces in them.
   eg: a folder named program files,
   the we use command cd "program files" to move into it
   

cd .. 
   this is used to exit current directory by one directory
  eg: C:\zeed\zwindow\allCodes

touch 
   to create a file 
  touch eg touch my-list-of-gfs.txt creates a file named my-list-of-gfs.txt
  and touch test.ino creates an arduino file named test


rm and del  
  remove i.e delete eg. rm test.ino deletes the arduino file named test.

  del test.txt, this deletes the file named test.txt. here file can't be recovered


ls  
  this lists out everything in our current directory

^ the arrow-up key
   is used to browse history of the commands you have used in the past

mkdir 
  make directory i.e create a folder
  eg: mkdir test, creates a folder called test.

  eg mkdir "a folder with space" creates a folder with name "a folder with space"

  eg: mkdir test test1 test2, this creates three folders with names  test test1 test2 respectively


rmdir (works for empty folders only)
  directory can't be recovered
  to remove a folder i.e delete a folder
  eg: remdir test, removes a folder called test
  
  eg: rmdir test1 test2 test3 test, removes all the listed directories

  eg: rmdir test/test1/subFolder, this deletes subFolder

to remove a folder that isn't empty, use the /s flag
  eg: command:  `rmdir /s test` removes an unempty folder called test, 
    you will asked `are you sure`, then click "y" to mean yes


code 
   code test.txt opens up the text file called test using vscode or atom.

---

## GIT VERSION CONTROL
To use git for your project version control:

*Firstly you need to setup your account so that gitHub will know who is making changes*

1. We initialize it as a git repository using command `git init`
then you see a message like this:
```
Initialized empty Git repository in C:/zeed/zwindow/allCodes/vscode/github_class/gitrepos/repo1/.git/
``` 

1. Add it to staging area.

1. Commit it.



---


<!-- This is a Comment, it looks just like HTML comment -->
<!-- MarkDown Tutorial -->
# Level 1 heading (just like your `<h1></h1>`)
## Level 2 heading (just like your `<h2></h2>`)
### Level 3 heading (just like your `<h3></h3>`)
#### Level 4 heading (just like your `<h4></h4>`)
##### Level 5 heading (just like your `<h5></h5>`)
###### Level 6 heading (just like your `<h6></h6>`)

### To add code snippets

`digitalWrite(led, HIGH);// this is a single line code `

```
/*This is a How to add a multi-line code */
#include <Servo.h>
#include <HOC.h>
void setup() {
  Serial.begin();
}
```

### To be language specific:
***Add the language keyword***
```Cpp
/*This is a C++ code(Arduino to be specific) */
#include <Servo.h>
#include <HOC.h>
void setup() {
  Serial.begin();
}
```

```JavaScript
/*This is JavaScript */
Console.log("I'm getting married soon");
Console.log("But I must make enough money first");
```

```HTML
<!-- this is an HTML Markup -->
<p>This is a paragraph in HTML</p>
<a href="github.com/EngineerHamziey">This is a link to my GitHub account</a>
```

---

This is an horizontal line
isn't that cool

---

*This is how to write an italics*

~~This is a Striked through or deleted text~~