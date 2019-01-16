# Hexagram30 Codox Theme

This is a modern and responsive [codox][codox] theme developed for
use by hexagram30 projects and ultimately based based on
[codox-theme-rdash](https://github.com/xsc/codox-theme-rdash).

[![Hexagram30 Theme](https://raw.githubusercontent.com/hexagram30/codox-theme/master/screenshots/screen-1-thumb.png)](https://raw.githubusercontent.com/hexagram30/codox-theme/master/screenshots/screen-1.png)


Note that this needs codox ≥ 0.10.0.

[codox]: https://github.com/weavejester/codox


## Usage

Add the following dependency to your `project.clj`:

[![Clojars Project](https://img.shields.io/clojars/v/hexagram30/codox-theme.svg)](https://clojars.org/hexagram30/codox-theme)

Then set the following:

```clojure
:codox {:themes [:hexagram30]}
```

For syntax highlighting capabilities, you'll need to activate Markdown rendering
via:

```clojure
:codox {:metadata {:doc/format :markdown}
        :themes [:hexagram30]}
```


## Example

- [hexagram30/societatis](https://hexagram30.github.io/societatis)


## License

Copyright &copy; 2019 Hexagram30

Copyright &copy; 2017 Duncan McGreggor

Copyright &copy; 2016 Yannick Scherer

This project is licensed under the [Eclipse Public License 1.0][license].

[license]: https://www.eclipse.org/legal/epl-v10.html

## Derivative

This theme is based on the codox default assets licensed under the
[Eclipse Public License v1.0][epl]:

```
Copyright (c) 2016 James Reeves
```

[epl]: http://www.eclipse.org/legal/epl-v10.html

The RDash UI assets are licensed under the MIT license:

```
The MIT License (MIT)

Copyright (c) 2014 rdash

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
```
