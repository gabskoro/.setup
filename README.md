### Initial setup

Clone this repo to your home folder.

Add this to the `.bashrc` file

```bash
for f in ~/.setup/*.settings ~/.setup/**/*.settings; do
   source $f
done
```
