# Add-collection-Tabs-in-home-page

First-> Go to section-> create new section file.
secondly-> copy the code from featured collection and paste it to the new created section.
third-> cut the slider component code from there
fourth-> paste the iquid code under the title.
fifth-> before the {% endfor %} and the last </div> paste the slider component code again.
sixth-> paste the jquery code at the bottom of the file
seventh-> Also paste the Style code there
Eight-> You will have to change the blocks as well:- 1) to add the block please visit this link "https://www.shopify.com/partners/blog/theme-blocks". 2) copy the block folder and paste it above the preset.
Nine-> Then at the very bottom of the file schema add this ",
      "blocks": [
        {
          "type": "Tab"
        }
      ]"  below the preset name.
      Ten-> At last you will have to go for the slider component and look there and change "setting to block".
