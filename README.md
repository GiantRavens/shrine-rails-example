# Rails 5 Shrine Upload Example

A barebones port of Janko's Shrine for Rails example application.

No CSS or styling - just the basics to do the following:

- add the shrine gem, an init file for shrine configuration, mount the shrine ImageUploader to the Photo model, add the 'virtual' image_uploader model
- a PHOTO has one image attachment
- the attachment is cached and stored locally in public/uploads/ (but that folder is added to .gitignore so that you're not checking images into your source code)
- added a present? check on rendering the thumbnails - deleted images were crashing the app without it
