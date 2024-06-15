# zed config

I have been playing around with this editor and I am actually quite amazed at how well it works. There are however, features implemented in much larger IDEs that I miss.
One such feature is the auto syncing of settings and keymaps. Thus this repository was created. I have setup my `~/.config/zed` folder to directly point at this repo, on
my various devices. That way I can just update config on one machine and then pull it to all the others.

Please keep in mind that this is MY config, I am not putting this in place for others to use. It is made public because I have no reason to keep it private, however I am not providing any
support, nor a guarentee of any sort (especially that you will **like** my config).

# references
* [All Zed Keybindings](https://zed.dev/docs/key-bindings#all-key-bindings)
* [Configuring Zed](https://zed.dev/docs/configuring-zed)

# settings choices
## AI settings
At this moment in time, I have found that AI is just a waste of my time (unless I am doing work that revolves around templates). For that reason I have disabled the menus for OpenAI services
or at minimum hidden the buttons. 
## Language Overrides
I have configured a PHP language override, for [pint](https://laravel.com/docs/11.x/pint) for formatting on save. This makes it quite easy to avoid common formatting weirdness. 
There are many of advantages to calling pint on save, another of which is that it will enforce that my code remains consise.
## Default Keymap
I used the base keymap of "IntelliJ", I have gotten used to their keymap and would like to continue using it to some extent.

# keymap choices
## accessing menus
I always want to have the ability to quickly toggle through the file viewer and console. Those are bound to cmd-1 and cmd-2 respectively.
## multi-cursor
There is a default keybind for multi-cursor support that I do not really remember or like, with that being said I have bound shift-cmd-d to be `editor::selectNext` which will select 
the next occurrance of the selected text. cmd-d will duplicate the line (not overridden).
