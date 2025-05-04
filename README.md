## Fallout GRUB theme

Supported languages: Chinese (simplified), Chinese (traditional), English, French, German, Hungarian, Italian, Korean, Latvian, Norwegian, Polish, Portuguese, Russian, Rusyn, Spanish, Turkish, Ukrainian

![](https://i.imgur.com/7LUYwTn.gif)

---


### Installation / update

- **Secure way:**

  - Download install script:

    ```sh
    wget -P /tmp https://github.com/RanMd/fallout-grub-theme/blob/master/install.sh
    ```
    or 

    ```sh
    curl -L -o /tmp/install.sh https://github.com/RanMd/fallout-grub-theme/blob/master/install.sh
    ```

  - Review it at `/tmp/install.sh`

  - Run it:

    ```sh
    bash /tmp/install.sh
    ```

<br>

You can use `--lang` option to select language and disable interactive language selection, e.g.:

```sh
bash /tmp/install.sh --lang German
```

or

```sh
wget -O- https://github.com/shvchk/fallout-grub-theme/raw/master/install.sh | bash -s -- --lang Korean
```

Full list of languages see in `INSTALLER_LANGS` variable in [install.sh](install.sh)

---

### See also

- [Poly light GRUB theme](https://github.com/shvchk/poly-light)
- [Poly dark GRUB theme](https://github.com/shvchk/poly-dark)
