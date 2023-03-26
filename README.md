# StrictDoc.tmbundle
StrictDoc.tmbundle is a TextMate bundle that provides support for StrictDoc markup.

## Alternative for VS Code, JetBrains IDE and similar

Most IDEs use JSON to describe the syntax.
In that case, you should visit [strictdoc-project/strictdoc.tmLanguage](https://github.com/strictdoc-project/strictdoc.tmLanguage) repository.

## Alternative for Sublime Text

Sublime Text can use both .sublime-syntax and .tmLanguage files for syntax highlighting. 
We recommend that you use this version: [strictdoc-project/strictdoc.sublime-syntax](https://github.com/strictdoc-project/strictdoc.sublime-syntax) because its syntax is more precise and works correctly with the included RST markup.

## Included RST markup

StrictDoc.tmbundle includes RST markup, which is used for multiline fields.
If you are not interested in RST markup support, you can ignore this section.

If your code editor:
+ uses PLIST to describe the grammar
+ and the RST bundle uses the scopeName `text.restructuredtext"`,
then this bundle will work for you.

For example **TextMate** fully satisfies these conditions.

If you want to use plist but your RST bundle has a different name, you will need to change the string `text.restructuredtext` to match your bundle's name (e.g. it is often `source.rst`).
