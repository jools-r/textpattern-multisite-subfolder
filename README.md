# Textpattern multisite template – admin subfolder

An alternative Textpattern Multisite configuration using an admin subfolder.

*Note: Currently experimental!*

This `site` folder is a template for a multisite setup where each site’s domain points to a folder and the admin area is reached via a `/textpattern` subfolder.

The following folder structure applies:

```
/webapps
    /site1
        …
        /textpattern
    /site2
        …
        /textpattern
/textpattern   <-- Textpattern repo
```

The name of the `webapps` folder and of `site1`, `site2`, etc. can be changed depending on your host’s requirements (e.g. `/sites` or `/www`) and webapp name (e.g. `/my-domain`). Each site’s domain should point to the respective `/site#` folder.

The standard setup is `/textpattern` but the folder can be renamed prior to setup, e.g. to `/admin` or `/manage`, etc.


