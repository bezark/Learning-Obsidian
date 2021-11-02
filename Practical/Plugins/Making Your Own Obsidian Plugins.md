Making your own Obsidian Plugin is very easy!

Plugins are built in Typescript which is just a fancy version of javascript. An obsidian plugin is essentially just a node.js script and can be written the exact same way. A great place to start is with the [sample plugin](https://github.com/obsidianmd/obsidian-sample-plugin)


This plugin makes use of the [Obsidian API](https://github.com/obsidianmd/obsidian-api) which is an easy way to interact with your vault through javascript.

Most of the documentation for the API is within comments ins the `obsidian.d.ts` file.
##### [](https://github.com/obsidianmd/obsidian-api#the-app-is-organized-into-a-few-major-modules)The app is organized into a few major modules:

-   `App`, the global object that owns everything else. You can access this via `this.app` inside your plugin. The `App` interface provides accessors for the following interfaces.
-   `Vault`, the interface that lets you interact with files and folders in the vault.
-   `Workspace`, the interface that lets you interact with panes on the screen.
-   `MetadataCache`, the interface that contains cached metadata about each markdown file, including headings, links, embeds, tags, and blocks.