## Initial setup

`.bash_profile` is executed for login shells, while `.bashrc` is executed for interactive non-login shells. So what I do is, I always source `.bashrc` in `.bash_profile`.

Open `.bash_profile` and add

```bash
source ~/.bashrc
```

Clone this repo to your home folder and add this to your `.bashrc` file

```bash
for f in ~/.setup/*.settings ~/.setup/**/*.settings; do
   source $f
done
```
