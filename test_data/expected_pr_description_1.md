Semi-automatic update generated by [nixpkgs-update](https://github.com/ryantm/nixpkgs-update) tools. This update was made based on information from https://update-site.com.


meta.description for foobar is: "Foobar package description"

meta.homepage for foobar is: "https://foobar-homepage.com"

meta.changelog for foobar is: "https://foobar-homepage.com/changelog/v1.2.3"


###### Updates performed
- Version Update
- Other Update

###### To inspect upstream changes

- [Release on GitHub](https://github.com/foobar/releases)

- [Compare changes on GitHub](https://github.com/foobar/compare)

###### Impact

<details>
<summary>
<b>Checks done</b> (click to expand)
</summary>

---

- built on NixOS
- Some other check

---

</details>
<details>
<summary>
<b>Rebuild report</b> (if merged into master) (click to expand)
</summary>

```
123 total rebuild path(s)
```

</details>

<details>
<summary>
<b>Instructions to test this update</b> (click to expand)
</summary>

---


```
nix-build -A foobar https://github.com/r-ryantm/nixpkgs/archive/af39cf77a0d42a4f6771043ec54221ed.tar.gz
```

After you've downloaded or built it, look at the files and if there are any, run the binaries:
```
ls -la /nix/store/some-hash-path
ls -la /nix/store/some-hash-path/bin
```

---

</details>
<br/>



### Pre-merge build results

We have automatically built all packages that will get rebuilt due to
this change.

This gives evidence on whether the upgrade will break dependent packages.
Note sometimes packages show up as _failed to build_ independent of the
change, simply because they are already broken on the target branch.

nixpkgs-review comment body

---

###### Maintainer pings

cc @maintainer1 for [testing](https://github.com/ryantm/nixpkgs-update/blob/master/doc/nixpkgs-maintainer-faq.md#r-ryantm-opened-a-pr-for-my-package-what-do-i-do).