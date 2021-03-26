The Assets action plugin will open all related files of an image in currently in production in Studio, for example layouts, dossiers or digital articles

Notes
- The plugin requires the user to be logged in Studio

![Plugin in action](https://github.com/WoodWing/OpenRelatedStudioFiles/blob/master/OpenRelatedStudioFiles.gif "Open related files in action")


Configuration
- Install the plugin in a folder on the Studio server
- Add the plugin as an external action plugin in the Assets Server
    - User interface Dialog, width 300, height 100
    - URL, for example http://docker.for.mac.localhost/integrations/OpenRelatedStudioFiles/index.html
    - Action location: Assets context menu
    - Config Properties
        - studioServerURL, for example http://docker.for.mac.localhost/server/index.php
        - studioClientURL, for example http://docker.for.mac.localhost/app/

Technical flow
- Searches for all variants in Assets
- Searches for all related files in Studio
- Open the search result in Studio client
