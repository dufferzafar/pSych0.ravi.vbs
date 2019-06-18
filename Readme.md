
# pSych0.ravi.vbs

A virus written in Visual Basic Script that messes with your files.

## story

I wrote this script in class 12th (~2011), to target my close friend Ravi. 
I'd asked him for two games but he instead gave me an empty pen drive on a Friday.
I then spent the weekend working on this "virus" as a payback.

I remember Sandeep (another good friend) coming to my house to hangout, and I explained to him what the virus would do; how I was planning to send it to Ravi etc. 
I remember him saying "ek baar virus bante huye dekh liya, toh ab aisa darr sa nahin raha" (once you see a virus being created, you don't really fear them anymore)

I didn't have an internet connection at my home back then, and I'd never programmed in VB before this (only read bits and pieces of code) so all I had was VB Docs in a single .chm file.

Once the script was finished, I had to come up with a way to make it run on Ravi's computer.
I compiled the VBScript into an exe, changed the exe's icon to that of a Windows 7 Folder, and named that "folder" - 'Games'.
Ravi never suspected anything and was an easy target!

After I'd had my fun bothering Ravi, I wrote a "removal" script that undid all the changes that the virus had made.

Ravi & I still bond over the kinds of silly stuff that we've done.
The two of us teamed up together to work on another virus - called "kohraam" - which was supposed to target Amit (another of our friends). 
We never ended up finishing that project. 
As always, something new must've caught my interest.

## behaviour of the virus

* Copies itself to system directories
* Disable Windows task manager, registry editor & a bunch of other sysadmin tools.
* Installs an external tool that hinders the mouse movement

```python
for drive in all_drives:

    for folder in drive:

        1.) Create a text file with some message

        2.) Rename all media files in the folder (changing their extension):
                file.mp3 "->" file.mp3.pSych0
```

* I spent some time creating a nice set of message boxes as well, so Ravi knew exactly what had happened!

## others

* I have a collection of scripts written in AutoHotkey that could be used to play pranks on people: [dufferzafar/pranks-and-all](https://github.com/dufferzafar/pranks-and-all)
