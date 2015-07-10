"LightWire" Skin
====================

*Based on "Icy Orange"*

![](https://processwire.com/talk/uploads/monthly_02_2015/post-140-0-82434300-1423925224.png)

You can set the skin globally if you just go to /site/modules/InutfieldCKEditor/config.js and add it there like this:

```javascript
CKEDITOR.editorConfig = function( config ) {
    config.skin = "lightwire,/site/modules/EditorSkinLightwire/skins/lightwire/"; // of course this has to be the path to your file so you might have to adjust it
};
```
