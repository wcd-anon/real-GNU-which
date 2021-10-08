![a fuckin leaf](https://raw.githubusercontent.com/Chanon7/real-GNU-which/main/which.jpg)

If you want GNU `which`, go here

https://ftp.gnu.org/gnu/which/

```
wget which-2.21.tar.gz
```
Ensure `gcc` and `make` are installed

Extract the tarball and cd to the directory and run
```
./configure
```
```
make install clean
```

Then you can (optionally) remove the fake which script at /usr/bin/which and either mv the newly installed /usr/local/bin/which to /usr/bin, symlink it, copy it, whatever and boom. You have real GNU which(1)


