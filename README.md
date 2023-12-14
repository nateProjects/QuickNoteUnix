# QuickNoteUnix
A way to take quick commandline notes in Obsidian on Mac / Linux

This project is a way to take quick notes in Linux or Mac. By default, it uses Dialog, but Kdialog or Zenity can be used instead.

## Requirements

The script needs Dialog installed on the system, and optionally Kdialog or Zenity if you want to use them for adding a note.

On a Mac install one or both of the following as needed:

``brew install dialog``

``brew install zenity``

## Configuration:

In the script, add the path to the inbox file, if you don't want to use Dialog then choose Zenity or Kdialog by commenting and uncommenting the relevant lines, and choose if you would like a Zenity multiline dialog or not by commenting or uncommenting the `zenity_multiline` line.

If you choose the have the Zenity multiline dialog, then the Enter key will add a newline, and you will need to press ctrl+tab twice, then Enter to add the note. And if you choose to not use the multiline dialog, then pressing enter will add the note. 

If you use Kdialog instead of Zenity, then the Enter key will create a newline, and you will need to press ctrl+Enter to add the note.

In KDE, you can map a keyboard shortcut to the script.

## History

This is based on https://github.com/Guy-92/QuickNoteLinux by Guy-92.

I wanted one script I could use from the commandline on my home Mac or Linux server, or at work on WSL Linux.

I also wanted to add the ability to pick a particular note to edit from the commandline.
