


# Android Studio to Xamarin Studio (AS-2-XS) Bindings
Custom bindings and theming to match Android Studio Darcula to Xamarin Studio / Visual Studio on Mac

Being an Android developer, I wanted to maintain a constant themeing, styling, and key bindings across IDEs. I haven't found any online resources that quite fit what I was looking for and so I decided to take some time to set up Xamarin/Visual Studio to be as close to my Android Studio as possible.

In this repository, you can find my custom keyboard bindings that should mimic most of the bindings in IntelliJ's Android Studio as well as syntax highlighting JSON file that mimics the Darcula theme plus a few custom modifications for my own coding pleasure. You can take these and use them as they are or modify them on your own machine to your specific needs. Enjoy!

## Installation

For the custom key bindings, on Mac, download and move (or copy and paste) the *Custom.mac-kb.xml* file to the following path:

*Xamarin Studio:*

    /Users/<youraccountname>/Library/XamarinStudio-<version>/KeyBindings/Custom.mac-kb.xml

*Visual Studio for Mac*

    /Users/<youraccountname>/Library/VisualStudio/<version>/KeyBindings/Custom.mac-kb.xml

Restart Xamarin Studio and the keybindings should work. If they are not working, try unsetting and resetting any keyboard bindings in Xamarin Studio Preferences so it will reload the custom bindings.

For the Darcula syntax highlighting, download the *Zarcula2.json* file. Then open Xamarin Studio and follow:

    Xamarin/Visual Studio -> Preferences -> Text Editor -> Syntax Highlighting -> Add

I would also recommend changing to the Xamarin Studio dark theme via:

    Xamarin/Visual Studio -> Preferences -> Visual Style -> User Interface Theme

##Example Screenshots

Android Studio in Darcula (with some personal modifications)
![Android Studio in Darcula](http://i.imgur.com/r4V4qgV.png "Android Studio in Darcula")

Xamarin Studio in Zarcula2
![Xamarin Studio in Zarcula2](http://i.imgur.com/ngsPeDq.png "Xamarin Studio in Zarcula2")

Xamarin Studio in Zarcula2
![Xamarin Studio in Zarcula2](http://i.imgur.com/fe9g47E.png "Xamarin Studio in Zarcula2")

## Contributing

If you find that I missed some bindings or syntax highlighting colors, feel free to fork, modify, and raise a pull request!

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## Acknowledgements

I found the original Darcula (Zarcula) theming from [@jzeferino](https://gist.github.com/jzeferino) and added my own customizations and updates to colors based on the current Darcula iteration. You can find the original syntax highlighting file here on his github - https://gist.github.com/jzeferino/0f9d820d4d8913b1c7e2
