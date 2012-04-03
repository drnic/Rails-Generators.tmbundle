# TextMate bundle for Ruby on Rails Generators

This TextMate bundle make it very easy to write Rails generators, templates or Rails Wizard recipes/scrolls.

## Available commands

Get the list via `rake list` from the console within the bundle project itself:

```
Snippets -> create_file [file]
Snippets -> file [file]
Snippets -> gem [gem]
Snippets -> gem_group [gem]
Snippets -> generate [gen]
Snippets -> gsub_file [gsub]
Snippets -> initializer [init]
Snippets -> inject_into_class [inj]
Snippets -> remove_file [rm]
Snippets -> route [route]
Snippets -> run [run]
```

## Installation

To install via Git:

		mkdir -p ~/Library/Application\ Support/TextMate/Bundles
		cd ~/Library/Application\ Support/TextMate/Bundles
		git clone git://github.com/drnic/Rails-Generators.tmbundle.git "Rails Generators.tmbundle"
		osascript -e 'tell app "TextMate" to reload bundles'

Source can be viewed or forked via GitHub: [http://github.com/drnic/Rails-Generators.tmbundle](http://github.com/drnic/Rails-Generators.tmbundle)

## License

(The MIT License)

Copyright (c) 2012 Dr Nic Williams

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
'Software'), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.