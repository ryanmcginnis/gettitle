# gettitle

Grab webpage title and append to a file (OS X, Safari only)

## Known Bugs

The script will continue until all tabs are closed, which may be undesirable.

If Safari has a dialog box open (e.g.: The page wants to use your location) the script will keep running but it will not close any tabs or append to the file.

In 10.8 and later, osascript will throw an error for CFURLGetFSRef in the terminal window. Don't worry: it just doesn't like relative paths. You can ignore the error.

If you use a Terminal-esque application rather than terminal (e.g.: iTerm), the script will not automatically quit. Could be resolved by killing by UID or some such solution.
