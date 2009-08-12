## Radiant Scribbish Theme
---

This is a port of the Scribbish theme that is available for other CMS and blog systems such as Memphisto and WordPress. The original is located [here](http://quotedprintable.com/pages/scribbish). To use this theme you will need the [import export extension](http://github.com/radiant/radiant-import-export-extension/tree) and the [settings extension](http://github.com/Squeegy/radiant-settings/tree/master). 

### Installation
1. Create your Radiant installation. Bootstrap the database and make sure to choose the option “Empty” for content when going through the prompts.
2. Install the import_export extension
3. From your radiant installations directory run: rake db:import THEME=/path/to/scribbish.yml
4. Copy /images/scribbish into /public/images
5. Copy /stylesheets/scribbish into /public/stylesheets
6. Copy /javascripts/site into /public/site

If you have any questions you can email me: charlie[dot]robbins[at]gmail[dot]com