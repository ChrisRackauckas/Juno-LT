Juno
====

Juno is an environment for the Julia language, with strong support for interactive development and a whole load of other niceties. It's implemented on top of Light Table, using the [Jewel](http://github.com/one-more-minute/Jewel-LT) plugin and a set of great defaults for Julia development.

Please see below for installation instructions or [the wiki](https://github.com/one-more-minute/Jupiter-LT/wiki) for documentation.

Note that Juno is halfway through a rename, and used to be called "Jupiter". Sorry for any confusion this causes.

![Screenshot](screenshot.png)

## Instructions

Note: to execute commands, `Ctrl+Space` then type the command's name.

* Make sure you're using [Julia v0.3](http://julialang.org/downloads/) or later.

* Install the plugin with Light Table's plugin manager ("show plugin manager" command, search for "Jupiter").

* Either make sure `julia` is on your path or set the :app behaviour `(:lt.objs.langs.julia/julia-path "/path/to/julia")`.
  * (Use the "user behaviors" command. See [here](https://gist.github.com/one-more-minute/9882389) for an example of setting the Julia path)

* Now restart LT. You should see a working indicator as the Julia client boots up – this may take a while the first time. Use the "toggle console" command to see output.

* Open a `.jl` file (or press `Ctrl-n` for a new one), type something, `Ctrl+Enter` to evaluate the line.

When an update is available, first `Pkg.update()` in Julia, then use the "update all outdated" command in Light Table.
