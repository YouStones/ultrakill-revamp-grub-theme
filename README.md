## ULTRAKILL GRUB theme

Supported languages: Chinese (simplified), Chinese (traditional), English, French, German, Hungarian, Italian, Korean, Latvian, Norwegian, Polish, Portuguese, Russian, Rusyn, Spanish, Turkish, Ukrainian

![ultragrub](https://github.com/user-attachments/assets/80958c25-d8d7-4c0d-8a11-f4de938fe9fc)


---


### Installation / update

- **Secure way:**

  - Download install script:

    ```sh
    wget -P /tmp https://github.com/YouStones/ultrakill-grub-theme/raw/master/install.sh
    ```

  - Review it at `/tmp/install.sh`

  - Run it:

    ```sh
    bash /tmp/install.sh
    ```

- **Easier, less secure way** — just download and run install script:

  ```sh
  wget -O - https://github.com/YouStones/ultrakill-grub-theme/raw/master/install.sh | bash
  ```

<br>

You can use `--lang` option to select language and disable interactive language selection, e.g.:

```sh
bash /tmp/install.sh --lang German
```

or

```sh
wget -O- https://github.com/Youstones/ultrakill-grub-theme/raw/master/install.sh | bash -s -- --lang Korean
```

Full list of languages see in `INSTALLER_LANGS` variable in [install.sh](install.sh)

---

I used [this theme](https://github.com/shvchk/fallout-grub-theme) as a base

Copyright (c) 2017 Andrei Shevchuk
