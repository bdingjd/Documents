# Package Manager

The package manager in Manjaro is called pacman, as opposed to apt-get in debian or yum in fedora.

```bash
#update system
sudo pacman -Syyu

#install
sudo pacman -S <package>

#remove
sudo pacman -R <package>
```
# Arch User Repository (AUR)

If you can't find certain packages, such as python-gym, you can try to search for it using the following command.

```bash
# AUR application search
yaourt <package name>

# For example
yaourt python-gym
```
Typically you want to install items that have good version numbers and -git at the end:

1 aur/python-gym-git r761.efeadfd-1 (6) (0.36)

# Installing global python packages in Manjaro

If you do not use a **virtual environment**, instead of using `pip` use `pacman` like so:

```bash
sudo pacman -S python-<package name>
```

