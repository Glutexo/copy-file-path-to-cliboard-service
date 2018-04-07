# Copy file path to clipboard #

This is a simple macOS service that copies a path of a selected file to the system clipboard.

## Usage ##

* Clone this repository.
* Pick one of the `workflow` packages and copy it either to `~/Library/Services` (only for current user), or to `/Library/Services` for all users.
* Rename the package to the name you want to see in the `Services` menu.
* Select a file in Finder.
* Find your service in the `Finder › Services` menu.

Voilà! The path of your selected file is now in the clipboard. Paste it somewhere to see that. A path of multiple files can be selected too. If you pick the `(all apps)` version, you can use it system-wide and not only in Finder.

Enjoy.
