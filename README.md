# SHspace
ALMOST puresh additions to the user space; additions work with busybox user space or are completely pure sh
---

### Adding:
  (Setup)
```sh
$ git clone https://git.unix.lgbt/Mia/SHspace.git ./shspace # or custom path
$ printf 'PATH="%s/shspace/bin:%s"' "$PWD" "$PATH" >> ~/.bashrc # or whatever u use
$ . ~/.bashrc # or whatever u use
```

## Utils:
```text
- grepp
  like busybox grep; only puresh + compatibile with sh style pattern matching
- filp
  makes use of mv, [ -h ], ln, and stat to flip or swap the location of a symlink
```
