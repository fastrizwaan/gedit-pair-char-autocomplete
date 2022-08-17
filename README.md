# gedit-pair-char-autocomplete
cloned repo of gedit-pair-char-autocomplete v1.0.6 from google.code for gedit3


# Automatic pair character completion plugin for gedit
Pair character autocompletion plugin for gedit

A gedit plugin that automatically inserts brackets, quotes, and parenthesis.
Usage

Automatically inserts a closing parenthesis ) whenever an opening parenthesis ( is typed. The default paired characters are (), [], {}, "", '', and ``. The plugin is smart enough to automatically overwrite existing closing brackets when appropriate.

Selecting a block of text and typing an opening parenthesis or quote character will enclose the selection in quotes or parenthesis.

To quickly jump out of nested quotes or brackets and start a newline, type Ctrl+Return. To jump to the end of the line, insert a semicolon, and start a newline, type Ctrl+Shift+Return.

Custom sets of per-language paired characters are supported. To change the default paired characters, or add support for new languages, edit the file pair_char_lang.py.
Installation

Download the latest version of the plugin and extract it. Be sure to download the a version of the plugin compatible with your version of gedit.

Run the `install.sh` script.
Restart gedit if it is already started.
Select `Edit->Preferences` from the menu. Click on the Plugins tab and `enable the Pair Character Completion plugin`.

