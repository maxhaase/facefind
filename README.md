# facefind
Finds human faces captured by optical input devices.

Usage: facefind ImageFile source
ImageFile: bitmap
source: optical device or storage
Optional: --list

You can enable monitor mode to continuosly capture images with a camera until ImageFile is found, or search for ImageFile recursively on disk storage.

An alert is issued on the first find by default, but --list returns a list of file names if a storage search is completed. 
