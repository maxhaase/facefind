# facefindFinds human faces captured by optical input devices.

Usage: facefind ImageFile source

ImageFile: bitmap
source: optical device or storage
Optional: --list, --names, --alert

You can enable monitor mode to continuously capture images with a camera until ImageFile is found, or search for ImageFile recursively on disk storage.

An alert is issued on the first find by default, but --list returns a list of file names if a storage search is completed. It can also output frames into a display in real-time, identifying the all the names of all the faces it sees by using the --names switch. 

It will beep if a match is found when using the --alert switch

