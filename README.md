# OAPM OpenRepo
The Fucked up openrepo for the fucked up package manager OAPM
## Adding Packages

1. Include a package manifest in the package, all fields must be present.
```json
{
  "name": "<your-project-name-here>",
  "version": "0.1.0",
  "description": "<your-project-descr>",
  "keywords": [],
  "license": "<License(we use FucKv2)>",
  "author": {
    "name": "<Your Username/Full Name>",
    "email": "<your email>",
    "url": "<Your website, if you do not have one, put the link to your github profile>"
  },
  "dependencies": {
    // Put your depedencies here like this:
    "rinode": "0.1.0"
  }
}
```
2. Open an issue containing the link to your Git repo.

> ### Adding Packages (with your own hands)
> 
> 1. Fork the repository.
> 2. Clone it
> 3. Add an entry to seeds.json
> 4. Push
> 5. Make a Pull request

## Resources

|Path|Description|
|---|---|
|/index.json|List of all packages on the repo.|
|/packages/packageName/package.json|Package manifest of the latest version.|
|/packages/packageName/versions.json|List of all available versions.|
|/packages/packageName/releases/version.zip|Release zip for that version.|
|/packages/packageName/releases/version.json|Manifest for that version.|

### All Packages

<!--begin:packages-->
|Package|Version|Updated|Description|
|---|---|---|---|
|[chat](./packages/chat)|0.1.0|07/13/25 - 22:02|Helper methods for the in-game chat.|
|[command](./packages/command)|0.1.4|07/07/25 - 22:11|Declarative command registration.|
|[console](./packages/console)|0.1.2|07/15/25 - 21:28|Provides the console object.|
|[devtools](./packages/devtools)|0.1.2|07/09/25 - 22:15|Developer's best friend.|
|[dummy1](./packages/dummy1)|0.1.0|07/01/25 - 19:16|The example package 1.|
|[dummy2](./packages/dummy2)|0.1.0|??/??/?? - ??:??|The example package 2.|
|[extract-zip](./packages/extract-zip)|0.1.0|06/30/25 - 10:48|Extract zip file to directory.|
|[fabric-api-events](./packages/fabric-api-events)|0.1.2|07/15/25 - 21:28|Event listeners for Fabric API events|
|[fetch](./packages/fetch)|0.1.2|07/15/25 - 21:28|Provides the fetch API.|
|[fs](./packages/fs)|0.1.3|07/06/25 - 17:28|Provides the fs object.|
|[listener](./packages/listener)|0.1.1|07/15/25 - 21:28|Event listeners for JSCore.|
|[print-events](./packages/print-events)|0.1.0|07/13/25 - 15:36|Saves a JSON file of all available events.|
|[promise](./packages/promise)|0.1.0|06/30/25 - 10:48|Provides the promise object.|
|[pully](./packages/pully)|0.1.9|07/11/25 - 20:14|Package manager.|
|[require](./packages/require)|0.1.1|06/30/25 - 16:45|Provides the require function.|
|[rinode](./packages/rinode)|0.1.1|07/06/25 - 13:30|Node.js simulator for Rhino.|
|[text](./packages/text)|0.1.2|07/15/25 - 23:13|Helper methods for Text related things.|
|[timer](./packages/timer)|0.1.0|07/06/25 - 13:30|Provide the setTimeout and setInterval methods.|
|[translate](./packages/translate)|0.1.0|07/15/25 - 21:28|Adds a small button next to each message to translate that message with LibreTranslate.|
|[updater](./packages/updater)|0.1.1|07/14/25 - 13:49|Notify you when there is an update.|
|[yarn-extra](./packages/yarn-extra)|0.1.0|07/13/25 - 00:00|Yarn helper functions.|
<!--end:packages-->
