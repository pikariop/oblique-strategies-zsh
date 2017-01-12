# oblique-strategies-zsh

Brian Eno and Peter Schmidt's [oblique strategies](http://en.wikipedia.org/wiki/Oblique_Strategies) as a very simple oh-my-zsh module. Modelled afer [ceejbot/oblique-strategies](https://github.com/ceejbot/oblique-strategies).

## Usage

Download the plugin into the custom plugin directory

```
cd $ZSH/custom/plugins
git clone git@github.com:pikariop/oblique-strategies-zsh.git obliquestrategies
```

Activate the plugin. Add `obliquestrategies` to the `plugins` list in `.zshrc`

```
plugins=(git obliquestrategies)
```

The function `print_oblique` is now available. Do fun stuff with it. Like pipe it to [ponysay](https://github.com/erkin/ponysay) in `.zshrc` for a motd-like experience.

## LICENSE

The unlicense: I own nothing. Whatever it is I might have accidentally created here, I release to everyone under the terms of the license.
