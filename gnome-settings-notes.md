# Want dark mode?
Go to `GNOME Settings->Appearance->Style`.

This is great, but it doesn't actually affect some applications. I.e., those using GTK2... I think. So the top bar of these programs will still have a light theme applied.

To have a dark theme applied to those, go to `GNOME Tweaks->Appearance->Legacy Applications`.

On a more recent install (Fedora 39), I had to install a package to find `Adwaita-dark` in *GNOME Tweaks*:
```bash
sudo dnf install gnome-themes-extra
```

# Want maximize and minimize buttons?
Go to `GNOME Tweaks->Windows->Titlebar Buttons->Maximize` and `GNOME Tweaks->Windows->Titlebar Buttons->Minimize`.

# Want `Alt+Tab` to switch windows instead of applications?
Go to `GNOME Settings->Keyboard->Keyboard Shortcuts->View and Customize Shortcuts->Navigation->Switch windows`.

I also have `Switch applications` and `Switch windows of an application` disabled there (the former being a side effect of reassigning `Alt+Tab`, likely).
