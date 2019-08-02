# sitecore-hotfixes-9.0.171219
Hotfixes that will be useful on all Sitecore 9.0.171219 projects

To install this project as a submodule in your sitecore repository:
```git submodule add --name hotfixes https://github.com/deepend-melbourne/sitecore-hotfixes-9.0.171219.git hotfixes/```

Then follow the install instructions for each fix below, as some hotfixes will require core DB changes for example.

## Hotfix 95002
*Bug:* New lines not rendering in EE for multi line text fields  
*Install instructions:* None  
*Additional info:* https://kb.sitecore.net/articles/748022  

## Hotfix 205547

*Bug:* `WARN  Authentication on CES Discovery service failed.` and `ERROR Could not update device detection database`  
*Install instructions:* None  
*Additional info:* https://kb.sitecore.net/articles/828414  

## Hotfix 220335

*Bug:* `System.FormatException: Unrecognized Guid format` fires from various areas of the code. Caused by invalid empty internal links. These look like a normal empty field in the content editor however when enabling 'raw values' you can see the value is `<link linktype="internal" />`. Can sometimes prevent pages from publishing including ancestors of the affected page.  
*Install instructions:* None  
*Additional info:* https://kb.sitecore.net/articles/771795
