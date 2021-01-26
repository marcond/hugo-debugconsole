# hugo-debugconsole

**DebugConsole** provides an easy to use partial that shows relevant Hugo debugging information on the browser console. This helps to debug Hugo site development without disrupting the site itself.

I created this plugin inspired by `debug.Dump` ([yes, such things exists!](https://github.com/gohugoio/hugoDocs/issues/1220)) and [Kaushal Modi's hugo-debugprint](https://github.com/kaushalmodi/hugo-debugprint). I needed something that could be contextual (i.e. be available right alongside the page I'm looking at) and also capable of preserving the page output. Because if I'm debugging it, for sure it's already broken some way and I don't want to dabble with extra stuff.  be is a beautiful multilingual API documentation theme for [Hugo](http://gohugo.io/). This theme is built on top of the beautiful work of [Robert Lord](https://github.com/lord) and others on the [Slate](https://github.com/slatedocs/slate) project ([Apache 2 License](https://github.com/slatedocs/slate/blob/master/LICENSE)).

<br/>

![Screenshot DebugConsole](https://raw.githubusercontent.com/marcond/hugo-debugconsole/master/images/screenshot.png)

## Use

To use the partial, do something etc etc etc:

```toml
[module]
  [[module.imports]]
    path = "github.com/marcond/hugo-debugconsole"
    disabled = false
```

**Note:** Note something here.

