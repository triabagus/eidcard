## For Security image canvas save
```
For security reasons, your local drive is declared to be "other-domain" and will taint the canvas.

(That's because your most sensitive info is likely on your local drive!).

While testing try these workarounds:

Put all page related files (.html, .jpg, .js, .css, etc) on your desktop (not in sub-folders).

Post your images to a site that supports cross-domain sharing (like dropbox.com). Be sure you put your images in dropbox's public folder and also set the cross origin flag when downloading the image (var img=new Image(); img.crossOrigin="anonymous" ...)

Install a webserver on your development computer (IIS and PHP web servers both have free editions that work nicely on a local computer).
```