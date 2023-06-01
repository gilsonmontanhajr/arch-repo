# arch-repo
Hey there,
Here you'll find the packages I use and unfortunately not found yet on archlinux repositories.

- google-chrome-stable
- slack
- yay

Are some of those.

## Add this as a archlinux repo
Open your `/etc/pacman.conf`, go for the last line of the file and add:

```
[gilson-stuff]
SigLevel = Optional TrustedOnly
Server = https://gilsonmontanhajr.github.io/$repo/$arch
```
