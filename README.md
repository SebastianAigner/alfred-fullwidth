# alfred-fullwidth
#### Workflow to turn text into ｆｕｌｌ　ｗｉｄｔｈ　ｃｈａｒａｃｔｅｒｓ

## How?
The unicode codepoints are modified so that each regular character is converted to their respective full-width counterpart. This python script is embedded in the Alfred 3 workflow, and can be imported with a single click. Type `fw foobar` and Alfred will paste `ｆｏｏｂａｒ` at your current cursor location.

The icon (a true work of art... 😉) is the result of a few seconds in Pixelmator, displays an "Open box" which is used to indicate spaces when explicitly noting them down (e.g. pen-and-paper).

The workflow does not have any external dependencies.

## Why?
Mostly for the [ａｅｓｔｈｅｔｉｃ](http://knowyourmeme.com/memes/aesthetic), but also pretty great if you want to ｅｍｐｈａｓｉｚｅ a statement in a context that does not support rich text.

## Credits
The embedded script uses a marginally modified "Widen-ASCII" [Gist](https://gist.github.com/jcayzac/1485005) by [jcayzac](https://github.com/jcayzac)

