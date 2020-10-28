# img

## Minimalistic screenshot uploader for Linux

img is a minimalistic bash script that uploads a **screen section** to **imgur** .

- On success, it copies the image link to the clipboard and notify.
- On failure, it notify an error

no output is produced.

img depends on **scrot**, **curl** and **xclip**.

> Recommended usage: Bind a key (such as PrtSc) to execute the script easily.

### i3 considerations

if you are using i3 consider using --release on `bindsym` to avoid errors
example:
```
bindsym --release $mod+Ctrl+p exec ~/.scripts/img.sh
```

forked from : https://github.com/Ceryn/img

