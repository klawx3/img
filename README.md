# img

## Minimalistic screenshot uploader for Linux

img is a minimalistic bash script that uploads a **screen section** to imgur.
On success, it copies the image link to the clipboard and notify.
On failure, it writes the curl output to `/tmp/img_upload.png`, where the image is also stored and notify error.
No output is produced.

img depends on **scrot**, **curl** and **xclip**.

Recommended usage: Bind a key (such as PrtSc) to execute the script easily.

forked from : https://github.com/Ceryn/img

