# hugo-radix-icons
Hugo module to easily use [radix Icons](https://radixicons.org/) anywhere in your site.

## Installation

First, [init](https://gohugo.io/hugo-modules/use-modules/#initialize-a-new-module) your project as Hugo Module.:

```
hugo mod init github.com/<your-user>/<your-project>
```

Then edit your config file to import the module:

```toml
# config.toml
[module]
  [[module.imports]]
    path = "github.com/bradp/hugo-radix-icons"
```

### Upating

To update all modules:
```
hugo mod get -u
```

You may need to run `hugo mod clean` if something isn't working right.


## Usage

To any layout file, radix use this partial (replacing 'download' with your chosen icon.)

```
{{ partial "radix-icons/icon" "download" }}
```

To view all the icons & their names, you can go to `<your-site>/radixicons`.

Enjoy!
