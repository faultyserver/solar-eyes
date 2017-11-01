# SolarEyes Color Scheme

SolarEyes is a terrible name for a color scheme based mostly on the ever-popular [Solarized theme](http://ethanschoonover.com/solarized) (the light version), but with some modifications for higher contrast in some languages.

Additionally, it aims to visually resolve some inconsistencies in the syntax definitions for similar languages (e.g. Elixir vs. Ruby, Ruby vs. Crystal).

![SolarEyes color scheme sample](/res/sample.png?raw=true "SolarEyes Color Scheme Sample")

This color scheme has mostly come from working with [Elixir](https://elixir-lang.org), [Ruby](https://ruby-lang.org), [Crystal](https://crystal-lang.org), and from my development of [Myst](https://github.com/myst-lang/myst). It is an evolving project that has only recently started, so expect some inconsistencies for a while. Changes probably won't be common, but may be large and "breaking" when they do happen. I'll try to tag releases whenever things settle down for a while.

Sadly, a good portion of the nice features of this color scheme (grayed-out underscore variable names, bold block parameters, etc.) will _not_ work with most languages, because their syntax definitions do not distinguish them enough to accurately highlight them. Help make these features work more universally by submitting issues and fixes to those repositories!

# Installation

This package has not been published to the main Package Control channel. To install it, add the repository to Package Control (see the "Add Repository" section at https://packagecontrol.io/docs/usage) with the url https://github.com/faultyserver/solar-eyes.

Once the repository has been added, you should be able to install the package as normal through Package Control. It will be under the name `solar-eyes`.


# Contributing

If you have a suggestion about color highlighting or notice any inconsistencies, I'd love it if you [filed an issue for it](https://github.com/faultyserver/solar-eyes/issues/new), or, if you're comfortable with it, feel free to [make a Pull Request](https://github.com/faultyserver/solar-eyes/pulls/new). Please include samples of what's changed from _both before and after the change_ so it's easier to compare.

Note that this is only a theme file. As such, this theme cannot affect how the syntax definitions tag tokens in a file. Issues with the syntax parsing itself should be brought up with their respective owners.
