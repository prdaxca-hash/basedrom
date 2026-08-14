# RezeOS modifications

This directory is for locally supplied binary modifications used by the RezeOS workflow.

Expected files:

- `mods/Lawnchair/Lawnchair.apk`
- `mods/framework-res/framework-res.apk`

The workflow validates `framework-res.apk` against the downloaded RestlessOS copy before replacement and refuses to continue if `AndroidManifest.xml` or `resources.arsc` changes.
