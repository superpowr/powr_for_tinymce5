# 🎉 Welcome to POWr for TinyMCE5 🎉

## How to install:

### Step 1. Add the powr_plugin.js to your page where the TinyMCE5 editor is rendered

Option 1: Add powr_plugin.js from CDN:

      <script src="https://cdn.jsdelivr.net/gh/superpowr/powr_for_tinymce5/powr_plugin.js"></script>

Option 2: Add powr_plugin.js from local file.

[Download POWr for TinyMCE5 Plugin](https://cdn.jsdelivr.net/gh/superpowr/powr_for_tinymce5/powr_plugin.js)

      <script src="https://YOURSITE.com/PATH-TO-DIRECTORY/powr_plugin.js"></script>


### Step 2: Add POWr when initializing TinyMCE:
JavaScript:

    tinymce.init({
      selector:'textarea',
      plugins: 'powr', //Adds POWr Plugin JS
      toolbar: 'powr', //Add POWr Plugin to the toolbar
      extended_valid_elements : "script[src|async]", //Allow POWr.js script to function
      height: '600px'
    });


### Completely functional demo:

    <!DOCTYPE html>
    <html>
      <head>
        <script src="https://cdn.tiny.cloud/1/no-api-key/tinymce/5/tinymce.min.js"></script>
        <script src="https://cdn.jsdelivr.net/gh/superpowr/powr_for_tinymce5/powr_plugin.js"></script>
        <script>
          tinymce.init({
            selector:'textarea',
            plugins: 'powr',
            toolbar: 'powr',
            extended_valid_elements : "script[src|async]",
            height: '600px'
          });
        </script>
      </head>
      <body>
        <textarea>Welcome to POWr for TinyMCE!</textarea>
      </body>
    </html>


## How to create and edit a POWr Plugin:

After the POWr for TinyMCE5 is installed, you can easily create Forms, Galleries, Social Feeds, Countdown Timers, Ecommerce, and much more!

1. Easily add a POWr Plugin within TinyMCE Editor by clicking the `POWr` Dropdown and selecting a plugin.

2. The Plugin  will then appear within the Editor. Click `Edit` to open the POWr Editor and design & customize your Plugin.

## Need help?
[Visit the POWr help center](https://www.powr.io/knowledge-base) and get answers!
