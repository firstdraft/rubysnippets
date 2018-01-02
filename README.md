Ruby snippet for cloud 9
===================

This plugins adds a new ruby snippets to C9.


Installation on c9.io
---------------------

Run the following in c9 terminal:

    # Create a folder
    mkdir ~/.c9/plugins

    # Clone the plugin
    git clone https://github.com/firstdraft/rubysnippets.git ~/.c9/plugins/rubysnippets

    # Click Cloud9 -> Open Your Init Script and add the below code
    services.pluginManager.loadPackage([
      "~/.c9/plugins/rubysnippets/package.json",
    ]);

    # Refresh the page

