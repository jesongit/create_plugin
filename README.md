create_plugin
=====

load all create function

Build
-----

    $ rebar3 compile

Use
---

Add the plugin to your rebar config:

    {plugins, [
        {create_plugin, {git, "https://host/user/create_plugin.git", {tag, "0.1.0"}}}
    ]}.

Then just call your plugin directly in an existing application:


    $ rebar3 create_plugin
    ===> Fetching create_plugin
    ===> Compiling create_plugin
    <Plugin Output>
