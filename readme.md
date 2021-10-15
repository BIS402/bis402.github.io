# Quick Start

* First, hugo new site quickstart
* Next, added the theme from https://github.com/calintat/minimal 
* Then, from the root of your Hugo site, type the following:

```
$ git submodule add https://github.com/calintat/minimal.git themes/minimal
$ git submodule init
$ git submodule update
```

* Now you can get updates to Minimal in the future by updating the submodule:

```
$ git submodule update --remote themes/minimal
```

* To get started, copy the `config.toml` file inside `exampleSite` to the root of your Hugo site:

```
$ cp themes/minimal/exampleSite/config.toml .
```
