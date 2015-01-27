#ShuttleViewer

ShuttleViewer is a plugin for fileShuttle. It adds a neat landing page for your images, much like droplr and cloudapp. ShuttleViewer is composed of HTML, CSS and JS, which should be uploaded to your image hosting server.

View a [real life example here](http://sht.tl/iKLtFX) of ShuttleViewer in action.

![step 1](https://raw.githubusercontent.com/vephinx/ShuttleViewer/master/example.png)

##Features
- Scales images to fit your window
- Makes viewing on mobile more pleasant
- Provides shortcut for copying the link
- Lets you add link to your own site

##Currently Supported File Formats
- Image: jpg, jpeg, png, gif, tiff, bmp
- Video: mov, avi, mp4, mkv

##Install Guide
0. Make sure you have [FileShuttle](http://fileshuttle.io/) installed.

1. Download this repository, and add the 'theme' directory and index.html to the same directory that your images end up in.

![step 1](https://raw.githubusercontent.com/vephinx/ShuttleViewer/master/step1.png)

2. Open FileShuttle preferences and add '/?' to the end of the URL field.

![step 1](https://raw.githubusercontent.com/vephinx/ShuttleViewer/master/step2.png)

3. Done!

##Todos
- Let users zoom in if the image is scaled down
- Provide an .htaccess with PHP option, to remove the /? from the url
