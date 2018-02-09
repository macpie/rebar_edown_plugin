# rebar_edown_plugin

[![Hex](https://img.shields.io/hexpm/v/rebar_edown_plugin.svg)](https://hex.pm/packages/rebar_edown_plugin)

A rebar3 plugin for [edown](https://github.com/esl/edown).

## Build

```
$ rebar3 compile
```

## Use

Add the plugin to your `rebar.config`:

```erlang
{plugins, [rebar_edown_plugin]}.
```

Or using other version directly from github:

```erlang
{plugins, [
  {rebar_edown_plugin,
   {git, "git://github.com/altenwald/rebar_edown_plugin.git", {tag, "0.5.0"}}}
]}.
```

Then run the plugin:

```
$ rebar3 edown
===> Fetching rebar_edown_plugin
===> Compiling rebar_edown_plugin
Running edown for myapp
```
