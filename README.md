# Installation

```
git clone https://github.com/stormten24/c9.snippets.git ~/.c9/plugins/c9.snippets
```

## Add to AWS Init
AWS Cloud 9 > Open Your Init Script
```
services["language.complete"] = services["languageComplete"];

services.pluginManager.loadPackage([
    "~/.c9/plugins/myPlugin/package.json",
])
```

## Refresh your browser
Test by opening a Javascript file, type "test", then press tab.
You can easily add more to the snippets to the files (must use tabs for indentation).
