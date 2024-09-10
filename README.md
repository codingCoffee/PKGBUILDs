
<div align="center">
  <h1>
    PKGBUILDs
  </h1>
  <h4>PKGBUILD repository for my AUR packages</h4>
</div>


```
makepkg --printsrcinfo > .SRCINFO
```

```
git init .
git checkout -b master
git remote add origin ssh://aur@aur.archlinux.org/gobang-bin.git
git add .
git commit
```
