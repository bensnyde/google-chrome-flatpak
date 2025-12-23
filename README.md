# google-chrome-flatpak
Google's Chrome Browser as a Flatpak

### Build 
```
flatpak-builder --force-clean --user --install-deps-from=flathub --repo=repo --install builddir com.google.Chrome.yml
```

### Run
```
flatpak run com.google.Chrome
```
