# dotfiles-solus

[Solus](https://getsol.us/home/) dotifiles managed by [yadm](https://github.com/TheLocehiliosan/yadm).

[Solus](https://getsol.us/home/) initial/setup [configuration](https://github.com/maxdevjs/dotfiles-solus-config)

## What is included

- [maxdevjs/dotfiles-fish](https://github.com/maxdevjs/dotfiles-fish)
- [maxdevjs/dotfiles-kitty](https://github.com/maxdevjs/dotfiles-kitty)
- [maxdevjs/dotfiles-rofi](https://github.com/maxdevjs/dotfiles-rofi)
- [maxdevjs/dotfiles-nvim](https://github.com/maxdevjs/dotfiles-nvim)

## Troubleshooting 🤪

As [Github](https://github.com/) [renamed](https://github.com/github/renaming) its master branch to main, exists the
possibility that [yadm](https://github.com/TheLocehiliosan/yadm) will complain
when pushing.

<details>
<summary>Solution</summary>

The solution will most likely be to move the `master` branch to `main`:

```yaml
$ branch -M main
```

The previous command renames the branch called `main` to `main` thanks to the `-m` flag.

```yaml
$ man git-branch
```

Now it should work 🥳:

```yaml
$ push -u origin main
```

</details>

<details>
<summary>Add Yadm remote and push</summary>

```yaml
$ yadm remote add origin https://github.com/maxdevjs/dotfiles-solus.git
$ yadm push -f -u origin main
```

</details>

## TODO

- [x] setup [i3](https://i3wm.org/)
   - setup [maxdevjs/dotfiles-i3-config](https://github.com/maxdevjs/dotfiles-i3-config)
  - [x] setup [polybar](https://github.com/polybar/polybar)
    - setup [maxdevjs/dotfiles-polybar](https://github.com/maxdevjs/dotfiles-polybar-config) 
  - [x] setup [rofi](https://github.com/davatorium/rofi)
    - [maxdevjs/dotfiles-rofi](https://github.com/maxdevjs/dotfiles-rofi-config)

