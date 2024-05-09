# Tailwind Fold with Names

Tailwind is an amazing way to write CSS. It's easy to duplicate from project to project, reduces total lines of code, and gets rid of bulky CSS files. However, for me it has always had 2 main flaws - it's messy to read and you can't easily tell what you're looking at.

A few developers have come up with this Inline Fold solution that hides away the CSS when you're not using it, I just added one modification to
always show the first word in your class/className. This allows you to create names for your HTML elements so you can still use BEM styling or
naming conventions of any kind. Read on for more!

## Features

![Format comparison](images/docs/tailwind-fold-example.png)

By default, automatic folding is enabled, but you can customize this behavior in the settings.
**PRO TIP** - Quickly toggle folding using the keyboard shortcut `Ctrl+Alt+A`

## Extension Settings

This extension allows for the following settings:

-   `tailwind-fold.autoFold`: Enable/disable automatic class attribute folding
-   `tailwind-fold.unfoldIfLineSelected`: Unfolds class attributes if line is selected
-   `tailwind-fold.showTailwindImage`: Show/hide the tailwind logo infront of folded content
-   `tailwind-fold.foldedText`: Text to show when class attributes are folded
-   `tailwind-fold.foldedTextColor`: Color of the text when folded
-   `tailwind-fold.foldedTextBackgroundColor`: Background color of the text when folded
-   `tailwind-fold.unfoldedTextOpacity`: Opacity of unfolded class attributes
-   `tailwind-fold.supportedLanguages`: Array of languages the extension is enabled for
-   `tailwind-fold.foldLengthThreshold`: Specifies the minimum number of characters required for a section to fold

## Notes

_This extension folds all class attributes, even if there are no tailwind specific attributes._
_Credit due to stivoat! This is a modified fork of "Tailwind Fold" (See https://github.com/stivoat/tailwind-fold for original)._
