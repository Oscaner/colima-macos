# colima-macos

# Setup ColimaLoginHook and ColimaLogoutHook.

```shell
> sudo defaults write com.apple.loginwindow LoginHook $HOME/.config/colima-macos/login.sh
> sudo defaults write com.apple.loginwindow LogoutHook $HOME/.config/colima-macos/logout.sh
```

# Delete

```shell
> sudo defaults delete com.apple.loginwindow LoginHook
> sudo defaults delete com.apple.loginwindow LogoutHook
```
