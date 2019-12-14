# com.newtonsoft.json 
Unity package manager setup for Newtonsoft's JSON library (https://www.newtonsoft.com/json) 

For more information about using Json.net in your Unity project, check this page:

https://gist.github.com/gekidoslair/121237697a05d87fa40ede58030f4394

## UPDATE

Unity has provided an official distribution of Newtonsoft's JSON library via Packman. To use, simply add the following to your package.json:

```"com.unity.nuget.newtonsoft-json": "1.1.2"```

In the Dependencies section of your project's manifest.json.

Note: to reference the newtonsoft library from another assembly (asmdef), you must check
'override references' on the asmdef and this will provide a dropdown with a list of the 
available binary assemblies in the project. 

## Version

This package includes the DLL version of JSON.Net

Version: 12.0.1.22727

## Add to your project

Open the manifest.json for your project and add the following entry to your list of dependencies

```"com.newtonsoft.json": "https://github.com/PixelWizards/com.newtonsoft.json.git",```

For example:

```{
  "dependencies": {
    "com.newtonsoft.json": "https://github.com/PixelWizards/com.newtonsoft.json.git",
    "com.unity.ads": "2.0.8",
    "com.unity.analytics": "3.2.2",
    "com.unity.collab-proxy": "1.2.15",
    ...
    }
 }```
