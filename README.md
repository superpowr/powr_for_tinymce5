# 🎉 Welcome to POWr for TinyMCE5 🎉

## How to install:

### Step 1. Add the powr_plugin.js where TinyMCE5 editor is rendered

Option 1: Add powr_plugin.js from CDN:

      <script src="https://cdn.jsdelivr.net/gh/superpowr/powr_for_tinymce5/powr_plugin.js"></script>

Option 2: Add powr_plugin.js from local file.

[Download POWr for TinyMCE5 Plugin](https://cdn.jsdelivr.net/gh/superpowr/powr_for_tinymce5/powr_plugin.js)

      <script src="https://YOURSITE.com/PATH-TO-DIRECTORY/powr_plugin.js"></script>


### Step 2: Add POWr when initializing TinyMCE:
JavaScript:

    tinymce.init({
      selector:'textarea',
      plugins: 'powr', // Add POWr Plugin
      toolbar: 'powr', // Set POWr Plugin position in TinyMCE toolbar
      extended_valid_elements: "script[src|async]", // Allow POWr.js script to function
      height: '600px'
    });

*Note: extended_valid_elements: "script[src|async]" is needed for POWr Plugins to render!*

*Note: POWr plugins require an http or https request to render (i.e. a server needs to be running and not just the local filesystem).*

### Demo & Boilerplate Code:

[View Demo on JS Fiddle Here](https://jsfiddle.net/1k6p8hzu/)

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

1. Add a POWr Plugin within TinyMCE Editor by clicking the `POWr` Dropdown and selecting a plugin.

2. The Plugin  will then appear within the Editor. Click `Edit` to open the POWr Editor and design & customize your Plugin.

*Note: To publish your content, you will be prompted to create an account on POWr.io so you can edit and manage your plugins in the future.*

![Create and Edit a POWr Plugin](https://powr.s3-us-west-1.amazonaws.com/email+gifs++/On+page+edit "Create and Edit a POWr Plugin")

## Need help?
[Visit the POWr help center](https://www.powr.io/knowledge-base) and get answers!
