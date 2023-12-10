# Folderbase
Convert your Markdown Notes into a website / digital garden. Runs as an installable PWA as well. Use online or offline. 

# Requirements
Web Server running PHP 7.3 or higher. 

# Install
This works online or offline. For offline use, you must have a local server app such as [MAMP](https://www.mamp.info/en/mac/) or KSWeb 

Unzip the package and place it in your web server's folder root. Navigate to the address (e.g. 192.168.1.103:8888/folderbase) and the demo site should appear. 

# Demo Site

- The 'Folders' section shows the contents of `/folderbase/content/main/`.
- the 'Drafts' section shows the contents of `/folderbase/content/drafts`.
- All images and media are stored in `/folderbase/assets`.

Each folder added to `/main` must have an `index.md` file with at least the `title: Folder Name` and `template: home-subpage` properties filled in. See the demo site files for details. 

# About
Folderbase is a fork of [Pico CMS](https://github.com/picocms/Pico), v3.0-alpha, and includes the [Pico-Search](https://github.com/PontusHorn/Pico-Search) Plugin. 
