# PxTone Collab in Flatpak

this project is a -Successful- attempt to make PTCollab able to run in flatpak

For now, you can get this working by using these commands:

```
flatpak-builder --force-clean build-dir io.github.yuxshao.ptcollab.yml
flatpak-builder --user --install build-dir io.github.yuxshao.ptcollab.yml
```
