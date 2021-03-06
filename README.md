## My Favorite Things

This project that is named just like [John Coltrane's album](https://en.wikipedia.org/wiki/My_Favorite_Things_(album))
it's an attempt to automate every step of a fresh Arch Linux installation. It assume a custom workflow used by me, and
builds an environment with this workflow in mind.

Everything is automated using `make` and `m4`. There are many utilities and system specific scripts in order to provide
seamless integration.

### Usage

You can take advantage of whole `make` tasks bundle, or specific ones:

```sh
# Install everything necessary for core functions like sound, power, bluetooth, aur-helper, etc
make system

# Install and configure VIm
make applications/vim
```

### Extensibility

Tasks have a small degree of configuration, basically provided by `m4`, for few applications configuration you can
define a coloscheme and your personal info like name and email, please look at `config.mk`.

### Preview

Here are a few photos, I'm using a grayscale colorscheme with a deep focus intent:

![Desktop](http://i.imgur.com/VsM9bFc.png)

- **File browser**: ranger
- **Bar**: lemonbar
- **Player**: ncmpcpp
- **Wallpaper**: dinamically generated via hsetroot
- **Fonts**: tamzenm, siji

### Third Party

- Firefox user style: https://userstyles.org/styles/135593/firefox-edge-light-dark
- Slack sidebar: `#073642,#002B36,#B58900,#FDF6E3,#CB4B16,#FDF6E3,#2AA198,#DC322F`
